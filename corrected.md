# Corrected Errors.

- Line 11 in app.js, changed wordRoutes to wordRouter for the app.use in line 36.
- env file needed to be created for MONGODB_URI
- Line 14 in app.js, added process.env to connect.
- In Word.js had to require mongoose.
- Line 1 in wordRoutes.js had to invoke router.
- getUpdateWord was undefined, added it to be destructured.
- Line 33 in wordRoutes fixed spelling error at module.exports.
- Had to created app variable and invoke express in app.js.
- dotEnv wasn't required in app.js.
- In wordController getAllWords, inside the parameters res and req needed to be switched around.
- Line 9 in index.ejs needed a closing tag.
- Line 10 in index.ejs needed to add an ejs out tag at the start of the console.log... Does console.log need to even be there???
- 