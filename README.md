# Chars Mod Mail
A package made with JavaScript to help you create an amazing discord mod mail bot!
# Setup
```
const charModMail = require('char-mod-mail');

client.on("ready", () => {
charModMail.ModMail(client, {
  guildID: "SERVER ID",
  categoryID: "CATEGORY ID",
  staffRole: "STAFF ROLE ID",
  embedColor: "EMBED COLOR HEX",
  anonymousReply: true/false,
  closedTitle: "Your Mod Mail Has Been Closed",
  closedMessage: "A Staff Member Has Deleted You Mod Mail!",
  staffOpenedTitle: "User Opened Mod Mail",
  staffOpenedMessage: "The User Opened A Mod Mail And Is Now Wait For A Reply!",
  userOpenedTitle: "Mod Mail Created",
  userOpenedMessage: "You Created A Mod Mail Ticket!",
  wrongEmoji: "EMOJI",
  rightEmoji: "EMOJI" 
})
});
```