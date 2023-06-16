# Leetcode-vs-code
Access leet code through vs code step by step

This guide is mainly for people can not login leetcode in vs in this repo https://github.com/LeetCode-OpenSource/vscode-leetcode


If you encoutner the error after running the command 

`leetcode user -c`

login: (node:5080) Warning: Accessing non-existent property 'padLevels' of module exports inside circular dependency
(Use `node --trace-warnings ...` to show where the warning was created)

1. Then go to this link to dowload the modified version https://marketplace.visualstudio.com/items?itemName=Adaex.vscode-leetcode&ssr=false#overview

2. Install the extenstion 

![image](https://github.com/lechuhuuha/Leetcode-vs-code/assets/59781669/d2f54fb5-e837-499f-b643-b465f4b7886f)

3. After install the extension in vscode you log into leetcode.com in a browser. 
  In Chrome, right click and select "Inspect". Switch to tab "Network", "XHR". 
  Then click any button on leetcode.com(now should be on the left split screen). 
  Now you should be able to see the cookie as @yihong0618 showed in the pic. 
  Copy the two cookie csrf and  LEETCODE_SESSION
  Like this example
  csrftoken="your-csrk-token"; LEETCODE_SESSION="you-leetcode-session";

4. Click login using cookie in this image
  ![image](https://github.com/lechuhuuha/Leetcode-vs-code/assets/59781669/3c7db828-383c-4b49-8047-91d4a294f04e)

5. Add you username or email you use to login in leetcode
6. Paste your cookie in step 3 
7. Hit enter then wait a bit for the extenstion to work

Happy leetcoding!
