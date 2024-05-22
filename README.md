# AutoUnfriends-Roblox

AUTO UNFRIEND ALL ROBLOX
Step 1 : Install Extention
https://chromewebstore.google.com/detail/roblox-friend-removal-but/jgllchbkhjeiaombmpkapalbmpolmelp

Step 2 : Go to : https://www.roblox.com/users/friends#!/friends

Step 3 : Open Dev Tool Click Console
![image](https://github.com/PankKRB/AutoUnfriends-Roblox/assets/87706843/e7ddc586-db76-41ed-9ba8-6a5c1f432a35)

Step 5 : 
Copy And Paste This Code To Console

CODE:
```
let clickCount = 0;

function clickIconAlert() {
  const iconAlerts = document.querySelectorAll('span.icon-alert');

  iconAlerts.forEach(icon => {
    icon.click();
    clickCount++;
    console.log(`Click ${clickCount} Time`);
  });
}

setInterval(clickIconAlert, 1000);

```



https://github.com/PankKRB/AutoUnfriends-Roblox/assets/87706843/65ff4443-f661-4d2f-9364-fb3f00304736

