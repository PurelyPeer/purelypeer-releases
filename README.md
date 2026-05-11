# PurelyPeer Application Release Public History

This is a separate repository for PurelyPeer releases, while the source code repositories are still private (for security reasons).


# 0.9.1 <img src="https://img.shields.io/badge/Latest-Stable-green?style=flat-square" align="center" height="20" />

### 🚀 Features
- `Quests`: added new type of quest called Private Quests (these quests are just visible to whom the owner shares the quest QR code and requires a passcode upon cashdrop collection)

### ✨ Improvements
- `Security`: sanitized quest memos before saving to database
- `Security`: enhancements on security issues on both server and app
- `Vaults`: sent vault refund to quest owner instead of subdividing it on vault owner, merchant and PurelyPeer
- `Stats`: enhanced stats fetching speed
- `Gallery`: ordered NFTs by transaction timestamp


# 0.8.2 <img src="https://img.shields.io/badge/History-v0.8.2-blue?style=flat-square" align="center" height="20" />

### 📦 Source File
- [Release APK](./apks/purelypeer-app-v0.8.2_android.apk)

### ✨ Improvements
- `Create Mode`: added media posting during quest creation
- `Create Mode`: added text moderation on quest name and memo
- `Explore Mode`: removed comment creation for unfunded quests
- `Notifications`: opens app when clicked and redirects to corresponding page
- `Notifications`: add push notifications when someone liked your comment(s)
- `Notifications`: add push notifications when someone commented on your quest(s)
- `Comments`: enhanced UI/UX
- `App`: optimized bundle size

### 🔧 Bug Fixes
- `Create Mode`: fixed bug on memo editing becoming null
- `Notifications`: fixed bug on multicast notifications for flagging cashdrops and unblocking users

# 0.8.1 <img src="https://img.shields.io/badge/History-v0.8.1-blue?style=flat-square" align="center" height="20" />

### 📦 Source File
- [Release APK](./apks/purelypeer-app-v0.8.1_android.apk)

### 🚀 Features
- `Create Mode`: users can now add media
- `Explore Mode`: users can now add comments
- `Quests`: added text (name, memo, media, comments) and image (media) moderation using OpenAI
- `Transactions`: added `OP_RETURN` tags to PurelyPeer transactions for better tracking

### ✨ Improvements
- `Texts`: simplified date formatting
- `Theme`: updated air theme buttons

### 🔧 Bug Fixes
- `Quest Details`: corrected cashdrops remaining count when quest is not yet active
- `Quest Details`: fixed blank URLs showing as unsafe


# 0.8.0 <img src="https://img.shields.io/badge/Status-Deprecated-red?style=flat-square" align="center" height="20" />

### 📦 Source File
- [Release APK](./apks/purelypeer-app-v0.8.0_android.apk)

### 🚀 Features
- `CashTokens`: added CashTokens support for wallets (send, receive, gallery, etc.)

### ✨ Improvements
- `Collect Mode`: added background OTP verification
- `Collect Mode`: added exploit analysis to prevent fake or automated collections
- `Notifications`: clicking notifications now redirect to their corresponding page
- `Transactions`: redesigned display of transaction history and handling of transactions
- `Onboarding`: enabled wallet importing during the onboarding process for a smoother setup experience

### 🔧 Bug Fixes
- `Create Mode`: fixed quest URL validation
- `Notifications`: fixed multicast push notifications not working
