# chat-design
chat design for qb-core


![Preview](https://i.imgur.com/Q6lkbXu.png)

# -------- Important --------
Don't replace the entire folder, just copy the files and paste in your chat folder.



# Change color of the border

New qb-core uses chat:addMessage trigger,
```
  TriggerClientEvent('chat:addMessage', src, {
  color = {255, 0, 0}, <-- here 
  multiline = true,
  args = {'Admin Report - '..name..' ('..targetSrc..')', msg}
})
```

For the old just go to the index.css 
