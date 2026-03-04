# Telegram MTProto API — полная русская документация по объектам и типам

Источник структуры: официальный detailed schema JSON.

- Layer: **214**
- Базовых типов: **558**
- Конструкторов / объектов: **1479**

## Как читать записи

- Формат конструктора: `predicate(field:type, ...) => BaseType`.
- `BaseType` = абстрактный тип/семейство; конкретные объекты перечислены как его constructors.
- Для точной TL-страницы используй ссылки `type/...` и `constructor/...` Telegram.

## Содержание

- [AccountDaysTTL](#accountdaysttl) - 1 constructors
- [AttachMenuBot](#attachmenubot) - 1 constructors
- [AttachMenuBotIcon](#attachmenuboticon) - 1 constructors
- [AttachMenuBotIconColor](#attachmenuboticoncolor) - 1 constructors
- [AttachMenuBots](#attachmenubots) - 2 constructors
- [AttachMenuBotsBot](#attachmenubotsbot) - 1 constructors
- [AttachMenuPeerType](#attachmenupeertype) - 5 constructors
- [Authorization](#authorization) - 1 constructors
- [AutoDownloadSettings](#autodownloadsettings) - 1 constructors
- [AutoSaveException](#autosaveexception) - 1 constructors
- [AutoSaveSettings](#autosavesettings) - 1 constructors
- [AvailableEffect](#availableeffect) - 1 constructors
- [AvailableReaction](#availablereaction) - 1 constructors
- [BankCardOpenUrl](#bankcardopenurl) - 1 constructors
- [BaseTheme](#basetheme) - 5 constructors
- [Birthday](#birthday) - 1 constructors
- [Bool](#bool) - 2 constructors
- [Boost](#boost) - 1 constructors
- [BotApp](#botapp) - 2 constructors
- [BotAppSettings](#botappsettings) - 1 constructors
- [BotBusinessConnection](#botbusinessconnection) - 1 constructors
- [BotCommand](#botcommand) - 1 constructors
- [BotCommandScope](#botcommandscope) - 7 constructors
- [BotInfo](#botinfo) - 1 constructors
- [BotInlineMessage](#botinlinemessage) - 7 constructors
- [BotInlineResult](#botinlineresult) - 2 constructors
- [BotMenuButton](#botmenubutton) - 3 constructors
- [BotPreviewMedia](#botpreviewmedia) - 1 constructors
- [BotVerification](#botverification) - 1 constructors
- [BotVerifierSettings](#botverifiersettings) - 1 constructors
- [BusinessAwayMessage](#businessawaymessage) - 1 constructors
- [BusinessAwayMessageSchedule](#businessawaymessageschedule) - 3 constructors
- [BusinessBotRecipients](#businessbotrecipients) - 1 constructors
- [BusinessBotRights](#businessbotrights) - 1 constructors
- [BusinessChatLink](#businesschatlink) - 1 constructors
- [BusinessGreetingMessage](#businessgreetingmessage) - 1 constructors
- [BusinessIntro](#businessintro) - 1 constructors
- [BusinessLocation](#businesslocation) - 1 constructors
- [BusinessRecipients](#businessrecipients) - 1 constructors
- [BusinessWeeklyOpen](#businessweeklyopen) - 1 constructors
- [BusinessWorkHours](#businessworkhours) - 1 constructors
- [CdnConfig](#cdnconfig) - 1 constructors
- [CdnPublicKey](#cdnpublickey) - 1 constructors
- [ChannelAdminLogEvent](#channeladminlogevent) - 1 constructors
- [ChannelAdminLogEventAction](#channeladminlogeventaction) - 51 constructors
- [ChannelAdminLogEventsFilter](#channeladminlogeventsfilter) - 1 constructors
- [ChannelLocation](#channellocation) - 2 constructors
- [ChannelMessagesFilter](#channelmessagesfilter) - 2 constructors
- [ChannelParticipant](#channelparticipant) - 6 constructors
- [ChannelParticipantsFilter](#channelparticipantsfilter) - 8 constructors
- [Chat](#chat) - 5 constructors
- [ChatAdminRights](#chatadminrights) - 1 constructors
- [ChatAdminWithInvites](#chatadminwithinvites) - 1 constructors
- [ChatBannedRights](#chatbannedrights) - 1 constructors
- [ChatFull](#chatfull) - 2 constructors
- [ChatInvite](#chatinvite) - 3 constructors
- [ChatInviteImporter](#chatinviteimporter) - 1 constructors
- [ChatOnlines](#chatonlines) - 1 constructors
- [ChatParticipant](#chatparticipant) - 3 constructors
- [ChatParticipants](#chatparticipants) - 2 constructors
- [ChatPhoto](#chatphoto) - 2 constructors
- [ChatReactions](#chatreactions) - 3 constructors
- [ChatTheme](#chattheme) - 2 constructors
- [CodeSettings](#codesettings) - 1 constructors
- [Config](#config) - 1 constructors
- [ConnectedBot](#connectedbot) - 1 constructors
- [ConnectedBotStarRef](#connectedbotstarref) - 1 constructors
- [Contact](#contact) - 1 constructors
- [ContactBirthday](#contactbirthday) - 1 constructors
- [ContactStatus](#contactstatus) - 1 constructors
- [DataJSON](#datajson) - 1 constructors
- [DcOption](#dcoption) - 1 constructors
- [DefaultHistoryTTL](#defaulthistoryttl) - 1 constructors
- [Dialog](#dialog) - 2 constructors
- [DialogFilter](#dialogfilter) - 3 constructors
- [DialogFilterSuggested](#dialogfiltersuggested) - 1 constructors
- [DialogPeer](#dialogpeer) - 2 constructors
- [DisallowedGiftsSettings](#disallowedgiftssettings) - 1 constructors
- [Document](#document) - 2 constructors
- [DocumentAttribute](#documentattribute) - 8 constructors
- [DraftMessage](#draftmessage) - 2 constructors
- [EmailVerification](#emailverification) - 3 constructors
- [EmailVerifyPurpose](#emailverifypurpose) - 3 constructors
- [EmojiGroup](#emojigroup) - 3 constructors
- [EmojiKeyword](#emojikeyword) - 2 constructors
- [EmojiKeywordsDifference](#emojikeywordsdifference) - 1 constructors
- [EmojiLanguage](#emojilanguage) - 1 constructors
- [EmojiList](#emojilist) - 2 constructors
- [EmojiStatus](#emojistatus) - 4 constructors
- [EmojiURL](#emojiurl) - 1 constructors
- [EncryptedChat](#encryptedchat) - 5 constructors
- [EncryptedFile](#encryptedfile) - 2 constructors
- [EncryptedMessage](#encryptedmessage) - 2 constructors
- [Error](#error) - 1 constructors
- [ExportedChatInvite](#exportedchatinvite) - 2 constructors
- [ExportedChatlistInvite](#exportedchatlistinvite) - 1 constructors
- [ExportedContactToken](#exportedcontacttoken) - 1 constructors
- [ExportedMessageLink](#exportedmessagelink) - 1 constructors
- [ExportedStoryLink](#exportedstorylink) - 1 constructors
- [FactCheck](#factcheck) - 1 constructors
- [FileHash](#filehash) - 1 constructors
- [Folder](#folder) - 1 constructors
- [FolderPeer](#folderpeer) - 1 constructors
- [ForumTopic](#forumtopic) - 2 constructors
- [FoundStory](#foundstory) - 1 constructors
- [Game](#game) - 1 constructors
- [GeoPoint](#geopoint) - 2 constructors
- [GeoPointAddress](#geopointaddress) - 1 constructors
- [GlobalPrivacySettings](#globalprivacysettings) - 1 constructors
- [GroupCall](#groupcall) - 2 constructors
- [GroupCallParticipant](#groupcallparticipant) - 1 constructors
- [GroupCallParticipantVideo](#groupcallparticipantvideo) - 1 constructors
- [GroupCallParticipantVideoSourceGroup](#groupcallparticipantvideosourcegroup) - 1 constructors
- [GroupCallStreamChannel](#groupcallstreamchannel) - 1 constructors
- [HighScore](#highscore) - 1 constructors
- [ImportedContact](#importedcontact) - 1 constructors
- [InlineBotSwitchPM](#inlinebotswitchpm) - 1 constructors
- [InlineBotWebView](#inlinebotwebview) - 1 constructors
- [InlineQueryPeerType](#inlinequerypeertype) - 6 constructors
- [InputAppEvent](#inputappevent) - 1 constructors
- [InputBotApp](#inputbotapp) - 2 constructors
- [InputBotInlineMessage](#inputbotinlinemessage) - 8 constructors
- [InputBotInlineMessageID](#inputbotinlinemessageid) - 2 constructors
- [InputBotInlineResult](#inputbotinlineresult) - 4 constructors
- [InputBusinessAwayMessage](#inputbusinessawaymessage) - 1 constructors
- [InputBusinessBotRecipients](#inputbusinessbotrecipients) - 1 constructors
- [InputBusinessChatLink](#inputbusinesschatlink) - 1 constructors
- [InputBusinessGreetingMessage](#inputbusinessgreetingmessage) - 1 constructors
- [InputBusinessIntro](#inputbusinessintro) - 1 constructors
- [InputBusinessRecipients](#inputbusinessrecipients) - 1 constructors
- [InputChannel](#inputchannel) - 3 constructors
- [InputChatPhoto](#inputchatphoto) - 3 constructors
- [InputChatTheme](#inputchattheme) - 3 constructors
- [InputChatlist](#inputchatlist) - 1 constructors
- [InputCheckPasswordSRP](#inputcheckpasswordsrp) - 2 constructors
- [InputClientProxy](#inputclientproxy) - 1 constructors
- [InputCollectible](#inputcollectible) - 2 constructors
- [InputContact](#inputcontact) - 1 constructors
- [InputDialogPeer](#inputdialogpeer) - 2 constructors
- [InputDocument](#inputdocument) - 2 constructors
- [InputEncryptedChat](#inputencryptedchat) - 1 constructors
- [InputEncryptedFile](#inputencryptedfile) - 4 constructors
- [InputFile](#inputfile) - 3 constructors
- [InputFileLocation](#inputfilelocation) - 10 constructors
- [InputFolderPeer](#inputfolderpeer) - 1 constructors
- [InputGame](#inputgame) - 2 constructors
- [InputGeoPoint](#inputgeopoint) - 2 constructors
- [InputGroupCall](#inputgroupcall) - 3 constructors
- [InputInvoice](#inputinvoice) - 12 constructors
- [InputMedia](#inputmedia) - 19 constructors
- [InputMessage](#inputmessage) - 4 constructors
- [InputNotifyPeer](#inputnotifypeer) - 5 constructors
- [InputPaymentCredentials](#inputpaymentcredentials) - 4 constructors
- [InputPeer](#inputpeer) - 7 constructors
- [InputPeerNotifySettings](#inputpeernotifysettings) - 1 constructors
- [InputPhoneCall](#inputphonecall) - 1 constructors
- [InputPhoto](#inputphoto) - 2 constructors
- [InputPrivacyKey](#inputprivacykey) - 13 constructors
- [InputPrivacyRule](#inputprivacyrule) - 12 constructors
- [InputQuickReplyShortcut](#inputquickreplyshortcut) - 2 constructors
- [InputReplyTo](#inputreplyto) - 3 constructors
- [InputSavedStarGift](#inputsavedstargift) - 3 constructors
- [InputSecureFile](#inputsecurefile) - 2 constructors
- [InputSecureValue](#inputsecurevalue) - 1 constructors
- [InputSingleMedia](#inputsinglemedia) - 1 constructors
- [InputStarsTransaction](#inputstarstransaction) - 1 constructors
- [InputStickerSet](#inputstickerset) - 12 constructors
- [InputStickerSetItem](#inputstickersetitem) - 1 constructors
- [InputStickeredMedia](#inputstickeredmedia) - 2 constructors
- [InputStorePaymentPurpose](#inputstorepaymentpurpose) - 8 constructors
- [InputTheme](#inputtheme) - 2 constructors
- [InputThemeSettings](#inputthemesettings) - 1 constructors
- [InputUser](#inputuser) - 4 constructors
- [InputWallPaper](#inputwallpaper) - 3 constructors
- [InputWebDocument](#inputwebdocument) - 1 constructors
- [InputWebFileLocation](#inputwebfilelocation) - 3 constructors
- [Invoice](#invoice) - 1 constructors
- [JSONObjectValue](#jsonobjectvalue) - 1 constructors
- [JSONValue](#jsonvalue) - 6 constructors
- [KeyboardButton](#keyboardbutton) - 18 constructors
- [KeyboardButtonRow](#keyboardbuttonrow) - 1 constructors
- [LabeledPrice](#labeledprice) - 1 constructors
- [LangPackDifference](#langpackdifference) - 1 constructors
- [LangPackLanguage](#langpacklanguage) - 1 constructors
- [LangPackString](#langpackstring) - 3 constructors
- [MaskCoords](#maskcoords) - 1 constructors
- [MediaArea](#mediaarea) - 9 constructors
- [MediaAreaCoordinates](#mediaareacoordinates) - 1 constructors
- [Message](#message) - 3 constructors
- [MessageAction](#messageaction) - 57 constructors
- [MessageEntity](#messageentity) - 21 constructors
- [MessageExtendedMedia](#messageextendedmedia) - 2 constructors
- [MessageFwdHeader](#messagefwdheader) - 1 constructors
- [MessageMedia](#messagemedia) - 18 constructors
- [MessagePeerReaction](#messagepeerreaction) - 1 constructors
- [MessagePeerVote](#messagepeervote) - 3 constructors
- [MessageRange](#messagerange) - 1 constructors
- [MessageReactions](#messagereactions) - 1 constructors
- [MessageReactor](#messagereactor) - 1 constructors
- [MessageReplies](#messagereplies) - 1 constructors
- [MessageReplyHeader](#messagereplyheader) - 2 constructors
- [MessageReportOption](#messagereportoption) - 1 constructors
- [MessageViews](#messageviews) - 1 constructors
- [MessagesFilter](#messagesfilter) - 17 constructors
- [MissingInvitee](#missinginvitee) - 1 constructors
- [MyBoost](#myboost) - 1 constructors
- [NearestDc](#nearestdc) - 1 constructors
- [NotificationSound](#notificationsound) - 4 constructors
- [NotifyPeer](#notifypeer) - 5 constructors
- [Null](#null) - 1 constructors
- [OutboxReadDate](#outboxreaddate) - 1 constructors
- [Page](#page) - 1 constructors
- [PageBlock](#pageblock) - 29 constructors
- [PageCaption](#pagecaption) - 1 constructors
- [PageListItem](#pagelistitem) - 2 constructors
- [PageListOrderedItem](#pagelistordereditem) - 2 constructors
- [PageRelatedArticle](#pagerelatedarticle) - 1 constructors
- [PageTableCell](#pagetablecell) - 1 constructors
- [PageTableRow](#pagetablerow) - 1 constructors
- [PaidReactionPrivacy](#paidreactionprivacy) - 3 constructors
- [PasswordKdfAlgo](#passwordkdfalgo) - 2 constructors
- [PaymentCharge](#paymentcharge) - 1 constructors
- [PaymentFormMethod](#paymentformmethod) - 1 constructors
- [PaymentRequestedInfo](#paymentrequestedinfo) - 1 constructors
- [PaymentSavedCredentials](#paymentsavedcredentials) - 1 constructors
- [Peer](#peer) - 3 constructors
- [PeerBlocked](#peerblocked) - 1 constructors
- [PeerColor](#peercolor) - 1 constructors
- [PeerLocated](#peerlocated) - 2 constructors
- [PeerNotifySettings](#peernotifysettings) - 1 constructors
- [PeerSettings](#peersettings) - 1 constructors
- [PeerStories](#peerstories) - 1 constructors
- [PendingSuggestion](#pendingsuggestion) - 1 constructors
- [PhoneCall](#phonecall) - 6 constructors
- [PhoneCallDiscardReason](#phonecalldiscardreason) - 5 constructors
- [PhoneCallProtocol](#phonecallprotocol) - 1 constructors
- [PhoneConnection](#phoneconnection) - 2 constructors
- [Photo](#photo) - 2 constructors
- [PhotoSize](#photosize) - 6 constructors
- [Poll](#poll) - 1 constructors
- [PollAnswer](#pollanswer) - 1 constructors
- [PollAnswerVoters](#pollanswervoters) - 1 constructors
- [PollResults](#pollresults) - 1 constructors
- [PopularContact](#popularcontact) - 1 constructors
- [PostAddress](#postaddress) - 1 constructors
- [PostInteractionCounters](#postinteractioncounters) - 2 constructors
- [PremiumGiftCodeOption](#premiumgiftcodeoption) - 1 constructors
- [PremiumSubscriptionOption](#premiumsubscriptionoption) - 1 constructors
- [PrepaidGiveaway](#prepaidgiveaway) - 2 constructors
- [PrivacyKey](#privacykey) - 13 constructors
- [PrivacyRule](#privacyrule) - 12 constructors
- [ProfileTab](#profiletab) - 8 constructors
- [PublicForward](#publicforward) - 2 constructors
- [QuickReply](#quickreply) - 1 constructors
- [Reaction](#reaction) - 4 constructors
- [ReactionCount](#reactioncount) - 1 constructors
- [ReactionNotificationsFrom](#reactionnotificationsfrom) - 2 constructors
- [ReactionsNotifySettings](#reactionsnotifysettings) - 1 constructors
- [ReadParticipantDate](#readparticipantdate) - 1 constructors
- [ReceivedNotifyMessage](#receivednotifymessage) - 1 constructors
- [RecentMeUrl](#recentmeurl) - 5 constructors
- [ReplyMarkup](#replymarkup) - 4 constructors
- [ReportReason](#reportreason) - 10 constructors
- [ReportResult](#reportresult) - 3 constructors
- [RequestPeerType](#requestpeertype) - 3 constructors
- [RequestedPeer](#requestedpeer) - 3 constructors
- [RequirementToContact](#requirementtocontact) - 3 constructors
- [RestrictionReason](#restrictionreason) - 1 constructors
- [RichText](#richtext) - 16 constructors
- [SavedContact](#savedcontact) - 1 constructors
- [SavedDialog](#saveddialog) - 2 constructors
- [SavedReactionTag](#savedreactiontag) - 1 constructors
- [SavedStarGift](#savedstargift) - 1 constructors
- [SearchPostsFlood](#searchpostsflood) - 1 constructors
- [SearchResultsCalendarPeriod](#searchresultscalendarperiod) - 1 constructors
- [SearchResultsPosition](#searchresultsposition) - 1 constructors
- [SecureCredentialsEncrypted](#securecredentialsencrypted) - 1 constructors
- [SecureData](#securedata) - 1 constructors
- [SecureFile](#securefile) - 2 constructors
- [SecurePasswordKdfAlgo](#securepasswordkdfalgo) - 3 constructors
- [SecurePlainData](#secureplaindata) - 2 constructors
- [SecureRequiredType](#securerequiredtype) - 2 constructors
- [SecureSecretSettings](#securesecretsettings) - 1 constructors
- [SecureValue](#securevalue) - 1 constructors
- [SecureValueError](#securevalueerror) - 9 constructors
- [SecureValueHash](#securevaluehash) - 1 constructors
- [SecureValueType](#securevaluetype) - 13 constructors
- [SendAsPeer](#sendaspeer) - 1 constructors
- [SendMessageAction](#sendmessageaction) - 18 constructors
- [ShippingOption](#shippingoption) - 1 constructors
- [SmsJob](#smsjob) - 1 constructors
- [SponsoredMessage](#sponsoredmessage) - 1 constructors
- [SponsoredMessageReportOption](#sponsoredmessagereportoption) - 1 constructors
- [SponsoredPeer](#sponsoredpeer) - 1 constructors
- [StarGift](#stargift) - 2 constructors
- [StarGiftAttribute](#stargiftattribute) - 4 constructors
- [StarGiftAttributeCounter](#stargiftattributecounter) - 1 constructors
- [StarGiftAttributeId](#stargiftattributeid) - 3 constructors
- [StarGiftCollection](#stargiftcollection) - 1 constructors
- [StarRefProgram](#starrefprogram) - 1 constructors
- [StarsAmount](#starsamount) - 2 constructors
- [StarsGiftOption](#starsgiftoption) - 1 constructors
- [StarsGiveawayOption](#starsgiveawayoption) - 1 constructors
- [StarsGiveawayWinnersOption](#starsgiveawaywinnersoption) - 1 constructors
- [StarsRating](#starsrating) - 1 constructors
- [StarsRevenueStatus](#starsrevenuestatus) - 1 constructors
- [StarsSubscription](#starssubscription) - 1 constructors
- [StarsSubscriptionPricing](#starssubscriptionpricing) - 1 constructors
- [StarsTopupOption](#starstopupoption) - 1 constructors
- [StarsTransaction](#starstransaction) - 1 constructors
- [StarsTransactionPeer](#starstransactionpeer) - 8 constructors
- [StatsAbsValueAndPrev](#statsabsvalueandprev) - 1 constructors
- [StatsDateRangeDays](#statsdaterangedays) - 1 constructors
- [StatsGraph](#statsgraph) - 3 constructors
- [StatsGroupTopAdmin](#statsgrouptopadmin) - 1 constructors
- [StatsGroupTopInviter](#statsgrouptopinviter) - 1 constructors
- [StatsGroupTopPoster](#statsgrouptopposter) - 1 constructors
- [StatsPercentValue](#statspercentvalue) - 1 constructors
- [StatsURL](#statsurl) - 1 constructors
- [StickerKeyword](#stickerkeyword) - 1 constructors
- [StickerPack](#stickerpack) - 1 constructors
- [StickerSet](#stickerset) - 1 constructors
- [StickerSetCovered](#stickersetcovered) - 4 constructors
- [StoriesStealthMode](#storiesstealthmode) - 1 constructors
- [StoryAlbum](#storyalbum) - 1 constructors
- [StoryFwdHeader](#storyfwdheader) - 1 constructors
- [StoryItem](#storyitem) - 3 constructors
- [StoryReaction](#storyreaction) - 3 constructors
- [StoryView](#storyview) - 3 constructors
- [StoryViews](#storyviews) - 1 constructors
- [SuggestedPost](#suggestedpost) - 1 constructors
- [TextWithEntities](#textwithentities) - 1 constructors
- [Theme](#theme) - 1 constructors
- [ThemeSettings](#themesettings) - 1 constructors
- [Timezone](#timezone) - 1 constructors
- [TodoCompletion](#todocompletion) - 1 constructors
- [TodoItem](#todoitem) - 1 constructors
- [TodoList](#todolist) - 1 constructors
- [TopPeer](#toppeer) - 1 constructors
- [TopPeerCategory](#toppeercategory) - 9 constructors
- [TopPeerCategoryPeers](#toppeercategorypeers) - 1 constructors
- [True](#true) - 1 constructors
- [Update](#update) - 145 constructors
- [Updates](#updates) - 7 constructors
- [UrlAuthResult](#urlauthresult) - 3 constructors
- [User](#user) - 2 constructors
- [UserFull](#userfull) - 1 constructors
- [UserProfilePhoto](#userprofilephoto) - 2 constructors
- [UserStatus](#userstatus) - 6 constructors
- [Username](#username) - 1 constructors
- [Vector t](#vector-t) - 1 constructors
- [VideoSize](#videosize) - 3 constructors
- [WallPaper](#wallpaper) - 2 constructors
- [WallPaperSettings](#wallpapersettings) - 1 constructors
- [WebAuthorization](#webauthorization) - 1 constructors
- [WebDocument](#webdocument) - 2 constructors
- [WebPage](#webpage) - 4 constructors
- [WebPageAttribute](#webpageattribute) - 5 constructors
- [WebViewMessageSent](#webviewmessagesent) - 1 constructors
- [WebViewResult](#webviewresult) - 1 constructors
- [account.AuthorizationForm](#account-authorizationform) - 1 constructors
- [account.Authorizations](#account-authorizations) - 1 constructors
- [account.AutoDownloadSettings](#account-autodownloadsettings) - 1 constructors
- [account.AutoSaveSettings](#account-autosavesettings) - 1 constructors
- [account.BusinessChatLinks](#account-businesschatlinks) - 1 constructors
- [account.ChatThemes](#account-chatthemes) - 2 constructors
- [account.ConnectedBots](#account-connectedbots) - 1 constructors
- [account.ContentSettings](#account-contentsettings) - 1 constructors
- [account.EmailVerified](#account-emailverified) - 2 constructors
- [account.EmojiStatuses](#account-emojistatuses) - 2 constructors
- [account.PaidMessagesRevenue](#account-paidmessagesrevenue) - 1 constructors
- [account.Password](#account-password) - 1 constructors
- [account.PasswordInputSettings](#account-passwordinputsettings) - 1 constructors
- [account.PasswordSettings](#account-passwordsettings) - 1 constructors
- [account.PrivacyRules](#account-privacyrules) - 1 constructors
- [account.ResetPasswordResult](#account-resetpasswordresult) - 3 constructors
- [account.ResolvedBusinessChatLinks](#account-resolvedbusinesschatlinks) - 1 constructors
- [account.SavedMusicIds](#account-savedmusicids) - 2 constructors
- [account.SavedRingtone](#account-savedringtone) - 2 constructors
- [account.SavedRingtones](#account-savedringtones) - 2 constructors
- [account.SentEmailCode](#account-sentemailcode) - 1 constructors
- [account.Takeout](#account-takeout) - 1 constructors
- [account.Themes](#account-themes) - 2 constructors
- [account.TmpPassword](#account-tmppassword) - 1 constructors
- [account.WallPapers](#account-wallpapers) - 2 constructors
- [account.WebAuthorizations](#account-webauthorizations) - 1 constructors
- [auth.Authorization](#auth-authorization) - 2 constructors
- [auth.CodeType](#auth-codetype) - 5 constructors
- [auth.ExportedAuthorization](#auth-exportedauthorization) - 1 constructors
- [auth.LoggedOut](#auth-loggedout) - 1 constructors
- [auth.LoginToken](#auth-logintoken) - 3 constructors
- [auth.PasswordRecovery](#auth-passwordrecovery) - 1 constructors
- [auth.SentCode](#auth-sentcode) - 3 constructors
- [auth.SentCodeType](#auth-sentcodetype) - 11 constructors
- [bots.BotInfo](#bots-botinfo) - 1 constructors
- [bots.PopularAppBots](#bots-popularappbots) - 1 constructors
- [bots.PreviewInfo](#bots-previewinfo) - 1 constructors
- [channels.AdminLogResults](#channels-adminlogresults) - 1 constructors
- [channels.ChannelParticipant](#channels-channelparticipant) - 1 constructors
- [channels.ChannelParticipants](#channels-channelparticipants) - 2 constructors
- [channels.SendAsPeers](#channels-sendaspeers) - 1 constructors
- [channels.SponsoredMessageReportResult](#channels-sponsoredmessagereportresult) - 3 constructors
- [chatlists.ChatlistInvite](#chatlists-chatlistinvite) - 2 constructors
- [chatlists.ChatlistUpdates](#chatlists-chatlistupdates) - 1 constructors
- [chatlists.ExportedChatlistInvite](#chatlists-exportedchatlistinvite) - 1 constructors
- [chatlists.ExportedInvites](#chatlists-exportedinvites) - 1 constructors
- [contacts.Blocked](#contacts-blocked) - 2 constructors
- [contacts.ContactBirthdays](#contacts-contactbirthdays) - 1 constructors
- [contacts.Contacts](#contacts-contacts) - 2 constructors
- [contacts.Found](#contacts-found) - 1 constructors
- [contacts.ImportedContacts](#contacts-importedcontacts) - 1 constructors
- [contacts.ResolvedPeer](#contacts-resolvedpeer) - 1 constructors
- [contacts.SponsoredPeers](#contacts-sponsoredpeers) - 2 constructors
- [contacts.TopPeers](#contacts-toppeers) - 3 constructors
- [fragment.CollectibleInfo](#fragment-collectibleinfo) - 1 constructors
- [help.AppConfig](#help-appconfig) - 2 constructors
- [help.AppUpdate](#help-appupdate) - 2 constructors
- [help.CountriesList](#help-countrieslist) - 2 constructors
- [help.Country](#help-country) - 1 constructors
- [help.CountryCode](#help-countrycode) - 1 constructors
- [help.DeepLinkInfo](#help-deeplinkinfo) - 2 constructors
- [help.InviteText](#help-invitetext) - 1 constructors
- [help.PassportConfig](#help-passportconfig) - 2 constructors
- [help.PeerColorOption](#help-peercoloroption) - 1 constructors
- [help.PeerColorSet](#help-peercolorset) - 2 constructors
- [help.PeerColors](#help-peercolors) - 2 constructors
- [help.PremiumPromo](#help-premiumpromo) - 1 constructors
- [help.PromoData](#help-promodata) - 2 constructors
- [help.RecentMeUrls](#help-recentmeurls) - 1 constructors
- [help.Support](#help-support) - 1 constructors
- [help.SupportName](#help-supportname) - 1 constructors
- [help.TermsOfService](#help-termsofservice) - 1 constructors
- [help.TermsOfServiceUpdate](#help-termsofserviceupdate) - 2 constructors
- [help.TimezonesList](#help-timezoneslist) - 2 constructors
- [help.UserInfo](#help-userinfo) - 2 constructors
- [messages.AffectedFoundMessages](#messages-affectedfoundmessages) - 1 constructors
- [messages.AffectedHistory](#messages-affectedhistory) - 1 constructors
- [messages.AffectedMessages](#messages-affectedmessages) - 1 constructors
- [messages.AllStickers](#messages-allstickers) - 2 constructors
- [messages.ArchivedStickers](#messages-archivedstickers) - 1 constructors
- [messages.AvailableEffects](#messages-availableeffects) - 2 constructors
- [messages.AvailableReactions](#messages-availablereactions) - 2 constructors
- [messages.BotApp](#messages-botapp) - 1 constructors
- [messages.BotCallbackAnswer](#messages-botcallbackanswer) - 1 constructors
- [messages.BotPreparedInlineMessage](#messages-botpreparedinlinemessage) - 1 constructors
- [messages.BotResults](#messages-botresults) - 1 constructors
- [messages.ChatAdminsWithInvites](#messages-chatadminswithinvites) - 1 constructors
- [messages.ChatFull](#messages-chatfull) - 1 constructors
- [messages.ChatInviteImporters](#messages-chatinviteimporters) - 1 constructors
- [messages.Chats](#messages-chats) - 2 constructors
- [messages.CheckedHistoryImportPeer](#messages-checkedhistoryimportpeer) - 1 constructors
- [messages.DhConfig](#messages-dhconfig) - 2 constructors
- [messages.DialogFilters](#messages-dialogfilters) - 1 constructors
- [messages.Dialogs](#messages-dialogs) - 3 constructors
- [messages.DiscussionMessage](#messages-discussionmessage) - 1 constructors
- [messages.EmojiGroups](#messages-emojigroups) - 2 constructors
- [messages.ExportedChatInvite](#messages-exportedchatinvite) - 2 constructors
- [messages.ExportedChatInvites](#messages-exportedchatinvites) - 1 constructors
- [messages.FavedStickers](#messages-favedstickers) - 2 constructors
- [messages.FeaturedStickers](#messages-featuredstickers) - 2 constructors
- [messages.ForumTopics](#messages-forumtopics) - 1 constructors
- [messages.FoundStickerSets](#messages-foundstickersets) - 2 constructors
- [messages.FoundStickers](#messages-foundstickers) - 2 constructors
- [messages.HighScores](#messages-highscores) - 1 constructors
- [messages.HistoryImport](#messages-historyimport) - 1 constructors
- [messages.HistoryImportParsed](#messages-historyimportparsed) - 1 constructors
- [messages.InactiveChats](#messages-inactivechats) - 1 constructors
- [messages.InvitedUsers](#messages-invitedusers) - 1 constructors
- [messages.MessageEditData](#messages-messageeditdata) - 1 constructors
- [messages.MessageReactionsList](#messages-messagereactionslist) - 1 constructors
- [messages.MessageViews](#messages-messageviews) - 1 constructors
- [messages.Messages](#messages-messages) - 4 constructors
- [messages.MyStickers](#messages-mystickers) - 1 constructors
- [messages.PeerDialogs](#messages-peerdialogs) - 1 constructors
- [messages.PeerSettings](#messages-peersettings) - 1 constructors
- [messages.PreparedInlineMessage](#messages-preparedinlinemessage) - 1 constructors
- [messages.QuickReplies](#messages-quickreplies) - 2 constructors
- [messages.Reactions](#messages-reactions) - 2 constructors
- [messages.RecentStickers](#messages-recentstickers) - 2 constructors
- [messages.SavedDialogs](#messages-saveddialogs) - 3 constructors
- [messages.SavedGifs](#messages-savedgifs) - 2 constructors
- [messages.SavedReactionTags](#messages-savedreactiontags) - 2 constructors
- [messages.SearchCounter](#messages-searchcounter) - 1 constructors
- [messages.SearchResultsCalendar](#messages-searchresultscalendar) - 1 constructors
- [messages.SearchResultsPositions](#messages-searchresultspositions) - 1 constructors
- [messages.SentEncryptedMessage](#messages-sentencryptedmessage) - 2 constructors
- [messages.SponsoredMessages](#messages-sponsoredmessages) - 2 constructors
- [messages.StickerSet](#messages-stickerset) - 2 constructors
- [messages.StickerSetInstallResult](#messages-stickersetinstallresult) - 2 constructors
- [messages.Stickers](#messages-stickers) - 2 constructors
- [messages.TranscribedAudio](#messages-transcribedaudio) - 1 constructors
- [messages.TranslatedText](#messages-translatedtext) - 1 constructors
- [messages.VotesList](#messages-voteslist) - 1 constructors
- [messages.WebPage](#messages-webpage) - 1 constructors
- [messages.WebPagePreview](#messages-webpagepreview) - 1 constructors
- [payments.BankCardData](#payments-bankcarddata) - 1 constructors
- [payments.CheckCanSendGiftResult](#payments-checkcansendgiftresult) - 2 constructors
- [payments.CheckedGiftCode](#payments-checkedgiftcode) - 1 constructors
- [payments.ConnectedStarRefBots](#payments-connectedstarrefbots) - 1 constructors
- [payments.ExportedInvoice](#payments-exportedinvoice) - 1 constructors
- [payments.GiveawayInfo](#payments-giveawayinfo) - 2 constructors
- [payments.PaymentForm](#payments-paymentform) - 3 constructors
- [payments.PaymentReceipt](#payments-paymentreceipt) - 2 constructors
- [payments.PaymentResult](#payments-paymentresult) - 2 constructors
- [payments.ResaleStarGifts](#payments-resalestargifts) - 1 constructors
- [payments.SavedInfo](#payments-savedinfo) - 1 constructors
- [payments.SavedStarGifts](#payments-savedstargifts) - 1 constructors
- [payments.StarGiftCollections](#payments-stargiftcollections) - 2 constructors
- [payments.StarGiftUpgradePreview](#payments-stargiftupgradepreview) - 1 constructors
- [payments.StarGiftWithdrawalUrl](#payments-stargiftwithdrawalurl) - 1 constructors
- [payments.StarGifts](#payments-stargifts) - 2 constructors
- [payments.StarsRevenueAdsAccountUrl](#payments-starsrevenueadsaccounturl) - 1 constructors
- [payments.StarsRevenueStats](#payments-starsrevenuestats) - 1 constructors
- [payments.StarsRevenueWithdrawalUrl](#payments-starsrevenuewithdrawalurl) - 1 constructors
- [payments.StarsStatus](#payments-starsstatus) - 1 constructors
- [payments.SuggestedStarRefBots](#payments-suggestedstarrefbots) - 1 constructors
- [payments.UniqueStarGift](#payments-uniquestargift) - 1 constructors
- [payments.UniqueStarGiftValueInfo](#payments-uniquestargiftvalueinfo) - 1 constructors
- [payments.ValidatedRequestedInfo](#payments-validatedrequestedinfo) - 1 constructors
- [phone.ExportedGroupCallInvite](#phone-exportedgroupcallinvite) - 1 constructors
- [phone.GroupCall](#phone-groupcall) - 1 constructors
- [phone.GroupCallStreamChannels](#phone-groupcallstreamchannels) - 1 constructors
- [phone.GroupCallStreamRtmpUrl](#phone-groupcallstreamrtmpurl) - 1 constructors
- [phone.GroupParticipants](#phone-groupparticipants) - 1 constructors
- [phone.JoinAsPeers](#phone-joinaspeers) - 1 constructors
- [phone.PhoneCall](#phone-phonecall) - 1 constructors
- [photos.Photo](#photos-photo) - 1 constructors
- [photos.Photos](#photos-photos) - 2 constructors
- [premium.BoostsList](#premium-boostslist) - 1 constructors
- [premium.BoostsStatus](#premium-boostsstatus) - 1 constructors
- [premium.MyBoosts](#premium-myboosts) - 1 constructors
- [smsjobs.EligibilityToJoin](#smsjobs-eligibilitytojoin) - 1 constructors
- [smsjobs.Status](#smsjobs-status) - 1 constructors
- [stats.BroadcastStats](#stats-broadcaststats) - 1 constructors
- [stats.MegagroupStats](#stats-megagroupstats) - 1 constructors
- [stats.MessageStats](#stats-messagestats) - 1 constructors
- [stats.PublicForwards](#stats-publicforwards) - 1 constructors
- [stats.StoryStats](#stats-storystats) - 1 constructors
- [stickers.SuggestedShortName](#stickers-suggestedshortname) - 1 constructors
- [storage.FileType](#storage-filetype) - 10 constructors
- [stories.Albums](#stories-albums) - 2 constructors
- [stories.AllStories](#stories-allstories) - 2 constructors
- [stories.CanSendStoryCount](#stories-cansendstorycount) - 1 constructors
- [stories.FoundStories](#stories-foundstories) - 1 constructors
- [stories.PeerStories](#stories-peerstories) - 1 constructors
- [stories.Stories](#stories-stories) - 1 constructors
- [stories.StoryReactionsList](#stories-storyreactionslist) - 1 constructors
- [stories.StoryViews](#stories-storyviews) - 1 constructors
- [stories.StoryViewsList](#stories-storyviewslist) - 1 constructors
- [updates.ChannelDifference](#updates-channeldifference) - 3 constructors
- [updates.Difference](#updates-difference) - 4 constructors
- [updates.State](#updates-state) - 1 constructors
- [upload.CdnFile](#upload-cdnfile) - 2 constructors
- [upload.File](#upload-file) - 2 constructors
- [upload.WebFile](#upload-webfile) - 1 constructors
- [users.SavedMusic](#users-savedmusic) - 2 constructors
- [users.UserFull](#users-userfull) - 1 constructors
- [users.Users](#users-users) - 2 constructors

## `AccountDaysTTL`

- Официальный тип: https://core.telegram.org/type/AccountDaysTTL
- Количество constructors: **1**

### `accountDaysTTL`

- ID: `-1194283041` / `0xb8d0afdf`
- Сигнатура: `accountDaysTTL(days:int) => AccountDaysTTL`
- Официальная страница конструктора: https://core.telegram.org/constructor/accountDaysTTL
- Поля:
  - `days`: `int`

## `AttachMenuBot`

- Официальный тип: https://core.telegram.org/type/AttachMenuBot
- Количество constructors: **1**

### `attachMenuBot`

- ID: `-653423106` / `0xd90d8dfe`
- Сигнатура: `attachMenuBot(flags:#, inactive:flags.0?true, has_settings:flags.1?true, request_write_access:flags.2?true, show_in_attach_menu:flags.3?true, show_in_side_menu:flags.4?true, side_menu_disclaimer_needed:flags.5?true, bot_id:long, short_name:string, peer_types:flags.3?Vector, icons:Vector) => AttachMenuBot`
- Официальная страница конструктора: https://core.telegram.org/constructor/attachMenuBot
- Поля:
  - `flags`: `#` - служебное поле flags
  - `inactive`: `flags.0?true` - optional через flags.0
  - `has_settings`: `flags.1?true` - optional через flags.1
  - `request_write_access`: `flags.2?true` - optional через flags.2
  - `show_in_attach_menu`: `flags.3?true` - optional через flags.3
  - `show_in_side_menu`: `flags.4?true` - optional через flags.4
  - `side_menu_disclaimer_needed`: `flags.5?true` - optional через flags.5
  - `bot_id`: `long`
  - `short_name`: `string`
  - `peer_types`: `flags.3?Vector` - optional через flags.3
  - `icons`: `Vector`

## `AttachMenuBotIcon`

- Официальный тип: https://core.telegram.org/type/AttachMenuBotIcon
- Количество constructors: **1**

### `attachMenuBotIcon`

- ID: `-1297663893` / `0xb2a7386b`
- Сигнатура: `attachMenuBotIcon(flags:#, name:string, icon:Document, colors:flags.0?Vector) => AttachMenuBotIcon`
- Официальная страница конструктора: https://core.telegram.org/constructor/attachMenuBotIcon
- Поля:
  - `flags`: `#` - служебное поле flags
  - `name`: `string`
  - `icon`: `Document`
  - `colors`: `flags.0?Vector` - optional через flags.0

## `AttachMenuBotIconColor`

- Официальный тип: https://core.telegram.org/type/AttachMenuBotIconColor
- Количество constructors: **1**

### `attachMenuBotIconColor`

- ID: `1165423600` / `0x4576f3f0`
- Сигнатура: `attachMenuBotIconColor(name:string, color:int) => AttachMenuBotIconColor`
- Официальная страница конструктора: https://core.telegram.org/constructor/attachMenuBotIconColor
- Поля:
  - `name`: `string`
  - `color`: `int`

## `AttachMenuBots`

- Официальный тип: https://core.telegram.org/type/AttachMenuBots
- Количество constructors: **2**

### `attachMenuBots`

- ID: `1011024320` / `0x3c4301c0`
- Сигнатура: `attachMenuBots(hash:long, bots:Vector, users:Vector) => AttachMenuBots`
- Официальная страница конструктора: https://core.telegram.org/constructor/attachMenuBots
- Поля:
  - `hash`: `long`
  - `bots`: `Vector`
  - `users`: `Vector`

### `attachMenuBotsNotModified`

- ID: `-237467044` / `0xf1d88a5c`
- Сигнатура: `attachMenuBotsNotModified() => AttachMenuBots`
- Официальная страница конструктора: https://core.telegram.org/constructor/attachMenuBotsNotModified
- Поля:
  - Нет полей.

## `AttachMenuBotsBot`

- Официальный тип: https://core.telegram.org/type/AttachMenuBotsBot
- Количество constructors: **1**

### `attachMenuBotsBot`

- ID: `-1816172929` / `0x93bf667f`
- Сигнатура: `attachMenuBotsBot(bot:AttachMenuBot, users:Vector) => AttachMenuBotsBot`
- Официальная страница конструктора: https://core.telegram.org/constructor/attachMenuBotsBot
- Поля:
  - `bot`: `AttachMenuBot`
  - `users`: `Vector`

## `AttachMenuPeerType`

- Официальный тип: https://core.telegram.org/type/AttachMenuPeerType
- Количество constructors: **5**

### `attachMenuPeerTypeBotPM`

- ID: `-1020528102` / `0xc32bfa1a`
- Сигнатура: `attachMenuPeerTypeBotPM() => AttachMenuPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/attachMenuPeerTypeBotPM
- Поля:
  - Нет полей.

### `attachMenuPeerTypeBroadcast`

- ID: `2080104188` / `0x7bfbdefc`
- Сигнатура: `attachMenuPeerTypeBroadcast() => AttachMenuPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/attachMenuPeerTypeBroadcast
- Поля:
  - Нет полей.

### `attachMenuPeerTypeChat`

- ID: `84480319` / `0x0509113f`
- Сигнатура: `attachMenuPeerTypeChat() => AttachMenuPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/attachMenuPeerTypeChat
- Поля:
  - Нет полей.

### `attachMenuPeerTypePM`

- ID: `-247016673` / `0xf146d31f`
- Сигнатура: `attachMenuPeerTypePM() => AttachMenuPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/attachMenuPeerTypePM
- Поля:
  - Нет полей.

### `attachMenuPeerTypeSameBotPM`

- ID: `2104224014` / `0x7d6be90e`
- Сигнатура: `attachMenuPeerTypeSameBotPM() => AttachMenuPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/attachMenuPeerTypeSameBotPM
- Поля:
  - Нет полей.

## `Authorization`

- Официальный тип: https://core.telegram.org/type/Authorization
- Количество constructors: **1**

### `authorization`

- ID: `-1392388579` / `0xad01d61d`
- Сигнатура: `authorization(flags:#, current:flags.0?true, official_app:flags.1?true, password_pending:flags.2?true, encrypted_requests_disabled:flags.3?true, call_requests_disabled:flags.4?true, unconfirmed:flags.5?true, hash:long, device_model:string, platform:string, system_version:string, api_id:int, app_name:string, app_version:string, date_created:int, date_active:int, ip:string, country:string, region:string) => Authorization`
- Официальная страница конструктора: https://core.telegram.org/constructor/authorization
- Поля:
  - `flags`: `#` - служебное поле flags
  - `current`: `flags.0?true` - optional через flags.0
  - `official_app`: `flags.1?true` - optional через flags.1
  - `password_pending`: `flags.2?true` - optional через flags.2
  - `encrypted_requests_disabled`: `flags.3?true` - optional через flags.3
  - `call_requests_disabled`: `flags.4?true` - optional через flags.4
  - `unconfirmed`: `flags.5?true` - optional через flags.5
  - `hash`: `long`
  - `device_model`: `string`
  - `platform`: `string`
  - `system_version`: `string`
  - `api_id`: `int`
  - `app_name`: `string`
  - `app_version`: `string`
  - `date_created`: `int`
  - `date_active`: `int`
  - `ip`: `string`
  - `country`: `string`
  - `region`: `string`

## `AutoDownloadSettings`

- Официальный тип: https://core.telegram.org/type/AutoDownloadSettings
- Количество constructors: **1**

### `autoDownloadSettings`

- ID: `-1163561432` / `0xbaa57628`
- Сигнатура: `autoDownloadSettings(flags:#, disabled:flags.0?true, video_preload_large:flags.1?true, audio_preload_next:flags.2?true, phonecalls_less_data:flags.3?true, stories_preload:flags.4?true, photo_size_max:int, video_size_max:long, file_size_max:long, video_upload_maxbitrate:int, small_queue_active_operations_max:int, large_queue_active_operations_max:int) => AutoDownloadSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/autoDownloadSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `disabled`: `flags.0?true` - optional через flags.0
  - `video_preload_large`: `flags.1?true` - optional через flags.1
  - `audio_preload_next`: `flags.2?true` - optional через flags.2
  - `phonecalls_less_data`: `flags.3?true` - optional через flags.3
  - `stories_preload`: `flags.4?true` - optional через flags.4
  - `photo_size_max`: `int`
  - `video_size_max`: `long`
  - `file_size_max`: `long`
  - `video_upload_maxbitrate`: `int`
  - `small_queue_active_operations_max`: `int`
  - `large_queue_active_operations_max`: `int`

## `AutoSaveException`

- Официальный тип: https://core.telegram.org/type/AutoSaveException
- Количество constructors: **1**

### `autoSaveException`

- ID: `-2124403385` / `0x81602d47`
- Сигнатура: `autoSaveException(peer:Peer, settings:AutoSaveSettings) => AutoSaveException`
- Официальная страница конструктора: https://core.telegram.org/constructor/autoSaveException
- Поля:
  - `peer`: `Peer`
  - `settings`: `AutoSaveSettings`

## `AutoSaveSettings`

- Официальный тип: https://core.telegram.org/type/AutoSaveSettings
- Количество constructors: **1**

### `autoSaveSettings`

- ID: `-934791986` / `0xc84834ce`
- Сигнатура: `autoSaveSettings(flags:#, photos:flags.0?true, videos:flags.1?true, video_max_size:flags.2?long) => AutoSaveSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/autoSaveSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `photos`: `flags.0?true` - optional через flags.0
  - `videos`: `flags.1?true` - optional через flags.1
  - `video_max_size`: `flags.2?long` - optional через flags.2

## `AvailableEffect`

- Официальный тип: https://core.telegram.org/type/AvailableEffect
- Количество constructors: **1**

### `availableEffect`

- ID: `-1815879042` / `0x93c3e27e`
- Сигнатура: `availableEffect(flags:#, premium_required:flags.2?true, id:long, emoticon:string, static_icon_id:flags.0?long, effect_sticker_id:long, effect_animation_id:flags.1?long) => AvailableEffect`
- Официальная страница конструктора: https://core.telegram.org/constructor/availableEffect
- Поля:
  - `flags`: `#` - служебное поле flags
  - `premium_required`: `flags.2?true` - optional через flags.2
  - `id`: `long`
  - `emoticon`: `string`
  - `static_icon_id`: `flags.0?long` - optional через flags.0
  - `effect_sticker_id`: `long`
  - `effect_animation_id`: `flags.1?long` - optional через flags.1

## `AvailableReaction`

- Официальный тип: https://core.telegram.org/type/AvailableReaction
- Количество constructors: **1**

### `availableReaction`

- ID: `-1065882623` / `0xc077ec01`
- Сигнатура: `availableReaction(flags:#, inactive:flags.0?true, premium:flags.2?true, reaction:string, title:string, static_icon:Document, appear_animation:Document, select_animation:Document, activate_animation:Document, effect_animation:Document, around_animation:flags.1?Document, center_icon:flags.1?Document) => AvailableReaction`
- Официальная страница конструктора: https://core.telegram.org/constructor/availableReaction
- Поля:
  - `flags`: `#` - служебное поле flags
  - `inactive`: `flags.0?true` - optional через flags.0
  - `premium`: `flags.2?true` - optional через flags.2
  - `reaction`: `string`
  - `title`: `string`
  - `static_icon`: `Document`
  - `appear_animation`: `Document`
  - `select_animation`: `Document`
  - `activate_animation`: `Document`
  - `effect_animation`: `Document`
  - `around_animation`: `flags.1?Document` - optional через flags.1
  - `center_icon`: `flags.1?Document` - optional через flags.1

## `BankCardOpenUrl`

- Официальный тип: https://core.telegram.org/type/BankCardOpenUrl
- Количество constructors: **1**

### `bankCardOpenUrl`

- ID: `-177732982` / `0xf568028a`
- Сигнатура: `bankCardOpenUrl(url:string, name:string) => BankCardOpenUrl`
- Официальная страница конструктора: https://core.telegram.org/constructor/bankCardOpenUrl
- Поля:
  - `url`: `string`
  - `name`: `string`

## `BaseTheme`

- Официальный тип: https://core.telegram.org/type/BaseTheme
- Количество constructors: **5**

### `baseThemeArctic`

- ID: `1527845466` / `0x5b11125a`
- Сигнатура: `baseThemeArctic() => BaseTheme`
- Официальная страница конструктора: https://core.telegram.org/constructor/baseThemeArctic
- Поля:
  - Нет полей.

### `baseThemeClassic`

- ID: `-1012849566` / `0xc3a12462`
- Сигнатура: `baseThemeClassic() => BaseTheme`
- Официальная страница конструктора: https://core.telegram.org/constructor/baseThemeClassic
- Поля:
  - Нет полей.

### `baseThemeDay`

- ID: `-69724536` / `0xfbd81688`
- Сигнатура: `baseThemeDay() => BaseTheme`
- Официальная страница конструктора: https://core.telegram.org/constructor/baseThemeDay
- Поля:
  - Нет полей.

### `baseThemeNight`

- ID: `-1212997976` / `0xb7b31ea8`
- Сигнатура: `baseThemeNight() => BaseTheme`
- Официальная страница конструктора: https://core.telegram.org/constructor/baseThemeNight
- Поля:
  - Нет полей.

### `baseThemeTinted`

- ID: `1834973166` / `0x6d5f77ee`
- Сигнатура: `baseThemeTinted() => BaseTheme`
- Официальная страница конструктора: https://core.telegram.org/constructor/baseThemeTinted
- Поля:
  - Нет полей.

## `Birthday`

- Официальный тип: https://core.telegram.org/type/Birthday
- Количество constructors: **1**

### `birthday`

- ID: `1821253126` / `0x6c8e1e06`
- Сигнатура: `birthday(flags:#, day:int, month:int, year:flags.0?int) => Birthday`
- Официальная страница конструктора: https://core.telegram.org/constructor/birthday
- Поля:
  - `flags`: `#` - служебное поле flags
  - `day`: `int`
  - `month`: `int`
  - `year`: `flags.0?int` - optional через flags.0

## `Bool`

- Официальный тип: https://core.telegram.org/type/Bool
- Количество constructors: **2**

### `boolFalse`

- ID: `-1132882121` / `0xbc799737`
- Сигнатура: `boolFalse() => Bool`
- Официальная страница конструктора: https://core.telegram.org/constructor/boolFalse
- Поля:
  - Нет полей.

### `boolTrue`

- ID: `-1720552011` / `0x997275b5`
- Сигнатура: `boolTrue() => Bool`
- Официальная страница конструктора: https://core.telegram.org/constructor/boolTrue
- Поля:
  - Нет полей.

## `Boost`

- Официальный тип: https://core.telegram.org/type/Boost
- Количество constructors: **1**

### `boost`

- ID: `1262359766` / `0x4b3e14d6`
- Сигнатура: `boost(flags:#, gift:flags.1?true, giveaway:flags.2?true, unclaimed:flags.3?true, id:string, user_id:flags.0?long, giveaway_msg_id:flags.2?int, date:int, expires:int, used_gift_slug:flags.4?string, multiplier:flags.5?int, stars:flags.6?long) => Boost`
- Официальная страница конструктора: https://core.telegram.org/constructor/boost
- Поля:
  - `flags`: `#` - служебное поле flags
  - `gift`: `flags.1?true` - optional через flags.1
  - `giveaway`: `flags.2?true` - optional через flags.2
  - `unclaimed`: `flags.3?true` - optional через flags.3
  - `id`: `string`
  - `user_id`: `flags.0?long` - optional через flags.0
  - `giveaway_msg_id`: `flags.2?int` - optional через flags.2
  - `date`: `int`
  - `expires`: `int`
  - `used_gift_slug`: `flags.4?string` - optional через flags.4
  - `multiplier`: `flags.5?int` - optional через flags.5
  - `stars`: `flags.6?long` - optional через flags.6

## `BotApp`

- Официальный тип: https://core.telegram.org/type/BotApp
- Количество constructors: **2**

### `botApp`

- ID: `-1778593322` / `0x95fcd1d6`
- Сигнатура: `botApp(flags:#, id:long, access_hash:long, short_name:string, title:string, description:string, photo:Photo, document:flags.0?Document, hash:long) => BotApp`
- Официальная страница конструктора: https://core.telegram.org/constructor/botApp
- Поля:
  - `flags`: `#` - служебное поле flags
  - `id`: `long`
  - `access_hash`: `long`
  - `short_name`: `string`
  - `title`: `string`
  - `description`: `string`
  - `photo`: `Photo`
  - `document`: `flags.0?Document` - optional через flags.0
  - `hash`: `long`

### `botAppNotModified`

- ID: `1571189943` / `0x5da674b7`
- Сигнатура: `botAppNotModified() => BotApp`
- Официальная страница конструктора: https://core.telegram.org/constructor/botAppNotModified
- Поля:
  - Нет полей.

## `BotAppSettings`

- Официальный тип: https://core.telegram.org/type/BotAppSettings
- Количество constructors: **1**

### `botAppSettings`

- ID: `-912582320` / `0xc99b1950`
- Сигнатура: `botAppSettings(flags:#, placeholder_path:flags.0?bytes, background_color:flags.1?int, background_dark_color:flags.2?int, header_color:flags.3?int, header_dark_color:flags.4?int) => BotAppSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/botAppSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `placeholder_path`: `flags.0?bytes` - optional через flags.0
  - `background_color`: `flags.1?int` - optional через flags.1
  - `background_dark_color`: `flags.2?int` - optional через flags.2
  - `header_color`: `flags.3?int` - optional через flags.3
  - `header_dark_color`: `flags.4?int` - optional через flags.4

## `BotBusinessConnection`

- Официальный тип: https://core.telegram.org/type/BotBusinessConnection
- Количество constructors: **1**

### `botBusinessConnection`

- ID: `-1892371723` / `0x8f34b2f5`
- Сигнатура: `botBusinessConnection(flags:#, disabled:flags.1?true, connection_id:string, user_id:long, dc_id:int, date:int, rights:flags.2?BusinessBotRights) => BotBusinessConnection`
- Официальная страница конструктора: https://core.telegram.org/constructor/botBusinessConnection
- Поля:
  - `flags`: `#` - служебное поле flags
  - `disabled`: `flags.1?true` - optional через flags.1
  - `connection_id`: `string`
  - `user_id`: `long`
  - `dc_id`: `int`
  - `date`: `int`
  - `rights`: `flags.2?BusinessBotRights` - optional через flags.2

## `BotCommand`

- Официальный тип: https://core.telegram.org/type/BotCommand
- Количество constructors: **1**

### `botCommand`

- ID: `-1032140601` / `0xc27ac8c7`
- Сигнатура: `botCommand(command:string, description:string) => BotCommand`
- Официальная страница конструктора: https://core.telegram.org/constructor/botCommand
- Поля:
  - `command`: `string`
  - `description`: `string`

## `BotCommandScope`

- Официальный тип: https://core.telegram.org/type/BotCommandScope
- Количество constructors: **7**

### `botCommandScopeChatAdmins`

- ID: `-1180016534` / `0xb9aa606a`
- Сигнатура: `botCommandScopeChatAdmins() => BotCommandScope`
- Официальная страница конструктора: https://core.telegram.org/constructor/botCommandScopeChatAdmins
- Поля:
  - Нет полей.

### `botCommandScopeChats`

- ID: `1877059713` / `0x6fe1a881`
- Сигнатура: `botCommandScopeChats() => BotCommandScope`
- Официальная страница конструктора: https://core.telegram.org/constructor/botCommandScopeChats
- Поля:
  - Нет полей.

### `botCommandScopeDefault`

- ID: `795652779` / `0x2f6cb2ab`
- Сигнатура: `botCommandScopeDefault() => BotCommandScope`
- Официальная страница конструктора: https://core.telegram.org/constructor/botCommandScopeDefault
- Поля:
  - Нет полей.

### `botCommandScopePeer`

- ID: `-610432643` / `0xdb9d897d`
- Сигнатура: `botCommandScopePeer(peer:InputPeer) => BotCommandScope`
- Официальная страница конструктора: https://core.telegram.org/constructor/botCommandScopePeer
- Поля:
  - `peer`: `InputPeer`

### `botCommandScopePeerAdmins`

- ID: `1071145937` / `0x3fd863d1`
- Сигнатура: `botCommandScopePeerAdmins(peer:InputPeer) => BotCommandScope`
- Официальная страница конструктора: https://core.telegram.org/constructor/botCommandScopePeerAdmins
- Поля:
  - `peer`: `InputPeer`

### `botCommandScopePeerUser`

- ID: `169026035` / `0x0a1321f3`
- Сигнатура: `botCommandScopePeerUser(peer:InputPeer, user_id:InputUser) => BotCommandScope`
- Официальная страница конструктора: https://core.telegram.org/constructor/botCommandScopePeerUser
- Поля:
  - `peer`: `InputPeer`
  - `user_id`: `InputUser`

### `botCommandScopeUsers`

- ID: `1011811544` / `0x3c4f04d8`
- Сигнатура: `botCommandScopeUsers() => BotCommandScope`
- Официальная страница конструктора: https://core.telegram.org/constructor/botCommandScopeUsers
- Поля:
  - Нет полей.

## `BotInfo`

- Официальный тип: https://core.telegram.org/type/BotInfo
- Количество constructors: **1**

### `botInfo`

- ID: `1300890265` / `0x4d8a0299`
- Сигнатура: `botInfo(flags:#, has_preview_medias:flags.6?true, user_id:flags.0?long, description:flags.1?string, description_photo:flags.4?Photo, description_document:flags.5?Document, commands:flags.2?Vector, menu_button:flags.3?BotMenuButton, privacy_policy_url:flags.7?string, app_settings:flags.8?BotAppSettings, verifier_settings:flags.9?BotVerifierSettings) => BotInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/botInfo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `has_preview_medias`: `flags.6?true` - optional через flags.6
  - `user_id`: `flags.0?long` - optional через flags.0
  - `description`: `flags.1?string` - optional через flags.1
  - `description_photo`: `flags.4?Photo` - optional через flags.4
  - `description_document`: `flags.5?Document` - optional через flags.5
  - `commands`: `flags.2?Vector` - optional через flags.2
  - `menu_button`: `flags.3?BotMenuButton` - optional через flags.3
  - `privacy_policy_url`: `flags.7?string` - optional через flags.7
  - `app_settings`: `flags.8?BotAppSettings` - optional через flags.8
  - `verifier_settings`: `flags.9?BotVerifierSettings` - optional через flags.9

## `BotInlineMessage`

- Официальный тип: https://core.telegram.org/type/BotInlineMessage
- Количество constructors: **7**

### `botInlineMessageMediaAuto`

- ID: `1984755728` / `0x764cf810`
- Сигнатура: `botInlineMessageMediaAuto(flags:#, invert_media:flags.3?true, message:string, entities:flags.1?Vector, reply_markup:flags.2?ReplyMarkup) => BotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/botInlineMessageMediaAuto
- Поля:
  - `flags`: `#` - служебное поле flags
  - `invert_media`: `flags.3?true` - optional через flags.3
  - `message`: `string`
  - `entities`: `flags.1?Vector` - optional через flags.1
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `botInlineMessageMediaContact`

- ID: `416402882` / `0x18d1cdc2`
- Сигнатура: `botInlineMessageMediaContact(flags:#, phone_number:string, first_name:string, last_name:string, vcard:string, reply_markup:flags.2?ReplyMarkup) => BotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/botInlineMessageMediaContact
- Поля:
  - `flags`: `#` - служебное поле flags
  - `phone_number`: `string`
  - `first_name`: `string`
  - `last_name`: `string`
  - `vcard`: `string`
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `botInlineMessageMediaGeo`

- ID: `85477117` / `0x051846fd`
- Сигнатура: `botInlineMessageMediaGeo(flags:#, geo:GeoPoint, heading:flags.0?int, period:flags.1?int, proximity_notification_radius:flags.3?int, reply_markup:flags.2?ReplyMarkup) => BotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/botInlineMessageMediaGeo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `geo`: `GeoPoint`
  - `heading`: `flags.0?int` - optional через flags.0
  - `period`: `flags.1?int` - optional через flags.1
  - `proximity_notification_radius`: `flags.3?int` - optional через flags.3
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `botInlineMessageMediaInvoice`

- ID: `894081801` / `0x354a9b09`
- Сигнатура: `botInlineMessageMediaInvoice(flags:#, shipping_address_requested:flags.1?true, test:flags.3?true, title:string, description:string, photo:flags.0?WebDocument, currency:string, total_amount:long, reply_markup:flags.2?ReplyMarkup) => BotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/botInlineMessageMediaInvoice
- Поля:
  - `flags`: `#` - служебное поле flags
  - `shipping_address_requested`: `flags.1?true` - optional через flags.1
  - `test`: `flags.3?true` - optional через flags.3
  - `title`: `string`
  - `description`: `string`
  - `photo`: `flags.0?WebDocument` - optional через flags.0
  - `currency`: `string`
  - `total_amount`: `long`
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `botInlineMessageMediaVenue`

- ID: `-1970903652` / `0x8a86659c`
- Сигнатура: `botInlineMessageMediaVenue(flags:#, geo:GeoPoint, title:string, address:string, provider:string, venue_id:string, venue_type:string, reply_markup:flags.2?ReplyMarkup) => BotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/botInlineMessageMediaVenue
- Поля:
  - `flags`: `#` - служебное поле flags
  - `geo`: `GeoPoint`
  - `title`: `string`
  - `address`: `string`
  - `provider`: `string`
  - `venue_id`: `string`
  - `venue_type`: `string`
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `botInlineMessageMediaWebPage`

- ID: `-2137335386` / `0x809ad9a6`
- Сигнатура: `botInlineMessageMediaWebPage(flags:#, invert_media:flags.3?true, force_large_media:flags.4?true, force_small_media:flags.5?true, manual:flags.7?true, safe:flags.8?true, message:string, entities:flags.1?Vector, url:string, reply_markup:flags.2?ReplyMarkup) => BotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/botInlineMessageMediaWebPage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `invert_media`: `flags.3?true` - optional через flags.3
  - `force_large_media`: `flags.4?true` - optional через flags.4
  - `force_small_media`: `flags.5?true` - optional через flags.5
  - `manual`: `flags.7?true` - optional через flags.7
  - `safe`: `flags.8?true` - optional через flags.8
  - `message`: `string`
  - `entities`: `flags.1?Vector` - optional через flags.1
  - `url`: `string`
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `botInlineMessageText`

- ID: `-1937807902` / `0x8c7f65e2`
- Сигнатура: `botInlineMessageText(flags:#, no_webpage:flags.0?true, invert_media:flags.3?true, message:string, entities:flags.1?Vector, reply_markup:flags.2?ReplyMarkup) => BotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/botInlineMessageText
- Поля:
  - `flags`: `#` - служебное поле flags
  - `no_webpage`: `flags.0?true` - optional через flags.0
  - `invert_media`: `flags.3?true` - optional через flags.3
  - `message`: `string`
  - `entities`: `flags.1?Vector` - optional через flags.1
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

## `BotInlineResult`

- Официальный тип: https://core.telegram.org/type/BotInlineResult
- Количество constructors: **2**

### `botInlineMediaResult`

- ID: `400266251` / `0x17db940b`
- Сигнатура: `botInlineMediaResult(flags:#, id:string, type:string, photo:flags.0?Photo, document:flags.1?Document, title:flags.2?string, description:flags.3?string, send_message:BotInlineMessage) => BotInlineResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/botInlineMediaResult
- Поля:
  - `flags`: `#` - служебное поле flags
  - `id`: `string`
  - `type`: `string`
  - `photo`: `flags.0?Photo` - optional через flags.0
  - `document`: `flags.1?Document` - optional через flags.1
  - `title`: `flags.2?string` - optional через flags.2
  - `description`: `flags.3?string` - optional через flags.3
  - `send_message`: `BotInlineMessage`

### `botInlineResult`

- ID: `295067450` / `0x11965f3a`
- Сигнатура: `botInlineResult(flags:#, id:string, type:string, title:flags.1?string, description:flags.2?string, url:flags.3?string, thumb:flags.4?WebDocument, content:flags.5?WebDocument, send_message:BotInlineMessage) => BotInlineResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/botInlineResult
- Поля:
  - `flags`: `#` - служебное поле flags
  - `id`: `string`
  - `type`: `string`
  - `title`: `flags.1?string` - optional через flags.1
  - `description`: `flags.2?string` - optional через flags.2
  - `url`: `flags.3?string` - optional через flags.3
  - `thumb`: `flags.4?WebDocument` - optional через flags.4
  - `content`: `flags.5?WebDocument` - optional через flags.5
  - `send_message`: `BotInlineMessage`

## `BotMenuButton`

- Официальный тип: https://core.telegram.org/type/BotMenuButton
- Количество constructors: **3**

### `botMenuButton`

- ID: `-944407322` / `0xc7b57ce6`
- Сигнатура: `botMenuButton(text:string, url:string) => BotMenuButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/botMenuButton
- Поля:
  - `text`: `string`
  - `url`: `string`

### `botMenuButtonCommands`

- ID: `1113113093` / `0x4258c205`
- Сигнатура: `botMenuButtonCommands() => BotMenuButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/botMenuButtonCommands
- Поля:
  - Нет полей.

### `botMenuButtonDefault`

- ID: `1966318984` / `0x7533a588`
- Сигнатура: `botMenuButtonDefault() => BotMenuButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/botMenuButtonDefault
- Поля:
  - Нет полей.

## `BotPreviewMedia`

- Официальный тип: https://core.telegram.org/type/BotPreviewMedia
- Количество constructors: **1**

### `botPreviewMedia`

- ID: `602479523` / `0x23e91ba3`
- Сигнатура: `botPreviewMedia(date:int, media:MessageMedia) => BotPreviewMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/botPreviewMedia
- Поля:
  - `date`: `int`
  - `media`: `MessageMedia`

## `BotVerification`

- Официальный тип: https://core.telegram.org/type/BotVerification
- Количество constructors: **1**

### `botVerification`

- ID: `-113453988` / `0xf93cd45c`
- Сигнатура: `botVerification(bot_id:long, icon:long, description:string) => BotVerification`
- Официальная страница конструктора: https://core.telegram.org/constructor/botVerification
- Поля:
  - `bot_id`: `long`
  - `icon`: `long`
  - `description`: `string`

## `BotVerifierSettings`

- Официальный тип: https://core.telegram.org/type/BotVerifierSettings
- Количество constructors: **1**

### `botVerifierSettings`

- ID: `-1328716265` / `0xb0cd6617`
- Сигнатура: `botVerifierSettings(flags:#, can_modify_custom_description:flags.1?true, icon:long, company:string, custom_description:flags.0?string) => BotVerifierSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/botVerifierSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `can_modify_custom_description`: `flags.1?true` - optional через flags.1
  - `icon`: `long`
  - `company`: `string`
  - `custom_description`: `flags.0?string` - optional через flags.0

## `BusinessAwayMessage`

- Официальный тип: https://core.telegram.org/type/BusinessAwayMessage
- Количество constructors: **1**

### `businessAwayMessage`

- ID: `-283809188` / `0xef156a5c`
- Сигнатура: `businessAwayMessage(flags:#, offline_only:flags.0?true, shortcut_id:int, schedule:BusinessAwayMessageSchedule, recipients:BusinessRecipients) => BusinessAwayMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessAwayMessage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `offline_only`: `flags.0?true` - optional через flags.0
  - `shortcut_id`: `int`
  - `schedule`: `BusinessAwayMessageSchedule`
  - `recipients`: `BusinessRecipients`

## `BusinessAwayMessageSchedule`

- Официальный тип: https://core.telegram.org/type/BusinessAwayMessageSchedule
- Количество constructors: **3**

### `businessAwayMessageScheduleAlways`

- ID: `-910564679` / `0xc9b9e2b9`
- Сигнатура: `businessAwayMessageScheduleAlways() => BusinessAwayMessageSchedule`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessAwayMessageScheduleAlways
- Поля:
  - Нет полей.

### `businessAwayMessageScheduleCustom`

- ID: `-867328308` / `0xcc4d9ecc`
- Сигнатура: `businessAwayMessageScheduleCustom(start_date:int, end_date:int) => BusinessAwayMessageSchedule`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessAwayMessageScheduleCustom
- Поля:
  - `start_date`: `int`
  - `end_date`: `int`

### `businessAwayMessageScheduleOutsideWorkHours`

- ID: `-1007487743` / `0xc3f2f501`
- Сигнатура: `businessAwayMessageScheduleOutsideWorkHours() => BusinessAwayMessageSchedule`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessAwayMessageScheduleOutsideWorkHours
- Поля:
  - Нет полей.

## `BusinessBotRecipients`

- Официальный тип: https://core.telegram.org/type/BusinessBotRecipients
- Количество constructors: **1**

### `businessBotRecipients`

- ID: `-1198722189` / `0xb88cf373`
- Сигнатура: `businessBotRecipients(flags:#, existing_chats:flags.0?true, new_chats:flags.1?true, contacts:flags.2?true, non_contacts:flags.3?true, exclude_selected:flags.5?true, users:flags.4?Vector, exclude_users:flags.6?Vector) => BusinessBotRecipients`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessBotRecipients
- Поля:
  - `flags`: `#` - служебное поле flags
  - `existing_chats`: `flags.0?true` - optional через flags.0
  - `new_chats`: `flags.1?true` - optional через flags.1
  - `contacts`: `flags.2?true` - optional через flags.2
  - `non_contacts`: `flags.3?true` - optional через flags.3
  - `exclude_selected`: `flags.5?true` - optional через flags.5
  - `users`: `flags.4?Vector` - optional через flags.4
  - `exclude_users`: `flags.6?Vector` - optional через flags.6

## `BusinessBotRights`

- Официальный тип: https://core.telegram.org/type/BusinessBotRights
- Количество constructors: **1**

### `businessBotRights`

- ID: `-1604170505` / `0xa0624cf7`
- Сигнатура: `businessBotRights(flags:#, reply:flags.0?true, read_messages:flags.1?true, delete_sent_messages:flags.2?true, delete_received_messages:flags.3?true, edit_name:flags.4?true, edit_bio:flags.5?true, edit_profile_photo:flags.6?true, edit_username:flags.7?true, view_gifts:flags.8?true, sell_gifts:flags.9?true, change_gift_settings:flags.10?true, transfer_and_upgrade_gifts:flags.11?true, transfer_stars:flags.12?true, manage_stories:flags.13?true) => BusinessBotRights`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessBotRights
- Поля:
  - `flags`: `#` - служебное поле flags
  - `reply`: `flags.0?true` - optional через flags.0
  - `read_messages`: `flags.1?true` - optional через flags.1
  - `delete_sent_messages`: `flags.2?true` - optional через flags.2
  - `delete_received_messages`: `flags.3?true` - optional через flags.3
  - `edit_name`: `flags.4?true` - optional через flags.4
  - `edit_bio`: `flags.5?true` - optional через flags.5
  - `edit_profile_photo`: `flags.6?true` - optional через flags.6
  - `edit_username`: `flags.7?true` - optional через flags.7
  - `view_gifts`: `flags.8?true` - optional через flags.8
  - `sell_gifts`: `flags.9?true` - optional через flags.9
  - `change_gift_settings`: `flags.10?true` - optional через flags.10
  - `transfer_and_upgrade_gifts`: `flags.11?true` - optional через flags.11
  - `transfer_stars`: `flags.12?true` - optional через flags.12
  - `manage_stories`: `flags.13?true` - optional через flags.13

## `BusinessChatLink`

- Официальный тип: https://core.telegram.org/type/BusinessChatLink
- Количество constructors: **1**

### `businessChatLink`

- ID: `-1263638929` / `0xb4ae666f`
- Сигнатура: `businessChatLink(flags:#, link:string, message:string, entities:flags.0?Vector, title:flags.1?string, views:int) => BusinessChatLink`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessChatLink
- Поля:
  - `flags`: `#` - служебное поле flags
  - `link`: `string`
  - `message`: `string`
  - `entities`: `flags.0?Vector` - optional через flags.0
  - `title`: `flags.1?string` - optional через flags.1
  - `views`: `int`

## `BusinessGreetingMessage`

- Официальный тип: https://core.telegram.org/type/BusinessGreetingMessage
- Количество constructors: **1**

### `businessGreetingMessage`

- ID: `-451302485` / `0xe519abab`
- Сигнатура: `businessGreetingMessage(shortcut_id:int, recipients:BusinessRecipients, no_activity_days:int) => BusinessGreetingMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessGreetingMessage
- Поля:
  - `shortcut_id`: `int`
  - `recipients`: `BusinessRecipients`
  - `no_activity_days`: `int`

## `BusinessIntro`

- Официальный тип: https://core.telegram.org/type/BusinessIntro
- Количество constructors: **1**

### `businessIntro`

- ID: `1510606445` / `0x5a0a066d`
- Сигнатура: `businessIntro(flags:#, title:string, description:string, sticker:flags.0?Document) => BusinessIntro`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessIntro
- Поля:
  - `flags`: `#` - служебное поле flags
  - `title`: `string`
  - `description`: `string`
  - `sticker`: `flags.0?Document` - optional через flags.0

## `BusinessLocation`

- Официальный тип: https://core.telegram.org/type/BusinessLocation
- Количество constructors: **1**

### `businessLocation`

- ID: `-1403249929` / `0xac5c1af7`
- Сигнатура: `businessLocation(flags:#, geo_point:flags.0?GeoPoint, address:string) => BusinessLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessLocation
- Поля:
  - `flags`: `#` - служебное поле flags
  - `geo_point`: `flags.0?GeoPoint` - optional через flags.0
  - `address`: `string`

## `BusinessRecipients`

- Официальный тип: https://core.telegram.org/type/BusinessRecipients
- Количество constructors: **1**

### `businessRecipients`

- ID: `554733559` / `0x21108ff7`
- Сигнатура: `businessRecipients(flags:#, existing_chats:flags.0?true, new_chats:flags.1?true, contacts:flags.2?true, non_contacts:flags.3?true, exclude_selected:flags.5?true, users:flags.4?Vector) => BusinessRecipients`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessRecipients
- Поля:
  - `flags`: `#` - служебное поле flags
  - `existing_chats`: `flags.0?true` - optional через flags.0
  - `new_chats`: `flags.1?true` - optional через flags.1
  - `contacts`: `flags.2?true` - optional через flags.2
  - `non_contacts`: `flags.3?true` - optional через flags.3
  - `exclude_selected`: `flags.5?true` - optional через flags.5
  - `users`: `flags.4?Vector` - optional через flags.4

## `BusinessWeeklyOpen`

- Официальный тип: https://core.telegram.org/type/BusinessWeeklyOpen
- Количество constructors: **1**

### `businessWeeklyOpen`

- ID: `302717625` / `0x120b1ab9`
- Сигнатура: `businessWeeklyOpen(start_minute:int, end_minute:int) => BusinessWeeklyOpen`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessWeeklyOpen
- Поля:
  - `start_minute`: `int`
  - `end_minute`: `int`

## `BusinessWorkHours`

- Официальный тип: https://core.telegram.org/type/BusinessWorkHours
- Количество constructors: **1**

### `businessWorkHours`

- ID: `-1936543592` / `0x8c92b098`
- Сигнатура: `businessWorkHours(flags:#, open_now:flags.0?true, timezone_id:string, weekly_open:Vector) => BusinessWorkHours`
- Официальная страница конструктора: https://core.telegram.org/constructor/businessWorkHours
- Поля:
  - `flags`: `#` - служебное поле flags
  - `open_now`: `flags.0?true` - optional через flags.0
  - `timezone_id`: `string`
  - `weekly_open`: `Vector`

## `CdnConfig`

- Официальный тип: https://core.telegram.org/type/CdnConfig
- Количество constructors: **1**

### `cdnConfig`

- ID: `1462101002` / `0x5725e40a`
- Сигнатура: `cdnConfig(public_keys:Vector) => CdnConfig`
- Официальная страница конструктора: https://core.telegram.org/constructor/cdnConfig
- Поля:
  - `public_keys`: `Vector`

## `CdnPublicKey`

- Официальный тип: https://core.telegram.org/type/CdnPublicKey
- Количество constructors: **1**

### `cdnPublicKey`

- ID: `-914167110` / `0xc982eaba`
- Сигнатура: `cdnPublicKey(dc_id:int, public_key:string) => CdnPublicKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/cdnPublicKey
- Поля:
  - `dc_id`: `int`
  - `public_key`: `string`

## `ChannelAdminLogEvent`

- Официальный тип: https://core.telegram.org/type/ChannelAdminLogEvent
- Количество constructors: **1**

### `channelAdminLogEvent`

- ID: `531458253` / `0x1fad68cd`
- Сигнатура: `channelAdminLogEvent(id:long, date:int, user_id:long, action:ChannelAdminLogEventAction) => ChannelAdminLogEvent`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEvent
- Поля:
  - `id`: `long`
  - `date`: `int`
  - `user_id`: `long`
  - `action`: `ChannelAdminLogEventAction`

## `ChannelAdminLogEventAction`

- Официальный тип: https://core.telegram.org/type/ChannelAdminLogEventAction
- Количество constructors: **51**

### `channelAdminLogEventActionChangeAbout`

- ID: `1427671598` / `0x55188a2e`
- Сигнатура: `channelAdminLogEventActionChangeAbout(prev_value:string, new_value:string) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeAbout
- Поля:
  - `prev_value`: `string`
  - `new_value`: `string`

### `channelAdminLogEventActionChangeAvailableReactions`

- ID: `-1102180616` / `0xbe4e0ef8`
- Сигнатура: `channelAdminLogEventActionChangeAvailableReactions(prev_value:ChatReactions, new_value:ChatReactions) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeAvailableReactions
- Поля:
  - `prev_value`: `ChatReactions`
  - `new_value`: `ChatReactions`

### `channelAdminLogEventActionChangeEmojiStatus`

- ID: `1051328177` / `0x3ea9feb1`
- Сигнатура: `channelAdminLogEventActionChangeEmojiStatus(prev_value:EmojiStatus, new_value:EmojiStatus) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeEmojiStatus
- Поля:
  - `prev_value`: `EmojiStatus`
  - `new_value`: `EmojiStatus`

### `channelAdminLogEventActionChangeEmojiStickerSet`

- ID: `1188577451` / `0x46d840ab`
- Сигнатура: `channelAdminLogEventActionChangeEmojiStickerSet(prev_stickerset:InputStickerSet, new_stickerset:InputStickerSet) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeEmojiStickerSet
- Поля:
  - `prev_stickerset`: `InputStickerSet`
  - `new_stickerset`: `InputStickerSet`

### `channelAdminLogEventActionChangeHistoryTTL`

- ID: `1855199800` / `0x6e941a38`
- Сигнатура: `channelAdminLogEventActionChangeHistoryTTL(prev_value:int, new_value:int) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeHistoryTTL
- Поля:
  - `prev_value`: `int`
  - `new_value`: `int`

### `channelAdminLogEventActionChangeLinkedChat`

- ID: `84703944` / `0x050c7ac8`
- Сигнатура: `channelAdminLogEventActionChangeLinkedChat(prev_value:long, new_value:long) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeLinkedChat
- Поля:
  - `prev_value`: `long`
  - `new_value`: `long`

### `channelAdminLogEventActionChangeLocation`

- ID: `241923758` / `0x0e6b76ae`
- Сигнатура: `channelAdminLogEventActionChangeLocation(prev_value:ChannelLocation, new_value:ChannelLocation) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeLocation
- Поля:
  - `prev_value`: `ChannelLocation`
  - `new_value`: `ChannelLocation`

### `channelAdminLogEventActionChangePeerColor`

- ID: `1469507456` / `0x5796e780`
- Сигнатура: `channelAdminLogEventActionChangePeerColor(prev_value:PeerColor, new_value:PeerColor) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangePeerColor
- Поля:
  - `prev_value`: `PeerColor`
  - `new_value`: `PeerColor`

### `channelAdminLogEventActionChangePhoto`

- ID: `1129042607` / `0x434bd2af`
- Сигнатура: `channelAdminLogEventActionChangePhoto(prev_photo:Photo, new_photo:Photo) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangePhoto
- Поля:
  - `prev_photo`: `Photo`
  - `new_photo`: `Photo`

### `channelAdminLogEventActionChangeProfilePeerColor`

- ID: `1581742885` / `0x5e477b25`
- Сигнатура: `channelAdminLogEventActionChangeProfilePeerColor(prev_value:PeerColor, new_value:PeerColor) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeProfilePeerColor
- Поля:
  - `prev_value`: `PeerColor`
  - `new_value`: `PeerColor`

### `channelAdminLogEventActionChangeStickerSet`

- ID: `-1312568665` / `0xb1c3caa7`
- Сигнатура: `channelAdminLogEventActionChangeStickerSet(prev_stickerset:InputStickerSet, new_stickerset:InputStickerSet) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeStickerSet
- Поля:
  - `prev_stickerset`: `InputStickerSet`
  - `new_stickerset`: `InputStickerSet`

### `channelAdminLogEventActionChangeTitle`

- ID: `-421545947` / `0xe6dfb825`
- Сигнатура: `channelAdminLogEventActionChangeTitle(prev_value:string, new_value:string) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeTitle
- Поля:
  - `prev_value`: `string`
  - `new_value`: `string`

### `channelAdminLogEventActionChangeUsername`

- ID: `1783299128` / `0x6a4afc38`
- Сигнатура: `channelAdminLogEventActionChangeUsername(prev_value:string, new_value:string) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeUsername
- Поля:
  - `prev_value`: `string`
  - `new_value`: `string`

### `channelAdminLogEventActionChangeUsernames`

- ID: `-263212119` / `0xf04fb3a9`
- Сигнатура: `channelAdminLogEventActionChangeUsernames(prev_value:Vector, new_value:Vector) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeUsernames
- Поля:
  - `prev_value`: `Vector`
  - `new_value`: `Vector`

### `channelAdminLogEventActionChangeWallpaper`

- ID: `834362706` / `0x31bb5d52`
- Сигнатура: `channelAdminLogEventActionChangeWallpaper(prev_value:WallPaper, new_value:WallPaper) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionChangeWallpaper
- Поля:
  - `prev_value`: `WallPaper`
  - `new_value`: `WallPaper`

### `channelAdminLogEventActionCreateTopic`

- ID: `1483767080` / `0x58707d28`
- Сигнатура: `channelAdminLogEventActionCreateTopic(topic:ForumTopic) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionCreateTopic
- Поля:
  - `topic`: `ForumTopic`

### `channelAdminLogEventActionDefaultBannedRights`

- ID: `771095562` / `0x2df5fc0a`
- Сигнатура: `channelAdminLogEventActionDefaultBannedRights(prev_banned_rights:ChatBannedRights, new_banned_rights:ChatBannedRights) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionDefaultBannedRights
- Поля:
  - `prev_banned_rights`: `ChatBannedRights`
  - `new_banned_rights`: `ChatBannedRights`

### `channelAdminLogEventActionDeleteMessage`

- ID: `1121994683` / `0x42e047bb`
- Сигнатура: `channelAdminLogEventActionDeleteMessage(message:Message) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionDeleteMessage
- Поля:
  - `message`: `Message`

### `channelAdminLogEventActionDeleteTopic`

- ID: `-1374254839` / `0xae168909`
- Сигнатура: `channelAdminLogEventActionDeleteTopic(topic:ForumTopic) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionDeleteTopic
- Поля:
  - `topic`: `ForumTopic`

### `channelAdminLogEventActionDiscardGroupCall`

- ID: `-610299584` / `0xdb9f9140`
- Сигнатура: `channelAdminLogEventActionDiscardGroupCall(call:InputGroupCall) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionDiscardGroupCall
- Поля:
  - `call`: `InputGroupCall`

### `channelAdminLogEventActionEditMessage`

- ID: `1889215493` / `0x709b2405`
- Сигнатура: `channelAdminLogEventActionEditMessage(prev_message:Message, new_message:Message) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionEditMessage
- Поля:
  - `prev_message`: `Message`
  - `new_message`: `Message`

### `channelAdminLogEventActionEditTopic`

- ID: `-261103096` / `0xf06fe208`
- Сигнатура: `channelAdminLogEventActionEditTopic(prev_topic:ForumTopic, new_topic:ForumTopic) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionEditTopic
- Поля:
  - `prev_topic`: `ForumTopic`
  - `new_topic`: `ForumTopic`

### `channelAdminLogEventActionExportedInviteDelete`

- ID: `1515256996` / `0x5a50fca4`
- Сигнатура: `channelAdminLogEventActionExportedInviteDelete(invite:ExportedChatInvite) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionExportedInviteDelete
- Поля:
  - `invite`: `ExportedChatInvite`

### `channelAdminLogEventActionExportedInviteEdit`

- ID: `-384910503` / `0xe90ebb59`
- Сигнатура: `channelAdminLogEventActionExportedInviteEdit(prev_invite:ExportedChatInvite, new_invite:ExportedChatInvite) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionExportedInviteEdit
- Поля:
  - `prev_invite`: `ExportedChatInvite`
  - `new_invite`: `ExportedChatInvite`

### `channelAdminLogEventActionExportedInviteRevoke`

- ID: `1091179342` / `0x410a134e`
- Сигнатура: `channelAdminLogEventActionExportedInviteRevoke(invite:ExportedChatInvite) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionExportedInviteRevoke
- Поля:
  - `invite`: `ExportedChatInvite`

### `channelAdminLogEventActionParticipantInvite`

- ID: `-484690728` / `0xe31c34d8`
- Сигнатура: `channelAdminLogEventActionParticipantInvite(participant:ChannelParticipant) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionParticipantInvite
- Поля:
  - `participant`: `ChannelParticipant`

### `channelAdminLogEventActionParticipantJoin`

- ID: `405815507` / `0x183040d3`
- Сигнатура: `channelAdminLogEventActionParticipantJoin() => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionParticipantJoin
- Поля:
  - Нет полей.

### `channelAdminLogEventActionParticipantJoinByInvite`

- ID: `-23084712` / `0xfe9fc158`
- Сигнатура: `channelAdminLogEventActionParticipantJoinByInvite(flags:#, via_chatlist:flags.0?true, invite:ExportedChatInvite) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionParticipantJoinByInvite
- Поля:
  - `flags`: `#` - служебное поле flags
  - `via_chatlist`: `flags.0?true` - optional через flags.0
  - `invite`: `ExportedChatInvite`

### `channelAdminLogEventActionParticipantJoinByRequest`

- ID: `-1347021750` / `0xafb6144a`
- Сигнатура: `channelAdminLogEventActionParticipantJoinByRequest(invite:ExportedChatInvite, approved_by:long) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionParticipantJoinByRequest
- Поля:
  - `invite`: `ExportedChatInvite`
  - `approved_by`: `long`

### `channelAdminLogEventActionParticipantLeave`

- ID: `-124291086` / `0xf89777f2`
- Сигнатура: `channelAdminLogEventActionParticipantLeave() => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionParticipantLeave
- Поля:
  - Нет полей.

### `channelAdminLogEventActionParticipantMute`

- ID: `-115071790` / `0xf92424d2`
- Сигнатура: `channelAdminLogEventActionParticipantMute(participant:GroupCallParticipant) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionParticipantMute
- Поля:
  - `participant`: `GroupCallParticipant`

### `channelAdminLogEventActionParticipantSubExtend`

- ID: `1684286899` / `0x64642db3`
- Сигнатура: `channelAdminLogEventActionParticipantSubExtend(prev_participant:ChannelParticipant, new_participant:ChannelParticipant) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionParticipantSubExtend
- Поля:
  - `prev_participant`: `ChannelParticipant`
  - `new_participant`: `ChannelParticipant`

### `channelAdminLogEventActionParticipantToggleAdmin`

- ID: `-714643696` / `0xd5676710`
- Сигнатура: `channelAdminLogEventActionParticipantToggleAdmin(prev_participant:ChannelParticipant, new_participant:ChannelParticipant) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionParticipantToggleAdmin
- Поля:
  - `prev_participant`: `ChannelParticipant`
  - `new_participant`: `ChannelParticipant`

### `channelAdminLogEventActionParticipantToggleBan`

- ID: `-422036098` / `0xe6d83d7e`
- Сигнатура: `channelAdminLogEventActionParticipantToggleBan(prev_participant:ChannelParticipant, new_participant:ChannelParticipant) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionParticipantToggleBan
- Поля:
  - `prev_participant`: `ChannelParticipant`
  - `new_participant`: `ChannelParticipant`

### `channelAdminLogEventActionParticipantUnmute`

- ID: `-431740480` / `0xe64429c0`
- Сигнатура: `channelAdminLogEventActionParticipantUnmute(participant:GroupCallParticipant) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionParticipantUnmute
- Поля:
  - `participant`: `GroupCallParticipant`

### `channelAdminLogEventActionParticipantVolume`

- ID: `1048537159` / `0x3e7f6847`
- Сигнатура: `channelAdminLogEventActionParticipantVolume(participant:GroupCallParticipant) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionParticipantVolume
- Поля:
  - `participant`: `GroupCallParticipant`

### `channelAdminLogEventActionPinTopic`

- ID: `1569535291` / `0x5d8d353b`
- Сигнатура: `channelAdminLogEventActionPinTopic(flags:#, prev_topic:flags.0?ForumTopic, new_topic:flags.1?ForumTopic) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionPinTopic
- Поля:
  - `flags`: `#` - служебное поле flags
  - `prev_topic`: `flags.0?ForumTopic` - optional через flags.0
  - `new_topic`: `flags.1?ForumTopic` - optional через flags.1

### `channelAdminLogEventActionSendMessage`

- ID: `663693416` / `0x278f2868`
- Сигнатура: `channelAdminLogEventActionSendMessage(message:Message) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionSendMessage
- Поля:
  - `message`: `Message`

### `channelAdminLogEventActionStartGroupCall`

- ID: `589338437` / `0x23209745`
- Сигнатура: `channelAdminLogEventActionStartGroupCall(call:InputGroupCall) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionStartGroupCall
- Поля:
  - `call`: `InputGroupCall`

### `channelAdminLogEventActionStopPoll`

- ID: `-1895328189` / `0x8f079643`
- Сигнатура: `channelAdminLogEventActionStopPoll(message:Message) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionStopPoll
- Поля:
  - `message`: `Message`

### `channelAdminLogEventActionToggleAntiSpam`

- ID: `1693675004` / `0x64f36dfc`
- Сигнатура: `channelAdminLogEventActionToggleAntiSpam(new_value:Bool) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionToggleAntiSpam
- Поля:
  - `new_value`: `Bool`

### `channelAdminLogEventActionToggleAutotranslation`

- ID: `-988285058` / `0xc517f77e`
- Сигнатура: `channelAdminLogEventActionToggleAutotranslation(new_value:Bool) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionToggleAutotranslation
- Поля:
  - `new_value`: `Bool`

### `channelAdminLogEventActionToggleForum`

- ID: `46949251` / `0x02cc6383`
- Сигнатура: `channelAdminLogEventActionToggleForum(new_value:Bool) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionToggleForum
- Поля:
  - `new_value`: `Bool`

### `channelAdminLogEventActionToggleGroupCallSetting`

- ID: `1456906823` / `0x56d6a247`
- Сигнатура: `channelAdminLogEventActionToggleGroupCallSetting(join_muted:Bool) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionToggleGroupCallSetting
- Поля:
  - `join_muted`: `Bool`

### `channelAdminLogEventActionToggleInvites`

- ID: `460916654` / `0x1b7907ae`
- Сигнатура: `channelAdminLogEventActionToggleInvites(new_value:Bool) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionToggleInvites
- Поля:
  - `new_value`: `Bool`

### `channelAdminLogEventActionToggleNoForwards`

- ID: `-886388890` / `0xcb2ac766`
- Сигнатура: `channelAdminLogEventActionToggleNoForwards(new_value:Bool) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionToggleNoForwards
- Поля:
  - `new_value`: `Bool`

### `channelAdminLogEventActionTogglePreHistoryHidden`

- ID: `1599903217` / `0x5f5c95f1`
- Сигнатура: `channelAdminLogEventActionTogglePreHistoryHidden(new_value:Bool) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionTogglePreHistoryHidden
- Поля:
  - `new_value`: `Bool`

### `channelAdminLogEventActionToggleSignatureProfiles`

- ID: `1621597305` / `0x60a79c79`
- Сигнатура: `channelAdminLogEventActionToggleSignatureProfiles(new_value:Bool) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionToggleSignatureProfiles
- Поля:
  - `new_value`: `Bool`

### `channelAdminLogEventActionToggleSignatures`

- ID: `648939889` / `0x26ae0971`
- Сигнатура: `channelAdminLogEventActionToggleSignatures(new_value:Bool) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionToggleSignatures
- Поля:
  - `new_value`: `Bool`

### `channelAdminLogEventActionToggleSlowMode`

- ID: `1401984889` / `0x53909779`
- Сигнатура: `channelAdminLogEventActionToggleSlowMode(prev_value:int, new_value:int) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionToggleSlowMode
- Поля:
  - `prev_value`: `int`
  - `new_value`: `int`

### `channelAdminLogEventActionUpdatePinned`

- ID: `-370660328` / `0xe9e82c18`
- Сигнатура: `channelAdminLogEventActionUpdatePinned(message:Message) => ChannelAdminLogEventAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventActionUpdatePinned
- Поля:
  - `message`: `Message`

## `ChannelAdminLogEventsFilter`

- Официальный тип: https://core.telegram.org/type/ChannelAdminLogEventsFilter
- Количество constructors: **1**

### `channelAdminLogEventsFilter`

- ID: `-368018716` / `0xea107ae4`
- Сигнатура: `channelAdminLogEventsFilter(flags:#, join:flags.0?true, leave:flags.1?true, invite:flags.2?true, ban:flags.3?true, unban:flags.4?true, kick:flags.5?true, unkick:flags.6?true, promote:flags.7?true, demote:flags.8?true, info:flags.9?true, settings:flags.10?true, pinned:flags.11?true, edit:flags.12?true, delete:flags.13?true, group_call:flags.14?true, invites:flags.15?true, send:flags.16?true, forums:flags.17?true, sub_extend:flags.18?true) => ChannelAdminLogEventsFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelAdminLogEventsFilter
- Поля:
  - `flags`: `#` - служебное поле flags
  - `join`: `flags.0?true` - optional через flags.0
  - `leave`: `flags.1?true` - optional через flags.1
  - `invite`: `flags.2?true` - optional через flags.2
  - `ban`: `flags.3?true` - optional через flags.3
  - `unban`: `flags.4?true` - optional через flags.4
  - `kick`: `flags.5?true` - optional через flags.5
  - `unkick`: `flags.6?true` - optional через flags.6
  - `promote`: `flags.7?true` - optional через flags.7
  - `demote`: `flags.8?true` - optional через flags.8
  - `info`: `flags.9?true` - optional через flags.9
  - `settings`: `flags.10?true` - optional через flags.10
  - `pinned`: `flags.11?true` - optional через flags.11
  - `edit`: `flags.12?true` - optional через flags.12
  - `delete`: `flags.13?true` - optional через flags.13
  - `group_call`: `flags.14?true` - optional через flags.14
  - `invites`: `flags.15?true` - optional через flags.15
  - `send`: `flags.16?true` - optional через flags.16
  - `forums`: `flags.17?true` - optional через flags.17
  - `sub_extend`: `flags.18?true` - optional через flags.18

## `ChannelLocation`

- Официальный тип: https://core.telegram.org/type/ChannelLocation
- Количество constructors: **2**

### `channelLocation`

- ID: `547062491` / `0x209b82db`
- Сигнатура: `channelLocation(geo_point:GeoPoint, address:string) => ChannelLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelLocation
- Поля:
  - `geo_point`: `GeoPoint`
  - `address`: `string`

### `channelLocationEmpty`

- ID: `-1078612597` / `0xbfb5ad8b`
- Сигнатура: `channelLocationEmpty() => ChannelLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelLocationEmpty
- Поля:
  - Нет полей.

## `ChannelMessagesFilter`

- Официальный тип: https://core.telegram.org/type/ChannelMessagesFilter
- Количество constructors: **2**

### `channelMessagesFilter`

- ID: `-847783593` / `0xcd77d957`
- Сигнатура: `channelMessagesFilter(flags:#, exclude_new_messages:flags.1?true, ranges:Vector) => ChannelMessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelMessagesFilter
- Поля:
  - `flags`: `#` - служебное поле flags
  - `exclude_new_messages`: `flags.1?true` - optional через flags.1
  - `ranges`: `Vector`

### `channelMessagesFilterEmpty`

- ID: `-1798033689` / `0x94d42ee7`
- Сигнатура: `channelMessagesFilterEmpty() => ChannelMessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelMessagesFilterEmpty
- Поля:
  - Нет полей.

## `ChannelParticipant`

- Официальный тип: https://core.telegram.org/type/ChannelParticipant
- Количество constructors: **6**

### `channelParticipant`

- ID: `-885426663` / `0xcb397619`
- Сигнатура: `channelParticipant(flags:#, user_id:long, date:int, subscription_until_date:flags.0?int) => ChannelParticipant`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipant
- Поля:
  - `flags`: `#` - служебное поле flags
  - `user_id`: `long`
  - `date`: `int`
  - `subscription_until_date`: `flags.0?int` - optional через flags.0

### `channelParticipantAdmin`

- ID: `885242707` / `0x34c3bb53`
- Сигнатура: `channelParticipantAdmin(flags:#, can_edit:flags.0?true, self:flags.1?true, user_id:long, inviter_id:flags.1?long, promoted_by:long, date:int, admin_rights:ChatAdminRights, rank:flags.2?string) => ChannelParticipant`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantAdmin
- Поля:
  - `flags`: `#` - служебное поле flags
  - `can_edit`: `flags.0?true` - optional через flags.0
  - `self`: `flags.1?true` - optional через flags.1
  - `user_id`: `long`
  - `inviter_id`: `flags.1?long` - optional через flags.1
  - `promoted_by`: `long`
  - `date`: `int`
  - `admin_rights`: `ChatAdminRights`
  - `rank`: `flags.2?string` - optional через flags.2

### `channelParticipantBanned`

- ID: `1844969806` / `0x6df8014e`
- Сигнатура: `channelParticipantBanned(flags:#, left:flags.0?true, peer:Peer, kicked_by:long, date:int, banned_rights:ChatBannedRights) => ChannelParticipant`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantBanned
- Поля:
  - `flags`: `#` - служебное поле flags
  - `left`: `flags.0?true` - optional через flags.0
  - `peer`: `Peer`
  - `kicked_by`: `long`
  - `date`: `int`
  - `banned_rights`: `ChatBannedRights`

### `channelParticipantCreator`

- ID: `803602899` / `0x2fe601d3`
- Сигнатура: `channelParticipantCreator(flags:#, user_id:long, admin_rights:ChatAdminRights, rank:flags.0?string) => ChannelParticipant`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantCreator
- Поля:
  - `flags`: `#` - служебное поле flags
  - `user_id`: `long`
  - `admin_rights`: `ChatAdminRights`
  - `rank`: `flags.0?string` - optional через flags.0

### `channelParticipantLeft`

- ID: `453242886` / `0x1b03f006`
- Сигнатура: `channelParticipantLeft(peer:Peer) => ChannelParticipant`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantLeft
- Поля:
  - `peer`: `Peer`

### `channelParticipantSelf`

- ID: `1331723247` / `0x4f607bef`
- Сигнатура: `channelParticipantSelf(flags:#, via_request:flags.0?true, user_id:long, inviter_id:long, date:int, subscription_until_date:flags.1?int) => ChannelParticipant`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantSelf
- Поля:
  - `flags`: `#` - служебное поле flags
  - `via_request`: `flags.0?true` - optional через flags.0
  - `user_id`: `long`
  - `inviter_id`: `long`
  - `date`: `int`
  - `subscription_until_date`: `flags.1?int` - optional через flags.1

## `ChannelParticipantsFilter`

- Официальный тип: https://core.telegram.org/type/ChannelParticipantsFilter
- Количество constructors: **8**

### `channelParticipantsAdmins`

- ID: `-1268741783` / `0xb4608969`
- Сигнатура: `channelParticipantsAdmins() => ChannelParticipantsFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantsAdmins
- Поля:
  - Нет полей.

### `channelParticipantsBanned`

- ID: `338142689` / `0x1427a5e1`
- Сигнатура: `channelParticipantsBanned(q:string) => ChannelParticipantsFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantsBanned
- Поля:
  - `q`: `string`

### `channelParticipantsBots`

- ID: `-1328445861` / `0xb0d1865b`
- Сигнатура: `channelParticipantsBots() => ChannelParticipantsFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantsBots
- Поля:
  - Нет полей.

### `channelParticipantsContacts`

- ID: `-1150621555` / `0xbb6ae88d`
- Сигнатура: `channelParticipantsContacts(q:string) => ChannelParticipantsFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantsContacts
- Поля:
  - `q`: `string`

### `channelParticipantsKicked`

- ID: `-1548400251` / `0xa3b54985`
- Сигнатура: `channelParticipantsKicked(q:string) => ChannelParticipantsFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantsKicked
- Поля:
  - `q`: `string`

### `channelParticipantsMentions`

- ID: `-531931925` / `0xe04b5ceb`
- Сигнатура: `channelParticipantsMentions(flags:#, q:flags.0?string, top_msg_id:flags.1?int) => ChannelParticipantsFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantsMentions
- Поля:
  - `flags`: `#` - служебное поле flags
  - `q`: `flags.0?string` - optional через flags.0
  - `top_msg_id`: `flags.1?int` - optional через flags.1

### `channelParticipantsRecent`

- ID: `-566281095` / `0xde3f3c79`
- Сигнатура: `channelParticipantsRecent() => ChannelParticipantsFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantsRecent
- Поля:
  - Нет полей.

### `channelParticipantsSearch`

- ID: `106343499` / `0x0656ac4b`
- Сигнатура: `channelParticipantsSearch(q:string) => ChannelParticipantsFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelParticipantsSearch
- Поля:
  - `q`: `string`

## `Chat`

- Официальный тип: https://core.telegram.org/type/Chat
- Количество constructors: **5**

### `channel`

- ID: `-26717355` / `0xfe685355`
- Сигнатура: `channel(flags:#, creator:flags.0?true, left:flags.2?true, broadcast:flags.5?true, verified:flags.7?true, megagroup:flags.8?true, restricted:flags.9?true, signatures:flags.11?true, min:flags.12?true, scam:flags.19?true, has_link:flags.20?true, has_geo:flags.21?true, slowmode_enabled:flags.22?true, call_active:flags.23?true, call_not_empty:flags.24?true, fake:flags.25?true, gigagroup:flags.26?true, noforwards:flags.27?true, join_to_send:flags.28?true, join_request:flags.29?true, forum:flags.30?true, flags2:#, stories_hidden:flags2.1?true, stories_hidden_min:flags2.2?true, stories_unavailable:flags2.3?true, signature_profiles:flags2.12?true, autotranslation:flags2.15?true, broadcast_messages_allowed:flags2.16?true, monoforum:flags2.17?true, forum_tabs:flags2.19?true, id:long, access_hash:flags.13?long, title:string, username:flags.6?string, photo:ChatPhoto, date:int, restriction_reason:flags.9?Vector, admin_rights:flags.14?ChatAdminRights, banned_rights:flags.15?ChatBannedRights, default_banned_rights:flags.18?ChatBannedRights, participants_count:flags.17?int, usernames:flags2.0?Vector, stories_max_id:flags2.4?int, color:flags2.7?PeerColor, profile_color:flags2.8?PeerColor, emoji_status:flags2.9?EmojiStatus, level:flags2.10?int, subscription_until_date:flags2.11?int, bot_verification_icon:flags2.13?long, send_paid_messages_stars:flags2.14?long, linked_monoforum_id:flags2.18?long) => Chat`
- Официальная страница конструктора: https://core.telegram.org/constructor/channel
- Поля:
  - `flags`: `#` - служебное поле flags
  - `creator`: `flags.0?true` - optional через flags.0
  - `left`: `flags.2?true` - optional через flags.2
  - `broadcast`: `flags.5?true` - optional через flags.5
  - `verified`: `flags.7?true` - optional через flags.7
  - `megagroup`: `flags.8?true` - optional через flags.8
  - `restricted`: `flags.9?true` - optional через flags.9
  - `signatures`: `flags.11?true` - optional через flags.11
  - `min`: `flags.12?true` - optional через flags.12
  - `scam`: `flags.19?true` - optional через flags.19
  - `has_link`: `flags.20?true` - optional через flags.20
  - `has_geo`: `flags.21?true` - optional через flags.21
  - `slowmode_enabled`: `flags.22?true` - optional через flags.22
  - `call_active`: `flags.23?true` - optional через flags.23
  - `call_not_empty`: `flags.24?true` - optional через flags.24
  - `fake`: `flags.25?true` - optional через flags.25
  - `gigagroup`: `flags.26?true` - optional через flags.26
  - `noforwards`: `flags.27?true` - optional через flags.27
  - `join_to_send`: `flags.28?true` - optional через flags.28
  - `join_request`: `flags.29?true` - optional через flags.29
  - `forum`: `flags.30?true` - optional через flags.30
  - `flags2`: `#` - служебное поле flags
  - `stories_hidden`: `flags2.1?true` - optional через flags2.1
  - `stories_hidden_min`: `flags2.2?true` - optional через flags2.2
  - `stories_unavailable`: `flags2.3?true` - optional через flags2.3
  - `signature_profiles`: `flags2.12?true` - optional через flags2.12
  - `autotranslation`: `flags2.15?true` - optional через flags2.15
  - `broadcast_messages_allowed`: `flags2.16?true` - optional через flags2.16
  - `monoforum`: `flags2.17?true` - optional через flags2.17
  - `forum_tabs`: `flags2.19?true` - optional через flags2.19
  - `id`: `long`
  - `access_hash`: `flags.13?long` - optional через flags.13
  - `title`: `string`
  - `username`: `flags.6?string` - optional через flags.6
  - `photo`: `ChatPhoto`
  - `date`: `int`
  - `restriction_reason`: `flags.9?Vector` - optional через flags.9
  - `admin_rights`: `flags.14?ChatAdminRights` - optional через flags.14
  - `banned_rights`: `flags.15?ChatBannedRights` - optional через flags.15
  - `default_banned_rights`: `flags.18?ChatBannedRights` - optional через flags.18
  - `participants_count`: `flags.17?int` - optional через flags.17
  - `usernames`: `flags2.0?Vector` - optional через flags2.0
  - `stories_max_id`: `flags2.4?int` - optional через flags2.4
  - `color`: `flags2.7?PeerColor` - optional через flags2.7
  - `profile_color`: `flags2.8?PeerColor` - optional через flags2.8
  - `emoji_status`: `flags2.9?EmojiStatus` - optional через flags2.9
  - `level`: `flags2.10?int` - optional через flags2.10
  - `subscription_until_date`: `flags2.11?int` - optional через flags2.11
  - `bot_verification_icon`: `flags2.13?long` - optional через flags2.13
  - `send_paid_messages_stars`: `flags2.14?long` - optional через flags2.14
  - `linked_monoforum_id`: `flags2.18?long` - optional через flags2.18

### `channelForbidden`

- ID: `399807445` / `0x17d493d5`
- Сигнатура: `channelForbidden(flags:#, broadcast:flags.5?true, megagroup:flags.8?true, id:long, access_hash:long, title:string, until_date:flags.16?int) => Chat`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelForbidden
- Поля:
  - `flags`: `#` - служебное поле flags
  - `broadcast`: `flags.5?true` - optional через flags.5
  - `megagroup`: `flags.8?true` - optional через flags.8
  - `id`: `long`
  - `access_hash`: `long`
  - `title`: `string`
  - `until_date`: `flags.16?int` - optional через flags.16

### `chat`

- ID: `1103884886` / `0x41cbf256`
- Сигнатура: `chat(flags:#, creator:flags.0?true, left:flags.2?true, deactivated:flags.5?true, call_active:flags.23?true, call_not_empty:flags.24?true, noforwards:flags.25?true, id:long, title:string, photo:ChatPhoto, participants_count:int, date:int, version:int, migrated_to:flags.6?InputChannel, admin_rights:flags.14?ChatAdminRights, default_banned_rights:flags.18?ChatBannedRights) => Chat`
- Официальная страница конструктора: https://core.telegram.org/constructor/chat
- Поля:
  - `flags`: `#` - служебное поле flags
  - `creator`: `flags.0?true` - optional через flags.0
  - `left`: `flags.2?true` - optional через flags.2
  - `deactivated`: `flags.5?true` - optional через flags.5
  - `call_active`: `flags.23?true` - optional через flags.23
  - `call_not_empty`: `flags.24?true` - optional через flags.24
  - `noforwards`: `flags.25?true` - optional через flags.25
  - `id`: `long`
  - `title`: `string`
  - `photo`: `ChatPhoto`
  - `participants_count`: `int`
  - `date`: `int`
  - `version`: `int`
  - `migrated_to`: `flags.6?InputChannel` - optional через flags.6
  - `admin_rights`: `flags.14?ChatAdminRights` - optional через flags.14
  - `default_banned_rights`: `flags.18?ChatBannedRights` - optional через flags.18

### `chatEmpty`

- ID: `693512293` / `0x29562865`
- Сигнатура: `chatEmpty(id:long) => Chat`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatEmpty
- Поля:
  - `id`: `long`

### `chatForbidden`

- ID: `1704108455` / `0x6592a1a7`
- Сигнатура: `chatForbidden(id:long, title:string) => Chat`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatForbidden
- Поля:
  - `id`: `long`
  - `title`: `string`

## `ChatAdminRights`

- Официальный тип: https://core.telegram.org/type/ChatAdminRights
- Количество constructors: **1**

### `chatAdminRights`

- ID: `1605510357` / `0x5fb224d5`
- Сигнатура: `chatAdminRights(flags:#, change_info:flags.0?true, post_messages:flags.1?true, edit_messages:flags.2?true, delete_messages:flags.3?true, ban_users:flags.4?true, invite_users:flags.5?true, pin_messages:flags.7?true, add_admins:flags.9?true, anonymous:flags.10?true, manage_call:flags.11?true, other:flags.12?true, manage_topics:flags.13?true, post_stories:flags.14?true, edit_stories:flags.15?true, delete_stories:flags.16?true, manage_direct_messages:flags.17?true) => ChatAdminRights`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatAdminRights
- Поля:
  - `flags`: `#` - служебное поле flags
  - `change_info`: `flags.0?true` - optional через flags.0
  - `post_messages`: `flags.1?true` - optional через flags.1
  - `edit_messages`: `flags.2?true` - optional через flags.2
  - `delete_messages`: `flags.3?true` - optional через flags.3
  - `ban_users`: `flags.4?true` - optional через flags.4
  - `invite_users`: `flags.5?true` - optional через flags.5
  - `pin_messages`: `flags.7?true` - optional через flags.7
  - `add_admins`: `flags.9?true` - optional через flags.9
  - `anonymous`: `flags.10?true` - optional через flags.10
  - `manage_call`: `flags.11?true` - optional через flags.11
  - `other`: `flags.12?true` - optional через flags.12
  - `manage_topics`: `flags.13?true` - optional через flags.13
  - `post_stories`: `flags.14?true` - optional через flags.14
  - `edit_stories`: `flags.15?true` - optional через flags.15
  - `delete_stories`: `flags.16?true` - optional через flags.16
  - `manage_direct_messages`: `flags.17?true` - optional через flags.17

## `ChatAdminWithInvites`

- Официальный тип: https://core.telegram.org/type/ChatAdminWithInvites
- Количество constructors: **1**

### `chatAdminWithInvites`

- ID: `-219353309` / `0xf2ecef23`
- Сигнатура: `chatAdminWithInvites(admin_id:long, invites_count:int, revoked_invites_count:int) => ChatAdminWithInvites`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatAdminWithInvites
- Поля:
  - `admin_id`: `long`
  - `invites_count`: `int`
  - `revoked_invites_count`: `int`

## `ChatBannedRights`

- Официальный тип: https://core.telegram.org/type/ChatBannedRights
- Количество constructors: **1**

### `chatBannedRights`

- ID: `-1626209256` / `0x9f120418`
- Сигнатура: `chatBannedRights(flags:#, view_messages:flags.0?true, send_messages:flags.1?true, send_media:flags.2?true, send_stickers:flags.3?true, send_gifs:flags.4?true, send_games:flags.5?true, send_inline:flags.6?true, embed_links:flags.7?true, send_polls:flags.8?true, change_info:flags.10?true, invite_users:flags.15?true, pin_messages:flags.17?true, manage_topics:flags.18?true, send_photos:flags.19?true, send_videos:flags.20?true, send_roundvideos:flags.21?true, send_audios:flags.22?true, send_voices:flags.23?true, send_docs:flags.24?true, send_plain:flags.25?true, until_date:int) => ChatBannedRights`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatBannedRights
- Поля:
  - `flags`: `#` - служебное поле flags
  - `view_messages`: `flags.0?true` - optional через flags.0
  - `send_messages`: `flags.1?true` - optional через flags.1
  - `send_media`: `flags.2?true` - optional через flags.2
  - `send_stickers`: `flags.3?true` - optional через flags.3
  - `send_gifs`: `flags.4?true` - optional через flags.4
  - `send_games`: `flags.5?true` - optional через flags.5
  - `send_inline`: `flags.6?true` - optional через flags.6
  - `embed_links`: `flags.7?true` - optional через flags.7
  - `send_polls`: `flags.8?true` - optional через flags.8
  - `change_info`: `flags.10?true` - optional через flags.10
  - `invite_users`: `flags.15?true` - optional через flags.15
  - `pin_messages`: `flags.17?true` - optional через flags.17
  - `manage_topics`: `flags.18?true` - optional через flags.18
  - `send_photos`: `flags.19?true` - optional через flags.19
  - `send_videos`: `flags.20?true` - optional через flags.20
  - `send_roundvideos`: `flags.21?true` - optional через flags.21
  - `send_audios`: `flags.22?true` - optional через flags.22
  - `send_voices`: `flags.23?true` - optional через flags.23
  - `send_docs`: `flags.24?true` - optional через flags.24
  - `send_plain`: `flags.25?true` - optional через flags.25
  - `until_date`: `int`

## `ChatFull`

- Официальный тип: https://core.telegram.org/type/ChatFull
- Количество constructors: **2**

### `channelFull`

- ID: `-455036259` / `0xe4e0b29d`
- Сигнатура: `channelFull(flags:#, can_view_participants:flags.3?true, can_set_username:flags.6?true, can_set_stickers:flags.7?true, hidden_prehistory:flags.10?true, can_set_location:flags.16?true, has_scheduled:flags.19?true, can_view_stats:flags.20?true, blocked:flags.22?true, flags2:#, can_delete_channel:flags2.0?true, antispam:flags2.1?true, participants_hidden:flags2.2?true, translations_disabled:flags2.3?true, stories_pinned_available:flags2.5?true, view_forum_as_messages:flags2.6?true, restricted_sponsored:flags2.11?true, can_view_revenue:flags2.12?true, paid_media_allowed:flags2.14?true, can_view_stars_revenue:flags2.15?true, paid_reactions_available:flags2.16?true, stargifts_available:flags2.19?true, paid_messages_available:flags2.20?true, id:long, about:string, participants_count:flags.0?int, admins_count:flags.1?int, kicked_count:flags.2?int, banned_count:flags.2?int, online_count:flags.13?int, read_inbox_max_id:int, read_outbox_max_id:int, unread_count:int, chat_photo:Photo, notify_settings:PeerNotifySettings, exported_invite:flags.23?ExportedChatInvite, bot_info:Vector, migrated_from_chat_id:flags.4?long, migrated_from_max_id:flags.4?int, pinned_msg_id:flags.5?int, stickerset:flags.8?StickerSet, available_min_id:flags.9?int, folder_id:flags.11?int, linked_chat_id:flags.14?long, location:flags.15?ChannelLocation, slowmode_seconds:flags.17?int, slowmode_next_send_date:flags.18?int, stats_dc:flags.12?int, pts:int, call:flags.21?InputGroupCall, ttl_period:flags.24?int, pending_suggestions:flags.25?Vector, groupcall_default_join_as:flags.26?Peer, theme_emoticon:flags.27?string, requests_pending:flags.28?int, recent_requesters:flags.28?Vector, default_send_as:flags.29?Peer, available_reactions:flags.30?ChatReactions, reactions_limit:flags2.13?int, stories:flags2.4?PeerStories, wallpaper:flags2.7?WallPaper, boosts_applied:flags2.8?int, boosts_unrestrict:flags2.9?int, emojiset:flags2.10?StickerSet, bot_verification:flags2.17?BotVerification, stargifts_count:flags2.18?int, send_paid_messages_stars:flags2.21?long, main_tab:flags2.22?ProfileTab) => ChatFull`
- Официальная страница конструктора: https://core.telegram.org/constructor/channelFull
- Поля:
  - `flags`: `#` - служебное поле flags
  - `can_view_participants`: `flags.3?true` - optional через flags.3
  - `can_set_username`: `flags.6?true` - optional через flags.6
  - `can_set_stickers`: `flags.7?true` - optional через flags.7
  - `hidden_prehistory`: `flags.10?true` - optional через flags.10
  - `can_set_location`: `flags.16?true` - optional через flags.16
  - `has_scheduled`: `flags.19?true` - optional через flags.19
  - `can_view_stats`: `flags.20?true` - optional через flags.20
  - `blocked`: `flags.22?true` - optional через flags.22
  - `flags2`: `#` - служебное поле flags
  - `can_delete_channel`: `flags2.0?true` - optional через flags2.0
  - `antispam`: `flags2.1?true` - optional через flags2.1
  - `participants_hidden`: `flags2.2?true` - optional через flags2.2
  - `translations_disabled`: `flags2.3?true` - optional через flags2.3
  - `stories_pinned_available`: `flags2.5?true` - optional через flags2.5
  - `view_forum_as_messages`: `flags2.6?true` - optional через flags2.6
  - `restricted_sponsored`: `flags2.11?true` - optional через flags2.11
  - `can_view_revenue`: `flags2.12?true` - optional через flags2.12
  - `paid_media_allowed`: `flags2.14?true` - optional через flags2.14
  - `can_view_stars_revenue`: `flags2.15?true` - optional через flags2.15
  - `paid_reactions_available`: `flags2.16?true` - optional через flags2.16
  - `stargifts_available`: `flags2.19?true` - optional через flags2.19
  - `paid_messages_available`: `flags2.20?true` - optional через flags2.20
  - `id`: `long`
  - `about`: `string`
  - `participants_count`: `flags.0?int` - optional через flags.0
  - `admins_count`: `flags.1?int` - optional через flags.1
  - `kicked_count`: `flags.2?int` - optional через flags.2
  - `banned_count`: `flags.2?int` - optional через flags.2
  - `online_count`: `flags.13?int` - optional через flags.13
  - `read_inbox_max_id`: `int`
  - `read_outbox_max_id`: `int`
  - `unread_count`: `int`
  - `chat_photo`: `Photo`
  - `notify_settings`: `PeerNotifySettings`
  - `exported_invite`: `flags.23?ExportedChatInvite` - optional через flags.23
  - `bot_info`: `Vector`
  - `migrated_from_chat_id`: `flags.4?long` - optional через flags.4
  - `migrated_from_max_id`: `flags.4?int` - optional через flags.4
  - `pinned_msg_id`: `flags.5?int` - optional через flags.5
  - `stickerset`: `flags.8?StickerSet` - optional через flags.8
  - `available_min_id`: `flags.9?int` - optional через flags.9
  - `folder_id`: `flags.11?int` - optional через flags.11
  - `linked_chat_id`: `flags.14?long` - optional через flags.14
  - `location`: `flags.15?ChannelLocation` - optional через flags.15
  - `slowmode_seconds`: `flags.17?int` - optional через flags.17
  - `slowmode_next_send_date`: `flags.18?int` - optional через flags.18
  - `stats_dc`: `flags.12?int` - optional через flags.12
  - `pts`: `int`
  - `call`: `flags.21?InputGroupCall` - optional через flags.21
  - `ttl_period`: `flags.24?int` - optional через flags.24
  - `pending_suggestions`: `flags.25?Vector` - optional через flags.25
  - `groupcall_default_join_as`: `flags.26?Peer` - optional через flags.26
  - `theme_emoticon`: `flags.27?string` - optional через flags.27
  - `requests_pending`: `flags.28?int` - optional через flags.28
  - `recent_requesters`: `flags.28?Vector` - optional через flags.28
  - `default_send_as`: `flags.29?Peer` - optional через flags.29
  - `available_reactions`: `flags.30?ChatReactions` - optional через flags.30
  - `reactions_limit`: `flags2.13?int` - optional через flags2.13
  - `stories`: `flags2.4?PeerStories` - optional через flags2.4
  - `wallpaper`: `flags2.7?WallPaper` - optional через flags2.7
  - `boosts_applied`: `flags2.8?int` - optional через flags2.8
  - `boosts_unrestrict`: `flags2.9?int` - optional через flags2.9
  - `emojiset`: `flags2.10?StickerSet` - optional через flags2.10
  - `bot_verification`: `flags2.17?BotVerification` - optional через flags2.17
  - `stargifts_count`: `flags2.18?int` - optional через flags2.18
  - `send_paid_messages_stars`: `flags2.21?long` - optional через flags2.21
  - `main_tab`: `flags2.22?ProfileTab` - optional через flags2.22

### `chatFull`

- ID: `640893467` / `0x2633421b`
- Сигнатура: `chatFull(flags:#, can_set_username:flags.7?true, has_scheduled:flags.8?true, translations_disabled:flags.19?true, id:long, about:string, participants:ChatParticipants, chat_photo:flags.2?Photo, notify_settings:PeerNotifySettings, exported_invite:flags.13?ExportedChatInvite, bot_info:flags.3?Vector, pinned_msg_id:flags.6?int, folder_id:flags.11?int, call:flags.12?InputGroupCall, ttl_period:flags.14?int, groupcall_default_join_as:flags.15?Peer, theme_emoticon:flags.16?string, requests_pending:flags.17?int, recent_requesters:flags.17?Vector, available_reactions:flags.18?ChatReactions, reactions_limit:flags.20?int) => ChatFull`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatFull
- Поля:
  - `flags`: `#` - служебное поле flags
  - `can_set_username`: `flags.7?true` - optional через flags.7
  - `has_scheduled`: `flags.8?true` - optional через flags.8
  - `translations_disabled`: `flags.19?true` - optional через flags.19
  - `id`: `long`
  - `about`: `string`
  - `participants`: `ChatParticipants`
  - `chat_photo`: `flags.2?Photo` - optional через flags.2
  - `notify_settings`: `PeerNotifySettings`
  - `exported_invite`: `flags.13?ExportedChatInvite` - optional через flags.13
  - `bot_info`: `flags.3?Vector` - optional через flags.3
  - `pinned_msg_id`: `flags.6?int` - optional через flags.6
  - `folder_id`: `flags.11?int` - optional через flags.11
  - `call`: `flags.12?InputGroupCall` - optional через flags.12
  - `ttl_period`: `flags.14?int` - optional через flags.14
  - `groupcall_default_join_as`: `flags.15?Peer` - optional через flags.15
  - `theme_emoticon`: `flags.16?string` - optional через flags.16
  - `requests_pending`: `flags.17?int` - optional через flags.17
  - `recent_requesters`: `flags.17?Vector` - optional через flags.17
  - `available_reactions`: `flags.18?ChatReactions` - optional через flags.18
  - `reactions_limit`: `flags.20?int` - optional через flags.20

## `ChatInvite`

- Официальный тип: https://core.telegram.org/type/ChatInvite
- Количество constructors: **3**

### `chatInvite`

- ID: `1553807106` / `0x5c9d3702`
- Сигнатура: `chatInvite(flags:#, channel:flags.0?true, broadcast:flags.1?true, public:flags.2?true, megagroup:flags.3?true, request_needed:flags.6?true, verified:flags.7?true, scam:flags.8?true, fake:flags.9?true, can_refulfill_subscription:flags.11?true, title:string, about:flags.5?string, photo:Photo, participants_count:int, participants:flags.4?Vector, color:int, subscription_pricing:flags.10?StarsSubscriptionPricing, subscription_form_id:flags.12?long, bot_verification:flags.13?BotVerification) => ChatInvite`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatInvite
- Поля:
  - `flags`: `#` - служебное поле flags
  - `channel`: `flags.0?true` - optional через flags.0
  - `broadcast`: `flags.1?true` - optional через flags.1
  - `public`: `flags.2?true` - optional через flags.2
  - `megagroup`: `flags.3?true` - optional через flags.3
  - `request_needed`: `flags.6?true` - optional через flags.6
  - `verified`: `flags.7?true` - optional через flags.7
  - `scam`: `flags.8?true` - optional через flags.8
  - `fake`: `flags.9?true` - optional через flags.9
  - `can_refulfill_subscription`: `flags.11?true` - optional через flags.11
  - `title`: `string`
  - `about`: `flags.5?string` - optional через flags.5
  - `photo`: `Photo`
  - `participants_count`: `int`
  - `participants`: `flags.4?Vector` - optional через flags.4
  - `color`: `int`
  - `subscription_pricing`: `flags.10?StarsSubscriptionPricing` - optional через flags.10
  - `subscription_form_id`: `flags.12?long` - optional через flags.12
  - `bot_verification`: `flags.13?BotVerification` - optional через flags.13

### `chatInviteAlready`

- ID: `1516793212` / `0x5a686d7c`
- Сигнатура: `chatInviteAlready(chat:Chat) => ChatInvite`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatInviteAlready
- Поля:
  - `chat`: `Chat`

### `chatInvitePeek`

- ID: `1634294960` / `0x61695cb0`
- Сигнатура: `chatInvitePeek(chat:Chat, expires:int) => ChatInvite`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatInvitePeek
- Поля:
  - `chat`: `Chat`
  - `expires`: `int`

## `ChatInviteImporter`

- Официальный тип: https://core.telegram.org/type/ChatInviteImporter
- Количество constructors: **1**

### `chatInviteImporter`

- ID: `-1940201511` / `0x8c5adfd9`
- Сигнатура: `chatInviteImporter(flags:#, requested:flags.0?true, via_chatlist:flags.3?true, user_id:long, date:int, about:flags.2?string, approved_by:flags.1?long) => ChatInviteImporter`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatInviteImporter
- Поля:
  - `flags`: `#` - служебное поле flags
  - `requested`: `flags.0?true` - optional через flags.0
  - `via_chatlist`: `flags.3?true` - optional через flags.3
  - `user_id`: `long`
  - `date`: `int`
  - `about`: `flags.2?string` - optional через flags.2
  - `approved_by`: `flags.1?long` - optional через flags.1

## `ChatOnlines`

- Официальный тип: https://core.telegram.org/type/ChatOnlines
- Количество constructors: **1**

### `chatOnlines`

- ID: `-264117680` / `0xf041e250`
- Сигнатура: `chatOnlines(onlines:int) => ChatOnlines`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatOnlines
- Поля:
  - `onlines`: `int`

## `ChatParticipant`

- Официальный тип: https://core.telegram.org/type/ChatParticipant
- Количество constructors: **3**

### `chatParticipant`

- ID: `-1070776313` / `0xc02d4007`
- Сигнатура: `chatParticipant(user_id:long, inviter_id:long, date:int) => ChatParticipant`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatParticipant
- Поля:
  - `user_id`: `long`
  - `inviter_id`: `long`
  - `date`: `int`

### `chatParticipantAdmin`

- ID: `-1600962725` / `0xa0933f5b`
- Сигнатура: `chatParticipantAdmin(user_id:long, inviter_id:long, date:int) => ChatParticipant`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatParticipantAdmin
- Поля:
  - `user_id`: `long`
  - `inviter_id`: `long`
  - `date`: `int`

### `chatParticipantCreator`

- ID: `-462696732` / `0xe46bcee4`
- Сигнатура: `chatParticipantCreator(user_id:long) => ChatParticipant`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatParticipantCreator
- Поля:
  - `user_id`: `long`

## `ChatParticipants`

- Официальный тип: https://core.telegram.org/type/ChatParticipants
- Количество constructors: **2**

### `chatParticipants`

- ID: `1018991608` / `0x3cbc93f8`
- Сигнатура: `chatParticipants(chat_id:long, participants:Vector, version:int) => ChatParticipants`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatParticipants
- Поля:
  - `chat_id`: `long`
  - `participants`: `Vector`
  - `version`: `int`

### `chatParticipantsForbidden`

- ID: `-2023500831` / `0x8763d3e1`
- Сигнатура: `chatParticipantsForbidden(flags:#, chat_id:long, self_participant:flags.0?ChatParticipant) => ChatParticipants`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatParticipantsForbidden
- Поля:
  - `flags`: `#` - служебное поле flags
  - `chat_id`: `long`
  - `self_participant`: `flags.0?ChatParticipant` - optional через flags.0

## `ChatPhoto`

- Официальный тип: https://core.telegram.org/type/ChatPhoto
- Количество constructors: **2**

### `chatPhoto`

- ID: `476978193` / `0x1c6e1c11`
- Сигнатура: `chatPhoto(flags:#, has_video:flags.0?true, photo_id:long, stripped_thumb:flags.1?bytes, dc_id:int) => ChatPhoto`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatPhoto
- Поля:
  - `flags`: `#` - служебное поле flags
  - `has_video`: `flags.0?true` - optional через flags.0
  - `photo_id`: `long`
  - `stripped_thumb`: `flags.1?bytes` - optional через flags.1
  - `dc_id`: `int`

### `chatPhotoEmpty`

- ID: `935395612` / `0x37c1011c`
- Сигнатура: `chatPhotoEmpty() => ChatPhoto`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatPhotoEmpty
- Поля:
  - Нет полей.

## `ChatReactions`

- Официальный тип: https://core.telegram.org/type/ChatReactions
- Количество constructors: **3**

### `chatReactionsAll`

- ID: `1385335754` / `0x52928bca`
- Сигнатура: `chatReactionsAll(flags:#, allow_custom:flags.0?true) => ChatReactions`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatReactionsAll
- Поля:
  - `flags`: `#` - служебное поле flags
  - `allow_custom`: `flags.0?true` - optional через flags.0

### `chatReactionsNone`

- ID: `-352570692` / `0xeafc32bc`
- Сигнатура: `chatReactionsNone() => ChatReactions`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatReactionsNone
- Поля:
  - Нет полей.

### `chatReactionsSome`

- ID: `1713193015` / `0x661d4037`
- Сигнатура: `chatReactionsSome(reactions:Vector) => ChatReactions`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatReactionsSome
- Поля:
  - `reactions`: `Vector`

## `ChatTheme`

- Официальный тип: https://core.telegram.org/type/ChatTheme
- Количество constructors: **2**

### `chatTheme`

- ID: `-1008731132` / `0xc3dffc04`
- Сигнатура: `chatTheme(emoticon:string) => ChatTheme`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatTheme
- Поля:
  - `emoticon`: `string`

### `chatThemeUniqueGift`

- ID: `878246344` / `0x3458f9c8`
- Сигнатура: `chatThemeUniqueGift(gift:StarGift, theme_settings:Vector) => ChatTheme`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatThemeUniqueGift
- Поля:
  - `gift`: `StarGift`
  - `theme_settings`: `Vector`

## `CodeSettings`

- Официальный тип: https://core.telegram.org/type/CodeSettings
- Количество constructors: **1**

### `codeSettings`

- ID: `-1390068360` / `0xad253d78`
- Сигнатура: `codeSettings(flags:#, allow_flashcall:flags.0?true, current_number:flags.1?true, allow_app_hash:flags.4?true, allow_missed_call:flags.5?true, allow_firebase:flags.7?true, unknown_number:flags.9?true, logout_tokens:flags.6?Vector, token:flags.8?string, app_sandbox:flags.8?Bool) => CodeSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/codeSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `allow_flashcall`: `flags.0?true` - optional через flags.0
  - `current_number`: `flags.1?true` - optional через flags.1
  - `allow_app_hash`: `flags.4?true` - optional через flags.4
  - `allow_missed_call`: `flags.5?true` - optional через flags.5
  - `allow_firebase`: `flags.7?true` - optional через flags.7
  - `unknown_number`: `flags.9?true` - optional через flags.9
  - `logout_tokens`: `flags.6?Vector` - optional через flags.6
  - `token`: `flags.8?string` - optional через flags.8
  - `app_sandbox`: `flags.8?Bool` - optional через flags.8

## `Config`

- Официальный тип: https://core.telegram.org/type/Config
- Количество constructors: **1**

### `config`

- ID: `-870702050` / `0xcc1a241e`
- Сигнатура: `config(flags:#, default_p2p_contacts:flags.3?true, preload_featured_stickers:flags.4?true, revoke_pm_inbox:flags.6?true, blocked_mode:flags.8?true, force_try_ipv6:flags.14?true, date:int, expires:int, test_mode:Bool, this_dc:int, dc_options:Vector, dc_txt_domain_name:string, chat_size_max:int, megagroup_size_max:int, forwarded_count_max:int, online_update_period_ms:int, offline_blur_timeout_ms:int, offline_idle_timeout_ms:int, online_cloud_timeout_ms:int, notify_cloud_delay_ms:int, notify_default_delay_ms:int, push_chat_period_ms:int, push_chat_limit:int, edit_time_limit:int, revoke_time_limit:int, revoke_pm_time_limit:int, rating_e_decay:int, stickers_recent_limit:int, channels_read_media_period:int, tmp_sessions:flags.0?int, call_receive_timeout_ms:int, call_ring_timeout_ms:int, call_connect_timeout_ms:int, call_packet_timeout_ms:int, me_url_prefix:string, autoupdate_url_prefix:flags.7?string, gif_search_username:flags.9?string, venue_search_username:flags.10?string, img_search_username:flags.11?string, static_maps_provider:flags.12?string, caption_length_max:int, message_length_max:int, webfile_dc_id:int, suggested_lang_code:flags.2?string, lang_pack_version:flags.2?int, base_lang_pack_version:flags.2?int, reactions_default:flags.15?Reaction, autologin_token:flags.16?string) => Config`
- Официальная страница конструктора: https://core.telegram.org/constructor/config
- Поля:
  - `flags`: `#` - служебное поле flags
  - `default_p2p_contacts`: `flags.3?true` - optional через flags.3
  - `preload_featured_stickers`: `flags.4?true` - optional через flags.4
  - `revoke_pm_inbox`: `flags.6?true` - optional через flags.6
  - `blocked_mode`: `flags.8?true` - optional через flags.8
  - `force_try_ipv6`: `flags.14?true` - optional через flags.14
  - `date`: `int`
  - `expires`: `int`
  - `test_mode`: `Bool`
  - `this_dc`: `int`
  - `dc_options`: `Vector`
  - `dc_txt_domain_name`: `string`
  - `chat_size_max`: `int`
  - `megagroup_size_max`: `int`
  - `forwarded_count_max`: `int`
  - `online_update_period_ms`: `int`
  - `offline_blur_timeout_ms`: `int`
  - `offline_idle_timeout_ms`: `int`
  - `online_cloud_timeout_ms`: `int`
  - `notify_cloud_delay_ms`: `int`
  - `notify_default_delay_ms`: `int`
  - `push_chat_period_ms`: `int`
  - `push_chat_limit`: `int`
  - `edit_time_limit`: `int`
  - `revoke_time_limit`: `int`
  - `revoke_pm_time_limit`: `int`
  - `rating_e_decay`: `int`
  - `stickers_recent_limit`: `int`
  - `channels_read_media_period`: `int`
  - `tmp_sessions`: `flags.0?int` - optional через flags.0
  - `call_receive_timeout_ms`: `int`
  - `call_ring_timeout_ms`: `int`
  - `call_connect_timeout_ms`: `int`
  - `call_packet_timeout_ms`: `int`
  - `me_url_prefix`: `string`
  - `autoupdate_url_prefix`: `flags.7?string` - optional через flags.7
  - `gif_search_username`: `flags.9?string` - optional через flags.9
  - `venue_search_username`: `flags.10?string` - optional через flags.10
  - `img_search_username`: `flags.11?string` - optional через flags.11
  - `static_maps_provider`: `flags.12?string` - optional через flags.12
  - `caption_length_max`: `int`
  - `message_length_max`: `int`
  - `webfile_dc_id`: `int`
  - `suggested_lang_code`: `flags.2?string` - optional через flags.2
  - `lang_pack_version`: `flags.2?int` - optional через flags.2
  - `base_lang_pack_version`: `flags.2?int` - optional через flags.2
  - `reactions_default`: `flags.15?Reaction` - optional через flags.15
  - `autologin_token`: `flags.16?string` - optional через flags.16

## `ConnectedBot`

- Официальный тип: https://core.telegram.org/type/ConnectedBot
- Количество constructors: **1**

### `connectedBot`

- ID: `-849058964` / `0xcd64636c`
- Сигнатура: `connectedBot(flags:#, bot_id:long, recipients:BusinessBotRecipients, rights:BusinessBotRights) => ConnectedBot`
- Официальная страница конструктора: https://core.telegram.org/constructor/connectedBot
- Поля:
  - `flags`: `#` - служебное поле flags
  - `bot_id`: `long`
  - `recipients`: `BusinessBotRecipients`
  - `rights`: `BusinessBotRights`

## `ConnectedBotStarRef`

- Официальный тип: https://core.telegram.org/type/ConnectedBotStarRef
- Количество constructors: **1**

### `connectedBotStarRef`

- ID: `429997937` / `0x19a13f71`
- Сигнатура: `connectedBotStarRef(flags:#, revoked:flags.1?true, url:string, date:int, bot_id:long, commission_permille:int, duration_months:flags.0?int, participants:long, revenue:long) => ConnectedBotStarRef`
- Официальная страница конструктора: https://core.telegram.org/constructor/connectedBotStarRef
- Поля:
  - `flags`: `#` - служебное поле flags
  - `revoked`: `flags.1?true` - optional через flags.1
  - `url`: `string`
  - `date`: `int`
  - `bot_id`: `long`
  - `commission_permille`: `int`
  - `duration_months`: `flags.0?int` - optional через flags.0
  - `participants`: `long`
  - `revenue`: `long`

## `Contact`

- Официальный тип: https://core.telegram.org/type/Contact
- Количество constructors: **1**

### `contact`

- ID: `341499403` / `0x145ade0b`
- Сигнатура: `contact(user_id:long, mutual:Bool) => Contact`
- Официальная страница конструктора: https://core.telegram.org/constructor/contact
- Поля:
  - `user_id`: `long`
  - `mutual`: `Bool`

## `ContactBirthday`

- Официальный тип: https://core.telegram.org/type/ContactBirthday
- Количество constructors: **1**

### `contactBirthday`

- ID: `496600883` / `0x1d998733`
- Сигнатура: `contactBirthday(contact_id:long, birthday:Birthday) => ContactBirthday`
- Официальная страница конструктора: https://core.telegram.org/constructor/contactBirthday
- Поля:
  - `contact_id`: `long`
  - `birthday`: `Birthday`

## `ContactStatus`

- Официальный тип: https://core.telegram.org/type/ContactStatus
- Количество constructors: **1**

### `contactStatus`

- ID: `383348795` / `0x16d9703b`
- Сигнатура: `contactStatus(user_id:long, status:UserStatus) => ContactStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/contactStatus
- Поля:
  - `user_id`: `long`
  - `status`: `UserStatus`

## `DataJSON`

- Официальный тип: https://core.telegram.org/type/DataJSON
- Количество constructors: **1**

### `dataJSON`

- ID: `2104790276` / `0x7d748d04`
- Сигнатура: `dataJSON(data:string) => DataJSON`
- Официальная страница конструктора: https://core.telegram.org/constructor/dataJSON
- Поля:
  - `data`: `string`

## `DcOption`

- Официальный тип: https://core.telegram.org/type/DcOption
- Количество constructors: **1**

### `dcOption`

- ID: `414687501` / `0x18b7a10d`
- Сигнатура: `dcOption(flags:#, ipv6:flags.0?true, media_only:flags.1?true, tcpo_only:flags.2?true, cdn:flags.3?true, static:flags.4?true, this_port_only:flags.5?true, id:int, ip_address:string, port:int, secret:flags.10?bytes) => DcOption`
- Официальная страница конструктора: https://core.telegram.org/constructor/dcOption
- Поля:
  - `flags`: `#` - служебное поле flags
  - `ipv6`: `flags.0?true` - optional через flags.0
  - `media_only`: `flags.1?true` - optional через flags.1
  - `tcpo_only`: `flags.2?true` - optional через flags.2
  - `cdn`: `flags.3?true` - optional через flags.3
  - `static`: `flags.4?true` - optional через flags.4
  - `this_port_only`: `flags.5?true` - optional через flags.5
  - `id`: `int`
  - `ip_address`: `string`
  - `port`: `int`
  - `secret`: `flags.10?bytes` - optional через flags.10

## `DefaultHistoryTTL`

- Официальный тип: https://core.telegram.org/type/DefaultHistoryTTL
- Количество constructors: **1**

### `defaultHistoryTTL`

- ID: `1135897376` / `0x43b46b20`
- Сигнатура: `defaultHistoryTTL(period:int) => DefaultHistoryTTL`
- Официальная страница конструктора: https://core.telegram.org/constructor/defaultHistoryTTL
- Поля:
  - `period`: `int`

## `Dialog`

- Официальный тип: https://core.telegram.org/type/Dialog
- Количество constructors: **2**

### `dialog`

- ID: `-712374074` / `0xd58a08c6`
- Сигнатура: `dialog(flags:#, pinned:flags.2?true, unread_mark:flags.3?true, view_forum_as_messages:flags.6?true, peer:Peer, top_message:int, read_inbox_max_id:int, read_outbox_max_id:int, unread_count:int, unread_mentions_count:int, unread_reactions_count:int, notify_settings:PeerNotifySettings, pts:flags.0?int, draft:flags.1?DraftMessage, folder_id:flags.4?int, ttl_period:flags.5?int) => Dialog`
- Официальная страница конструктора: https://core.telegram.org/constructor/dialog
- Поля:
  - `flags`: `#` - служебное поле flags
  - `pinned`: `flags.2?true` - optional через flags.2
  - `unread_mark`: `flags.3?true` - optional через flags.3
  - `view_forum_as_messages`: `flags.6?true` - optional через flags.6
  - `peer`: `Peer`
  - `top_message`: `int`
  - `read_inbox_max_id`: `int`
  - `read_outbox_max_id`: `int`
  - `unread_count`: `int`
  - `unread_mentions_count`: `int`
  - `unread_reactions_count`: `int`
  - `notify_settings`: `PeerNotifySettings`
  - `pts`: `flags.0?int` - optional через flags.0
  - `draft`: `flags.1?DraftMessage` - optional через flags.1
  - `folder_id`: `flags.4?int` - optional через flags.4
  - `ttl_period`: `flags.5?int` - optional через flags.5

### `dialogFolder`

- ID: `1908216652` / `0x71bd134c`
- Сигнатура: `dialogFolder(flags:#, pinned:flags.2?true, folder:Folder, peer:Peer, top_message:int, unread_muted_peers_count:int, unread_unmuted_peers_count:int, unread_muted_messages_count:int, unread_unmuted_messages_count:int) => Dialog`
- Официальная страница конструктора: https://core.telegram.org/constructor/dialogFolder
- Поля:
  - `flags`: `#` - служебное поле flags
  - `pinned`: `flags.2?true` - optional через flags.2
  - `folder`: `Folder`
  - `peer`: `Peer`
  - `top_message`: `int`
  - `unread_muted_peers_count`: `int`
  - `unread_unmuted_peers_count`: `int`
  - `unread_muted_messages_count`: `int`
  - `unread_unmuted_messages_count`: `int`

## `DialogFilter`

- Официальный тип: https://core.telegram.org/type/DialogFilter
- Количество constructors: **3**

### `dialogFilter`

- ID: `-1438177711` / `0xaa472651`
- Сигнатура: `dialogFilter(flags:#, contacts:flags.0?true, non_contacts:flags.1?true, groups:flags.2?true, broadcasts:flags.3?true, bots:flags.4?true, exclude_muted:flags.11?true, exclude_read:flags.12?true, exclude_archived:flags.13?true, title_noanimate:flags.28?true, id:int, title:TextWithEntities, emoticon:flags.25?string, color:flags.27?int, pinned_peers:Vector, include_peers:Vector, exclude_peers:Vector) => DialogFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/dialogFilter
- Поля:
  - `flags`: `#` - служебное поле flags
  - `contacts`: `flags.0?true` - optional через flags.0
  - `non_contacts`: `flags.1?true` - optional через flags.1
  - `groups`: `flags.2?true` - optional через flags.2
  - `broadcasts`: `flags.3?true` - optional через flags.3
  - `bots`: `flags.4?true` - optional через flags.4
  - `exclude_muted`: `flags.11?true` - optional через flags.11
  - `exclude_read`: `flags.12?true` - optional через flags.12
  - `exclude_archived`: `flags.13?true` - optional через flags.13
  - `title_noanimate`: `flags.28?true` - optional через flags.28
  - `id`: `int`
  - `title`: `TextWithEntities`
  - `emoticon`: `flags.25?string` - optional через flags.25
  - `color`: `flags.27?int` - optional через flags.27
  - `pinned_peers`: `Vector`
  - `include_peers`: `Vector`
  - `exclude_peers`: `Vector`

### `dialogFilterChatlist`

- ID: `-1772913705` / `0x96537bd7`
- Сигнатура: `dialogFilterChatlist(flags:#, has_my_invites:flags.26?true, title_noanimate:flags.28?true, id:int, title:TextWithEntities, emoticon:flags.25?string, color:flags.27?int, pinned_peers:Vector, include_peers:Vector) => DialogFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/dialogFilterChatlist
- Поля:
  - `flags`: `#` - служебное поле flags
  - `has_my_invites`: `flags.26?true` - optional через flags.26
  - `title_noanimate`: `flags.28?true` - optional через flags.28
  - `id`: `int`
  - `title`: `TextWithEntities`
  - `emoticon`: `flags.25?string` - optional через flags.25
  - `color`: `flags.27?int` - optional через flags.27
  - `pinned_peers`: `Vector`
  - `include_peers`: `Vector`

### `dialogFilterDefault`

- ID: `909284270` / `0x363293ae`
- Сигнатура: `dialogFilterDefault() => DialogFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/dialogFilterDefault
- Поля:
  - Нет полей.

## `DialogFilterSuggested`

- Официальный тип: https://core.telegram.org/type/DialogFilterSuggested
- Количество constructors: **1**

### `dialogFilterSuggested`

- ID: `2004110666` / `0x77744d4a`
- Сигнатура: `dialogFilterSuggested(filter:DialogFilter, description:string) => DialogFilterSuggested`
- Официальная страница конструктора: https://core.telegram.org/constructor/dialogFilterSuggested
- Поля:
  - `filter`: `DialogFilter`
  - `description`: `string`

## `DialogPeer`

- Официальный тип: https://core.telegram.org/type/DialogPeer
- Количество constructors: **2**

### `dialogPeer`

- ID: `-445792507` / `0xe56dbf05`
- Сигнатура: `dialogPeer(peer:Peer) => DialogPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/dialogPeer
- Поля:
  - `peer`: `Peer`

### `dialogPeerFolder`

- ID: `1363483106` / `0x514519e2`
- Сигнатура: `dialogPeerFolder(folder_id:int) => DialogPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/dialogPeerFolder
- Поля:
  - `folder_id`: `int`

## `DisallowedGiftsSettings`

- Официальный тип: https://core.telegram.org/type/DisallowedGiftsSettings
- Количество constructors: **1**

### `disallowedGiftsSettings`

- ID: `1911715524` / `0x71f276c4`
- Сигнатура: `disallowedGiftsSettings(flags:#, disallow_unlimited_stargifts:flags.0?true, disallow_limited_stargifts:flags.1?true, disallow_unique_stargifts:flags.2?true, disallow_premium_gifts:flags.3?true) => DisallowedGiftsSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/disallowedGiftsSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `disallow_unlimited_stargifts`: `flags.0?true` - optional через flags.0
  - `disallow_limited_stargifts`: `flags.1?true` - optional через flags.1
  - `disallow_unique_stargifts`: `flags.2?true` - optional через flags.2
  - `disallow_premium_gifts`: `flags.3?true` - optional через flags.3

## `Document`

- Официальный тип: https://core.telegram.org/type/Document
- Количество constructors: **2**

### `document`

- ID: `-1881881384` / `0x8fd4c4d8`
- Сигнатура: `document(flags:#, id:long, access_hash:long, file_reference:bytes, date:int, mime_type:string, size:long, thumbs:flags.0?Vector, video_thumbs:flags.1?Vector, dc_id:int, attributes:Vector) => Document`
- Официальная страница конструктора: https://core.telegram.org/constructor/document
- Поля:
  - `flags`: `#` - служебное поле flags
  - `id`: `long`
  - `access_hash`: `long`
  - `file_reference`: `bytes`
  - `date`: `int`
  - `mime_type`: `string`
  - `size`: `long`
  - `thumbs`: `flags.0?Vector` - optional через flags.0
  - `video_thumbs`: `flags.1?Vector` - optional через flags.1
  - `dc_id`: `int`
  - `attributes`: `Vector`

### `documentEmpty`

- ID: `922273905` / `0x36f8c871`
- Сигнатура: `documentEmpty(id:long) => Document`
- Официальная страница конструктора: https://core.telegram.org/constructor/documentEmpty
- Поля:
  - `id`: `long`

## `DocumentAttribute`

- Официальный тип: https://core.telegram.org/type/DocumentAttribute
- Количество constructors: **8**

### `documentAttributeAnimated`

- ID: `297109817` / `0x11b58939`
- Сигнатура: `documentAttributeAnimated() => DocumentAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/documentAttributeAnimated
- Поля:
  - Нет полей.

### `documentAttributeAudio`

- ID: `-1739392570` / `0x9852f9c6`
- Сигнатура: `documentAttributeAudio(flags:#, voice:flags.10?true, duration:int, title:flags.0?string, performer:flags.1?string, waveform:flags.2?bytes) => DocumentAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/documentAttributeAudio
- Поля:
  - `flags`: `#` - служебное поле flags
  - `voice`: `flags.10?true` - optional через flags.10
  - `duration`: `int`
  - `title`: `flags.0?string` - optional через flags.0
  - `performer`: `flags.1?string` - optional через flags.1
  - `waveform`: `flags.2?bytes` - optional через flags.2

### `documentAttributeCustomEmoji`

- ID: `-48981863` / `0xfd149899`
- Сигнатура: `documentAttributeCustomEmoji(flags:#, free:flags.0?true, text_color:flags.1?true, alt:string, stickerset:InputStickerSet) => DocumentAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/documentAttributeCustomEmoji
- Поля:
  - `flags`: `#` - служебное поле flags
  - `free`: `flags.0?true` - optional через flags.0
  - `text_color`: `flags.1?true` - optional через flags.1
  - `alt`: `string`
  - `stickerset`: `InputStickerSet`

### `documentAttributeFilename`

- ID: `358154344` / `0x15590068`
- Сигнатура: `documentAttributeFilename(file_name:string) => DocumentAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/documentAttributeFilename
- Поля:
  - `file_name`: `string`

### `documentAttributeHasStickers`

- ID: `-1744710921` / `0x9801d2f7`
- Сигнатура: `documentAttributeHasStickers() => DocumentAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/documentAttributeHasStickers
- Поля:
  - Нет полей.

### `documentAttributeImageSize`

- ID: `1815593308` / `0x6c37c15c`
- Сигнатура: `documentAttributeImageSize(w:int, h:int) => DocumentAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/documentAttributeImageSize
- Поля:
  - `w`: `int`
  - `h`: `int`

### `documentAttributeSticker`

- ID: `1662637586` / `0x6319d612`
- Сигнатура: `documentAttributeSticker(flags:#, mask:flags.1?true, alt:string, stickerset:InputStickerSet, mask_coords:flags.0?MaskCoords) => DocumentAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/documentAttributeSticker
- Поля:
  - `flags`: `#` - служебное поле flags
  - `mask`: `flags.1?true` - optional через flags.1
  - `alt`: `string`
  - `stickerset`: `InputStickerSet`
  - `mask_coords`: `flags.0?MaskCoords` - optional через flags.0

### `documentAttributeVideo`

- ID: `1137015880` / `0x43c57c48`
- Сигнатура: `documentAttributeVideo(flags:#, round_message:flags.0?true, supports_streaming:flags.1?true, nosound:flags.3?true, duration:double, w:int, h:int, preload_prefix_size:flags.2?int, video_start_ts:flags.4?double, video_codec:flags.5?string) => DocumentAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/documentAttributeVideo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `round_message`: `flags.0?true` - optional через flags.0
  - `supports_streaming`: `flags.1?true` - optional через flags.1
  - `nosound`: `flags.3?true` - optional через flags.3
  - `duration`: `double`
  - `w`: `int`
  - `h`: `int`
  - `preload_prefix_size`: `flags.2?int` - optional через flags.2
  - `video_start_ts`: `flags.4?double` - optional через flags.4
  - `video_codec`: `flags.5?string` - optional через flags.5

## `DraftMessage`

- Официальный тип: https://core.telegram.org/type/DraftMessage
- Количество constructors: **2**

### `draftMessage`

- ID: `-1763006997` / `0x96eaa5eb`
- Сигнатура: `draftMessage(flags:#, no_webpage:flags.1?true, invert_media:flags.6?true, reply_to:flags.4?InputReplyTo, message:string, entities:flags.3?Vector, media:flags.5?InputMedia, date:int, effect:flags.7?long, suggested_post:flags.8?SuggestedPost) => DraftMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/draftMessage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `no_webpage`: `flags.1?true` - optional через flags.1
  - `invert_media`: `flags.6?true` - optional через flags.6
  - `reply_to`: `flags.4?InputReplyTo` - optional через flags.4
  - `message`: `string`
  - `entities`: `flags.3?Vector` - optional через flags.3
  - `media`: `flags.5?InputMedia` - optional через flags.5
  - `date`: `int`
  - `effect`: `flags.7?long` - optional через flags.7
  - `suggested_post`: `flags.8?SuggestedPost` - optional через flags.8

### `draftMessageEmpty`

- ID: `453805082` / `0x1b0c841a`
- Сигнатура: `draftMessageEmpty(flags:#, date:flags.0?int) => DraftMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/draftMessageEmpty
- Поля:
  - `flags`: `#` - служебное поле flags
  - `date`: `flags.0?int` - optional через flags.0

## `EmailVerification`

- Официальный тип: https://core.telegram.org/type/EmailVerification
- Количество constructors: **3**

### `emailVerificationApple`

- ID: `-1764723459` / `0x96d074fd`
- Сигнатура: `emailVerificationApple(token:string) => EmailVerification`
- Официальная страница конструктора: https://core.telegram.org/constructor/emailVerificationApple
- Поля:
  - `token`: `string`

### `emailVerificationCode`

- ID: `-1842457175` / `0x922e55a9`
- Сигнатура: `emailVerificationCode(code:string) => EmailVerification`
- Официальная страница конструктора: https://core.telegram.org/constructor/emailVerificationCode
- Поля:
  - `code`: `string`

### `emailVerificationGoogle`

- ID: `-611279166` / `0xdb909ec2`
- Сигнатура: `emailVerificationGoogle(token:string) => EmailVerification`
- Официальная страница конструктора: https://core.telegram.org/constructor/emailVerificationGoogle
- Поля:
  - `token`: `string`

## `EmailVerifyPurpose`

- Официальный тип: https://core.telegram.org/type/EmailVerifyPurpose
- Количество constructors: **3**

### `emailVerifyPurposeLoginChange`

- ID: `1383932651` / `0x527d22eb`
- Сигнатура: `emailVerifyPurposeLoginChange() => EmailVerifyPurpose`
- Официальная страница конструктора: https://core.telegram.org/constructor/emailVerifyPurposeLoginChange
- Поля:
  - Нет полей.

### `emailVerifyPurposeLoginSetup`

- ID: `1128644211` / `0x4345be73`
- Сигнатура: `emailVerifyPurposeLoginSetup(phone_number:string, phone_code_hash:string) => EmailVerifyPurpose`
- Официальная страница конструктора: https://core.telegram.org/constructor/emailVerifyPurposeLoginSetup
- Поля:
  - `phone_number`: `string`
  - `phone_code_hash`: `string`

### `emailVerifyPurposePassport`

- ID: `-1141565819` / `0xbbf51685`
- Сигнатура: `emailVerifyPurposePassport() => EmailVerifyPurpose`
- Официальная страница конструктора: https://core.telegram.org/constructor/emailVerifyPurposePassport
- Поля:
  - Нет полей.

## `EmojiGroup`

- Официальный тип: https://core.telegram.org/type/EmojiGroup
- Количество constructors: **3**

### `emojiGroup`

- ID: `2056961449` / `0x7a9abda9`
- Сигнатура: `emojiGroup(title:string, icon_emoji_id:long, emoticons:Vector) => EmojiGroup`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiGroup
- Поля:
  - `title`: `string`
  - `icon_emoji_id`: `long`
  - `emoticons`: `Vector`

### `emojiGroupGreeting`

- ID: `-2133693241` / `0x80d26cc7`
- Сигнатура: `emojiGroupGreeting(title:string, icon_emoji_id:long, emoticons:Vector) => EmojiGroup`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiGroupGreeting
- Поля:
  - `title`: `string`
  - `icon_emoji_id`: `long`
  - `emoticons`: `Vector`

### `emojiGroupPremium`

- ID: `154914612` / `0x093bcf34`
- Сигнатура: `emojiGroupPremium(title:string, icon_emoji_id:long) => EmojiGroup`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiGroupPremium
- Поля:
  - `title`: `string`
  - `icon_emoji_id`: `long`

## `EmojiKeyword`

- Официальный тип: https://core.telegram.org/type/EmojiKeyword
- Количество constructors: **2**

### `emojiKeyword`

- ID: `-709641735` / `0xd5b3b9f9`
- Сигнатура: `emojiKeyword(keyword:string, emoticons:Vector) => EmojiKeyword`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiKeyword
- Поля:
  - `keyword`: `string`
  - `emoticons`: `Vector`

### `emojiKeywordDeleted`

- ID: `594408994` / `0x236df622`
- Сигнатура: `emojiKeywordDeleted(keyword:string, emoticons:Vector) => EmojiKeyword`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiKeywordDeleted
- Поля:
  - `keyword`: `string`
  - `emoticons`: `Vector`

## `EmojiKeywordsDifference`

- Официальный тип: https://core.telegram.org/type/EmojiKeywordsDifference
- Количество constructors: **1**

### `emojiKeywordsDifference`

- ID: `1556570557` / `0x5cc761bd`
- Сигнатура: `emojiKeywordsDifference(lang_code:string, from_version:int, version:int, keywords:Vector) => EmojiKeywordsDifference`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiKeywordsDifference
- Поля:
  - `lang_code`: `string`
  - `from_version`: `int`
  - `version`: `int`
  - `keywords`: `Vector`

## `EmojiLanguage`

- Официальный тип: https://core.telegram.org/type/EmojiLanguage
- Количество constructors: **1**

### `emojiLanguage`

- ID: `-1275374751` / `0xb3fb5361`
- Сигнатура: `emojiLanguage(lang_code:string) => EmojiLanguage`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiLanguage
- Поля:
  - `lang_code`: `string`

## `EmojiList`

- Официальный тип: https://core.telegram.org/type/EmojiList
- Количество constructors: **2**

### `emojiList`

- ID: `2048790993` / `0x7a1e11d1`
- Сигнатура: `emojiList(hash:long, document_id:Vector) => EmojiList`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiList
- Поля:
  - `hash`: `long`
  - `document_id`: `Vector`

### `emojiListNotModified`

- ID: `1209970170` / `0x481eadfa`
- Сигнатура: `emojiListNotModified() => EmojiList`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiListNotModified
- Поля:
  - Нет полей.

## `EmojiStatus`

- Официальный тип: https://core.telegram.org/type/EmojiStatus
- Количество constructors: **4**

### `emojiStatus`

- ID: `-402717046` / `0xe7ff068a`
- Сигнатура: `emojiStatus(flags:#, document_id:long, until:flags.0?int) => EmojiStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiStatus
- Поля:
  - `flags`: `#` - служебное поле flags
  - `document_id`: `long`
  - `until`: `flags.0?int` - optional через flags.0

### `emojiStatusCollectible`

- ID: `1904500795` / `0x7184603b`
- Сигнатура: `emojiStatusCollectible(flags:#, collectible_id:long, document_id:long, title:string, slug:string, pattern_document_id:long, center_color:int, edge_color:int, pattern_color:int, text_color:int, until:flags.0?int) => EmojiStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiStatusCollectible
- Поля:
  - `flags`: `#` - служебное поле flags
  - `collectible_id`: `long`
  - `document_id`: `long`
  - `title`: `string`
  - `slug`: `string`
  - `pattern_document_id`: `long`
  - `center_color`: `int`
  - `edge_color`: `int`
  - `pattern_color`: `int`
  - `text_color`: `int`
  - `until`: `flags.0?int` - optional через flags.0

### `emojiStatusEmpty`

- ID: `769727150` / `0x2de11aae`
- Сигнатура: `emojiStatusEmpty() => EmojiStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiStatusEmpty
- Поля:
  - Нет полей.

### `inputEmojiStatusCollectible`

- ID: `118758847` / `0x07141dbf`
- Сигнатура: `inputEmojiStatusCollectible(flags:#, collectible_id:long, until:flags.0?int) => EmojiStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputEmojiStatusCollectible
- Поля:
  - `flags`: `#` - служебное поле flags
  - `collectible_id`: `long`
  - `until`: `flags.0?int` - optional через flags.0

## `EmojiURL`

- Официальный тип: https://core.telegram.org/type/EmojiURL
- Количество constructors: **1**

### `emojiURL`

- ID: `-1519029347` / `0xa575739d`
- Сигнатура: `emojiURL(url:string) => EmojiURL`
- Официальная страница конструктора: https://core.telegram.org/constructor/emojiURL
- Поля:
  - `url`: `string`

## `EncryptedChat`

- Официальный тип: https://core.telegram.org/type/EncryptedChat
- Количество constructors: **5**

### `encryptedChat`

- ID: `1643173063` / `0x61f0d4c7`
- Сигнатура: `encryptedChat(id:int, access_hash:long, date:int, admin_id:long, participant_id:long, g_a_or_b:bytes, key_fingerprint:long) => EncryptedChat`
- Официальная страница конструктора: https://core.telegram.org/constructor/encryptedChat
- Поля:
  - `id`: `int`
  - `access_hash`: `long`
  - `date`: `int`
  - `admin_id`: `long`
  - `participant_id`: `long`
  - `g_a_or_b`: `bytes`
  - `key_fingerprint`: `long`

### `encryptedChatDiscarded`

- ID: `505183301` / `0x1e1c7c45`
- Сигнатура: `encryptedChatDiscarded(flags:#, history_deleted:flags.0?true, id:int) => EncryptedChat`
- Официальная страница конструктора: https://core.telegram.org/constructor/encryptedChatDiscarded
- Поля:
  - `flags`: `#` - служебное поле flags
  - `history_deleted`: `flags.0?true` - optional через flags.0
  - `id`: `int`

### `encryptedChatEmpty`

- ID: `-1417756512` / `0xab7ec0a0`
- Сигнатура: `encryptedChatEmpty(id:int) => EncryptedChat`
- Официальная страница конструктора: https://core.telegram.org/constructor/encryptedChatEmpty
- Поля:
  - `id`: `int`

### `encryptedChatRequested`

- ID: `1223809356` / `0x48f1d94c`
- Сигнатура: `encryptedChatRequested(flags:#, folder_id:flags.0?int, id:int, access_hash:long, date:int, admin_id:long, participant_id:long, g_a:bytes) => EncryptedChat`
- Официальная страница конструктора: https://core.telegram.org/constructor/encryptedChatRequested
- Поля:
  - `flags`: `#` - служебное поле flags
  - `folder_id`: `flags.0?int` - optional через flags.0
  - `id`: `int`
  - `access_hash`: `long`
  - `date`: `int`
  - `admin_id`: `long`
  - `participant_id`: `long`
  - `g_a`: `bytes`

### `encryptedChatWaiting`

- ID: `1722964307` / `0x66b25953`
- Сигнатура: `encryptedChatWaiting(id:int, access_hash:long, date:int, admin_id:long, participant_id:long) => EncryptedChat`
- Официальная страница конструктора: https://core.telegram.org/constructor/encryptedChatWaiting
- Поля:
  - `id`: `int`
  - `access_hash`: `long`
  - `date`: `int`
  - `admin_id`: `long`
  - `participant_id`: `long`

## `EncryptedFile`

- Официальный тип: https://core.telegram.org/type/EncryptedFile
- Количество constructors: **2**

### `encryptedFile`

- ID: `-1476358952` / `0xa8008cd8`
- Сигнатура: `encryptedFile(id:long, access_hash:long, size:long, dc_id:int, key_fingerprint:int) => EncryptedFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/encryptedFile
- Поля:
  - `id`: `long`
  - `access_hash`: `long`
  - `size`: `long`
  - `dc_id`: `int`
  - `key_fingerprint`: `int`

### `encryptedFileEmpty`

- ID: `-1038136962` / `0xc21f497e`
- Сигнатура: `encryptedFileEmpty() => EncryptedFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/encryptedFileEmpty
- Поля:
  - Нет полей.

## `EncryptedMessage`

- Официальный тип: https://core.telegram.org/type/EncryptedMessage
- Количество constructors: **2**

### `encryptedMessage`

- ID: `-317144808` / `0xed18c118`
- Сигнатура: `encryptedMessage(random_id:long, chat_id:int, date:int, bytes:bytes, file:EncryptedFile) => EncryptedMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/encryptedMessage
- Поля:
  - `random_id`: `long`
  - `chat_id`: `int`
  - `date`: `int`
  - `bytes`: `bytes`
  - `file`: `EncryptedFile`

### `encryptedMessageService`

- ID: `594758406` / `0x23734b06`
- Сигнатура: `encryptedMessageService(random_id:long, chat_id:int, date:int, bytes:bytes) => EncryptedMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/encryptedMessageService
- Поля:
  - `random_id`: `long`
  - `chat_id`: `int`
  - `date`: `int`
  - `bytes`: `bytes`

## `Error`

- Официальный тип: https://core.telegram.org/type/Error
- Количество constructors: **1**

### `error`

- ID: `-994444869` / `0xc4b9f9bb`
- Сигнатура: `error(code:int, text:string) => Error`
- Официальная страница конструктора: https://core.telegram.org/constructor/error
- Поля:
  - `code`: `int`
  - `text`: `string`

## `ExportedChatInvite`

- Официальный тип: https://core.telegram.org/type/ExportedChatInvite
- Количество constructors: **2**

### `chatInviteExported`

- ID: `-1574126186` / `0xa22cbd96`
- Сигнатура: `chatInviteExported(flags:#, revoked:flags.0?true, permanent:flags.5?true, request_needed:flags.6?true, link:string, admin_id:long, date:int, start_date:flags.4?int, expire_date:flags.1?int, usage_limit:flags.2?int, usage:flags.3?int, requested:flags.7?int, subscription_expired:flags.10?int, title:flags.8?string, subscription_pricing:flags.9?StarsSubscriptionPricing) => ExportedChatInvite`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatInviteExported
- Поля:
  - `flags`: `#` - служебное поле flags
  - `revoked`: `flags.0?true` - optional через flags.0
  - `permanent`: `flags.5?true` - optional через flags.5
  - `request_needed`: `flags.6?true` - optional через flags.6
  - `link`: `string`
  - `admin_id`: `long`
  - `date`: `int`
  - `start_date`: `flags.4?int` - optional через flags.4
  - `expire_date`: `flags.1?int` - optional через flags.1
  - `usage_limit`: `flags.2?int` - optional через flags.2
  - `usage`: `flags.3?int` - optional через flags.3
  - `requested`: `flags.7?int` - optional через flags.7
  - `subscription_expired`: `flags.10?int` - optional через flags.10
  - `title`: `flags.8?string` - optional через flags.8
  - `subscription_pricing`: `flags.9?StarsSubscriptionPricing` - optional через flags.9

### `chatInvitePublicJoinRequests`

- ID: `-317687113` / `0xed107ab7`
- Сигнатура: `chatInvitePublicJoinRequests() => ExportedChatInvite`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatInvitePublicJoinRequests
- Поля:
  - Нет полей.

## `ExportedChatlistInvite`

- Официальный тип: https://core.telegram.org/type/ExportedChatlistInvite
- Количество constructors: **1**

### `exportedChatlistInvite`

- ID: `206668204` / `0x0c5181ac`
- Сигнатура: `exportedChatlistInvite(flags:#, title:string, url:string, peers:Vector) => ExportedChatlistInvite`
- Официальная страница конструктора: https://core.telegram.org/constructor/exportedChatlistInvite
- Поля:
  - `flags`: `#` - служебное поле flags
  - `title`: `string`
  - `url`: `string`
  - `peers`: `Vector`

## `ExportedContactToken`

- Официальный тип: https://core.telegram.org/type/ExportedContactToken
- Количество constructors: **1**

### `exportedContactToken`

- ID: `1103040667` / `0x41bf109b`
- Сигнатура: `exportedContactToken(url:string, expires:int) => ExportedContactToken`
- Официальная страница конструктора: https://core.telegram.org/constructor/exportedContactToken
- Поля:
  - `url`: `string`
  - `expires`: `int`

## `ExportedMessageLink`

- Официальный тип: https://core.telegram.org/type/ExportedMessageLink
- Количество constructors: **1**

### `exportedMessageLink`

- ID: `1571494644` / `0x5dab1af4`
- Сигнатура: `exportedMessageLink(link:string, html:string) => ExportedMessageLink`
- Официальная страница конструктора: https://core.telegram.org/constructor/exportedMessageLink
- Поля:
  - `link`: `string`
  - `html`: `string`

## `ExportedStoryLink`

- Официальный тип: https://core.telegram.org/type/ExportedStoryLink
- Количество constructors: **1**

### `exportedStoryLink`

- ID: `1070138683` / `0x3fc9053b`
- Сигнатура: `exportedStoryLink(link:string) => ExportedStoryLink`
- Официальная страница конструктора: https://core.telegram.org/constructor/exportedStoryLink
- Поля:
  - `link`: `string`

## `FactCheck`

- Официальный тип: https://core.telegram.org/type/FactCheck
- Количество constructors: **1**

### `factCheck`

- ID: `-1197736753` / `0xb89bfccf`
- Сигнатура: `factCheck(flags:#, need_check:flags.0?true, country:flags.1?string, text:flags.1?TextWithEntities, hash:long) => FactCheck`
- Официальная страница конструктора: https://core.telegram.org/constructor/factCheck
- Поля:
  - `flags`: `#` - служебное поле flags
  - `need_check`: `flags.0?true` - optional через flags.0
  - `country`: `flags.1?string` - optional через flags.1
  - `text`: `flags.1?TextWithEntities` - optional через flags.1
  - `hash`: `long`

## `FileHash`

- Официальный тип: https://core.telegram.org/type/FileHash
- Количество constructors: **1**

### `fileHash`

- ID: `-207944868` / `0xf39b035c`
- Сигнатура: `fileHash(offset:long, limit:int, hash:bytes) => FileHash`
- Официальная страница конструктора: https://core.telegram.org/constructor/fileHash
- Поля:
  - `offset`: `long`
  - `limit`: `int`
  - `hash`: `bytes`

## `Folder`

- Официальный тип: https://core.telegram.org/type/Folder
- Количество constructors: **1**

### `folder`

- ID: `-11252123` / `0xff544e65`
- Сигнатура: `folder(flags:#, autofill_new_broadcasts:flags.0?true, autofill_public_groups:flags.1?true, autofill_new_correspondents:flags.2?true, id:int, title:string, photo:flags.3?ChatPhoto) => Folder`
- Официальная страница конструктора: https://core.telegram.org/constructor/folder
- Поля:
  - `flags`: `#` - служебное поле flags
  - `autofill_new_broadcasts`: `flags.0?true` - optional через flags.0
  - `autofill_public_groups`: `flags.1?true` - optional через flags.1
  - `autofill_new_correspondents`: `flags.2?true` - optional через flags.2
  - `id`: `int`
  - `title`: `string`
  - `photo`: `flags.3?ChatPhoto` - optional через flags.3

## `FolderPeer`

- Официальный тип: https://core.telegram.org/type/FolderPeer
- Количество constructors: **1**

### `folderPeer`

- ID: `-373643672` / `0xe9baa668`
- Сигнатура: `folderPeer(peer:Peer, folder_id:int) => FolderPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/folderPeer
- Поля:
  - `peer`: `Peer`
  - `folder_id`: `int`

## `ForumTopic`

- Официальный тип: https://core.telegram.org/type/ForumTopic
- Количество constructors: **2**

### `forumTopic`

- ID: `1903173033` / `0x71701da9`
- Сигнатура: `forumTopic(flags:#, my:flags.1?true, closed:flags.2?true, pinned:flags.3?true, short:flags.5?true, hidden:flags.6?true, id:int, date:int, title:string, icon_color:int, icon_emoji_id:flags.0?long, top_message:int, read_inbox_max_id:int, read_outbox_max_id:int, unread_count:int, unread_mentions_count:int, unread_reactions_count:int, from_id:Peer, notify_settings:PeerNotifySettings, draft:flags.4?DraftMessage) => ForumTopic`
- Официальная страница конструктора: https://core.telegram.org/constructor/forumTopic
- Поля:
  - `flags`: `#` - служебное поле flags
  - `my`: `flags.1?true` - optional через flags.1
  - `closed`: `flags.2?true` - optional через flags.2
  - `pinned`: `flags.3?true` - optional через flags.3
  - `short`: `flags.5?true` - optional через flags.5
  - `hidden`: `flags.6?true` - optional через flags.6
  - `id`: `int`
  - `date`: `int`
  - `title`: `string`
  - `icon_color`: `int`
  - `icon_emoji_id`: `flags.0?long` - optional через flags.0
  - `top_message`: `int`
  - `read_inbox_max_id`: `int`
  - `read_outbox_max_id`: `int`
  - `unread_count`: `int`
  - `unread_mentions_count`: `int`
  - `unread_reactions_count`: `int`
  - `from_id`: `Peer`
  - `notify_settings`: `PeerNotifySettings`
  - `draft`: `flags.4?DraftMessage` - optional через flags.4

### `forumTopicDeleted`

- ID: `37687451` / `0x023f109b`
- Сигнатура: `forumTopicDeleted(id:int) => ForumTopic`
- Официальная страница конструктора: https://core.telegram.org/constructor/forumTopicDeleted
- Поля:
  - `id`: `int`

## `FoundStory`

- Официальный тип: https://core.telegram.org/type/FoundStory
- Количество constructors: **1**

### `foundStory`

- ID: `-394605632` / `0xe87acbc0`
- Сигнатура: `foundStory(peer:Peer, story:StoryItem) => FoundStory`
- Официальная страница конструктора: https://core.telegram.org/constructor/foundStory
- Поля:
  - `peer`: `Peer`
  - `story`: `StoryItem`

## `Game`

- Официальный тип: https://core.telegram.org/type/Game
- Количество constructors: **1**

### `game`

- ID: `-1107729093` / `0xbdf9653b`
- Сигнатура: `game(flags:#, id:long, access_hash:long, short_name:string, title:string, description:string, photo:Photo, document:flags.0?Document) => Game`
- Официальная страница конструктора: https://core.telegram.org/constructor/game
- Поля:
  - `flags`: `#` - служебное поле flags
  - `id`: `long`
  - `access_hash`: `long`
  - `short_name`: `string`
  - `title`: `string`
  - `description`: `string`
  - `photo`: `Photo`
  - `document`: `flags.0?Document` - optional через flags.0

## `GeoPoint`

- Официальный тип: https://core.telegram.org/type/GeoPoint
- Количество constructors: **2**

### `geoPoint`

- ID: `-1297942941` / `0xb2a2f663`
- Сигнатура: `geoPoint(flags:#, long:double, lat:double, access_hash:long, accuracy_radius:flags.0?int) => GeoPoint`
- Официальная страница конструктора: https://core.telegram.org/constructor/geoPoint
- Поля:
  - `flags`: `#` - служебное поле flags
  - `long`: `double`
  - `lat`: `double`
  - `access_hash`: `long`
  - `accuracy_radius`: `flags.0?int` - optional через flags.0

### `geoPointEmpty`

- ID: `286776671` / `0x1117dd5f`
- Сигнатура: `geoPointEmpty() => GeoPoint`
- Официальная страница конструктора: https://core.telegram.org/constructor/geoPointEmpty
- Поля:
  - Нет полей.

## `GeoPointAddress`

- Официальный тип: https://core.telegram.org/type/GeoPointAddress
- Количество constructors: **1**

### `geoPointAddress`

- ID: `-565420653` / `0xde4c5d93`
- Сигнатура: `geoPointAddress(flags:#, country_iso2:string, state:flags.0?string, city:flags.1?string, street:flags.2?string) => GeoPointAddress`
- Официальная страница конструктора: https://core.telegram.org/constructor/geoPointAddress
- Поля:
  - `flags`: `#` - служебное поле flags
  - `country_iso2`: `string`
  - `state`: `flags.0?string` - optional через flags.0
  - `city`: `flags.1?string` - optional через flags.1
  - `street`: `flags.2?string` - optional через flags.2

## `GlobalPrivacySettings`

- Официальный тип: https://core.telegram.org/type/GlobalPrivacySettings
- Количество constructors: **1**

### `globalPrivacySettings`

- ID: `-29248689` / `0xfe41b34f`
- Сигнатура: `globalPrivacySettings(flags:#, archive_and_mute_new_noncontact_peers:flags.0?true, keep_archived_unmuted:flags.1?true, keep_archived_folders:flags.2?true, hide_read_marks:flags.3?true, new_noncontact_peers_require_premium:flags.4?true, display_gifts_button:flags.7?true, noncontact_peers_paid_stars:flags.5?long, disallowed_gifts:flags.6?DisallowedGiftsSettings) => GlobalPrivacySettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/globalPrivacySettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `archive_and_mute_new_noncontact_peers`: `flags.0?true` - optional через flags.0
  - `keep_archived_unmuted`: `flags.1?true` - optional через flags.1
  - `keep_archived_folders`: `flags.2?true` - optional через flags.2
  - `hide_read_marks`: `flags.3?true` - optional через flags.3
  - `new_noncontact_peers_require_premium`: `flags.4?true` - optional через flags.4
  - `display_gifts_button`: `flags.7?true` - optional через flags.7
  - `noncontact_peers_paid_stars`: `flags.5?long` - optional через flags.5
  - `disallowed_gifts`: `flags.6?DisallowedGiftsSettings` - optional через flags.6

## `GroupCall`

- Официальный тип: https://core.telegram.org/type/GroupCall
- Количество constructors: **2**

### `groupCall`

- ID: `1429932961` / `0x553b0ba1`
- Сигнатура: `groupCall(flags:#, join_muted:flags.1?true, can_change_join_muted:flags.2?true, join_date_asc:flags.6?true, schedule_start_subscribed:flags.8?true, can_start_video:flags.9?true, record_video_active:flags.11?true, rtmp_stream:flags.12?true, listeners_hidden:flags.13?true, conference:flags.14?true, creator:flags.15?true, id:long, access_hash:long, participants_count:int, title:flags.3?string, stream_dc_id:flags.4?int, record_start_date:flags.5?int, schedule_date:flags.7?int, unmuted_video_count:flags.10?int, unmuted_video_limit:int, version:int, invite_link:flags.16?string) => GroupCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/groupCall
- Поля:
  - `flags`: `#` - служебное поле flags
  - `join_muted`: `flags.1?true` - optional через flags.1
  - `can_change_join_muted`: `flags.2?true` - optional через flags.2
  - `join_date_asc`: `flags.6?true` - optional через flags.6
  - `schedule_start_subscribed`: `flags.8?true` - optional через flags.8
  - `can_start_video`: `flags.9?true` - optional через flags.9
  - `record_video_active`: `flags.11?true` - optional через flags.11
  - `rtmp_stream`: `flags.12?true` - optional через flags.12
  - `listeners_hidden`: `flags.13?true` - optional через flags.13
  - `conference`: `flags.14?true` - optional через flags.14
  - `creator`: `flags.15?true` - optional через flags.15
  - `id`: `long`
  - `access_hash`: `long`
  - `participants_count`: `int`
  - `title`: `flags.3?string` - optional через flags.3
  - `stream_dc_id`: `flags.4?int` - optional через flags.4
  - `record_start_date`: `flags.5?int` - optional через flags.5
  - `schedule_date`: `flags.7?int` - optional через flags.7
  - `unmuted_video_count`: `flags.10?int` - optional через flags.10
  - `unmuted_video_limit`: `int`
  - `version`: `int`
  - `invite_link`: `flags.16?string` - optional через flags.16

### `groupCallDiscarded`

- ID: `2004925620` / `0x7780bcb4`
- Сигнатура: `groupCallDiscarded(id:long, access_hash:long, duration:int) => GroupCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/groupCallDiscarded
- Поля:
  - `id`: `long`
  - `access_hash`: `long`
  - `duration`: `int`

## `GroupCallParticipant`

- Официальный тип: https://core.telegram.org/type/GroupCallParticipant
- Количество constructors: **1**

### `groupCallParticipant`

- ID: `-341428482` / `0xeba636fe`
- Сигнатура: `groupCallParticipant(flags:#, muted:flags.0?true, left:flags.1?true, can_self_unmute:flags.2?true, just_joined:flags.4?true, versioned:flags.5?true, min:flags.8?true, muted_by_you:flags.9?true, volume_by_admin:flags.10?true, self:flags.12?true, video_joined:flags.15?true, peer:Peer, date:int, active_date:flags.3?int, source:int, volume:flags.7?int, about:flags.11?string, raise_hand_rating:flags.13?long, video:flags.6?GroupCallParticipantVideo, presentation:flags.14?GroupCallParticipantVideo) => GroupCallParticipant`
- Официальная страница конструктора: https://core.telegram.org/constructor/groupCallParticipant
- Поля:
  - `flags`: `#` - служебное поле flags
  - `muted`: `flags.0?true` - optional через flags.0
  - `left`: `flags.1?true` - optional через flags.1
  - `can_self_unmute`: `flags.2?true` - optional через flags.2
  - `just_joined`: `flags.4?true` - optional через flags.4
  - `versioned`: `flags.5?true` - optional через flags.5
  - `min`: `flags.8?true` - optional через flags.8
  - `muted_by_you`: `flags.9?true` - optional через flags.9
  - `volume_by_admin`: `flags.10?true` - optional через flags.10
  - `self`: `flags.12?true` - optional через flags.12
  - `video_joined`: `flags.15?true` - optional через flags.15
  - `peer`: `Peer`
  - `date`: `int`
  - `active_date`: `flags.3?int` - optional через flags.3
  - `source`: `int`
  - `volume`: `flags.7?int` - optional через flags.7
  - `about`: `flags.11?string` - optional через flags.11
  - `raise_hand_rating`: `flags.13?long` - optional через flags.13
  - `video`: `flags.6?GroupCallParticipantVideo` - optional через flags.6
  - `presentation`: `flags.14?GroupCallParticipantVideo` - optional через flags.14

## `GroupCallParticipantVideo`

- Официальный тип: https://core.telegram.org/type/GroupCallParticipantVideo
- Количество constructors: **1**

### `groupCallParticipantVideo`

- ID: `1735736008` / `0x67753ac8`
- Сигнатура: `groupCallParticipantVideo(flags:#, paused:flags.0?true, endpoint:string, source_groups:Vector, audio_source:flags.1?int) => GroupCallParticipantVideo`
- Официальная страница конструктора: https://core.telegram.org/constructor/groupCallParticipantVideo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `paused`: `flags.0?true` - optional через flags.0
  - `endpoint`: `string`
  - `source_groups`: `Vector`
  - `audio_source`: `flags.1?int` - optional через flags.1

## `GroupCallParticipantVideoSourceGroup`

- Официальный тип: https://core.telegram.org/type/GroupCallParticipantVideoSourceGroup
- Количество constructors: **1**

### `groupCallParticipantVideoSourceGroup`

- ID: `-592373577` / `0xdcb118b7`
- Сигнатура: `groupCallParticipantVideoSourceGroup(semantics:string, sources:Vector) => GroupCallParticipantVideoSourceGroup`
- Официальная страница конструктора: https://core.telegram.org/constructor/groupCallParticipantVideoSourceGroup
- Поля:
  - `semantics`: `string`
  - `sources`: `Vector`

## `GroupCallStreamChannel`

- Официальный тип: https://core.telegram.org/type/GroupCallStreamChannel
- Количество constructors: **1**

### `groupCallStreamChannel`

- ID: `-2132064081` / `0x80eb48af`
- Сигнатура: `groupCallStreamChannel(channel:int, scale:int, last_timestamp_ms:long) => GroupCallStreamChannel`
- Официальная страница конструктора: https://core.telegram.org/constructor/groupCallStreamChannel
- Поля:
  - `channel`: `int`
  - `scale`: `int`
  - `last_timestamp_ms`: `long`

## `HighScore`

- Официальный тип: https://core.telegram.org/type/HighScore
- Количество constructors: **1**

### `highScore`

- ID: `1940093419` / `0x73a379eb`
- Сигнатура: `highScore(pos:int, user_id:long, score:int) => HighScore`
- Официальная страница конструктора: https://core.telegram.org/constructor/highScore
- Поля:
  - `pos`: `int`
  - `user_id`: `long`
  - `score`: `int`

## `ImportedContact`

- Официальный тип: https://core.telegram.org/type/ImportedContact
- Количество constructors: **1**

### `importedContact`

- ID: `-1052885936` / `0xc13e3c50`
- Сигнатура: `importedContact(user_id:long, client_id:long) => ImportedContact`
- Официальная страница конструктора: https://core.telegram.org/constructor/importedContact
- Поля:
  - `user_id`: `long`
  - `client_id`: `long`

## `InlineBotSwitchPM`

- Официальный тип: https://core.telegram.org/type/InlineBotSwitchPM
- Количество constructors: **1**

### `inlineBotSwitchPM`

- ID: `1008755359` / `0x3c20629f`
- Сигнатура: `inlineBotSwitchPM(text:string, start_param:string) => InlineBotSwitchPM`
- Официальная страница конструктора: https://core.telegram.org/constructor/inlineBotSwitchPM
- Поля:
  - `text`: `string`
  - `start_param`: `string`

## `InlineBotWebView`

- Официальный тип: https://core.telegram.org/type/InlineBotWebView
- Количество constructors: **1**

### `inlineBotWebView`

- ID: `-1250781739` / `0xb57295d5`
- Сигнатура: `inlineBotWebView(text:string, url:string) => InlineBotWebView`
- Официальная страница конструктора: https://core.telegram.org/constructor/inlineBotWebView
- Поля:
  - `text`: `string`
  - `url`: `string`

## `InlineQueryPeerType`

- Официальный тип: https://core.telegram.org/type/InlineQueryPeerType
- Количество constructors: **6**

### `inlineQueryPeerTypeBotPM`

- ID: `238759180` / `0x0e3b2d0c`
- Сигнатура: `inlineQueryPeerTypeBotPM() => InlineQueryPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/inlineQueryPeerTypeBotPM
- Поля:
  - Нет полей.

### `inlineQueryPeerTypeBroadcast`

- ID: `1664413338` / `0x6334ee9a`
- Сигнатура: `inlineQueryPeerTypeBroadcast() => InlineQueryPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/inlineQueryPeerTypeBroadcast
- Поля:
  - Нет полей.

### `inlineQueryPeerTypeChat`

- ID: `-681130742` / `0xd766c50a`
- Сигнатура: `inlineQueryPeerTypeChat() => InlineQueryPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/inlineQueryPeerTypeChat
- Поля:
  - Нет полей.

### `inlineQueryPeerTypeMegagroup`

- ID: `1589952067` / `0x5ec4be43`
- Сигнатура: `inlineQueryPeerTypeMegagroup() => InlineQueryPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/inlineQueryPeerTypeMegagroup
- Поля:
  - Нет полей.

### `inlineQueryPeerTypePM`

- ID: `-2093215828` / `0x833c0fac`
- Сигнатура: `inlineQueryPeerTypePM() => InlineQueryPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/inlineQueryPeerTypePM
- Поля:
  - Нет полей.

### `inlineQueryPeerTypeSameBotPM`

- ID: `813821341` / `0x3081ed9d`
- Сигнатура: `inlineQueryPeerTypeSameBotPM() => InlineQueryPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/inlineQueryPeerTypeSameBotPM
- Поля:
  - Нет полей.

## `InputAppEvent`

- Официальный тип: https://core.telegram.org/type/InputAppEvent
- Количество constructors: **1**

### `inputAppEvent`

- ID: `488313413` / `0x1d1b1245`
- Сигнатура: `inputAppEvent(time:double, type:string, peer:long, data:JSONValue) => InputAppEvent`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputAppEvent
- Поля:
  - `time`: `double`
  - `type`: `string`
  - `peer`: `long`
  - `data`: `JSONValue`

## `InputBotApp`

- Официальный тип: https://core.telegram.org/type/InputBotApp
- Количество constructors: **2**

### `inputBotAppID`

- ID: `-1457472134` / `0xa920bd7a`
- Сигнатура: `inputBotAppID(id:long, access_hash:long) => InputBotApp`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotAppID
- Поля:
  - `id`: `long`
  - `access_hash`: `long`

### `inputBotAppShortName`

- ID: `-1869872121` / `0x908c0407`
- Сигнатура: `inputBotAppShortName(bot_id:InputUser, short_name:string) => InputBotApp`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotAppShortName
- Поля:
  - `bot_id`: `InputUser`
  - `short_name`: `string`

## `InputBotInlineMessage`

- Официальный тип: https://core.telegram.org/type/InputBotInlineMessage
- Количество constructors: **8**

### `inputBotInlineMessageGame`

- ID: `1262639204` / `0x4b425864`
- Сигнатура: `inputBotInlineMessageGame(flags:#, reply_markup:flags.2?ReplyMarkup) => InputBotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineMessageGame
- Поля:
  - `flags`: `#` - служебное поле flags
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `inputBotInlineMessageMediaAuto`

- ID: `864077702` / `0x3380c786`
- Сигнатура: `inputBotInlineMessageMediaAuto(flags:#, invert_media:flags.3?true, message:string, entities:flags.1?Vector, reply_markup:flags.2?ReplyMarkup) => InputBotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineMessageMediaAuto
- Поля:
  - `flags`: `#` - служебное поле flags
  - `invert_media`: `flags.3?true` - optional через flags.3
  - `message`: `string`
  - `entities`: `flags.1?Vector` - optional через flags.1
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `inputBotInlineMessageMediaContact`

- ID: `-1494368259` / `0xa6edbffd`
- Сигнатура: `inputBotInlineMessageMediaContact(flags:#, phone_number:string, first_name:string, last_name:string, vcard:string, reply_markup:flags.2?ReplyMarkup) => InputBotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineMessageMediaContact
- Поля:
  - `flags`: `#` - служебное поле flags
  - `phone_number`: `string`
  - `first_name`: `string`
  - `last_name`: `string`
  - `vcard`: `string`
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `inputBotInlineMessageMediaGeo`

- ID: `-1768777083` / `0x96929a85`
- Сигнатура: `inputBotInlineMessageMediaGeo(flags:#, geo_point:InputGeoPoint, heading:flags.0?int, period:flags.1?int, proximity_notification_radius:flags.3?int, reply_markup:flags.2?ReplyMarkup) => InputBotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineMessageMediaGeo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `geo_point`: `InputGeoPoint`
  - `heading`: `flags.0?int` - optional через flags.0
  - `period`: `flags.1?int` - optional через flags.1
  - `proximity_notification_radius`: `flags.3?int` - optional через flags.3
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `inputBotInlineMessageMediaInvoice`

- ID: `-672693723` / `0xd7e78225`
- Сигнатура: `inputBotInlineMessageMediaInvoice(flags:#, title:string, description:string, photo:flags.0?InputWebDocument, invoice:Invoice, payload:bytes, provider:string, provider_data:DataJSON, reply_markup:flags.2?ReplyMarkup) => InputBotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineMessageMediaInvoice
- Поля:
  - `flags`: `#` - служебное поле flags
  - `title`: `string`
  - `description`: `string`
  - `photo`: `flags.0?InputWebDocument` - optional через flags.0
  - `invoice`: `Invoice`
  - `payload`: `bytes`
  - `provider`: `string`
  - `provider_data`: `DataJSON`
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `inputBotInlineMessageMediaVenue`

- ID: `1098628881` / `0x417bbf11`
- Сигнатура: `inputBotInlineMessageMediaVenue(flags:#, geo_point:InputGeoPoint, title:string, address:string, provider:string, venue_id:string, venue_type:string, reply_markup:flags.2?ReplyMarkup) => InputBotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineMessageMediaVenue
- Поля:
  - `flags`: `#` - служебное поле flags
  - `geo_point`: `InputGeoPoint`
  - `title`: `string`
  - `address`: `string`
  - `provider`: `string`
  - `venue_id`: `string`
  - `venue_type`: `string`
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `inputBotInlineMessageMediaWebPage`

- ID: `-1109605104` / `0xbddcc510`
- Сигнатура: `inputBotInlineMessageMediaWebPage(flags:#, invert_media:flags.3?true, force_large_media:flags.4?true, force_small_media:flags.5?true, optional:flags.6?true, message:string, entities:flags.1?Vector, url:string, reply_markup:flags.2?ReplyMarkup) => InputBotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineMessageMediaWebPage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `invert_media`: `flags.3?true` - optional через flags.3
  - `force_large_media`: `flags.4?true` - optional через flags.4
  - `force_small_media`: `flags.5?true` - optional через flags.5
  - `optional`: `flags.6?true` - optional через flags.6
  - `message`: `string`
  - `entities`: `flags.1?Vector` - optional через flags.1
  - `url`: `string`
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

### `inputBotInlineMessageText`

- ID: `1036876423` / `0x3dcd7a87`
- Сигнатура: `inputBotInlineMessageText(flags:#, no_webpage:flags.0?true, invert_media:flags.3?true, message:string, entities:flags.1?Vector, reply_markup:flags.2?ReplyMarkup) => InputBotInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineMessageText
- Поля:
  - `flags`: `#` - служебное поле flags
  - `no_webpage`: `flags.0?true` - optional через flags.0
  - `invert_media`: `flags.3?true` - optional через flags.3
  - `message`: `string`
  - `entities`: `flags.1?Vector` - optional через flags.1
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2

## `InputBotInlineMessageID`

- Официальный тип: https://core.telegram.org/type/InputBotInlineMessageID
- Количество constructors: **2**

### `inputBotInlineMessageID`

- ID: `-1995686519` / `0x890c3d89`
- Сигнатура: `inputBotInlineMessageID(dc_id:int, id:long, access_hash:long) => InputBotInlineMessageID`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineMessageID
- Поля:
  - `dc_id`: `int`
  - `id`: `long`
  - `access_hash`: `long`

### `inputBotInlineMessageID64`

- ID: `-1227287081` / `0xb6d915d7`
- Сигнатура: `inputBotInlineMessageID64(dc_id:int, owner_id:long, id:int, access_hash:long) => InputBotInlineMessageID`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineMessageID64
- Поля:
  - `dc_id`: `int`
  - `owner_id`: `long`
  - `id`: `int`
  - `access_hash`: `long`

## `InputBotInlineResult`

- Официальный тип: https://core.telegram.org/type/InputBotInlineResult
- Количество constructors: **4**

### `inputBotInlineResult`

- ID: `-2000710887` / `0x88bf9319`
- Сигнатура: `inputBotInlineResult(flags:#, id:string, type:string, title:flags.1?string, description:flags.2?string, url:flags.3?string, thumb:flags.4?InputWebDocument, content:flags.5?InputWebDocument, send_message:InputBotInlineMessage) => InputBotInlineResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineResult
- Поля:
  - `flags`: `#` - служебное поле flags
  - `id`: `string`
  - `type`: `string`
  - `title`: `flags.1?string` - optional через flags.1
  - `description`: `flags.2?string` - optional через flags.2
  - `url`: `flags.3?string` - optional через flags.3
  - `thumb`: `flags.4?InputWebDocument` - optional через flags.4
  - `content`: `flags.5?InputWebDocument` - optional через flags.5
  - `send_message`: `InputBotInlineMessage`

### `inputBotInlineResultDocument`

- ID: `-459324` / `0xfff8fdc4`
- Сигнатура: `inputBotInlineResultDocument(flags:#, id:string, type:string, title:flags.1?string, description:flags.2?string, document:InputDocument, send_message:InputBotInlineMessage) => InputBotInlineResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineResultDocument
- Поля:
  - `flags`: `#` - служебное поле flags
  - `id`: `string`
  - `type`: `string`
  - `title`: `flags.1?string` - optional через flags.1
  - `description`: `flags.2?string` - optional через flags.2
  - `document`: `InputDocument`
  - `send_message`: `InputBotInlineMessage`

### `inputBotInlineResultGame`

- ID: `1336154098` / `0x4fa417f2`
- Сигнатура: `inputBotInlineResultGame(id:string, short_name:string, send_message:InputBotInlineMessage) => InputBotInlineResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineResultGame
- Поля:
  - `id`: `string`
  - `short_name`: `string`
  - `send_message`: `InputBotInlineMessage`

### `inputBotInlineResultPhoto`

- ID: `-1462213465` / `0xa8d864a7`
- Сигнатура: `inputBotInlineResultPhoto(id:string, type:string, photo:InputPhoto, send_message:InputBotInlineMessage) => InputBotInlineResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBotInlineResultPhoto
- Поля:
  - `id`: `string`
  - `type`: `string`
  - `photo`: `InputPhoto`
  - `send_message`: `InputBotInlineMessage`

## `InputBusinessAwayMessage`

- Официальный тип: https://core.telegram.org/type/InputBusinessAwayMessage
- Количество constructors: **1**

### `inputBusinessAwayMessage`

- ID: `-2094959136` / `0x832175e0`
- Сигнатура: `inputBusinessAwayMessage(flags:#, offline_only:flags.0?true, shortcut_id:int, schedule:BusinessAwayMessageSchedule, recipients:InputBusinessRecipients) => InputBusinessAwayMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBusinessAwayMessage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `offline_only`: `flags.0?true` - optional через flags.0
  - `shortcut_id`: `int`
  - `schedule`: `BusinessAwayMessageSchedule`
  - `recipients`: `InputBusinessRecipients`

## `InputBusinessBotRecipients`

- Официальный тип: https://core.telegram.org/type/InputBusinessBotRecipients
- Количество constructors: **1**

### `inputBusinessBotRecipients`

- ID: `-991587810` / `0xc4e5921e`
- Сигнатура: `inputBusinessBotRecipients(flags:#, existing_chats:flags.0?true, new_chats:flags.1?true, contacts:flags.2?true, non_contacts:flags.3?true, exclude_selected:flags.5?true, users:flags.4?Vector, exclude_users:flags.6?Vector) => InputBusinessBotRecipients`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBusinessBotRecipients
- Поля:
  - `flags`: `#` - служебное поле flags
  - `existing_chats`: `flags.0?true` - optional через flags.0
  - `new_chats`: `flags.1?true` - optional через flags.1
  - `contacts`: `flags.2?true` - optional через flags.2
  - `non_contacts`: `flags.3?true` - optional через flags.3
  - `exclude_selected`: `flags.5?true` - optional через flags.5
  - `users`: `flags.4?Vector` - optional через flags.4
  - `exclude_users`: `flags.6?Vector` - optional через flags.6

## `InputBusinessChatLink`

- Официальный тип: https://core.telegram.org/type/InputBusinessChatLink
- Количество constructors: **1**

### `inputBusinessChatLink`

- ID: `292003751` / `0x11679fa7`
- Сигнатура: `inputBusinessChatLink(flags:#, message:string, entities:flags.0?Vector, title:flags.1?string) => InputBusinessChatLink`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBusinessChatLink
- Поля:
  - `flags`: `#` - служебное поле flags
  - `message`: `string`
  - `entities`: `flags.0?Vector` - optional через flags.0
  - `title`: `flags.1?string` - optional через flags.1

## `InputBusinessGreetingMessage`

- Официальный тип: https://core.telegram.org/type/InputBusinessGreetingMessage
- Количество constructors: **1**

### `inputBusinessGreetingMessage`

- ID: `26528571` / `0x0194cb3b`
- Сигнатура: `inputBusinessGreetingMessage(shortcut_id:int, recipients:InputBusinessRecipients, no_activity_days:int) => InputBusinessGreetingMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBusinessGreetingMessage
- Поля:
  - `shortcut_id`: `int`
  - `recipients`: `InputBusinessRecipients`
  - `no_activity_days`: `int`

## `InputBusinessIntro`

- Официальный тип: https://core.telegram.org/type/InputBusinessIntro
- Количество constructors: **1**

### `inputBusinessIntro`

- ID: `163867085` / `0x09c469cd`
- Сигнатура: `inputBusinessIntro(flags:#, title:string, description:string, sticker:flags.0?InputDocument) => InputBusinessIntro`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBusinessIntro
- Поля:
  - `flags`: `#` - служебное поле flags
  - `title`: `string`
  - `description`: `string`
  - `sticker`: `flags.0?InputDocument` - optional через flags.0

## `InputBusinessRecipients`

- Официальный тип: https://core.telegram.org/type/InputBusinessRecipients
- Количество constructors: **1**

### `inputBusinessRecipients`

- ID: `1871393450` / `0x6f8b32aa`
- Сигнатура: `inputBusinessRecipients(flags:#, existing_chats:flags.0?true, new_chats:flags.1?true, contacts:flags.2?true, non_contacts:flags.3?true, exclude_selected:flags.5?true, users:flags.4?Vector) => InputBusinessRecipients`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputBusinessRecipients
- Поля:
  - `flags`: `#` - служебное поле flags
  - `existing_chats`: `flags.0?true` - optional через flags.0
  - `new_chats`: `flags.1?true` - optional через flags.1
  - `contacts`: `flags.2?true` - optional через flags.2
  - `non_contacts`: `flags.3?true` - optional через flags.3
  - `exclude_selected`: `flags.5?true` - optional через flags.5
  - `users`: `flags.4?Vector` - optional через flags.4

## `InputChannel`

- Официальный тип: https://core.telegram.org/type/InputChannel
- Количество constructors: **3**

### `inputChannel`

- ID: `-212145112` / `0xf35aec28`
- Сигнатура: `inputChannel(channel_id:long, access_hash:long) => InputChannel`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputChannel
- Поля:
  - `channel_id`: `long`
  - `access_hash`: `long`

### `inputChannelEmpty`

- ID: `-292807034` / `0xee8c1e86`
- Сигнатура: `inputChannelEmpty() => InputChannel`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputChannelEmpty
- Поля:
  - Нет полей.

### `inputChannelFromMessage`

- ID: `1536380829` / `0x5b934f9d`
- Сигнатура: `inputChannelFromMessage(peer:InputPeer, msg_id:int, channel_id:long) => InputChannel`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputChannelFromMessage
- Поля:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `channel_id`: `long`

## `InputChatPhoto`

- Официальный тип: https://core.telegram.org/type/InputChatPhoto
- Количество constructors: **3**

### `inputChatPhoto`

- ID: `-1991004873` / `0x8953ad37`
- Сигнатура: `inputChatPhoto(id:InputPhoto) => InputChatPhoto`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputChatPhoto
- Поля:
  - `id`: `InputPhoto`

### `inputChatPhotoEmpty`

- ID: `480546647` / `0x1ca48f57`
- Сигнатура: `inputChatPhotoEmpty() => InputChatPhoto`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputChatPhotoEmpty
- Поля:
  - Нет полей.

### `inputChatUploadedPhoto`

- ID: `-1110593856` / `0xbdcdaec0`
- Сигнатура: `inputChatUploadedPhoto(flags:#, file:flags.0?InputFile, video:flags.1?InputFile, video_start_ts:flags.2?double, video_emoji_markup:flags.3?VideoSize) => InputChatPhoto`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputChatUploadedPhoto
- Поля:
  - `flags`: `#` - служебное поле flags
  - `file`: `flags.0?InputFile` - optional через flags.0
  - `video`: `flags.1?InputFile` - optional через flags.1
  - `video_start_ts`: `flags.2?double` - optional через flags.2
  - `video_emoji_markup`: `flags.3?VideoSize` - optional через flags.3

## `InputChatTheme`

- Официальный тип: https://core.telegram.org/type/InputChatTheme
- Количество constructors: **3**

### `inputChatTheme`

- ID: `-918689444` / `0xc93de95c`
- Сигнатура: `inputChatTheme(emoticon:string) => InputChatTheme`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputChatTheme
- Поля:
  - `emoticon`: `string`

### `inputChatThemeEmpty`

- ID: `-2094627709` / `0x83268483`
- Сигнатура: `inputChatThemeEmpty() => InputChatTheme`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputChatThemeEmpty
- Поля:
  - Нет полей.

### `inputChatThemeUniqueGift`

- ID: `-2014978076` / `0x87e5dfe4`
- Сигнатура: `inputChatThemeUniqueGift(slug:string) => InputChatTheme`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputChatThemeUniqueGift
- Поля:
  - `slug`: `string`

## `InputChatlist`

- Официальный тип: https://core.telegram.org/type/InputChatlist
- Количество constructors: **1**

### `inputChatlistDialogFilter`

- ID: `-203367885` / `0xf3e0da33`
- Сигнатура: `inputChatlistDialogFilter(filter_id:int) => InputChatlist`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputChatlistDialogFilter
- Поля:
  - `filter_id`: `int`

## `InputCheckPasswordSRP`

- Официальный тип: https://core.telegram.org/type/InputCheckPasswordSRP
- Количество constructors: **2**

### `inputCheckPasswordEmpty`

- ID: `-1736378792` / `0x9880f658`
- Сигнатура: `inputCheckPasswordEmpty() => InputCheckPasswordSRP`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputCheckPasswordEmpty
- Поля:
  - Нет полей.

### `inputCheckPasswordSRP`

- ID: `-763367294` / `0xd27ff082`
- Сигнатура: `inputCheckPasswordSRP(srp_id:long, A:bytes, M1:bytes) => InputCheckPasswordSRP`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputCheckPasswordSRP
- Поля:
  - `srp_id`: `long`
  - `A`: `bytes`
  - `M1`: `bytes`

## `InputClientProxy`

- Официальный тип: https://core.telegram.org/type/InputClientProxy
- Количество constructors: **1**

### `inputClientProxy`

- ID: `1968737087` / `0x75588b3f`
- Сигнатура: `inputClientProxy(address:string, port:int) => InputClientProxy`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputClientProxy
- Поля:
  - `address`: `string`
  - `port`: `int`

## `InputCollectible`

- Официальный тип: https://core.telegram.org/type/InputCollectible
- Количество constructors: **2**

### `inputCollectiblePhone`

- ID: `-1562241884` / `0xa2e214a4`
- Сигнатура: `inputCollectiblePhone(phone:string) => InputCollectible`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputCollectiblePhone
- Поля:
  - `phone`: `string`

### `inputCollectibleUsername`

- ID: `-476815191` / `0xe39460a9`
- Сигнатура: `inputCollectibleUsername(username:string) => InputCollectible`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputCollectibleUsername
- Поля:
  - `username`: `string`

## `InputContact`

- Официальный тип: https://core.telegram.org/type/InputContact
- Количество constructors: **1**

### `inputPhoneContact`

- ID: `-208488460` / `0xf392b7f4`
- Сигнатура: `inputPhoneContact(client_id:long, phone:string, first_name:string, last_name:string) => InputContact`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPhoneContact
- Поля:
  - `client_id`: `long`
  - `phone`: `string`
  - `first_name`: `string`
  - `last_name`: `string`

## `InputDialogPeer`

- Официальный тип: https://core.telegram.org/type/InputDialogPeer
- Количество constructors: **2**

### `inputDialogPeer`

- ID: `-55902537` / `0xfcaafeb7`
- Сигнатура: `inputDialogPeer(peer:InputPeer) => InputDialogPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputDialogPeer
- Поля:
  - `peer`: `InputPeer`

### `inputDialogPeerFolder`

- ID: `1684014375` / `0x64600527`
- Сигнатура: `inputDialogPeerFolder(folder_id:int) => InputDialogPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputDialogPeerFolder
- Поля:
  - `folder_id`: `int`

## `InputDocument`

- Официальный тип: https://core.telegram.org/type/InputDocument
- Количество constructors: **2**

### `inputDocument`

- ID: `448771445` / `0x1abfb575`
- Сигнатура: `inputDocument(id:long, access_hash:long, file_reference:bytes) => InputDocument`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputDocument
- Поля:
  - `id`: `long`
  - `access_hash`: `long`
  - `file_reference`: `bytes`

### `inputDocumentEmpty`

- ID: `1928391342` / `0x72f0eaae`
- Сигнатура: `inputDocumentEmpty() => InputDocument`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputDocumentEmpty
- Поля:
  - Нет полей.

## `InputEncryptedChat`

- Официальный тип: https://core.telegram.org/type/InputEncryptedChat
- Количество constructors: **1**

### `inputEncryptedChat`

- ID: `-247351839` / `0xf141b5e1`
- Сигнатура: `inputEncryptedChat(chat_id:int, access_hash:long) => InputEncryptedChat`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputEncryptedChat
- Поля:
  - `chat_id`: `int`
  - `access_hash`: `long`

## `InputEncryptedFile`

- Официальный тип: https://core.telegram.org/type/InputEncryptedFile
- Количество constructors: **4**

### `inputEncryptedFile`

- ID: `1511503333` / `0x5a17b5e5`
- Сигнатура: `inputEncryptedFile(id:long, access_hash:long) => InputEncryptedFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputEncryptedFile
- Поля:
  - `id`: `long`
  - `access_hash`: `long`

### `inputEncryptedFileBigUploaded`

- ID: `767652808` / `0x2dc173c8`
- Сигнатура: `inputEncryptedFileBigUploaded(id:long, parts:int, key_fingerprint:int) => InputEncryptedFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputEncryptedFileBigUploaded
- Поля:
  - `id`: `long`
  - `parts`: `int`
  - `key_fingerprint`: `int`

### `inputEncryptedFileEmpty`

- ID: `406307684` / `0x1837c364`
- Сигнатура: `inputEncryptedFileEmpty() => InputEncryptedFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputEncryptedFileEmpty
- Поля:
  - Нет полей.

### `inputEncryptedFileUploaded`

- ID: `1690108678` / `0x64bd0306`
- Сигнатура: `inputEncryptedFileUploaded(id:long, parts:int, md5_checksum:string, key_fingerprint:int) => InputEncryptedFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputEncryptedFileUploaded
- Поля:
  - `id`: `long`
  - `parts`: `int`
  - `md5_checksum`: `string`
  - `key_fingerprint`: `int`

## `InputFile`

- Официальный тип: https://core.telegram.org/type/InputFile
- Количество constructors: **3**

### `inputFile`

- ID: `-181407105` / `0xf52ff27f`
- Сигнатура: `inputFile(id:long, parts:int, name:string, md5_checksum:string) => InputFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputFile
- Поля:
  - `id`: `long`
  - `parts`: `int`
  - `name`: `string`
  - `md5_checksum`: `string`

### `inputFileBig`

- ID: `-95482955` / `0xfa4f0bb5`
- Сигнатура: `inputFileBig(id:long, parts:int, name:string) => InputFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputFileBig
- Поля:
  - `id`: `long`
  - `parts`: `int`
  - `name`: `string`

### `inputFileStoryDocument`

- ID: `1658620744` / `0x62dc8b48`
- Сигнатура: `inputFileStoryDocument(id:InputDocument) => InputFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputFileStoryDocument
- Поля:
  - `id`: `InputDocument`

## `InputFileLocation`

- Официальный тип: https://core.telegram.org/type/InputFileLocation
- Количество constructors: **10**

### `inputDocumentFileLocation`

- ID: `-1160743548` / `0xbad07584`
- Сигнатура: `inputDocumentFileLocation(id:long, access_hash:long, file_reference:bytes, thumb_size:string) => InputFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputDocumentFileLocation
- Поля:
  - `id`: `long`
  - `access_hash`: `long`
  - `file_reference`: `bytes`
  - `thumb_size`: `string`

### `inputEncryptedFileLocation`

- ID: `-182231723` / `0xf5235d55`
- Сигнатура: `inputEncryptedFileLocation(id:long, access_hash:long) => InputFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputEncryptedFileLocation
- Поля:
  - `id`: `long`
  - `access_hash`: `long`

### `inputFileLocation`

- ID: `-539317279` / `0xdfdaabe1`
- Сигнатура: `inputFileLocation(volume_id:long, local_id:int, secret:long, file_reference:bytes) => InputFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputFileLocation
- Поля:
  - `volume_id`: `long`
  - `local_id`: `int`
  - `secret`: `long`
  - `file_reference`: `bytes`

### `inputGroupCallStream`

- ID: `93890858` / `0x0598a92a`
- Сигнатура: `inputGroupCallStream(flags:#, call:InputGroupCall, time_ms:long, scale:int, video_channel:flags.0?int, video_quality:flags.0?int) => InputFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputGroupCallStream
- Поля:
  - `flags`: `#` - служебное поле flags
  - `call`: `InputGroupCall`
  - `time_ms`: `long`
  - `scale`: `int`
  - `video_channel`: `flags.0?int` - optional через flags.0
  - `video_quality`: `flags.0?int` - optional через flags.0

### `inputPeerPhotoFileLocation`

- ID: `925204121` / `0x37257e99`
- Сигнатура: `inputPeerPhotoFileLocation(flags:#, big:flags.0?true, peer:InputPeer, photo_id:long) => InputFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPeerPhotoFileLocation
- Поля:
  - `flags`: `#` - служебное поле flags
  - `big`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`
  - `photo_id`: `long`

### `inputPhotoFileLocation`

- ID: `1075322878` / `0x40181ffe`
- Сигнатура: `inputPhotoFileLocation(id:long, access_hash:long, file_reference:bytes, thumb_size:string) => InputFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPhotoFileLocation
- Поля:
  - `id`: `long`
  - `access_hash`: `long`
  - `file_reference`: `bytes`
  - `thumb_size`: `string`

### `inputPhotoLegacyFileLocation`

- ID: `-667654413` / `0xd83466f3`
- Сигнатура: `inputPhotoLegacyFileLocation(id:long, access_hash:long, file_reference:bytes, volume_id:long, local_id:int, secret:long) => InputFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPhotoLegacyFileLocation
- Поля:
  - `id`: `long`
  - `access_hash`: `long`
  - `file_reference`: `bytes`
  - `volume_id`: `long`
  - `local_id`: `int`
  - `secret`: `long`

### `inputSecureFileLocation`

- ID: `-876089816` / `0xcbc7ee28`
- Сигнатура: `inputSecureFileLocation(id:long, access_hash:long) => InputFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputSecureFileLocation
- Поля:
  - `id`: `long`
  - `access_hash`: `long`

### `inputStickerSetThumb`

- ID: `-1652231205` / `0x9d84f3db`
- Сигнатура: `inputStickerSetThumb(stickerset:InputStickerSet, thumb_version:int) => InputFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetThumb
- Поля:
  - `stickerset`: `InputStickerSet`
  - `thumb_version`: `int`

### `inputTakeoutFileLocation`

- ID: `700340377` / `0x29be5899`
- Сигнатура: `inputTakeoutFileLocation() => InputFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputTakeoutFileLocation
- Поля:
  - Нет полей.

## `InputFolderPeer`

- Официальный тип: https://core.telegram.org/type/InputFolderPeer
- Количество constructors: **1**

### `inputFolderPeer`

- ID: `-70073706` / `0xfbd2c296`
- Сигнатура: `inputFolderPeer(peer:InputPeer, folder_id:int) => InputFolderPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputFolderPeer
- Поля:
  - `peer`: `InputPeer`
  - `folder_id`: `int`

## `InputGame`

- Официальный тип: https://core.telegram.org/type/InputGame
- Количество constructors: **2**

### `inputGameID`

- ID: `53231223` / `0x032c3e77`
- Сигнатура: `inputGameID(id:long, access_hash:long) => InputGame`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputGameID
- Поля:
  - `id`: `long`
  - `access_hash`: `long`

### `inputGameShortName`

- ID: `-1020139510` / `0xc331e80a`
- Сигнатура: `inputGameShortName(bot_id:InputUser, short_name:string) => InputGame`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputGameShortName
- Поля:
  - `bot_id`: `InputUser`
  - `short_name`: `string`

## `InputGeoPoint`

- Официальный тип: https://core.telegram.org/type/InputGeoPoint
- Количество constructors: **2**

### `inputGeoPoint`

- ID: `1210199983` / `0x48222faf`
- Сигнатура: `inputGeoPoint(flags:#, lat:double, long:double, accuracy_radius:flags.0?int) => InputGeoPoint`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputGeoPoint
- Поля:
  - `flags`: `#` - служебное поле flags
  - `lat`: `double`
  - `long`: `double`
  - `accuracy_radius`: `flags.0?int` - optional через flags.0

### `inputGeoPointEmpty`

- ID: `-457104426` / `0xe4c123d6`
- Сигнатура: `inputGeoPointEmpty() => InputGeoPoint`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputGeoPointEmpty
- Поля:
  - Нет полей.

## `InputGroupCall`

- Официальный тип: https://core.telegram.org/type/InputGroupCall
- Количество constructors: **3**

### `inputGroupCall`

- ID: `-659913713` / `0xd8aa840f`
- Сигнатура: `inputGroupCall(id:long, access_hash:long) => InputGroupCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputGroupCall
- Поля:
  - `id`: `long`
  - `access_hash`: `long`

### `inputGroupCallInviteMessage`

- ID: `-1945083841` / `0x8c10603f`
- Сигнатура: `inputGroupCallInviteMessage(msg_id:int) => InputGroupCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputGroupCallInviteMessage
- Поля:
  - `msg_id`: `int`

### `inputGroupCallSlug`

- ID: `-33127873` / `0xfe06823f`
- Сигнатура: `inputGroupCallSlug(slug:string) => InputGroupCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputGroupCallSlug
- Поля:
  - `slug`: `string`

## `InputInvoice`

- Официальный тип: https://core.telegram.org/type/InputInvoice
- Количество constructors: **12**

### `inputInvoiceBusinessBotTransferStars`

- ID: `-191267262` / `0xf4997e42`
- Сигнатура: `inputInvoiceBusinessBotTransferStars(bot:InputUser, stars:long) => InputInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputInvoiceBusinessBotTransferStars
- Поля:
  - `bot`: `InputUser`
  - `stars`: `long`

### `inputInvoiceChatInviteSubscription`

- ID: `887591921` / `0x34e793f1`
- Сигнатура: `inputInvoiceChatInviteSubscription(hash:string) => InputInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputInvoiceChatInviteSubscription
- Поля:
  - `hash`: `string`

### `inputInvoiceMessage`

- ID: `-977967015` / `0xc5b56859`
- Сигнатура: `inputInvoiceMessage(peer:InputPeer, msg_id:int) => InputInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputInvoiceMessage
- Поля:
  - `peer`: `InputPeer`
  - `msg_id`: `int`

### `inputInvoicePremiumGiftCode`

- ID: `-1734841331` / `0x98986c0d`
- Сигнатура: `inputInvoicePremiumGiftCode(purpose:InputStorePaymentPurpose, option:PremiumGiftCodeOption) => InputInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputInvoicePremiumGiftCode
- Поля:
  - `purpose`: `InputStorePaymentPurpose`
  - `option`: `PremiumGiftCodeOption`

### `inputInvoicePremiumGiftStars`

- ID: `-625298705` / `0xdabab2ef`
- Сигнатура: `inputInvoicePremiumGiftStars(flags:#, user_id:InputUser, months:int, message:flags.0?TextWithEntities) => InputInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputInvoicePremiumGiftStars
- Поля:
  - `flags`: `#` - служебное поле flags
  - `user_id`: `InputUser`
  - `months`: `int`
  - `message`: `flags.0?TextWithEntities` - optional через flags.0

### `inputInvoiceSlug`

- ID: `-1020867857` / `0xc326caef`
- Сигнатура: `inputInvoiceSlug(slug:string) => InputInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputInvoiceSlug
- Поля:
  - `slug`: `string`

### `inputInvoiceStarGift`

- ID: `-396206446` / `0xe8625e92`
- Сигнатура: `inputInvoiceStarGift(flags:#, hide_name:flags.0?true, include_upgrade:flags.2?true, peer:InputPeer, gift_id:long, message:flags.1?TextWithEntities) => InputInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputInvoiceStarGift
- Поля:
  - `flags`: `#` - служебное поле flags
  - `hide_name`: `flags.0?true` - optional через flags.0
  - `include_upgrade`: `flags.2?true` - optional через flags.2
  - `peer`: `InputPeer`
  - `gift_id`: `long`
  - `message`: `flags.1?TextWithEntities` - optional через flags.1

### `inputInvoiceStarGiftPrepaidUpgrade`

- ID: `-1710536520` / `0x9a0b48b8`
- Сигнатура: `inputInvoiceStarGiftPrepaidUpgrade(peer:InputPeer, hash:string) => InputInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputInvoiceStarGiftPrepaidUpgrade
- Поля:
  - `peer`: `InputPeer`
  - `hash`: `string`

### `inputInvoiceStarGiftResale`

- ID: `-1012968668` / `0xc39f5324`
- Сигнатура: `inputInvoiceStarGiftResale(flags:#, ton:flags.0?true, slug:string, to_id:InputPeer) => InputInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputInvoiceStarGiftResale
- Поля:
  - `flags`: `#` - служебное поле flags
  - `ton`: `flags.0?true` - optional через flags.0
  - `slug`: `string`
  - `to_id`: `InputPeer`

### `inputInvoiceStarGiftTransfer`

- ID: `1247763417` / `0x4a5f5bd9`
- Сигнатура: `inputInvoiceStarGiftTransfer(stargift:InputSavedStarGift, to_id:InputPeer) => InputInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputInvoiceStarGiftTransfer
- Поля:
  - `stargift`: `InputSavedStarGift`
  - `to_id`: `InputPeer`

### `inputInvoiceStarGiftUpgrade`

- ID: `1300335965` / `0x4d818d5d`
- Сигнатура: `inputInvoiceStarGiftUpgrade(flags:#, keep_original_details:flags.0?true, stargift:InputSavedStarGift) => InputInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputInvoiceStarGiftUpgrade
- Поля:
  - `flags`: `#` - служебное поле flags
  - `keep_original_details`: `flags.0?true` - optional через flags.0
  - `stargift`: `InputSavedStarGift`

### `inputInvoiceStars`

- ID: `1710230755` / `0x65f00ce3`
- Сигнатура: `inputInvoiceStars(purpose:InputStorePaymentPurpose) => InputInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputInvoiceStars
- Поля:
  - `purpose`: `InputStorePaymentPurpose`

## `InputMedia`

- Официальный тип: https://core.telegram.org/type/InputMedia
- Количество constructors: **19**

### `inputMediaContact`

- ID: `-122978821` / `0xf8ab7dfb`
- Сигнатура: `inputMediaContact(phone_number:string, first_name:string, last_name:string, vcard:string) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaContact
- Поля:
  - `phone_number`: `string`
  - `first_name`: `string`
  - `last_name`: `string`
  - `vcard`: `string`

### `inputMediaDice`

- ID: `-428884101` / `0xe66fbf7b`
- Сигнатура: `inputMediaDice(emoticon:string) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaDice
- Поля:
  - `emoticon`: `string`

### `inputMediaDocument`

- ID: `-1468646731` / `0xa8763ab5`
- Сигнатура: `inputMediaDocument(flags:#, spoiler:flags.2?true, id:InputDocument, video_cover:flags.3?InputPhoto, video_timestamp:flags.4?int, ttl_seconds:flags.0?int, query:flags.1?string) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaDocument
- Поля:
  - `flags`: `#` - служебное поле flags
  - `spoiler`: `flags.2?true` - optional через flags.2
  - `id`: `InputDocument`
  - `video_cover`: `flags.3?InputPhoto` - optional через flags.3
  - `video_timestamp`: `flags.4?int` - optional через flags.4
  - `ttl_seconds`: `flags.0?int` - optional через flags.0
  - `query`: `flags.1?string` - optional через flags.1

### `inputMediaDocumentExternal`

- ID: `2006319353` / `0x779600f9`
- Сигнатура: `inputMediaDocumentExternal(flags:#, spoiler:flags.1?true, url:string, ttl_seconds:flags.0?int, video_cover:flags.2?InputPhoto, video_timestamp:flags.3?int) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaDocumentExternal
- Поля:
  - `flags`: `#` - служебное поле flags
  - `spoiler`: `flags.1?true` - optional через flags.1
  - `url`: `string`
  - `ttl_seconds`: `flags.0?int` - optional через flags.0
  - `video_cover`: `flags.2?InputPhoto` - optional через flags.2
  - `video_timestamp`: `flags.3?int` - optional через flags.3

### `inputMediaEmpty`

- ID: `-1771768449` / `0x9664f57f`
- Сигнатура: `inputMediaEmpty() => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaEmpty
- Поля:
  - Нет полей.

### `inputMediaGame`

- ID: `-750828557` / `0xd33f43f3`
- Сигнатура: `inputMediaGame(id:InputGame) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaGame
- Поля:
  - `id`: `InputGame`

### `inputMediaGeoLive`

- ID: `-1759532989` / `0x971fa843`
- Сигнатура: `inputMediaGeoLive(flags:#, stopped:flags.0?true, geo_point:InputGeoPoint, heading:flags.2?int, period:flags.1?int, proximity_notification_radius:flags.3?int) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaGeoLive
- Поля:
  - `flags`: `#` - служебное поле flags
  - `stopped`: `flags.0?true` - optional через flags.0
  - `geo_point`: `InputGeoPoint`
  - `heading`: `flags.2?int` - optional через flags.2
  - `period`: `flags.1?int` - optional через flags.1
  - `proximity_notification_radius`: `flags.3?int` - optional через flags.3

### `inputMediaGeoPoint`

- ID: `-104578748` / `0xf9c44144`
- Сигнатура: `inputMediaGeoPoint(geo_point:InputGeoPoint) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaGeoPoint
- Поля:
  - `geo_point`: `InputGeoPoint`

### `inputMediaInvoice`

- ID: `1080028941` / `0x405fef0d`
- Сигнатура: `inputMediaInvoice(flags:#, title:string, description:string, photo:flags.0?InputWebDocument, invoice:Invoice, payload:bytes, provider:flags.3?string, provider_data:DataJSON, start_param:flags.1?string, extended_media:flags.2?InputMedia) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaInvoice
- Поля:
  - `flags`: `#` - служебное поле flags
  - `title`: `string`
  - `description`: `string`
  - `photo`: `flags.0?InputWebDocument` - optional через flags.0
  - `invoice`: `Invoice`
  - `payload`: `bytes`
  - `provider`: `flags.3?string` - optional через flags.3
  - `provider_data`: `DataJSON`
  - `start_param`: `flags.1?string` - optional через flags.1
  - `extended_media`: `flags.2?InputMedia` - optional через flags.2

### `inputMediaPaidMedia`

- ID: `-1005571194` / `0xc4103386`
- Сигнатура: `inputMediaPaidMedia(flags:#, stars_amount:long, extended_media:Vector, payload:flags.0?string) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaPaidMedia
- Поля:
  - `flags`: `#` - служебное поле flags
  - `stars_amount`: `long`
  - `extended_media`: `Vector`
  - `payload`: `flags.0?string` - optional через flags.0

### `inputMediaPhoto`

- ID: `-1279654347` / `0xb3ba0635`
- Сигнатура: `inputMediaPhoto(flags:#, spoiler:flags.1?true, id:InputPhoto, ttl_seconds:flags.0?int) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaPhoto
- Поля:
  - `flags`: `#` - служебное поле flags
  - `spoiler`: `flags.1?true` - optional через flags.1
  - `id`: `InputPhoto`
  - `ttl_seconds`: `flags.0?int` - optional через flags.0

### `inputMediaPhotoExternal`

- ID: `-440664550` / `0xe5bbfe1a`
- Сигнатура: `inputMediaPhotoExternal(flags:#, spoiler:flags.1?true, url:string, ttl_seconds:flags.0?int) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaPhotoExternal
- Поля:
  - `flags`: `#` - служебное поле flags
  - `spoiler`: `flags.1?true` - optional через flags.1
  - `url`: `string`
  - `ttl_seconds`: `flags.0?int` - optional через flags.0

### `inputMediaPoll`

- ID: `261416433` / `0x0f94e5f1`
- Сигнатура: `inputMediaPoll(flags:#, poll:Poll, correct_answers:flags.0?Vector, solution:flags.1?string, solution_entities:flags.1?Vector) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaPoll
- Поля:
  - `flags`: `#` - служебное поле flags
  - `poll`: `Poll`
  - `correct_answers`: `flags.0?Vector` - optional через flags.0
  - `solution`: `flags.1?string` - optional через flags.1
  - `solution_entities`: `flags.1?Vector` - optional через flags.1

### `inputMediaStory`

- ID: `-1979852936` / `0x89fdd778`
- Сигнатура: `inputMediaStory(peer:InputPeer, id:int) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaStory
- Поля:
  - `peer`: `InputPeer`
  - `id`: `int`

### `inputMediaTodo`

- ID: `-1614454818` / `0x9fc55fde`
- Сигнатура: `inputMediaTodo(todo:TodoList) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaTodo
- Поля:
  - `todo`: `TodoList`

### `inputMediaUploadedDocument`

- ID: `58495792` / `0x037c9330`
- Сигнатура: `inputMediaUploadedDocument(flags:#, nosound_video:flags.3?true, force_file:flags.4?true, spoiler:flags.5?true, file:InputFile, thumb:flags.2?InputFile, mime_type:string, attributes:Vector, stickers:flags.0?Vector, video_cover:flags.6?InputPhoto, video_timestamp:flags.7?int, ttl_seconds:flags.1?int) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaUploadedDocument
- Поля:
  - `flags`: `#` - служебное поле flags
  - `nosound_video`: `flags.3?true` - optional через flags.3
  - `force_file`: `flags.4?true` - optional через flags.4
  - `spoiler`: `flags.5?true` - optional через flags.5
  - `file`: `InputFile`
  - `thumb`: `flags.2?InputFile` - optional через flags.2
  - `mime_type`: `string`
  - `attributes`: `Vector`
  - `stickers`: `flags.0?Vector` - optional через flags.0
  - `video_cover`: `flags.6?InputPhoto` - optional через flags.6
  - `video_timestamp`: `flags.7?int` - optional через flags.7
  - `ttl_seconds`: `flags.1?int` - optional через flags.1

### `inputMediaUploadedPhoto`

- ID: `505969924` / `0x1e287d04`
- Сигнатура: `inputMediaUploadedPhoto(flags:#, spoiler:flags.2?true, file:InputFile, stickers:flags.0?Vector, ttl_seconds:flags.1?int) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaUploadedPhoto
- Поля:
  - `flags`: `#` - служебное поле flags
  - `spoiler`: `flags.2?true` - optional через flags.2
  - `file`: `InputFile`
  - `stickers`: `flags.0?Vector` - optional через flags.0
  - `ttl_seconds`: `flags.1?int` - optional через flags.1

### `inputMediaVenue`

- ID: `-1052959727` / `0xc13d1c11`
- Сигнатура: `inputMediaVenue(geo_point:InputGeoPoint, title:string, address:string, provider:string, venue_id:string, venue_type:string) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaVenue
- Поля:
  - `geo_point`: `InputGeoPoint`
  - `title`: `string`
  - `address`: `string`
  - `provider`: `string`
  - `venue_id`: `string`
  - `venue_type`: `string`

### `inputMediaWebPage`

- ID: `-1038383031` / `0xc21b8849`
- Сигнатура: `inputMediaWebPage(flags:#, force_large_media:flags.0?true, force_small_media:flags.1?true, optional:flags.2?true, url:string) => InputMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaWebPage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `force_large_media`: `flags.0?true` - optional через flags.0
  - `force_small_media`: `flags.1?true` - optional через flags.1
  - `optional`: `flags.2?true` - optional через flags.2
  - `url`: `string`

## `InputMessage`

- Официальный тип: https://core.telegram.org/type/InputMessage
- Количество constructors: **4**

### `inputMessageCallbackQuery`

- ID: `-1392895362` / `0xacfa1a7e`
- Сигнатура: `inputMessageCallbackQuery(id:int, query_id:long) => InputMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessageCallbackQuery
- Поля:
  - `id`: `int`
  - `query_id`: `long`

### `inputMessageID`

- ID: `-1502174430` / `0xa676a322`
- Сигнатура: `inputMessageID(id:int) => InputMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessageID
- Поля:
  - `id`: `int`

### `inputMessagePinned`

- ID: `-2037963464` / `0x86872538`
- Сигнатура: `inputMessagePinned() => InputMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagePinned
- Поля:
  - Нет полей.

### `inputMessageReplyTo`

- ID: `-1160215659` / `0xbad88395`
- Сигнатура: `inputMessageReplyTo(id:int) => InputMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessageReplyTo
- Поля:
  - `id`: `int`

## `InputNotifyPeer`

- Официальный тип: https://core.telegram.org/type/InputNotifyPeer
- Количество constructors: **5**

### `inputNotifyBroadcasts`

- ID: `-1311015810` / `0xb1db7c7e`
- Сигнатура: `inputNotifyBroadcasts() => InputNotifyPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputNotifyBroadcasts
- Поля:
  - Нет полей.

### `inputNotifyChats`

- ID: `1251338318` / `0x4a95e84e`
- Сигнатура: `inputNotifyChats() => InputNotifyPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputNotifyChats
- Поля:
  - Нет полей.

### `inputNotifyForumTopic`

- ID: `1548122514` / `0x5c467992`
- Сигнатура: `inputNotifyForumTopic(peer:InputPeer, top_msg_id:int) => InputNotifyPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputNotifyForumTopic
- Поля:
  - `peer`: `InputPeer`
  - `top_msg_id`: `int`

### `inputNotifyPeer`

- ID: `-1195615476` / `0xb8bc5b0c`
- Сигнатура: `inputNotifyPeer(peer:InputPeer) => InputNotifyPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputNotifyPeer
- Поля:
  - `peer`: `InputPeer`

### `inputNotifyUsers`

- ID: `423314455` / `0x193b4417`
- Сигнатура: `inputNotifyUsers() => InputNotifyPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputNotifyUsers
- Поля:
  - Нет полей.

## `InputPaymentCredentials`

- Официальный тип: https://core.telegram.org/type/InputPaymentCredentials
- Количество constructors: **4**

### `inputPaymentCredentials`

- ID: `873977640` / `0x3417d728`
- Сигнатура: `inputPaymentCredentials(flags:#, save:flags.0?true, data:DataJSON) => InputPaymentCredentials`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPaymentCredentials
- Поля:
  - `flags`: `#` - служебное поле flags
  - `save`: `flags.0?true` - optional через flags.0
  - `data`: `DataJSON`

### `inputPaymentCredentialsApplePay`

- ID: `178373535` / `0x0aa1c39f`
- Сигнатура: `inputPaymentCredentialsApplePay(payment_data:DataJSON) => InputPaymentCredentials`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPaymentCredentialsApplePay
- Поля:
  - `payment_data`: `DataJSON`

### `inputPaymentCredentialsGooglePay`

- ID: `-1966921727` / `0x8ac32801`
- Сигнатура: `inputPaymentCredentialsGooglePay(payment_token:DataJSON) => InputPaymentCredentials`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPaymentCredentialsGooglePay
- Поля:
  - `payment_token`: `DataJSON`

### `inputPaymentCredentialsSaved`

- ID: `-1056001329` / `0xc10eb2cf`
- Сигнатура: `inputPaymentCredentialsSaved(id:string, tmp_password:bytes) => InputPaymentCredentials`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPaymentCredentialsSaved
- Поля:
  - `id`: `string`
  - `tmp_password`: `bytes`

## `InputPeer`

- Официальный тип: https://core.telegram.org/type/InputPeer
- Количество constructors: **7**

### `inputPeerChannel`

- ID: `666680316` / `0x27bcbbfc`
- Сигнатура: `inputPeerChannel(channel_id:long, access_hash:long) => InputPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPeerChannel
- Поля:
  - `channel_id`: `long`
  - `access_hash`: `long`

### `inputPeerChannelFromMessage`

- ID: `-1121318848` / `0xbd2a0840`
- Сигнатура: `inputPeerChannelFromMessage(peer:InputPeer, msg_id:int, channel_id:long) => InputPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPeerChannelFromMessage
- Поля:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `channel_id`: `long`

### `inputPeerChat`

- ID: `900291769` / `0x35a95cb9`
- Сигнатура: `inputPeerChat(chat_id:long) => InputPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPeerChat
- Поля:
  - `chat_id`: `long`

### `inputPeerEmpty`

- ID: `2134579434` / `0x7f3b18ea`
- Сигнатура: `inputPeerEmpty() => InputPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPeerEmpty
- Поля:
  - Нет полей.

### `inputPeerSelf`

- ID: `2107670217` / `0x7da07ec9`
- Сигнатура: `inputPeerSelf() => InputPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPeerSelf
- Поля:
  - Нет полей.

### `inputPeerUser`

- ID: `-571955892` / `0xdde8a54c`
- Сигнатура: `inputPeerUser(user_id:long, access_hash:long) => InputPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPeerUser
- Поля:
  - `user_id`: `long`
  - `access_hash`: `long`

### `inputPeerUserFromMessage`

- ID: `-1468331492` / `0xa87b0a1c`
- Сигнатура: `inputPeerUserFromMessage(peer:InputPeer, msg_id:int, user_id:long) => InputPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPeerUserFromMessage
- Поля:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `user_id`: `long`

## `InputPeerNotifySettings`

- Официальный тип: https://core.telegram.org/type/InputPeerNotifySettings
- Количество constructors: **1**

### `inputPeerNotifySettings`

- ID: `-892638494` / `0xcacb6ae2`
- Сигнатура: `inputPeerNotifySettings(flags:#, show_previews:flags.0?Bool, silent:flags.1?Bool, mute_until:flags.2?int, sound:flags.3?NotificationSound, stories_muted:flags.6?Bool, stories_hide_sender:flags.7?Bool, stories_sound:flags.8?NotificationSound) => InputPeerNotifySettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPeerNotifySettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `show_previews`: `flags.0?Bool` - optional через flags.0
  - `silent`: `flags.1?Bool` - optional через flags.1
  - `mute_until`: `flags.2?int` - optional через flags.2
  - `sound`: `flags.3?NotificationSound` - optional через flags.3
  - `stories_muted`: `flags.6?Bool` - optional через flags.6
  - `stories_hide_sender`: `flags.7?Bool` - optional через flags.7
  - `stories_sound`: `flags.8?NotificationSound` - optional через flags.8

## `InputPhoneCall`

- Официальный тип: https://core.telegram.org/type/InputPhoneCall
- Количество constructors: **1**

### `inputPhoneCall`

- ID: `506920429` / `0x1e36fded`
- Сигнатура: `inputPhoneCall(id:long, access_hash:long) => InputPhoneCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPhoneCall
- Поля:
  - `id`: `long`
  - `access_hash`: `long`

## `InputPhoto`

- Официальный тип: https://core.telegram.org/type/InputPhoto
- Количество constructors: **2**

### `inputPhoto`

- ID: `1001634122` / `0x3bb3b94a`
- Сигнатура: `inputPhoto(id:long, access_hash:long, file_reference:bytes) => InputPhoto`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPhoto
- Поля:
  - `id`: `long`
  - `access_hash`: `long`
  - `file_reference`: `bytes`

### `inputPhotoEmpty`

- ID: `483901197` / `0x1cd7bf0d`
- Сигнатура: `inputPhotoEmpty() => InputPhoto`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPhotoEmpty
- Поля:
  - Нет полей.

## `InputPrivacyKey`

- Официальный тип: https://core.telegram.org/type/InputPrivacyKey
- Количество constructors: **13**

### `inputPrivacyKeyAbout`

- ID: `941870144` / `0x3823cc40`
- Сигнатура: `inputPrivacyKeyAbout() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyAbout
- Поля:
  - Нет полей.

### `inputPrivacyKeyAddedByPhone`

- ID: `-786326563` / `0xd1219bdd`
- Сигнатура: `inputPrivacyKeyAddedByPhone() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyAddedByPhone
- Поля:
  - Нет полей.

### `inputPrivacyKeyBirthday`

- ID: `-698740276` / `0xd65a11cc`
- Сигнатура: `inputPrivacyKeyBirthday() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyBirthday
- Поля:
  - Нет полей.

### `inputPrivacyKeyChatInvite`

- ID: `-1107622874` / `0xbdfb0426`
- Сигнатура: `inputPrivacyKeyChatInvite() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyChatInvite
- Поля:
  - Нет полей.

### `inputPrivacyKeyForwards`

- ID: `-1529000952` / `0xa4dd4c08`
- Сигнатура: `inputPrivacyKeyForwards() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyForwards
- Поля:
  - Нет полей.

### `inputPrivacyKeyNoPaidMessages`

- ID: `-1111124044` / `0xbdc597b4`
- Сигнатура: `inputPrivacyKeyNoPaidMessages() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyNoPaidMessages
- Поля:
  - Нет полей.

### `inputPrivacyKeyPhoneCall`

- ID: `-88417185` / `0xfabadc5f`
- Сигнатура: `inputPrivacyKeyPhoneCall() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyPhoneCall
- Поля:
  - Нет полей.

### `inputPrivacyKeyPhoneNumber`

- ID: `55761658` / `0x0352dafa`
- Сигнатура: `inputPrivacyKeyPhoneNumber() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyPhoneNumber
- Поля:
  - Нет полей.

### `inputPrivacyKeyPhoneP2P`

- ID: `-610373422` / `0xdb9e70d2`
- Сигнатура: `inputPrivacyKeyPhoneP2P() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyPhoneP2P
- Поля:
  - Нет полей.

### `inputPrivacyKeyProfilePhoto`

- ID: `1461304012` / `0x5719bacc`
- Сигнатура: `inputPrivacyKeyProfilePhoto() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyProfilePhoto
- Поля:
  - Нет полей.

### `inputPrivacyKeyStarGiftsAutoSave`

- ID: `-512548031` / `0xe1732341`
- Сигнатура: `inputPrivacyKeyStarGiftsAutoSave() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyStarGiftsAutoSave
- Поля:
  - Нет полей.

### `inputPrivacyKeyStatusTimestamp`

- ID: `1335282456` / `0x4f96cb18`
- Сигнатура: `inputPrivacyKeyStatusTimestamp() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyStatusTimestamp
- Поля:
  - Нет полей.

### `inputPrivacyKeyVoiceMessages`

- ID: `-1360618136` / `0xaee69d68`
- Сигнатура: `inputPrivacyKeyVoiceMessages() => InputPrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyKeyVoiceMessages
- Поля:
  - Нет полей.

## `InputPrivacyRule`

- Официальный тип: https://core.telegram.org/type/InputPrivacyRule
- Количество constructors: **12**

### `inputPrivacyValueAllowAll`

- ID: `407582158` / `0x184b35ce`
- Сигнатура: `inputPrivacyValueAllowAll() => InputPrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyValueAllowAll
- Поля:
  - Нет полей.

### `inputPrivacyValueAllowBots`

- ID: `1515179237` / `0x5a4fcce5`
- Сигнатура: `inputPrivacyValueAllowBots() => InputPrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyValueAllowBots
- Поля:
  - Нет полей.

### `inputPrivacyValueAllowChatParticipants`

- ID: `-2079962673` / `0x840649cf`
- Сигнатура: `inputPrivacyValueAllowChatParticipants(chats:Vector) => InputPrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyValueAllowChatParticipants
- Поля:
  - `chats`: `Vector`

### `inputPrivacyValueAllowCloseFriends`

- ID: `793067081` / `0x2f453e49`
- Сигнатура: `inputPrivacyValueAllowCloseFriends() => InputPrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyValueAllowCloseFriends
- Поля:
  - Нет полей.

### `inputPrivacyValueAllowContacts`

- ID: `218751099` / `0x0d09e07b`
- Сигнатура: `inputPrivacyValueAllowContacts() => InputPrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyValueAllowContacts
- Поля:
  - Нет полей.

### `inputPrivacyValueAllowPremium`

- ID: `2009975281` / `0x77cdc9f1`
- Сигнатура: `inputPrivacyValueAllowPremium() => InputPrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyValueAllowPremium
- Поля:
  - Нет полей.

### `inputPrivacyValueAllowUsers`

- ID: `320652927` / `0x131cc67f`
- Сигнатура: `inputPrivacyValueAllowUsers(users:Vector) => InputPrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyValueAllowUsers
- Поля:
  - `users`: `Vector`

### `inputPrivacyValueDisallowAll`

- ID: `-697604407` / `0xd66b66c9`
- Сигнатура: `inputPrivacyValueDisallowAll() => InputPrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyValueDisallowAll
- Поля:
  - Нет полей.

### `inputPrivacyValueDisallowBots`

- ID: `-991594219` / `0xc4e57915`
- Сигнатура: `inputPrivacyValueDisallowBots() => InputPrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyValueDisallowBots
- Поля:
  - Нет полей.

### `inputPrivacyValueDisallowChatParticipants`

- ID: `-380694650` / `0xe94f0f86`
- Сигнатура: `inputPrivacyValueDisallowChatParticipants(chats:Vector) => InputPrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyValueDisallowChatParticipants
- Поля:
  - `chats`: `Vector`

### `inputPrivacyValueDisallowContacts`

- ID: `195371015` / `0x0ba52007`
- Сигнатура: `inputPrivacyValueDisallowContacts() => InputPrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyValueDisallowContacts
- Поля:
  - Нет полей.

### `inputPrivacyValueDisallowUsers`

- ID: `-1877932953` / `0x90110467`
- Сигнатура: `inputPrivacyValueDisallowUsers(users:Vector) => InputPrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputPrivacyValueDisallowUsers
- Поля:
  - `users`: `Vector`

## `InputQuickReplyShortcut`

- Официальный тип: https://core.telegram.org/type/InputQuickReplyShortcut
- Количество constructors: **2**

### `inputQuickReplyShortcut`

- ID: `609840449` / `0x24596d41`
- Сигнатура: `inputQuickReplyShortcut(shortcut:string) => InputQuickReplyShortcut`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputQuickReplyShortcut
- Поля:
  - `shortcut`: `string`

### `inputQuickReplyShortcutId`

- ID: `18418929` / `0x01190cf1`
- Сигнатура: `inputQuickReplyShortcutId(shortcut_id:int) => InputQuickReplyShortcut`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputQuickReplyShortcutId
- Поля:
  - `shortcut_id`: `int`

## `InputReplyTo`

- Официальный тип: https://core.telegram.org/type/InputReplyTo
- Количество constructors: **3**

### `inputReplyToMessage`

- ID: `-2036351472` / `0x869fbe10`
- Сигнатура: `inputReplyToMessage(flags:#, reply_to_msg_id:int, top_msg_id:flags.0?int, reply_to_peer_id:flags.1?InputPeer, quote_text:flags.2?string, quote_entities:flags.3?Vector, quote_offset:flags.4?int, monoforum_peer_id:flags.5?InputPeer, todo_item_id:flags.6?int) => InputReplyTo`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReplyToMessage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `reply_to_msg_id`: `int`
  - `top_msg_id`: `flags.0?int` - optional через flags.0
  - `reply_to_peer_id`: `flags.1?InputPeer` - optional через flags.1
  - `quote_text`: `flags.2?string` - optional через flags.2
  - `quote_entities`: `flags.3?Vector` - optional через flags.3
  - `quote_offset`: `flags.4?int` - optional через flags.4
  - `monoforum_peer_id`: `flags.5?InputPeer` - optional через flags.5
  - `todo_item_id`: `flags.6?int` - optional через flags.6

### `inputReplyToMonoForum`

- ID: `1775660101` / `0x69d66c45`
- Сигнатура: `inputReplyToMonoForum(monoforum_peer_id:InputPeer) => InputReplyTo`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReplyToMonoForum
- Поля:
  - `monoforum_peer_id`: `InputPeer`

### `inputReplyToStory`

- ID: `1484862010` / `0x5881323a`
- Сигнатура: `inputReplyToStory(peer:InputPeer, story_id:int) => InputReplyTo`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReplyToStory
- Поля:
  - `peer`: `InputPeer`
  - `story_id`: `int`

## `InputSavedStarGift`

- Официальный тип: https://core.telegram.org/type/InputSavedStarGift
- Количество constructors: **3**

### `inputSavedStarGiftChat`

- ID: `-251549057` / `0xf101aa7f`
- Сигнатура: `inputSavedStarGiftChat(peer:InputPeer, saved_id:long) => InputSavedStarGift`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputSavedStarGiftChat
- Поля:
  - `peer`: `InputPeer`
  - `saved_id`: `long`

### `inputSavedStarGiftSlug`

- ID: `545636920` / `0x2085c238`
- Сигнатура: `inputSavedStarGiftSlug(slug:string) => InputSavedStarGift`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputSavedStarGiftSlug
- Поля:
  - `slug`: `string`

### `inputSavedStarGiftUser`

- ID: `1764202389` / `0x69279795`
- Сигнатура: `inputSavedStarGiftUser(msg_id:int) => InputSavedStarGift`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputSavedStarGiftUser
- Поля:
  - `msg_id`: `int`

## `InputSecureFile`

- Официальный тип: https://core.telegram.org/type/InputSecureFile
- Количество constructors: **2**

### `inputSecureFile`

- ID: `1399317950` / `0x5367e5be`
- Сигнатура: `inputSecureFile(id:long, access_hash:long) => InputSecureFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputSecureFile
- Поля:
  - `id`: `long`
  - `access_hash`: `long`

### `inputSecureFileUploaded`

- ID: `859091184` / `0x3334b0f0`
- Сигнатура: `inputSecureFileUploaded(id:long, parts:int, md5_checksum:string, file_hash:bytes, secret:bytes) => InputSecureFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputSecureFileUploaded
- Поля:
  - `id`: `long`
  - `parts`: `int`
  - `md5_checksum`: `string`
  - `file_hash`: `bytes`
  - `secret`: `bytes`

## `InputSecureValue`

- Официальный тип: https://core.telegram.org/type/InputSecureValue
- Количество constructors: **1**

### `inputSecureValue`

- ID: `-618540889` / `0xdb21d0a7`
- Сигнатура: `inputSecureValue(flags:#, type:SecureValueType, data:flags.0?SecureData, front_side:flags.1?InputSecureFile, reverse_side:flags.2?InputSecureFile, selfie:flags.3?InputSecureFile, translation:flags.6?Vector, files:flags.4?Vector, plain_data:flags.5?SecurePlainData) => InputSecureValue`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputSecureValue
- Поля:
  - `flags`: `#` - служебное поле flags
  - `type`: `SecureValueType`
  - `data`: `flags.0?SecureData` - optional через flags.0
  - `front_side`: `flags.1?InputSecureFile` - optional через flags.1
  - `reverse_side`: `flags.2?InputSecureFile` - optional через flags.2
  - `selfie`: `flags.3?InputSecureFile` - optional через flags.3
  - `translation`: `flags.6?Vector` - optional через flags.6
  - `files`: `flags.4?Vector` - optional через flags.4
  - `plain_data`: `flags.5?SecurePlainData` - optional через flags.5

## `InputSingleMedia`

- Официальный тип: https://core.telegram.org/type/InputSingleMedia
- Количество constructors: **1**

### `inputSingleMedia`

- ID: `482797855` / `0x1cc6e91f`
- Сигнатура: `inputSingleMedia(flags:#, media:InputMedia, random_id:long, message:string, entities:flags.0?Vector) => InputSingleMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputSingleMedia
- Поля:
  - `flags`: `#` - служебное поле flags
  - `media`: `InputMedia`
  - `random_id`: `long`
  - `message`: `string`
  - `entities`: `flags.0?Vector` - optional через flags.0

## `InputStarsTransaction`

- Официальный тип: https://core.telegram.org/type/InputStarsTransaction
- Количество constructors: **1**

### `inputStarsTransaction`

- ID: `543876817` / `0x206ae6d1`
- Сигнатура: `inputStarsTransaction(flags:#, refund:flags.0?true, id:string) => InputStarsTransaction`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStarsTransaction
- Поля:
  - `flags`: `#` - служебное поле flags
  - `refund`: `flags.0?true` - optional через flags.0
  - `id`: `string`

## `InputStickerSet`

- Официальный тип: https://core.telegram.org/type/InputStickerSet
- Количество constructors: **12**

### `inputStickerSetAnimatedEmoji`

- ID: `42402760` / `0x028703c8`
- Сигнатура: `inputStickerSetAnimatedEmoji() => InputStickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetAnimatedEmoji
- Поля:
  - Нет полей.

### `inputStickerSetAnimatedEmojiAnimations`

- ID: `215889721` / `0x0cde3739`
- Сигнатура: `inputStickerSetAnimatedEmojiAnimations() => InputStickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetAnimatedEmojiAnimations
- Поля:
  - Нет полей.

### `inputStickerSetDice`

- ID: `-427863538` / `0xe67f520e`
- Сигнатура: `inputStickerSetDice(emoticon:string) => InputStickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetDice
- Поля:
  - `emoticon`: `string`

### `inputStickerSetEmojiChannelDefaultStatuses`

- ID: `1232373075` / `0x49748553`
- Сигнатура: `inputStickerSetEmojiChannelDefaultStatuses() => InputStickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetEmojiChannelDefaultStatuses
- Поля:
  - Нет полей.

### `inputStickerSetEmojiDefaultStatuses`

- ID: `701560302` / `0x29d0f5ee`
- Сигнатура: `inputStickerSetEmojiDefaultStatuses() => InputStickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetEmojiDefaultStatuses
- Поля:
  - Нет полей.

### `inputStickerSetEmojiDefaultTopicIcons`

- ID: `1153562857` / `0x44c1f8e9`
- Сигнатура: `inputStickerSetEmojiDefaultTopicIcons() => InputStickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetEmojiDefaultTopicIcons
- Поля:
  - Нет полей.

### `inputStickerSetEmojiGenericAnimations`

- ID: `80008398` / `0x04c4d4ce`
- Сигнатура: `inputStickerSetEmojiGenericAnimations() => InputStickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetEmojiGenericAnimations
- Поля:
  - Нет полей.

### `inputStickerSetEmpty`

- ID: `-4838507` / `0xffb62b95`
- Сигнатура: `inputStickerSetEmpty() => InputStickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetEmpty
- Поля:
  - Нет полей.

### `inputStickerSetID`

- ID: `-1645763991` / `0x9de7a269`
- Сигнатура: `inputStickerSetID(id:long, access_hash:long) => InputStickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetID
- Поля:
  - `id`: `long`
  - `access_hash`: `long`

### `inputStickerSetPremiumGifts`

- ID: `-930399486` / `0xc88b3b02`
- Сигнатура: `inputStickerSetPremiumGifts() => InputStickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetPremiumGifts
- Поля:
  - Нет полей.

### `inputStickerSetShortName`

- ID: `-2044933984` / `0x861cc8a0`
- Сигнатура: `inputStickerSetShortName(short_name:string) => InputStickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetShortName
- Поля:
  - `short_name`: `string`

### `inputStickerSetTonGifts`

- ID: `485912992` / `0x1cf671a0`
- Сигнатура: `inputStickerSetTonGifts() => InputStickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetTonGifts
- Поля:
  - Нет полей.

## `InputStickerSetItem`

- Официальный тип: https://core.telegram.org/type/InputStickerSetItem
- Количество constructors: **1**

### `inputStickerSetItem`

- ID: `853188252` / `0x32da9e9c`
- Сигнатура: `inputStickerSetItem(flags:#, document:InputDocument, emoji:string, mask_coords:flags.0?MaskCoords, keywords:flags.1?string) => InputStickerSetItem`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickerSetItem
- Поля:
  - `flags`: `#` - служебное поле flags
  - `document`: `InputDocument`
  - `emoji`: `string`
  - `mask_coords`: `flags.0?MaskCoords` - optional через flags.0
  - `keywords`: `flags.1?string` - optional через flags.1

## `InputStickeredMedia`

- Официальный тип: https://core.telegram.org/type/InputStickeredMedia
- Количество constructors: **2**

### `inputStickeredMediaDocument`

- ID: `70813275` / `0x0438865b`
- Сигнатура: `inputStickeredMediaDocument(id:InputDocument) => InputStickeredMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickeredMediaDocument
- Поля:
  - `id`: `InputDocument`

### `inputStickeredMediaPhoto`

- ID: `1251549527` / `0x4a992157`
- Сигнатура: `inputStickeredMediaPhoto(id:InputPhoto) => InputStickeredMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStickeredMediaPhoto
- Поля:
  - `id`: `InputPhoto`

## `InputStorePaymentPurpose`

- Официальный тип: https://core.telegram.org/type/InputStorePaymentPurpose
- Количество constructors: **8**

### `inputStorePaymentAuthCode`

- ID: `-1682807955` / `0x9bb2636d`
- Сигнатура: `inputStorePaymentAuthCode(flags:#, restore:flags.0?true, phone_number:string, phone_code_hash:string, currency:string, amount:long) => InputStorePaymentPurpose`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStorePaymentAuthCode
- Поля:
  - `flags`: `#` - служебное поле flags
  - `restore`: `flags.0?true` - optional через flags.0
  - `phone_number`: `string`
  - `phone_code_hash`: `string`
  - `currency`: `string`
  - `amount`: `long`

### `inputStorePaymentGiftPremium`

- ID: `1634697192` / `0x616f7fe8`
- Сигнатура: `inputStorePaymentGiftPremium(user_id:InputUser, currency:string, amount:long) => InputStorePaymentPurpose`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStorePaymentGiftPremium
- Поля:
  - `user_id`: `InputUser`
  - `currency`: `string`
  - `amount`: `long`

### `inputStorePaymentPremiumGiftCode`

- ID: `-75955309` / `0xfb790393`
- Сигнатура: `inputStorePaymentPremiumGiftCode(flags:#, users:Vector, boost_peer:flags.0?InputPeer, currency:string, amount:long, message:flags.1?TextWithEntities) => InputStorePaymentPurpose`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStorePaymentPremiumGiftCode
- Поля:
  - `flags`: `#` - служебное поле flags
  - `users`: `Vector`
  - `boost_peer`: `flags.0?InputPeer` - optional через flags.0
  - `currency`: `string`
  - `amount`: `long`
  - `message`: `flags.1?TextWithEntities` - optional через flags.1

### `inputStorePaymentPremiumGiveaway`

- ID: `369444042` / `0x160544ca`
- Сигнатура: `inputStorePaymentPremiumGiveaway(flags:#, only_new_subscribers:flags.0?true, winners_are_visible:flags.3?true, boost_peer:InputPeer, additional_peers:flags.1?Vector, countries_iso2:flags.2?Vector, prize_description:flags.4?string, random_id:long, until_date:int, currency:string, amount:long) => InputStorePaymentPurpose`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStorePaymentPremiumGiveaway
- Поля:
  - `flags`: `#` - служебное поле flags
  - `only_new_subscribers`: `flags.0?true` - optional через flags.0
  - `winners_are_visible`: `flags.3?true` - optional через flags.3
  - `boost_peer`: `InputPeer`
  - `additional_peers`: `flags.1?Vector` - optional через flags.1
  - `countries_iso2`: `flags.2?Vector` - optional через flags.2
  - `prize_description`: `flags.4?string` - optional через flags.4
  - `random_id`: `long`
  - `until_date`: `int`
  - `currency`: `string`
  - `amount`: `long`

### `inputStorePaymentPremiumSubscription`

- ID: `-1502273946` / `0xa6751e66`
- Сигнатура: `inputStorePaymentPremiumSubscription(flags:#, restore:flags.0?true, upgrade:flags.1?true) => InputStorePaymentPurpose`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStorePaymentPremiumSubscription
- Поля:
  - `flags`: `#` - служебное поле flags
  - `restore`: `flags.0?true` - optional через flags.0
  - `upgrade`: `flags.1?true` - optional через flags.1

### `inputStorePaymentStarsGift`

- ID: `494149367` / `0x1d741ef7`
- Сигнатура: `inputStorePaymentStarsGift(user_id:InputUser, stars:long, currency:string, amount:long) => InputStorePaymentPurpose`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStorePaymentStarsGift
- Поля:
  - `user_id`: `InputUser`
  - `stars`: `long`
  - `currency`: `string`
  - `amount`: `long`

### `inputStorePaymentStarsGiveaway`

- ID: `1964968186` / `0x751f08fa`
- Сигнатура: `inputStorePaymentStarsGiveaway(flags:#, only_new_subscribers:flags.0?true, winners_are_visible:flags.3?true, stars:long, boost_peer:InputPeer, additional_peers:flags.1?Vector, countries_iso2:flags.2?Vector, prize_description:flags.4?string, random_id:long, until_date:int, currency:string, amount:long, users:int) => InputStorePaymentPurpose`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStorePaymentStarsGiveaway
- Поля:
  - `flags`: `#` - служебное поле flags
  - `only_new_subscribers`: `flags.0?true` - optional через flags.0
  - `winners_are_visible`: `flags.3?true` - optional через flags.3
  - `stars`: `long`
  - `boost_peer`: `InputPeer`
  - `additional_peers`: `flags.1?Vector` - optional через flags.1
  - `countries_iso2`: `flags.2?Vector` - optional через flags.2
  - `prize_description`: `flags.4?string` - optional через flags.4
  - `random_id`: `long`
  - `until_date`: `int`
  - `currency`: `string`
  - `amount`: `long`
  - `users`: `int`

### `inputStorePaymentStarsTopup`

- ID: `-106780981` / `0xf9a2a6cb`
- Сигнатура: `inputStorePaymentStarsTopup(flags:#, stars:long, currency:string, amount:long, spend_purpose_peer:flags.0?InputPeer) => InputStorePaymentPurpose`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputStorePaymentStarsTopup
- Поля:
  - `flags`: `#` - служебное поле flags
  - `stars`: `long`
  - `currency`: `string`
  - `amount`: `long`
  - `spend_purpose_peer`: `flags.0?InputPeer` - optional через flags.0

## `InputTheme`

- Официальный тип: https://core.telegram.org/type/InputTheme
- Количество constructors: **2**

### `inputTheme`

- ID: `1012306921` / `0x3c5693e9`
- Сигнатура: `inputTheme(id:long, access_hash:long) => InputTheme`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputTheme
- Поля:
  - `id`: `long`
  - `access_hash`: `long`

### `inputThemeSlug`

- ID: `-175567375` / `0xf5890df1`
- Сигнатура: `inputThemeSlug(slug:string) => InputTheme`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputThemeSlug
- Поля:
  - `slug`: `string`

## `InputThemeSettings`

- Официальный тип: https://core.telegram.org/type/InputThemeSettings
- Количество constructors: **1**

### `inputThemeSettings`

- ID: `-1881255857` / `0x8fde504f`
- Сигнатура: `inputThemeSettings(flags:#, message_colors_animated:flags.2?true, base_theme:BaseTheme, accent_color:int, outbox_accent_color:flags.3?int, message_colors:flags.0?Vector, wallpaper:flags.1?InputWallPaper, wallpaper_settings:flags.1?WallPaperSettings) => InputThemeSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputThemeSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `message_colors_animated`: `flags.2?true` - optional через flags.2
  - `base_theme`: `BaseTheme`
  - `accent_color`: `int`
  - `outbox_accent_color`: `flags.3?int` - optional через flags.3
  - `message_colors`: `flags.0?Vector` - optional через flags.0
  - `wallpaper`: `flags.1?InputWallPaper` - optional через flags.1
  - `wallpaper_settings`: `flags.1?WallPaperSettings` - optional через flags.1

## `InputUser`

- Официальный тип: https://core.telegram.org/type/InputUser
- Количество constructors: **4**

### `inputUser`

- ID: `-233744186` / `0xf21158c6`
- Сигнатура: `inputUser(user_id:long, access_hash:long) => InputUser`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputUser
- Поля:
  - `user_id`: `long`
  - `access_hash`: `long`

### `inputUserEmpty`

- ID: `-1182234929` / `0xb98886cf`
- Сигнатура: `inputUserEmpty() => InputUser`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputUserEmpty
- Поля:
  - Нет полей.

### `inputUserFromMessage`

- ID: `497305826` / `0x1da448e2`
- Сигнатура: `inputUserFromMessage(peer:InputPeer, msg_id:int, user_id:long) => InputUser`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputUserFromMessage
- Поля:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `user_id`: `long`

### `inputUserSelf`

- ID: `-138301121` / `0xf7c1b13f`
- Сигнатура: `inputUserSelf() => InputUser`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputUserSelf
- Поля:
  - Нет полей.

## `InputWallPaper`

- Официальный тип: https://core.telegram.org/type/InputWallPaper
- Количество constructors: **3**

### `inputWallPaper`

- ID: `-433014407` / `0xe630b979`
- Сигнатура: `inputWallPaper(id:long, access_hash:long) => InputWallPaper`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputWallPaper
- Поля:
  - `id`: `long`
  - `access_hash`: `long`

### `inputWallPaperNoFile`

- ID: `-1770371538` / `0x967a462e`
- Сигнатура: `inputWallPaperNoFile(id:long) => InputWallPaper`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputWallPaperNoFile
- Поля:
  - `id`: `long`

### `inputWallPaperSlug`

- ID: `1913199744` / `0x72091c80`
- Сигнатура: `inputWallPaperSlug(slug:string) => InputWallPaper`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputWallPaperSlug
- Поля:
  - `slug`: `string`

## `InputWebDocument`

- Официальный тип: https://core.telegram.org/type/InputWebDocument
- Количество constructors: **1**

### `inputWebDocument`

- ID: `-1678949555` / `0x9bed434d`
- Сигнатура: `inputWebDocument(url:string, size:int, mime_type:string, attributes:Vector) => InputWebDocument`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputWebDocument
- Поля:
  - `url`: `string`
  - `size`: `int`
  - `mime_type`: `string`
  - `attributes`: `Vector`

## `InputWebFileLocation`

- Официальный тип: https://core.telegram.org/type/InputWebFileLocation
- Количество constructors: **3**

### `inputWebFileAudioAlbumThumbLocation`

- ID: `-193992412` / `0xf46fe924`
- Сигнатура: `inputWebFileAudioAlbumThumbLocation(flags:#, small:flags.2?true, document:flags.0?InputDocument, title:flags.1?string, performer:flags.1?string) => InputWebFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputWebFileAudioAlbumThumbLocation
- Поля:
  - `flags`: `#` - служебное поле flags
  - `small`: `flags.2?true` - optional через flags.2
  - `document`: `flags.0?InputDocument` - optional через flags.0
  - `title`: `flags.1?string` - optional через flags.1
  - `performer`: `flags.1?string` - optional через flags.1

### `inputWebFileGeoPointLocation`

- ID: `-1625153079` / `0x9f2221c9`
- Сигнатура: `inputWebFileGeoPointLocation(geo_point:InputGeoPoint, access_hash:long, w:int, h:int, zoom:int, scale:int) => InputWebFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputWebFileGeoPointLocation
- Поля:
  - `geo_point`: `InputGeoPoint`
  - `access_hash`: `long`
  - `w`: `int`
  - `h`: `int`
  - `zoom`: `int`
  - `scale`: `int`

### `inputWebFileLocation`

- ID: `-1036396922` / `0xc239d686`
- Сигнатура: `inputWebFileLocation(url:string, access_hash:long) => InputWebFileLocation`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputWebFileLocation
- Поля:
  - `url`: `string`
  - `access_hash`: `long`

## `Invoice`

- Официальный тип: https://core.telegram.org/type/Invoice
- Количество constructors: **1**

### `invoice`

- ID: `77522308` / `0x049ee584`
- Сигнатура: `invoice(flags:#, test:flags.0?true, name_requested:flags.1?true, phone_requested:flags.2?true, email_requested:flags.3?true, shipping_address_requested:flags.4?true, flexible:flags.5?true, phone_to_provider:flags.6?true, email_to_provider:flags.7?true, recurring:flags.9?true, currency:string, prices:Vector, max_tip_amount:flags.8?long, suggested_tip_amounts:flags.8?Vector, terms_url:flags.10?string, subscription_period:flags.11?int) => Invoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/invoice
- Поля:
  - `flags`: `#` - служебное поле flags
  - `test`: `flags.0?true` - optional через flags.0
  - `name_requested`: `flags.1?true` - optional через flags.1
  - `phone_requested`: `flags.2?true` - optional через flags.2
  - `email_requested`: `flags.3?true` - optional через flags.3
  - `shipping_address_requested`: `flags.4?true` - optional через flags.4
  - `flexible`: `flags.5?true` - optional через flags.5
  - `phone_to_provider`: `flags.6?true` - optional через flags.6
  - `email_to_provider`: `flags.7?true` - optional через flags.7
  - `recurring`: `flags.9?true` - optional через flags.9
  - `currency`: `string`
  - `prices`: `Vector`
  - `max_tip_amount`: `flags.8?long` - optional через flags.8
  - `suggested_tip_amounts`: `flags.8?Vector` - optional через flags.8
  - `terms_url`: `flags.10?string` - optional через flags.10
  - `subscription_period`: `flags.11?int` - optional через flags.11

## `JSONObjectValue`

- Официальный тип: https://core.telegram.org/type/JSONObjectValue
- Количество constructors: **1**

### `jsonObjectValue`

- ID: `-1059185703` / `0xc0de1bd9`
- Сигнатура: `jsonObjectValue(key:string, value:JSONValue) => JSONObjectValue`
- Официальная страница конструктора: https://core.telegram.org/constructor/jsonObjectValue
- Поля:
  - `key`: `string`
  - `value`: `JSONValue`

## `JSONValue`

- Официальный тип: https://core.telegram.org/type/JSONValue
- Количество constructors: **6**

### `jsonArray`

- ID: `-146520221` / `0xf7444763`
- Сигнатура: `jsonArray(value:Vector) => JSONValue`
- Официальная страница конструктора: https://core.telegram.org/constructor/jsonArray
- Поля:
  - `value`: `Vector`

### `jsonBool`

- ID: `-952869270` / `0xc7345e6a`
- Сигнатура: `jsonBool(value:Bool) => JSONValue`
- Официальная страница конструктора: https://core.telegram.org/constructor/jsonBool
- Поля:
  - `value`: `Bool`

### `jsonNull`

- ID: `1064139624` / `0x3f6d7b68`
- Сигнатура: `jsonNull() => JSONValue`
- Официальная страница конструктора: https://core.telegram.org/constructor/jsonNull
- Поля:
  - Нет полей.

### `jsonNumber`

- ID: `736157604` / `0x2be0dfa4`
- Сигнатура: `jsonNumber(value:double) => JSONValue`
- Официальная страница конструктора: https://core.telegram.org/constructor/jsonNumber
- Поля:
  - `value`: `double`

### `jsonObject`

- ID: `-1715350371` / `0x99c1d49d`
- Сигнатура: `jsonObject(value:Vector) => JSONValue`
- Официальная страница конструктора: https://core.telegram.org/constructor/jsonObject
- Поля:
  - `value`: `Vector`

### `jsonString`

- ID: `-1222740358` / `0xb71e767a`
- Сигнатура: `jsonString(value:string) => JSONValue`
- Официальная страница конструктора: https://core.telegram.org/constructor/jsonString
- Поля:
  - `value`: `string`

## `KeyboardButton`

- Официальный тип: https://core.telegram.org/type/KeyboardButton
- Количество constructors: **18**

### `inputKeyboardButtonRequestPeer`

- ID: `-916050683` / `0xc9662d05`
- Сигнатура: `inputKeyboardButtonRequestPeer(flags:#, name_requested:flags.0?true, username_requested:flags.1?true, photo_requested:flags.2?true, text:string, button_id:int, peer_type:RequestPeerType, max_quantity:int) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputKeyboardButtonRequestPeer
- Поля:
  - `flags`: `#` - служебное поле flags
  - `name_requested`: `flags.0?true` - optional через flags.0
  - `username_requested`: `flags.1?true` - optional через flags.1
  - `photo_requested`: `flags.2?true` - optional через flags.2
  - `text`: `string`
  - `button_id`: `int`
  - `peer_type`: `RequestPeerType`
  - `max_quantity`: `int`

### `inputKeyboardButtonUrlAuth`

- ID: `-802258988` / `0xd02e7fd4`
- Сигнатура: `inputKeyboardButtonUrlAuth(flags:#, request_write_access:flags.0?true, text:string, fwd_text:flags.1?string, url:string, bot:InputUser) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputKeyboardButtonUrlAuth
- Поля:
  - `flags`: `#` - служебное поле flags
  - `request_write_access`: `flags.0?true` - optional через flags.0
  - `text`: `string`
  - `fwd_text`: `flags.1?string` - optional через flags.1
  - `url`: `string`
  - `bot`: `InputUser`

### `inputKeyboardButtonUserProfile`

- ID: `-376962181` / `0xe988037b`
- Сигнатура: `inputKeyboardButtonUserProfile(text:string, user_id:InputUser) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputKeyboardButtonUserProfile
- Поля:
  - `text`: `string`
  - `user_id`: `InputUser`

### `keyboardButton`

- ID: `-1560655744` / `0xa2fa4880`
- Сигнатура: `keyboardButton(text:string) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButton
- Поля:
  - `text`: `string`

### `keyboardButtonBuy`

- ID: `-1344716869` / `0xafd93fbb`
- Сигнатура: `keyboardButtonBuy(text:string) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonBuy
- Поля:
  - `text`: `string`

### `keyboardButtonCallback`

- ID: `901503851` / `0x35bbdb6b`
- Сигнатура: `keyboardButtonCallback(flags:#, requires_password:flags.0?true, text:string, data:bytes) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonCallback
- Поля:
  - `flags`: `#` - служебное поле flags
  - `requires_password`: `flags.0?true` - optional через flags.0
  - `text`: `string`
  - `data`: `bytes`

### `keyboardButtonCopy`

- ID: `1976723854` / `0x75d2698e`
- Сигнатура: `keyboardButtonCopy(text:string, copy_text:string) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonCopy
- Поля:
  - `text`: `string`
  - `copy_text`: `string`

### `keyboardButtonGame`

- ID: `1358175439` / `0x50f41ccf`
- Сигнатура: `keyboardButtonGame(text:string) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonGame
- Поля:
  - `text`: `string`

### `keyboardButtonRequestGeoLocation`

- ID: `-59151553` / `0xfc796b3f`
- Сигнатура: `keyboardButtonRequestGeoLocation(text:string) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonRequestGeoLocation
- Поля:
  - `text`: `string`

### `keyboardButtonRequestPeer`

- ID: `1406648280` / `0x53d7bfd8`
- Сигнатура: `keyboardButtonRequestPeer(text:string, button_id:int, peer_type:RequestPeerType, max_quantity:int) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonRequestPeer
- Поля:
  - `text`: `string`
  - `button_id`: `int`
  - `peer_type`: `RequestPeerType`
  - `max_quantity`: `int`

### `keyboardButtonRequestPhone`

- ID: `-1318425559` / `0xb16a6c29`
- Сигнатура: `keyboardButtonRequestPhone(text:string) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonRequestPhone
- Поля:
  - `text`: `string`

### `keyboardButtonRequestPoll`

- ID: `-1144565411` / `0xbbc7515d`
- Сигнатура: `keyboardButtonRequestPoll(flags:#, quiz:flags.0?Bool, text:string) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonRequestPoll
- Поля:
  - `flags`: `#` - служебное поле flags
  - `quiz`: `flags.0?Bool` - optional через flags.0
  - `text`: `string`

### `keyboardButtonSimpleWebView`

- ID: `-1598009252` / `0xa0c0505c`
- Сигнатура: `keyboardButtonSimpleWebView(text:string, url:string) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonSimpleWebView
- Поля:
  - `text`: `string`
  - `url`: `string`

### `keyboardButtonSwitchInline`

- ID: `-1816527947` / `0x93b9fbb5`
- Сигнатура: `keyboardButtonSwitchInline(flags:#, same_peer:flags.0?true, text:string, query:string, peer_types:flags.1?Vector) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonSwitchInline
- Поля:
  - `flags`: `#` - служебное поле flags
  - `same_peer`: `flags.0?true` - optional через flags.0
  - `text`: `string`
  - `query`: `string`
  - `peer_types`: `flags.1?Vector` - optional через flags.1

### `keyboardButtonUrl`

- ID: `629866245` / `0x258aff05`
- Сигнатура: `keyboardButtonUrl(text:string, url:string) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonUrl
- Поля:
  - `text`: `string`
  - `url`: `string`

### `keyboardButtonUrlAuth`

- ID: `280464681` / `0x10b78d29`
- Сигнатура: `keyboardButtonUrlAuth(flags:#, text:string, fwd_text:flags.0?string, url:string, button_id:int) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonUrlAuth
- Поля:
  - `flags`: `#` - служебное поле flags
  - `text`: `string`
  - `fwd_text`: `flags.0?string` - optional через flags.0
  - `url`: `string`
  - `button_id`: `int`

### `keyboardButtonUserProfile`

- ID: `814112961` / `0x308660c1`
- Сигнатура: `keyboardButtonUserProfile(text:string, user_id:long) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonUserProfile
- Поля:
  - `text`: `string`
  - `user_id`: `long`

### `keyboardButtonWebView`

- ID: `326529584` / `0x13767230`
- Сигнатура: `keyboardButtonWebView(text:string, url:string) => KeyboardButton`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonWebView
- Поля:
  - `text`: `string`
  - `url`: `string`

## `KeyboardButtonRow`

- Официальный тип: https://core.telegram.org/type/KeyboardButtonRow
- Количество constructors: **1**

### `keyboardButtonRow`

- ID: `2002815875` / `0x77608b83`
- Сигнатура: `keyboardButtonRow(buttons:Vector) => KeyboardButtonRow`
- Официальная страница конструктора: https://core.telegram.org/constructor/keyboardButtonRow
- Поля:
  - `buttons`: `Vector`

## `LabeledPrice`

- Официальный тип: https://core.telegram.org/type/LabeledPrice
- Количество constructors: **1**

### `labeledPrice`

- ID: `-886477832` / `0xcb296bf8`
- Сигнатура: `labeledPrice(label:string, amount:long) => LabeledPrice`
- Официальная страница конструктора: https://core.telegram.org/constructor/labeledPrice
- Поля:
  - `label`: `string`
  - `amount`: `long`

## `LangPackDifference`

- Официальный тип: https://core.telegram.org/type/LangPackDifference
- Количество constructors: **1**

### `langPackDifference`

- ID: `-209337866` / `0xf385c1f6`
- Сигнатура: `langPackDifference(lang_code:string, from_version:int, version:int, strings:Vector) => LangPackDifference`
- Официальная страница конструктора: https://core.telegram.org/constructor/langPackDifference
- Поля:
  - `lang_code`: `string`
  - `from_version`: `int`
  - `version`: `int`
  - `strings`: `Vector`

## `LangPackLanguage`

- Официальный тип: https://core.telegram.org/type/LangPackLanguage
- Количество constructors: **1**

### `langPackLanguage`

- ID: `-288727837` / `0xeeca5ce3`
- Сигнатура: `langPackLanguage(flags:#, official:flags.0?true, rtl:flags.2?true, beta:flags.3?true, name:string, native_name:string, lang_code:string, base_lang_code:flags.1?string, plural_code:string, strings_count:int, translated_count:int, translations_url:string) => LangPackLanguage`
- Официальная страница конструктора: https://core.telegram.org/constructor/langPackLanguage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `official`: `flags.0?true` - optional через flags.0
  - `rtl`: `flags.2?true` - optional через flags.2
  - `beta`: `flags.3?true` - optional через flags.3
  - `name`: `string`
  - `native_name`: `string`
  - `lang_code`: `string`
  - `base_lang_code`: `flags.1?string` - optional через flags.1
  - `plural_code`: `string`
  - `strings_count`: `int`
  - `translated_count`: `int`
  - `translations_url`: `string`

## `LangPackString`

- Официальный тип: https://core.telegram.org/type/LangPackString
- Количество constructors: **3**

### `langPackString`

- ID: `-892239370` / `0xcad181f6`
- Сигнатура: `langPackString(key:string, value:string) => LangPackString`
- Официальная страница конструктора: https://core.telegram.org/constructor/langPackString
- Поля:
  - `key`: `string`
  - `value`: `string`

### `langPackStringDeleted`

- ID: `695856818` / `0x2979eeb2`
- Сигнатура: `langPackStringDeleted(key:string) => LangPackString`
- Официальная страница конструктора: https://core.telegram.org/constructor/langPackStringDeleted
- Поля:
  - `key`: `string`

### `langPackStringPluralized`

- ID: `1816636575` / `0x6c47ac9f`
- Сигнатура: `langPackStringPluralized(flags:#, key:string, zero_value:flags.0?string, one_value:flags.1?string, two_value:flags.2?string, few_value:flags.3?string, many_value:flags.4?string, other_value:string) => LangPackString`
- Официальная страница конструктора: https://core.telegram.org/constructor/langPackStringPluralized
- Поля:
  - `flags`: `#` - служебное поле flags
  - `key`: `string`
  - `zero_value`: `flags.0?string` - optional через flags.0
  - `one_value`: `flags.1?string` - optional через flags.1
  - `two_value`: `flags.2?string` - optional через flags.2
  - `few_value`: `flags.3?string` - optional через flags.3
  - `many_value`: `flags.4?string` - optional через flags.4
  - `other_value`: `string`

## `MaskCoords`

- Официальный тип: https://core.telegram.org/type/MaskCoords
- Количество constructors: **1**

### `maskCoords`

- ID: `-1361650766` / `0xaed6dbb2`
- Сигнатура: `maskCoords(n:int, x:double, y:double, zoom:double) => MaskCoords`
- Официальная страница конструктора: https://core.telegram.org/constructor/maskCoords
- Поля:
  - `n`: `int`
  - `x`: `double`
  - `y`: `double`
  - `zoom`: `double`

## `MediaArea`

- Официальный тип: https://core.telegram.org/type/MediaArea
- Количество constructors: **9**

### `inputMediaAreaChannelPost`

- ID: `577893055` / `0x2271f2bf`
- Сигнатура: `inputMediaAreaChannelPost(coordinates:MediaAreaCoordinates, channel:InputChannel, msg_id:int) => MediaArea`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaAreaChannelPost
- Поля:
  - `coordinates`: `MediaAreaCoordinates`
  - `channel`: `InputChannel`
  - `msg_id`: `int`

### `inputMediaAreaVenue`

- ID: `-1300094593` / `0xb282217f`
- Сигнатура: `inputMediaAreaVenue(coordinates:MediaAreaCoordinates, query_id:long, result_id:string) => MediaArea`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMediaAreaVenue
- Поля:
  - `coordinates`: `MediaAreaCoordinates`
  - `query_id`: `long`
  - `result_id`: `string`

### `mediaAreaChannelPost`

- ID: `1996756655` / `0x770416af`
- Сигнатура: `mediaAreaChannelPost(coordinates:MediaAreaCoordinates, channel_id:long, msg_id:int) => MediaArea`
- Официальная страница конструктора: https://core.telegram.org/constructor/mediaAreaChannelPost
- Поля:
  - `coordinates`: `MediaAreaCoordinates`
  - `channel_id`: `long`
  - `msg_id`: `int`

### `mediaAreaGeoPoint`

- ID: `-891992787` / `0xcad5452d`
- Сигнатура: `mediaAreaGeoPoint(flags:#, coordinates:MediaAreaCoordinates, geo:GeoPoint, address:flags.0?GeoPointAddress) => MediaArea`
- Официальная страница конструктора: https://core.telegram.org/constructor/mediaAreaGeoPoint
- Поля:
  - `flags`: `#` - служебное поле flags
  - `coordinates`: `MediaAreaCoordinates`
  - `geo`: `GeoPoint`
  - `address`: `flags.0?GeoPointAddress` - optional через flags.0

### `mediaAreaStarGift`

- ID: `1468491885` / `0x5787686d`
- Сигнатура: `mediaAreaStarGift(coordinates:MediaAreaCoordinates, slug:string) => MediaArea`
- Официальная страница конструктора: https://core.telegram.org/constructor/mediaAreaStarGift
- Поля:
  - `coordinates`: `MediaAreaCoordinates`
  - `slug`: `string`

### `mediaAreaSuggestedReaction`

- ID: `340088945` / `0x14455871`
- Сигнатура: `mediaAreaSuggestedReaction(flags:#, dark:flags.0?true, flipped:flags.1?true, coordinates:MediaAreaCoordinates, reaction:Reaction) => MediaArea`
- Официальная страница конструктора: https://core.telegram.org/constructor/mediaAreaSuggestedReaction
- Поля:
  - `flags`: `#` - служебное поле flags
  - `dark`: `flags.0?true` - optional через flags.0
  - `flipped`: `flags.1?true` - optional через flags.1
  - `coordinates`: `MediaAreaCoordinates`
  - `reaction`: `Reaction`

### `mediaAreaUrl`

- ID: `926421125` / `0x37381085`
- Сигнатура: `mediaAreaUrl(coordinates:MediaAreaCoordinates, url:string) => MediaArea`
- Официальная страница конструктора: https://core.telegram.org/constructor/mediaAreaUrl
- Поля:
  - `coordinates`: `MediaAreaCoordinates`
  - `url`: `string`

### `mediaAreaVenue`

- ID: `-1098720356` / `0xbe82db9c`
- Сигнатура: `mediaAreaVenue(coordinates:MediaAreaCoordinates, geo:GeoPoint, title:string, address:string, provider:string, venue_id:string, venue_type:string) => MediaArea`
- Официальная страница конструктора: https://core.telegram.org/constructor/mediaAreaVenue
- Поля:
  - `coordinates`: `MediaAreaCoordinates`
  - `geo`: `GeoPoint`
  - `title`: `string`
  - `address`: `string`
  - `provider`: `string`
  - `venue_id`: `string`
  - `venue_type`: `string`

### `mediaAreaWeather`

- ID: `1235637404` / `0x49a6549c`
- Сигнатура: `mediaAreaWeather(coordinates:MediaAreaCoordinates, emoji:string, temperature_c:double, color:int) => MediaArea`
- Официальная страница конструктора: https://core.telegram.org/constructor/mediaAreaWeather
- Поля:
  - `coordinates`: `MediaAreaCoordinates`
  - `emoji`: `string`
  - `temperature_c`: `double`
  - `color`: `int`

## `MediaAreaCoordinates`

- Официальный тип: https://core.telegram.org/type/MediaAreaCoordinates
- Количество constructors: **1**

### `mediaAreaCoordinates`

- ID: `-808853502` / `0xcfc9e002`
- Сигнатура: `mediaAreaCoordinates(flags:#, x:double, y:double, w:double, h:double, rotation:double, radius:flags.0?double) => MediaAreaCoordinates`
- Официальная страница конструктора: https://core.telegram.org/constructor/mediaAreaCoordinates
- Поля:
  - `flags`: `#` - служебное поле flags
  - `x`: `double`
  - `y`: `double`
  - `w`: `double`
  - `h`: `double`
  - `rotation`: `double`
  - `radius`: `flags.0?double` - optional через flags.0

## `Message`

- Официальный тип: https://core.telegram.org/type/Message
- Количество constructors: **3**

### `message`

- ID: `-1743401272` / `0x9815cec8`
- Сигнатура: `message(flags:#, out:flags.1?true, mentioned:flags.4?true, media_unread:flags.5?true, silent:flags.13?true, post:flags.14?true, from_scheduled:flags.18?true, legacy:flags.19?true, edit_hide:flags.21?true, pinned:flags.24?true, noforwards:flags.26?true, invert_media:flags.27?true, flags2:#, offline:flags2.1?true, video_processing_pending:flags2.4?true, paid_suggested_post_stars:flags2.8?true, paid_suggested_post_ton:flags2.9?true, id:int, from_id:flags.8?Peer, from_boosts_applied:flags.29?int, peer_id:Peer, saved_peer_id:flags.28?Peer, fwd_from:flags.2?MessageFwdHeader, via_bot_id:flags.11?long, via_business_bot_id:flags2.0?long, reply_to:flags.3?MessageReplyHeader, date:int, message:string, media:flags.9?MessageMedia, reply_markup:flags.6?ReplyMarkup, entities:flags.7?Vector, views:flags.10?int, forwards:flags.10?int, replies:flags.23?MessageReplies, edit_date:flags.15?int, post_author:flags.16?string, grouped_id:flags.17?long, reactions:flags.20?MessageReactions, restriction_reason:flags.22?Vector, ttl_period:flags.25?int, quick_reply_shortcut_id:flags.30?int, effect:flags2.2?long, factcheck:flags2.3?FactCheck, report_delivery_until_date:flags2.5?int, paid_message_stars:flags2.6?long, suggested_post:flags2.7?SuggestedPost) => Message`
- Официальная страница конструктора: https://core.telegram.org/constructor/message
- Поля:
  - `flags`: `#` - служебное поле flags
  - `out`: `flags.1?true` - optional через flags.1
  - `mentioned`: `flags.4?true` - optional через flags.4
  - `media_unread`: `flags.5?true` - optional через flags.5
  - `silent`: `flags.13?true` - optional через flags.13
  - `post`: `flags.14?true` - optional через flags.14
  - `from_scheduled`: `flags.18?true` - optional через flags.18
  - `legacy`: `flags.19?true` - optional через flags.19
  - `edit_hide`: `flags.21?true` - optional через flags.21
  - `pinned`: `flags.24?true` - optional через flags.24
  - `noforwards`: `flags.26?true` - optional через flags.26
  - `invert_media`: `flags.27?true` - optional через flags.27
  - `flags2`: `#` - служебное поле flags
  - `offline`: `flags2.1?true` - optional через flags2.1
  - `video_processing_pending`: `flags2.4?true` - optional через flags2.4
  - `paid_suggested_post_stars`: `flags2.8?true` - optional через flags2.8
  - `paid_suggested_post_ton`: `flags2.9?true` - optional через flags2.9
  - `id`: `int`
  - `from_id`: `flags.8?Peer` - optional через flags.8
  - `from_boosts_applied`: `flags.29?int` - optional через flags.29
  - `peer_id`: `Peer`
  - `saved_peer_id`: `flags.28?Peer` - optional через flags.28
  - `fwd_from`: `flags.2?MessageFwdHeader` - optional через flags.2
  - `via_bot_id`: `flags.11?long` - optional через flags.11
  - `via_business_bot_id`: `flags2.0?long` - optional через flags2.0
  - `reply_to`: `flags.3?MessageReplyHeader` - optional через flags.3
  - `date`: `int`
  - `message`: `string`
  - `media`: `flags.9?MessageMedia` - optional через flags.9
  - `reply_markup`: `flags.6?ReplyMarkup` - optional через flags.6
  - `entities`: `flags.7?Vector` - optional через flags.7
  - `views`: `flags.10?int` - optional через flags.10
  - `forwards`: `flags.10?int` - optional через flags.10
  - `replies`: `flags.23?MessageReplies` - optional через flags.23
  - `edit_date`: `flags.15?int` - optional через flags.15
  - `post_author`: `flags.16?string` - optional через flags.16
  - `grouped_id`: `flags.17?long` - optional через flags.17
  - `reactions`: `flags.20?MessageReactions` - optional через flags.20
  - `restriction_reason`: `flags.22?Vector` - optional через flags.22
  - `ttl_period`: `flags.25?int` - optional через flags.25
  - `quick_reply_shortcut_id`: `flags.30?int` - optional через flags.30
  - `effect`: `flags2.2?long` - optional через flags2.2
  - `factcheck`: `flags2.3?FactCheck` - optional через flags2.3
  - `report_delivery_until_date`: `flags2.5?int` - optional через flags2.5
  - `paid_message_stars`: `flags2.6?long` - optional через flags2.6
  - `suggested_post`: `flags2.7?SuggestedPost` - optional через flags2.7

### `messageEmpty`

- ID: `-1868117372` / `0x90a6ca84`
- Сигнатура: `messageEmpty(flags:#, id:int, peer_id:flags.0?Peer) => Message`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEmpty
- Поля:
  - `flags`: `#` - служебное поле flags
  - `id`: `int`
  - `peer_id`: `flags.0?Peer` - optional через flags.0

### `messageService`

- ID: `2055212554` / `0x7a800e0a`
- Сигнатура: `messageService(flags:#, out:flags.1?true, mentioned:flags.4?true, media_unread:flags.5?true, reactions_are_possible:flags.9?true, silent:flags.13?true, post:flags.14?true, legacy:flags.19?true, id:int, from_id:flags.8?Peer, peer_id:Peer, saved_peer_id:flags.28?Peer, reply_to:flags.3?MessageReplyHeader, date:int, action:MessageAction, reactions:flags.20?MessageReactions, ttl_period:flags.25?int) => Message`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageService
- Поля:
  - `flags`: `#` - служебное поле flags
  - `out`: `flags.1?true` - optional через flags.1
  - `mentioned`: `flags.4?true` - optional через flags.4
  - `media_unread`: `flags.5?true` - optional через flags.5
  - `reactions_are_possible`: `flags.9?true` - optional через flags.9
  - `silent`: `flags.13?true` - optional через flags.13
  - `post`: `flags.14?true` - optional через flags.14
  - `legacy`: `flags.19?true` - optional через flags.19
  - `id`: `int`
  - `from_id`: `flags.8?Peer` - optional через flags.8
  - `peer_id`: `Peer`
  - `saved_peer_id`: `flags.28?Peer` - optional через flags.28
  - `reply_to`: `flags.3?MessageReplyHeader` - optional через flags.3
  - `date`: `int`
  - `action`: `MessageAction`
  - `reactions`: `flags.20?MessageReactions` - optional через flags.20
  - `ttl_period`: `flags.25?int` - optional через flags.25

## `MessageAction`

- Официальный тип: https://core.telegram.org/type/MessageAction
- Количество constructors: **57**

### `messageActionBoostApply`

- ID: `-872240531` / `0xcc02aa6d`
- Сигнатура: `messageActionBoostApply(boosts:int) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionBoostApply
- Поля:
  - `boosts`: `int`

### `messageActionBotAllowed`

- ID: `-988359047` / `0xc516d679`
- Сигнатура: `messageActionBotAllowed(flags:#, attach_menu:flags.1?true, from_request:flags.3?true, domain:flags.0?string, app:flags.2?BotApp) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionBotAllowed
- Поля:
  - `flags`: `#` - служебное поле flags
  - `attach_menu`: `flags.1?true` - optional через flags.1
  - `from_request`: `flags.3?true` - optional через flags.3
  - `domain`: `flags.0?string` - optional через flags.0
  - `app`: `flags.2?BotApp` - optional через flags.2

### `messageActionChannelCreate`

- ID: `-1781355374` / `0x95d2ac92`
- Сигнатура: `messageActionChannelCreate(title:string) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionChannelCreate
- Поля:
  - `title`: `string`

### `messageActionChannelMigrateFrom`

- ID: `-365344535` / `0xea3948e9`
- Сигнатура: `messageActionChannelMigrateFrom(title:string, chat_id:long) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionChannelMigrateFrom
- Поля:
  - `title`: `string`
  - `chat_id`: `long`

### `messageActionChatAddUser`

- ID: `365886720` / `0x15cefd00`
- Сигнатура: `messageActionChatAddUser(users:Vector) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionChatAddUser
- Поля:
  - `users`: `Vector`

### `messageActionChatCreate`

- ID: `-1119368275` / `0xbd47cbad`
- Сигнатура: `messageActionChatCreate(title:string, users:Vector) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionChatCreate
- Поля:
  - `title`: `string`
  - `users`: `Vector`

### `messageActionChatDeletePhoto`

- ID: `-1780220945` / `0x95e3fbef`
- Сигнатура: `messageActionChatDeletePhoto() => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionChatDeletePhoto
- Поля:
  - Нет полей.

### `messageActionChatDeleteUser`

- ID: `-1539362612` / `0xa43f30cc`
- Сигнатура: `messageActionChatDeleteUser(user_id:long) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionChatDeleteUser
- Поля:
  - `user_id`: `long`

### `messageActionChatEditPhoto`

- ID: `2144015272` / `0x7fcb13a8`
- Сигнатура: `messageActionChatEditPhoto(photo:Photo) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionChatEditPhoto
- Поля:
  - `photo`: `Photo`

### `messageActionChatEditTitle`

- ID: `-1247687078` / `0xb5a1ce5a`
- Сигнатура: `messageActionChatEditTitle(title:string) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionChatEditTitle
- Поля:
  - `title`: `string`

### `messageActionChatJoinedByLink`

- ID: `51520707` / `0x031224c3`
- Сигнатура: `messageActionChatJoinedByLink(inviter_id:long) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionChatJoinedByLink
- Поля:
  - `inviter_id`: `long`

### `messageActionChatJoinedByRequest`

- ID: `-339958837` / `0xebbca3cb`
- Сигнатура: `messageActionChatJoinedByRequest() => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionChatJoinedByRequest
- Поля:
  - Нет полей.

### `messageActionChatMigrateTo`

- ID: `-519864430` / `0xe1037f92`
- Сигнатура: `messageActionChatMigrateTo(channel_id:long) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionChatMigrateTo
- Поля:
  - `channel_id`: `long`

### `messageActionConferenceCall`

- ID: `805187450` / `0x2ffe2f7a`
- Сигнатура: `messageActionConferenceCall(flags:#, missed:flags.0?true, active:flags.1?true, video:flags.4?true, call_id:long, duration:flags.2?int, other_participants:flags.3?Vector) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionConferenceCall
- Поля:
  - `flags`: `#` - служебное поле flags
  - `missed`: `flags.0?true` - optional через flags.0
  - `active`: `flags.1?true` - optional через flags.1
  - `video`: `flags.4?true` - optional через flags.4
  - `call_id`: `long`
  - `duration`: `flags.2?int` - optional через flags.2
  - `other_participants`: `flags.3?Vector` - optional через flags.3

### `messageActionContactSignUp`

- ID: `-202219658` / `0xf3f25f76`
- Сигнатура: `messageActionContactSignUp() => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionContactSignUp
- Поля:
  - Нет полей.

### `messageActionCustomAction`

- ID: `-85549226` / `0xfae69f56`
- Сигнатура: `messageActionCustomAction(message:string) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionCustomAction
- Поля:
  - `message`: `string`

### `messageActionEmpty`

- ID: `-1230047312` / `0xb6aef7b0`
- Сигнатура: `messageActionEmpty() => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionEmpty
- Поля:
  - Нет полей.

### `messageActionGameScore`

- ID: `-1834538890` / `0x92a72876`
- Сигнатура: `messageActionGameScore(game_id:long, score:int) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionGameScore
- Поля:
  - `game_id`: `long`
  - `score`: `int`

### `messageActionGeoProximityReached`

- ID: `-1730095465` / `0x98e0d697`
- Сигнатура: `messageActionGeoProximityReached(from_id:Peer, to_id:Peer, distance:int) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionGeoProximityReached
- Поля:
  - `from_id`: `Peer`
  - `to_id`: `Peer`
  - `distance`: `int`

### `messageActionGiftCode`

- ID: `1456486804` / `0x56d03994`
- Сигнатура: `messageActionGiftCode(flags:#, via_giveaway:flags.0?true, unclaimed:flags.5?true, boost_peer:flags.1?Peer, months:int, slug:string, currency:flags.2?string, amount:flags.2?long, crypto_currency:flags.3?string, crypto_amount:flags.3?long, message:flags.4?TextWithEntities) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionGiftCode
- Поля:
  - `flags`: `#` - служебное поле flags
  - `via_giveaway`: `flags.0?true` - optional через flags.0
  - `unclaimed`: `flags.5?true` - optional через flags.5
  - `boost_peer`: `flags.1?Peer` - optional через flags.1
  - `months`: `int`
  - `slug`: `string`
  - `currency`: `flags.2?string` - optional через flags.2
  - `amount`: `flags.2?long` - optional через flags.2
  - `crypto_currency`: `flags.3?string` - optional через flags.3
  - `crypto_amount`: `flags.3?long` - optional через flags.3
  - `message`: `flags.4?TextWithEntities` - optional через flags.4

### `messageActionGiftPremium`

- ID: `1818391802` / `0x6c6274fa`
- Сигнатура: `messageActionGiftPremium(flags:#, currency:string, amount:long, months:int, crypto_currency:flags.0?string, crypto_amount:flags.0?long, message:flags.1?TextWithEntities) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionGiftPremium
- Поля:
  - `flags`: `#` - служебное поле flags
  - `currency`: `string`
  - `amount`: `long`
  - `months`: `int`
  - `crypto_currency`: `flags.0?string` - optional через flags.0
  - `crypto_amount`: `flags.0?long` - optional через flags.0
  - `message`: `flags.1?TextWithEntities` - optional через flags.1

### `messageActionGiftStars`

- ID: `1171632161` / `0x45d5b021`
- Сигнатура: `messageActionGiftStars(flags:#, currency:string, amount:long, stars:long, crypto_currency:flags.0?string, crypto_amount:flags.0?long, transaction_id:flags.1?string) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionGiftStars
- Поля:
  - `flags`: `#` - служебное поле flags
  - `currency`: `string`
  - `amount`: `long`
  - `stars`: `long`
  - `crypto_currency`: `flags.0?string` - optional через flags.0
  - `crypto_amount`: `flags.0?long` - optional через flags.0
  - `transaction_id`: `flags.1?string` - optional через flags.1

### `messageActionGiftTon`

- ID: `-1465661799` / `0xa8a3c699`
- Сигнатура: `messageActionGiftTon(flags:#, currency:string, amount:long, crypto_currency:string, crypto_amount:long, transaction_id:flags.0?string) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionGiftTon
- Поля:
  - `flags`: `#` - служебное поле flags
  - `currency`: `string`
  - `amount`: `long`
  - `crypto_currency`: `string`
  - `crypto_amount`: `long`
  - `transaction_id`: `flags.0?string` - optional через flags.0

### `messageActionGiveawayLaunch`

- ID: `-1475391004` / `0xa80f51e4`
- Сигнатура: `messageActionGiveawayLaunch(flags:#, stars:flags.0?long) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionGiveawayLaunch
- Поля:
  - `flags`: `#` - служебное поле flags
  - `stars`: `flags.0?long` - optional через flags.0

### `messageActionGiveawayResults`

- ID: `-2015170219` / `0x87e2f155`
- Сигнатура: `messageActionGiveawayResults(flags:#, stars:flags.0?true, winners_count:int, unclaimed_count:int) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionGiveawayResults
- Поля:
  - `flags`: `#` - служебное поле flags
  - `stars`: `flags.0?true` - optional через flags.0
  - `winners_count`: `int`
  - `unclaimed_count`: `int`

### `messageActionGroupCall`

- ID: `2047704898` / `0x7a0d7f42`
- Сигнатура: `messageActionGroupCall(flags:#, call:InputGroupCall, duration:flags.0?int) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionGroupCall
- Поля:
  - `flags`: `#` - служебное поле flags
  - `call`: `InputGroupCall`
  - `duration`: `flags.0?int` - optional через flags.0

### `messageActionGroupCallScheduled`

- ID: `-1281329567` / `0xb3a07661`
- Сигнатура: `messageActionGroupCallScheduled(call:InputGroupCall, schedule_date:int) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionGroupCallScheduled
- Поля:
  - `call`: `InputGroupCall`
  - `schedule_date`: `int`

### `messageActionHistoryClear`

- ID: `-1615153660` / `0x9fbab604`
- Сигнатура: `messageActionHistoryClear() => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionHistoryClear
- Поля:
  - Нет полей.

### `messageActionInviteToGroupCall`

- ID: `1345295095` / `0x502f92f7`
- Сигнатура: `messageActionInviteToGroupCall(call:InputGroupCall, users:Vector) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionInviteToGroupCall
- Поля:
  - `call`: `InputGroupCall`
  - `users`: `Vector`

### `messageActionPaidMessagesPrice`

- ID: `-2068281992` / `0x84b88578`
- Сигнатура: `messageActionPaidMessagesPrice(flags:#, broadcast_messages_allowed:flags.0?true, stars:long) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionPaidMessagesPrice
- Поля:
  - `flags`: `#` - служебное поле flags
  - `broadcast_messages_allowed`: `flags.0?true` - optional через flags.0
  - `stars`: `long`

### `messageActionPaidMessagesRefunded`

- ID: `-1407246387` / `0xac1f1fcd`
- Сигнатура: `messageActionPaidMessagesRefunded(count:int, stars:long) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionPaidMessagesRefunded
- Поля:
  - `count`: `int`
  - `stars`: `long`

### `messageActionPaymentRefunded`

- ID: `1102307842` / `0x41b3e202`
- Сигнатура: `messageActionPaymentRefunded(flags:#, peer:Peer, currency:string, total_amount:long, payload:flags.0?bytes, charge:PaymentCharge) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionPaymentRefunded
- Поля:
  - `flags`: `#` - служебное поле flags
  - `peer`: `Peer`
  - `currency`: `string`
  - `total_amount`: `long`
  - `payload`: `flags.0?bytes` - optional через flags.0
  - `charge`: `PaymentCharge`

### `messageActionPaymentSent`

- ID: `-970673810` / `0xc624b16e`
- Сигнатура: `messageActionPaymentSent(flags:#, recurring_init:flags.2?true, recurring_used:flags.3?true, currency:string, total_amount:long, invoice_slug:flags.0?string, subscription_until_date:flags.4?int) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionPaymentSent
- Поля:
  - `flags`: `#` - служебное поле flags
  - `recurring_init`: `flags.2?true` - optional через flags.2
  - `recurring_used`: `flags.3?true` - optional через flags.3
  - `currency`: `string`
  - `total_amount`: `long`
  - `invoice_slug`: `flags.0?string` - optional через flags.0
  - `subscription_until_date`: `flags.4?int` - optional через flags.4

### `messageActionPaymentSentMe`

- ID: `-6288180` / `0xffa00ccc`
- Сигнатура: `messageActionPaymentSentMe(flags:#, recurring_init:flags.2?true, recurring_used:flags.3?true, currency:string, total_amount:long, payload:bytes, info:flags.0?PaymentRequestedInfo, shipping_option_id:flags.1?string, charge:PaymentCharge, subscription_until_date:flags.4?int) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionPaymentSentMe
- Поля:
  - `flags`: `#` - служебное поле flags
  - `recurring_init`: `flags.2?true` - optional через flags.2
  - `recurring_used`: `flags.3?true` - optional через flags.3
  - `currency`: `string`
  - `total_amount`: `long`
  - `payload`: `bytes`
  - `info`: `flags.0?PaymentRequestedInfo` - optional через flags.0
  - `shipping_option_id`: `flags.1?string` - optional через flags.1
  - `charge`: `PaymentCharge`
  - `subscription_until_date`: `flags.4?int` - optional через flags.4

### `messageActionPhoneCall`

- ID: `-2132731265` / `0x80e11a7f`
- Сигнатура: `messageActionPhoneCall(flags:#, video:flags.2?true, call_id:long, reason:flags.0?PhoneCallDiscardReason, duration:flags.1?int) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionPhoneCall
- Поля:
  - `flags`: `#` - служебное поле flags
  - `video`: `flags.2?true` - optional через flags.2
  - `call_id`: `long`
  - `reason`: `flags.0?PhoneCallDiscardReason` - optional через flags.0
  - `duration`: `flags.1?int` - optional через flags.1

### `messageActionPinMessage`

- ID: `-1799538451` / `0x94bd38ed`
- Сигнатура: `messageActionPinMessage() => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionPinMessage
- Поля:
  - Нет полей.

### `messageActionPrizeStars`

- ID: `-1341372510` / `0xb00c47a2`
- Сигнатура: `messageActionPrizeStars(flags:#, unclaimed:flags.0?true, stars:long, transaction_id:string, boost_peer:Peer, giveaway_msg_id:int) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionPrizeStars
- Поля:
  - `flags`: `#` - служебное поле flags
  - `unclaimed`: `flags.0?true` - optional через flags.0
  - `stars`: `long`
  - `transaction_id`: `string`
  - `boost_peer`: `Peer`
  - `giveaway_msg_id`: `int`

### `messageActionRequestedPeer`

- ID: `827428507` / `0x31518e9b`
- Сигнатура: `messageActionRequestedPeer(button_id:int, peers:Vector) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionRequestedPeer
- Поля:
  - `button_id`: `int`
  - `peers`: `Vector`

### `messageActionRequestedPeerSentMe`

- ID: `-1816979384` / `0x93b31848`
- Сигнатура: `messageActionRequestedPeerSentMe(button_id:int, peers:Vector) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionRequestedPeerSentMe
- Поля:
  - `button_id`: `int`
  - `peers`: `Vector`

### `messageActionScreenshotTaken`

- ID: `1200788123` / `0x4792929b`
- Сигнатура: `messageActionScreenshotTaken() => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionScreenshotTaken
- Поля:
  - Нет полей.

### `messageActionSecureValuesSent`

- ID: `-648257196` / `0xd95c6154`
- Сигнатура: `messageActionSecureValuesSent(types:Vector) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionSecureValuesSent
- Поля:
  - `types`: `Vector`

### `messageActionSecureValuesSentMe`

- ID: `455635795` / `0x1b287353`
- Сигнатура: `messageActionSecureValuesSentMe(values:Vector, credentials:SecureCredentialsEncrypted) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionSecureValuesSentMe
- Поля:
  - `values`: `Vector`
  - `credentials`: `SecureCredentialsEncrypted`

### `messageActionSetChatTheme`

- ID: `-1189364422` / `0xb91bbd3a`
- Сигнатура: `messageActionSetChatTheme(theme:ChatTheme) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionSetChatTheme
- Поля:
  - `theme`: `ChatTheme`

### `messageActionSetChatWallPaper`

- ID: `1348510708` / `0x5060a3f4`
- Сигнатура: `messageActionSetChatWallPaper(flags:#, same:flags.0?true, for_both:flags.1?true, wallpaper:WallPaper) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionSetChatWallPaper
- Поля:
  - `flags`: `#` - служебное поле flags
  - `same`: `flags.0?true` - optional через flags.0
  - `for_both`: `flags.1?true` - optional через flags.1
  - `wallpaper`: `WallPaper`

### `messageActionSetMessagesTTL`

- ID: `1007897979` / `0x3c134d7b`
- Сигнатура: `messageActionSetMessagesTTL(flags:#, period:int, auto_setting_from:flags.0?long) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionSetMessagesTTL
- Поля:
  - `flags`: `#` - служебное поле flags
  - `period`: `int`
  - `auto_setting_from`: `flags.0?long` - optional через flags.0

### `messageActionStarGift`

- ID: `-229775366` / `0xf24de7fa`
- Сигнатура: `messageActionStarGift(flags:#, name_hidden:flags.0?true, saved:flags.2?true, converted:flags.3?true, upgraded:flags.5?true, refunded:flags.9?true, can_upgrade:flags.10?true, prepaid_upgrade:flags.13?true, upgrade_separate:flags.16?true, gift:StarGift, message:flags.1?TextWithEntities, convert_stars:flags.4?long, upgrade_msg_id:flags.5?int, upgrade_stars:flags.8?long, from_id:flags.11?Peer, peer:flags.12?Peer, saved_id:flags.12?long, prepaid_upgrade_hash:flags.14?string, gift_msg_id:flags.15?int) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionStarGift
- Поля:
  - `flags`: `#` - служебное поле flags
  - `name_hidden`: `flags.0?true` - optional через flags.0
  - `saved`: `flags.2?true` - optional через flags.2
  - `converted`: `flags.3?true` - optional через flags.3
  - `upgraded`: `flags.5?true` - optional через flags.5
  - `refunded`: `flags.9?true` - optional через flags.9
  - `can_upgrade`: `flags.10?true` - optional через flags.10
  - `prepaid_upgrade`: `flags.13?true` - optional через flags.13
  - `upgrade_separate`: `flags.16?true` - optional через flags.16
  - `gift`: `StarGift`
  - `message`: `flags.1?TextWithEntities` - optional через flags.1
  - `convert_stars`: `flags.4?long` - optional через flags.4
  - `upgrade_msg_id`: `flags.5?int` - optional через flags.5
  - `upgrade_stars`: `flags.8?long` - optional через flags.8
  - `from_id`: `flags.11?Peer` - optional через flags.11
  - `peer`: `flags.12?Peer` - optional через flags.12
  - `saved_id`: `flags.12?long` - optional через flags.12
  - `prepaid_upgrade_hash`: `flags.14?string` - optional через flags.14
  - `gift_msg_id`: `flags.15?int` - optional через flags.15

### `messageActionStarGiftUnique`

- ID: `888627955` / `0x34f762f3`
- Сигнатура: `messageActionStarGiftUnique(flags:#, upgrade:flags.0?true, transferred:flags.1?true, saved:flags.2?true, refunded:flags.5?true, prepaid_upgrade:flags.11?true, gift:StarGift, can_export_at:flags.3?int, transfer_stars:flags.4?long, from_id:flags.6?Peer, peer:flags.7?Peer, saved_id:flags.7?long, resale_amount:flags.8?StarsAmount, can_transfer_at:flags.9?int, can_resell_at:flags.10?int) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionStarGiftUnique
- Поля:
  - `flags`: `#` - служебное поле flags
  - `upgrade`: `flags.0?true` - optional через flags.0
  - `transferred`: `flags.1?true` - optional через flags.1
  - `saved`: `flags.2?true` - optional через flags.2
  - `refunded`: `flags.5?true` - optional через flags.5
  - `prepaid_upgrade`: `flags.11?true` - optional через flags.11
  - `gift`: `StarGift`
  - `can_export_at`: `flags.3?int` - optional через flags.3
  - `transfer_stars`: `flags.4?long` - optional через flags.4
  - `from_id`: `flags.6?Peer` - optional через flags.6
  - `peer`: `flags.7?Peer` - optional через flags.7
  - `saved_id`: `flags.7?long` - optional через flags.7
  - `resale_amount`: `flags.8?StarsAmount` - optional через flags.8
  - `can_transfer_at`: `flags.9?int` - optional через flags.9
  - `can_resell_at`: `flags.10?int` - optional через flags.10

### `messageActionSuggestProfilePhoto`

- ID: `1474192222` / `0x57de635e`
- Сигнатура: `messageActionSuggestProfilePhoto(photo:Photo) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionSuggestProfilePhoto
- Поля:
  - `photo`: `Photo`

### `messageActionSuggestedPostApproval`

- ID: `-293988970` / `0xee7a1596`
- Сигнатура: `messageActionSuggestedPostApproval(flags:#, rejected:flags.0?true, balance_too_low:flags.1?true, reject_comment:flags.2?string, schedule_date:flags.3?int, price:flags.4?StarsAmount) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionSuggestedPostApproval
- Поля:
  - `flags`: `#` - служебное поле flags
  - `rejected`: `flags.0?true` - optional через flags.0
  - `balance_too_low`: `flags.1?true` - optional через flags.1
  - `reject_comment`: `flags.2?string` - optional через flags.2
  - `schedule_date`: `flags.3?int` - optional через flags.3
  - `price`: `flags.4?StarsAmount` - optional через flags.4

### `messageActionSuggestedPostRefund`

- ID: `1777932024` / `0x69f916f8`
- Сигнатура: `messageActionSuggestedPostRefund(flags:#, payer_initiated:flags.0?true) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionSuggestedPostRefund
- Поля:
  - `flags`: `#` - служебное поле flags
  - `payer_initiated`: `flags.0?true` - optional через flags.0

### `messageActionSuggestedPostSuccess`

- ID: `-1780625559` / `0x95ddcf69`
- Сигнатура: `messageActionSuggestedPostSuccess(price:StarsAmount) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionSuggestedPostSuccess
- Поля:
  - `price`: `StarsAmount`

### `messageActionTodoAppendTasks`

- ID: `-940721021` / `0xc7edbc83`
- Сигнатура: `messageActionTodoAppendTasks(list:Vector) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionTodoAppendTasks
- Поля:
  - `list`: `Vector`

### `messageActionTodoCompletions`

- ID: `-864265079` / `0xcc7c5c89`
- Сигнатура: `messageActionTodoCompletions(completed:Vector, incompleted:Vector) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionTodoCompletions
- Поля:
  - `completed`: `Vector`
  - `incompleted`: `Vector`

### `messageActionTopicCreate`

- ID: `228168278` / `0x0d999256`
- Сигнатура: `messageActionTopicCreate(flags:#, title:string, icon_color:int, icon_emoji_id:flags.0?long) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionTopicCreate
- Поля:
  - `flags`: `#` - служебное поле flags
  - `title`: `string`
  - `icon_color`: `int`
  - `icon_emoji_id`: `flags.0?long` - optional через flags.0

### `messageActionTopicEdit`

- ID: `-1064024032` / `0xc0944820`
- Сигнатура: `messageActionTopicEdit(flags:#, title:flags.0?string, icon_emoji_id:flags.1?long, closed:flags.2?Bool, hidden:flags.3?Bool) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionTopicEdit
- Поля:
  - `flags`: `#` - служебное поле flags
  - `title`: `flags.0?string` - optional через flags.0
  - `icon_emoji_id`: `flags.1?long` - optional через flags.1
  - `closed`: `flags.2?Bool` - optional через flags.2
  - `hidden`: `flags.3?Bool` - optional через flags.3

### `messageActionWebViewDataSent`

- ID: `-1262252875` / `0xb4c38cb5`
- Сигнатура: `messageActionWebViewDataSent(text:string) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionWebViewDataSent
- Поля:
  - `text`: `string`

### `messageActionWebViewDataSentMe`

- ID: `1205698681` / `0x47dd8079`
- Сигнатура: `messageActionWebViewDataSentMe(text:string, data:string) => MessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageActionWebViewDataSentMe
- Поля:
  - `text`: `string`
  - `data`: `string`

## `MessageEntity`

- Официальный тип: https://core.telegram.org/type/MessageEntity
- Количество constructors: **21**

### `inputMessageEntityMentionName`

- ID: `546203849` / `0x208e68c9`
- Сигнатура: `inputMessageEntityMentionName(offset:int, length:int, user_id:InputUser) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessageEntityMentionName
- Поля:
  - `offset`: `int`
  - `length`: `int`
  - `user_id`: `InputUser`

### `messageEntityBankCard`

- ID: `1981704948` / `0x761e6af4`
- Сигнатура: `messageEntityBankCard(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityBankCard
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityBlockquote`

- ID: `-238245204` / `0xf1ccaaac`
- Сигнатура: `messageEntityBlockquote(flags:#, collapsed:flags.0?true, offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityBlockquote
- Поля:
  - `flags`: `#` - служебное поле flags
  - `collapsed`: `flags.0?true` - optional через flags.0
  - `offset`: `int`
  - `length`: `int`

### `messageEntityBold`

- ID: `-1117713463` / `0xbd610bc9`
- Сигнатура: `messageEntityBold(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityBold
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityBotCommand`

- ID: `1827637959` / `0x6cef8ac7`
- Сигнатура: `messageEntityBotCommand(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityBotCommand
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityCashtag`

- ID: `1280209983` / `0x4c4e743f`
- Сигнатура: `messageEntityCashtag(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityCashtag
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityCode`

- ID: `681706865` / `0x28a20571`
- Сигнатура: `messageEntityCode(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityCode
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityCustomEmoji`

- ID: `-925956616` / `0xc8cf05f8`
- Сигнатура: `messageEntityCustomEmoji(offset:int, length:int, document_id:long) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityCustomEmoji
- Поля:
  - `offset`: `int`
  - `length`: `int`
  - `document_id`: `long`

### `messageEntityEmail`

- ID: `1692693954` / `0x64e475c2`
- Сигнатура: `messageEntityEmail(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityEmail
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityHashtag`

- ID: `1868782349` / `0x6f635b0d`
- Сигнатура: `messageEntityHashtag(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityHashtag
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityItalic`

- ID: `-2106619040` / `0x826f8b60`
- Сигнатура: `messageEntityItalic(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityItalic
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityMention`

- ID: `-100378723` / `0xfa04579d`
- Сигнатура: `messageEntityMention(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityMention
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityMentionName`

- ID: `-595914432` / `0xdc7b1140`
- Сигнатура: `messageEntityMentionName(offset:int, length:int, user_id:long) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityMentionName
- Поля:
  - `offset`: `int`
  - `length`: `int`
  - `user_id`: `long`

### `messageEntityPhone`

- ID: `-1687559349` / `0x9b69e34b`
- Сигнатура: `messageEntityPhone(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityPhone
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityPre`

- ID: `1938967520` / `0x73924be0`
- Сигнатура: `messageEntityPre(offset:int, length:int, language:string) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityPre
- Поля:
  - `offset`: `int`
  - `length`: `int`
  - `language`: `string`

### `messageEntitySpoiler`

- ID: `852137487` / `0x32ca960f`
- Сигнатура: `messageEntitySpoiler(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntitySpoiler
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityStrike`

- ID: `-1090087980` / `0xbf0693d4`
- Сигнатура: `messageEntityStrike(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityStrike
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityTextUrl`

- ID: `1990644519` / `0x76a6d327`
- Сигнатура: `messageEntityTextUrl(offset:int, length:int, url:string) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityTextUrl
- Поля:
  - `offset`: `int`
  - `length`: `int`
  - `url`: `string`

### `messageEntityUnderline`

- ID: `-1672577397` / `0x9c4e7e8b`
- Сигнатура: `messageEntityUnderline(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityUnderline
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityUnknown`

- ID: `-1148011883` / `0xbb92ba95`
- Сигнатура: `messageEntityUnknown(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityUnknown
- Поля:
  - `offset`: `int`
  - `length`: `int`

### `messageEntityUrl`

- ID: `1859134776` / `0x6ed02538`
- Сигнатура: `messageEntityUrl(offset:int, length:int) => MessageEntity`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageEntityUrl
- Поля:
  - `offset`: `int`
  - `length`: `int`

## `MessageExtendedMedia`

- Официальный тип: https://core.telegram.org/type/MessageExtendedMedia
- Количество constructors: **2**

### `messageExtendedMedia`

- ID: `-297296796` / `0xee479c64`
- Сигнатура: `messageExtendedMedia(media:MessageMedia) => MessageExtendedMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageExtendedMedia
- Поля:
  - `media`: `MessageMedia`

### `messageExtendedMediaPreview`

- ID: `-1386050360` / `0xad628cc8`
- Сигнатура: `messageExtendedMediaPreview(flags:#, w:flags.0?int, h:flags.0?int, thumb:flags.1?PhotoSize, video_duration:flags.2?int) => MessageExtendedMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageExtendedMediaPreview
- Поля:
  - `flags`: `#` - служебное поле flags
  - `w`: `flags.0?int` - optional через flags.0
  - `h`: `flags.0?int` - optional через flags.0
  - `thumb`: `flags.1?PhotoSize` - optional через flags.1
  - `video_duration`: `flags.2?int` - optional через flags.2

## `MessageFwdHeader`

- Официальный тип: https://core.telegram.org/type/MessageFwdHeader
- Количество constructors: **1**

### `messageFwdHeader`

- ID: `1313731771` / `0x4e4df4bb`
- Сигнатура: `messageFwdHeader(flags:#, imported:flags.7?true, saved_out:flags.11?true, from_id:flags.0?Peer, from_name:flags.5?string, date:int, channel_post:flags.2?int, post_author:flags.3?string, saved_from_peer:flags.4?Peer, saved_from_msg_id:flags.4?int, saved_from_id:flags.8?Peer, saved_from_name:flags.9?string, saved_date:flags.10?int, psa_type:flags.6?string) => MessageFwdHeader`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageFwdHeader
- Поля:
  - `flags`: `#` - служебное поле flags
  - `imported`: `flags.7?true` - optional через flags.7
  - `saved_out`: `flags.11?true` - optional через flags.11
  - `from_id`: `flags.0?Peer` - optional через flags.0
  - `from_name`: `flags.5?string` - optional через flags.5
  - `date`: `int`
  - `channel_post`: `flags.2?int` - optional через flags.2
  - `post_author`: `flags.3?string` - optional через flags.3
  - `saved_from_peer`: `flags.4?Peer` - optional через flags.4
  - `saved_from_msg_id`: `flags.4?int` - optional через flags.4
  - `saved_from_id`: `flags.8?Peer` - optional через flags.8
  - `saved_from_name`: `flags.9?string` - optional через flags.9
  - `saved_date`: `flags.10?int` - optional через flags.10
  - `psa_type`: `flags.6?string` - optional через flags.6

## `MessageMedia`

- Официальный тип: https://core.telegram.org/type/MessageMedia
- Количество constructors: **18**

### `messageMediaContact`

- ID: `1882335561` / `0x70322949`
- Сигнатура: `messageMediaContact(phone_number:string, first_name:string, last_name:string, vcard:string, user_id:long) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaContact
- Поля:
  - `phone_number`: `string`
  - `first_name`: `string`
  - `last_name`: `string`
  - `vcard`: `string`
  - `user_id`: `long`

### `messageMediaDice`

- ID: `1065280907` / `0x3f7ee58b`
- Сигнатура: `messageMediaDice(value:int, emoticon:string) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaDice
- Поля:
  - `value`: `int`
  - `emoticon`: `string`

### `messageMediaDocument`

- ID: `1389939929` / `0x52d8ccd9`
- Сигнатура: `messageMediaDocument(flags:#, nopremium:flags.3?true, spoiler:flags.4?true, video:flags.6?true, round:flags.7?true, voice:flags.8?true, document:flags.0?Document, alt_documents:flags.5?Vector, video_cover:flags.9?Photo, video_timestamp:flags.10?int, ttl_seconds:flags.2?int) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaDocument
- Поля:
  - `flags`: `#` - служебное поле flags
  - `nopremium`: `flags.3?true` - optional через flags.3
  - `spoiler`: `flags.4?true` - optional через flags.4
  - `video`: `flags.6?true` - optional через flags.6
  - `round`: `flags.7?true` - optional через flags.7
  - `voice`: `flags.8?true` - optional через flags.8
  - `document`: `flags.0?Document` - optional через flags.0
  - `alt_documents`: `flags.5?Vector` - optional через flags.5
  - `video_cover`: `flags.9?Photo` - optional через flags.9
  - `video_timestamp`: `flags.10?int` - optional через flags.10
  - `ttl_seconds`: `flags.2?int` - optional через flags.2

### `messageMediaEmpty`

- ID: `1038967584` / `0x3ded6320`
- Сигнатура: `messageMediaEmpty() => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaEmpty
- Поля:
  - Нет полей.

### `messageMediaGame`

- ID: `-38694904` / `0xfdb19008`
- Сигнатура: `messageMediaGame(game:Game) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaGame
- Поля:
  - `game`: `Game`

### `messageMediaGeo`

- ID: `1457575028` / `0x56e0d474`
- Сигнатура: `messageMediaGeo(geo:GeoPoint) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaGeo
- Поля:
  - `geo`: `GeoPoint`

### `messageMediaGeoLive`

- ID: `-1186937242` / `0xb940c666`
- Сигнатура: `messageMediaGeoLive(flags:#, geo:GeoPoint, heading:flags.0?int, period:int, proximity_notification_radius:flags.1?int) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaGeoLive
- Поля:
  - `flags`: `#` - служебное поле flags
  - `geo`: `GeoPoint`
  - `heading`: `flags.0?int` - optional через flags.0
  - `period`: `int`
  - `proximity_notification_radius`: `flags.1?int` - optional через flags.1

### `messageMediaGiveaway`

- ID: `-1442366485` / `0xaa073beb`
- Сигнатура: `messageMediaGiveaway(flags:#, only_new_subscribers:flags.0?true, winners_are_visible:flags.2?true, channels:Vector, countries_iso2:flags.1?Vector, prize_description:flags.3?string, quantity:int, months:flags.4?int, stars:flags.5?long, until_date:int) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaGiveaway
- Поля:
  - `flags`: `#` - служебное поле flags
  - `only_new_subscribers`: `flags.0?true` - optional через flags.0
  - `winners_are_visible`: `flags.2?true` - optional через flags.2
  - `channels`: `Vector`
  - `countries_iso2`: `flags.1?Vector` - optional через flags.1
  - `prize_description`: `flags.3?string` - optional через flags.3
  - `quantity`: `int`
  - `months`: `flags.4?int` - optional через flags.4
  - `stars`: `flags.5?long` - optional через flags.5
  - `until_date`: `int`

### `messageMediaGiveawayResults`

- ID: `-827703647` / `0xceaa3ea1`
- Сигнатура: `messageMediaGiveawayResults(flags:#, only_new_subscribers:flags.0?true, refunded:flags.2?true, channel_id:long, additional_peers_count:flags.3?int, launch_msg_id:int, winners_count:int, unclaimed_count:int, winners:Vector, months:flags.4?int, stars:flags.5?long, prize_description:flags.1?string, until_date:int) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaGiveawayResults
- Поля:
  - `flags`: `#` - служебное поле flags
  - `only_new_subscribers`: `flags.0?true` - optional через flags.0
  - `refunded`: `flags.2?true` - optional через flags.2
  - `channel_id`: `long`
  - `additional_peers_count`: `flags.3?int` - optional через flags.3
  - `launch_msg_id`: `int`
  - `winners_count`: `int`
  - `unclaimed_count`: `int`
  - `winners`: `Vector`
  - `months`: `flags.4?int` - optional через flags.4
  - `stars`: `flags.5?long` - optional через flags.5
  - `prize_description`: `flags.1?string` - optional через flags.1
  - `until_date`: `int`

### `messageMediaInvoice`

- ID: `-156940077` / `0xf6a548d3`
- Сигнатура: `messageMediaInvoice(flags:#, shipping_address_requested:flags.1?true, test:flags.3?true, title:string, description:string, photo:flags.0?WebDocument, receipt_msg_id:flags.2?int, currency:string, total_amount:long, start_param:string, extended_media:flags.4?MessageExtendedMedia) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaInvoice
- Поля:
  - `flags`: `#` - служебное поле flags
  - `shipping_address_requested`: `flags.1?true` - optional через flags.1
  - `test`: `flags.3?true` - optional через flags.3
  - `title`: `string`
  - `description`: `string`
  - `photo`: `flags.0?WebDocument` - optional через flags.0
  - `receipt_msg_id`: `flags.2?int` - optional через flags.2
  - `currency`: `string`
  - `total_amount`: `long`
  - `start_param`: `string`
  - `extended_media`: `flags.4?MessageExtendedMedia` - optional через flags.4

### `messageMediaPaidMedia`

- ID: `-1467669359` / `0xa8852491`
- Сигнатура: `messageMediaPaidMedia(stars_amount:long, extended_media:Vector) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaPaidMedia
- Поля:
  - `stars_amount`: `long`
  - `extended_media`: `Vector`

### `messageMediaPhoto`

- ID: `1766936791` / `0x695150d7`
- Сигнатура: `messageMediaPhoto(flags:#, spoiler:flags.3?true, photo:flags.0?Photo, ttl_seconds:flags.2?int) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaPhoto
- Поля:
  - `flags`: `#` - служебное поле flags
  - `spoiler`: `flags.3?true` - optional через flags.3
  - `photo`: `flags.0?Photo` - optional через flags.0
  - `ttl_seconds`: `flags.2?int` - optional через flags.2

### `messageMediaPoll`

- ID: `1272375192` / `0x4bd6e798`
- Сигнатура: `messageMediaPoll(poll:Poll, results:PollResults) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaPoll
- Поля:
  - `poll`: `Poll`
  - `results`: `PollResults`

### `messageMediaStory`

- ID: `1758159491` / `0x68cb6283`
- Сигнатура: `messageMediaStory(flags:#, via_mention:flags.1?true, peer:Peer, id:int, story:flags.0?StoryItem) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaStory
- Поля:
  - `flags`: `#` - служебное поле flags
  - `via_mention`: `flags.1?true` - optional через flags.1
  - `peer`: `Peer`
  - `id`: `int`
  - `story`: `flags.0?StoryItem` - optional через flags.0

### `messageMediaToDo`

- ID: `-1974226924` / `0x8a53b014`
- Сигнатура: `messageMediaToDo(flags:#, todo:TodoList, completions:flags.0?Vector) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaToDo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `todo`: `TodoList`
  - `completions`: `flags.0?Vector` - optional через flags.0

### `messageMediaUnsupported`

- ID: `-1618676578` / `0x9f84f49e`
- Сигнатура: `messageMediaUnsupported() => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaUnsupported
- Поля:
  - Нет полей.

### `messageMediaVenue`

- ID: `784356159` / `0x2ec0533f`
- Сигнатура: `messageMediaVenue(geo:GeoPoint, title:string, address:string, provider:string, venue_id:string, venue_type:string) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaVenue
- Поля:
  - `geo`: `GeoPoint`
  - `title`: `string`
  - `address`: `string`
  - `provider`: `string`
  - `venue_id`: `string`
  - `venue_type`: `string`

### `messageMediaWebPage`

- ID: `-571405253` / `0xddf10c3b`
- Сигнатура: `messageMediaWebPage(flags:#, force_large_media:flags.0?true, force_small_media:flags.1?true, manual:flags.3?true, safe:flags.4?true, webpage:WebPage) => MessageMedia`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageMediaWebPage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `force_large_media`: `flags.0?true` - optional через flags.0
  - `force_small_media`: `flags.1?true` - optional через flags.1
  - `manual`: `flags.3?true` - optional через flags.3
  - `safe`: `flags.4?true` - optional через flags.4
  - `webpage`: `WebPage`

## `MessagePeerReaction`

- Официальный тип: https://core.telegram.org/type/MessagePeerReaction
- Количество constructors: **1**

### `messagePeerReaction`

- ID: `-1938180548` / `0x8c79b63c`
- Сигнатура: `messagePeerReaction(flags:#, big:flags.0?true, unread:flags.1?true, my:flags.2?true, peer_id:Peer, date:int, reaction:Reaction) => MessagePeerReaction`
- Официальная страница конструктора: https://core.telegram.org/constructor/messagePeerReaction
- Поля:
  - `flags`: `#` - служебное поле flags
  - `big`: `flags.0?true` - optional через flags.0
  - `unread`: `flags.1?true` - optional через flags.1
  - `my`: `flags.2?true` - optional через flags.2
  - `peer_id`: `Peer`
  - `date`: `int`
  - `reaction`: `Reaction`

## `MessagePeerVote`

- Официальный тип: https://core.telegram.org/type/MessagePeerVote
- Количество constructors: **3**

### `messagePeerVote`

- ID: `-1228133028` / `0xb6cc2d5c`
- Сигнатура: `messagePeerVote(peer:Peer, option:bytes, date:int) => MessagePeerVote`
- Официальная страница конструктора: https://core.telegram.org/constructor/messagePeerVote
- Поля:
  - `peer`: `Peer`
  - `option`: `bytes`
  - `date`: `int`

### `messagePeerVoteInputOption`

- ID: `1959634180` / `0x74cda504`
- Сигнатура: `messagePeerVoteInputOption(peer:Peer, date:int) => MessagePeerVote`
- Официальная страница конструктора: https://core.telegram.org/constructor/messagePeerVoteInputOption
- Поля:
  - `peer`: `Peer`
  - `date`: `int`

### `messagePeerVoteMultiple`

- ID: `1177089766` / `0x4628f6e6`
- Сигнатура: `messagePeerVoteMultiple(peer:Peer, options:Vector, date:int) => MessagePeerVote`
- Официальная страница конструктора: https://core.telegram.org/constructor/messagePeerVoteMultiple
- Поля:
  - `peer`: `Peer`
  - `options`: `Vector`
  - `date`: `int`

## `MessageRange`

- Официальный тип: https://core.telegram.org/type/MessageRange
- Количество constructors: **1**

### `messageRange`

- ID: `182649427` / `0x0ae30253`
- Сигнатура: `messageRange(min_id:int, max_id:int) => MessageRange`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageRange
- Поля:
  - `min_id`: `int`
  - `max_id`: `int`

## `MessageReactions`

- Официальный тип: https://core.telegram.org/type/MessageReactions
- Количество constructors: **1**

### `messageReactions`

- ID: `171155211` / `0x0a339f0b`
- Сигнатура: `messageReactions(flags:#, min:flags.0?true, can_see_list:flags.2?true, reactions_as_tags:flags.3?true, results:Vector, recent_reactions:flags.1?Vector, top_reactors:flags.4?Vector) => MessageReactions`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageReactions
- Поля:
  - `flags`: `#` - служебное поле flags
  - `min`: `flags.0?true` - optional через flags.0
  - `can_see_list`: `flags.2?true` - optional через flags.2
  - `reactions_as_tags`: `flags.3?true` - optional через flags.3
  - `results`: `Vector`
  - `recent_reactions`: `flags.1?Vector` - optional через flags.1
  - `top_reactors`: `flags.4?Vector` - optional через flags.4

## `MessageReactor`

- Официальный тип: https://core.telegram.org/type/MessageReactor
- Количество constructors: **1**

### `messageReactor`

- ID: `1269016922` / `0x4ba3a95a`
- Сигнатура: `messageReactor(flags:#, top:flags.0?true, my:flags.1?true, anonymous:flags.2?true, peer_id:flags.3?Peer, count:int) => MessageReactor`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageReactor
- Поля:
  - `flags`: `#` - служебное поле flags
  - `top`: `flags.0?true` - optional через flags.0
  - `my`: `flags.1?true` - optional через flags.1
  - `anonymous`: `flags.2?true` - optional через flags.2
  - `peer_id`: `flags.3?Peer` - optional через flags.3
  - `count`: `int`

## `MessageReplies`

- Официальный тип: https://core.telegram.org/type/MessageReplies
- Количество constructors: **1**

### `messageReplies`

- ID: `-2083123262` / `0x83d60fc2`
- Сигнатура: `messageReplies(flags:#, comments:flags.0?true, replies:int, replies_pts:int, recent_repliers:flags.1?Vector, channel_id:flags.0?long, max_id:flags.2?int, read_max_id:flags.3?int) => MessageReplies`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageReplies
- Поля:
  - `flags`: `#` - служебное поле flags
  - `comments`: `flags.0?true` - optional через flags.0
  - `replies`: `int`
  - `replies_pts`: `int`
  - `recent_repliers`: `flags.1?Vector` - optional через flags.1
  - `channel_id`: `flags.0?long` - optional через flags.0
  - `max_id`: `flags.2?int` - optional через flags.2
  - `read_max_id`: `flags.3?int` - optional через flags.3

## `MessageReplyHeader`

- Официальный тип: https://core.telegram.org/type/MessageReplyHeader
- Количество constructors: **2**

### `messageReplyHeader`

- ID: `1763137035` / `0x6917560b`
- Сигнатура: `messageReplyHeader(flags:#, reply_to_scheduled:flags.2?true, forum_topic:flags.3?true, quote:flags.9?true, reply_to_msg_id:flags.4?int, reply_to_peer_id:flags.0?Peer, reply_from:flags.5?MessageFwdHeader, reply_media:flags.8?MessageMedia, reply_to_top_id:flags.1?int, quote_text:flags.6?string, quote_entities:flags.7?Vector, quote_offset:flags.10?int, todo_item_id:flags.11?int) => MessageReplyHeader`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageReplyHeader
- Поля:
  - `flags`: `#` - служебное поле flags
  - `reply_to_scheduled`: `flags.2?true` - optional через flags.2
  - `forum_topic`: `flags.3?true` - optional через flags.3
  - `quote`: `flags.9?true` - optional через flags.9
  - `reply_to_msg_id`: `flags.4?int` - optional через flags.4
  - `reply_to_peer_id`: `flags.0?Peer` - optional через flags.0
  - `reply_from`: `flags.5?MessageFwdHeader` - optional через flags.5
  - `reply_media`: `flags.8?MessageMedia` - optional через flags.8
  - `reply_to_top_id`: `flags.1?int` - optional через flags.1
  - `quote_text`: `flags.6?string` - optional через flags.6
  - `quote_entities`: `flags.7?Vector` - optional через flags.7
  - `quote_offset`: `flags.10?int` - optional через flags.10
  - `todo_item_id`: `flags.11?int` - optional через flags.11

### `messageReplyStoryHeader`

- ID: `240843065` / `0x0e5af939`
- Сигнатура: `messageReplyStoryHeader(peer:Peer, story_id:int) => MessageReplyHeader`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageReplyStoryHeader
- Поля:
  - `peer`: `Peer`
  - `story_id`: `int`

## `MessageReportOption`

- Официальный тип: https://core.telegram.org/type/MessageReportOption
- Количество constructors: **1**

### `messageReportOption`

- ID: `2030298073` / `0x7903e3d9`
- Сигнатура: `messageReportOption(text:string, option:bytes) => MessageReportOption`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageReportOption
- Поля:
  - `text`: `string`
  - `option`: `bytes`

## `MessageViews`

- Официальный тип: https://core.telegram.org/type/MessageViews
- Количество constructors: **1**

### `messageViews`

- ID: `1163625789` / `0x455b853d`
- Сигнатура: `messageViews(flags:#, views:flags.0?int, forwards:flags.1?int, replies:flags.2?MessageReplies) => MessageViews`
- Официальная страница конструктора: https://core.telegram.org/constructor/messageViews
- Поля:
  - `flags`: `#` - служебное поле flags
  - `views`: `flags.0?int` - optional через flags.0
  - `forwards`: `flags.1?int` - optional через flags.1
  - `replies`: `flags.2?MessageReplies` - optional через flags.2

## `MessagesFilter`

- Официальный тип: https://core.telegram.org/type/MessagesFilter
- Количество constructors: **17**

### `inputMessagesFilterChatPhotos`

- ID: `975236280` / `0x3a20ecb8`
- Сигнатура: `inputMessagesFilterChatPhotos() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterChatPhotos
- Поля:
  - Нет полей.

### `inputMessagesFilterContacts`

- ID: `-530392189` / `0xe062db83`
- Сигнатура: `inputMessagesFilterContacts() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterContacts
- Поля:
  - Нет полей.

### `inputMessagesFilterDocument`

- ID: `-1629621880` / `0x9eddf188`
- Сигнатура: `inputMessagesFilterDocument() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterDocument
- Поля:
  - Нет полей.

### `inputMessagesFilterEmpty`

- ID: `1474492012` / `0x57e2f66c`
- Сигнатура: `inputMessagesFilterEmpty() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterEmpty
- Поля:
  - Нет полей.

### `inputMessagesFilterGeo`

- ID: `-419271411` / `0xe7026d0d`
- Сигнатура: `inputMessagesFilterGeo() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterGeo
- Поля:
  - Нет полей.

### `inputMessagesFilterGif`

- ID: `-3644025` / `0xffc86587`
- Сигнатура: `inputMessagesFilterGif() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterGif
- Поля:
  - Нет полей.

### `inputMessagesFilterMusic`

- ID: `928101534` / `0x3751b49e`
- Сигнатура: `inputMessagesFilterMusic() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterMusic
- Поля:
  - Нет полей.

### `inputMessagesFilterMyMentions`

- ID: `-1040652646` / `0xc1f8e69a`
- Сигнатура: `inputMessagesFilterMyMentions() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterMyMentions
- Поля:
  - Нет полей.

### `inputMessagesFilterPhoneCalls`

- ID: `-2134272152` / `0x80c99768`
- Сигнатура: `inputMessagesFilterPhoneCalls(flags:#, missed:flags.0?true) => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterPhoneCalls
- Поля:
  - `flags`: `#` - служебное поле flags
  - `missed`: `flags.0?true` - optional через flags.0

### `inputMessagesFilterPhotoVideo`

- ID: `1458172132` / `0x56e9f0e4`
- Сигнатура: `inputMessagesFilterPhotoVideo() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterPhotoVideo
- Поля:
  - Нет полей.

### `inputMessagesFilterPhotos`

- ID: `-1777752804` / `0x9609a51c`
- Сигнатура: `inputMessagesFilterPhotos() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterPhotos
- Поля:
  - Нет полей.

### `inputMessagesFilterPinned`

- ID: `464520273` / `0x1bb00451`
- Сигнатура: `inputMessagesFilterPinned() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterPinned
- Поля:
  - Нет полей.

### `inputMessagesFilterRoundVideo`

- ID: `-1253451181` / `0xb549da53`
- Сигнатура: `inputMessagesFilterRoundVideo() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterRoundVideo
- Поля:
  - Нет полей.

### `inputMessagesFilterRoundVoice`

- ID: `2054952868` / `0x7a7c17a4`
- Сигнатура: `inputMessagesFilterRoundVoice() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterRoundVoice
- Поля:
  - Нет полей.

### `inputMessagesFilterUrl`

- ID: `2129714567` / `0x7ef0dd87`
- Сигнатура: `inputMessagesFilterUrl() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterUrl
- Поля:
  - Нет полей.

### `inputMessagesFilterVideo`

- ID: `-1614803355` / `0x9fc00e65`
- Сигнатура: `inputMessagesFilterVideo() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterVideo
- Поля:
  - Нет полей.

### `inputMessagesFilterVoice`

- ID: `1358283666` / `0x50f5c392`
- Сигнатура: `inputMessagesFilterVoice() => MessagesFilter`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputMessagesFilterVoice
- Поля:
  - Нет полей.

## `MissingInvitee`

- Официальный тип: https://core.telegram.org/type/MissingInvitee
- Количество constructors: **1**

### `missingInvitee`

- ID: `1653379620` / `0x628c9224`
- Сигнатура: `missingInvitee(flags:#, premium_would_allow_invite:flags.0?true, premium_required_for_pm:flags.1?true, user_id:long) => MissingInvitee`
- Официальная страница конструктора: https://core.telegram.org/constructor/missingInvitee
- Поля:
  - `flags`: `#` - служебное поле flags
  - `premium_would_allow_invite`: `flags.0?true` - optional через flags.0
  - `premium_required_for_pm`: `flags.1?true` - optional через flags.1
  - `user_id`: `long`

## `MyBoost`

- Официальный тип: https://core.telegram.org/type/MyBoost
- Количество constructors: **1**

### `myBoost`

- ID: `-1001897636` / `0xc448415c`
- Сигнатура: `myBoost(flags:#, slot:int, peer:flags.0?Peer, date:int, expires:int, cooldown_until_date:flags.1?int) => MyBoost`
- Официальная страница конструктора: https://core.telegram.org/constructor/myBoost
- Поля:
  - `flags`: `#` - служебное поле flags
  - `slot`: `int`
  - `peer`: `flags.0?Peer` - optional через flags.0
  - `date`: `int`
  - `expires`: `int`
  - `cooldown_until_date`: `flags.1?int` - optional через flags.1

## `NearestDc`

- Официальный тип: https://core.telegram.org/type/NearestDc
- Количество constructors: **1**

### `nearestDc`

- ID: `-1910892683` / `0x8e1a1775`
- Сигнатура: `nearestDc(country:string, this_dc:int, nearest_dc:int) => NearestDc`
- Официальная страница конструктора: https://core.telegram.org/constructor/nearestDc
- Поля:
  - `country`: `string`
  - `this_dc`: `int`
  - `nearest_dc`: `int`

## `NotificationSound`

- Официальный тип: https://core.telegram.org/type/NotificationSound
- Количество constructors: **4**

### `notificationSoundDefault`

- ID: `-1746354498` / `0x97e8bebe`
- Сигнатура: `notificationSoundDefault() => NotificationSound`
- Официальная страница конструктора: https://core.telegram.org/constructor/notificationSoundDefault
- Поля:
  - Нет полей.

### `notificationSoundLocal`

- ID: `-2096391452` / `0x830b9ae4`
- Сигнатура: `notificationSoundLocal(title:string, data:string) => NotificationSound`
- Официальная страница конструктора: https://core.telegram.org/constructor/notificationSoundLocal
- Поля:
  - `title`: `string`
  - `data`: `string`

### `notificationSoundNone`

- ID: `1863070943` / `0x6f0c34df`
- Сигнатура: `notificationSoundNone() => NotificationSound`
- Официальная страница конструктора: https://core.telegram.org/constructor/notificationSoundNone
- Поля:
  - Нет полей.

### `notificationSoundRingtone`

- ID: `-9666487` / `0xff6c8049`
- Сигнатура: `notificationSoundRingtone(id:long) => NotificationSound`
- Официальная страница конструктора: https://core.telegram.org/constructor/notificationSoundRingtone
- Поля:
  - `id`: `long`

## `NotifyPeer`

- Официальный тип: https://core.telegram.org/type/NotifyPeer
- Количество constructors: **5**

### `notifyBroadcasts`

- ID: `-703403793` / `0xd612e8ef`
- Сигнатура: `notifyBroadcasts() => NotifyPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/notifyBroadcasts
- Поля:
  - Нет полей.

### `notifyChats`

- ID: `-1073230141` / `0xc007cec3`
- Сигнатура: `notifyChats() => NotifyPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/notifyChats
- Поля:
  - Нет полей.

### `notifyForumTopic`

- ID: `577659656` / `0x226e6308`
- Сигнатура: `notifyForumTopic(peer:Peer, top_msg_id:int) => NotifyPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/notifyForumTopic
- Поля:
  - `peer`: `Peer`
  - `top_msg_id`: `int`

### `notifyPeer`

- ID: `-1613493288` / `0x9fd40bd8`
- Сигнатура: `notifyPeer(peer:Peer) => NotifyPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/notifyPeer
- Поля:
  - `peer`: `Peer`

### `notifyUsers`

- ID: `-1261946036` / `0xb4c83b4c`
- Сигнатура: `notifyUsers() => NotifyPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/notifyUsers
- Поля:
  - Нет полей.

## `Null`

- Официальный тип: https://core.telegram.org/type/Null
- Количество constructors: **1**

### `null`

- ID: `1450380236` / `0x56730bcc`
- Сигнатура: `null() => Null`
- Официальная страница конструктора: https://core.telegram.org/constructor/null
- Поля:
  - Нет полей.

## `OutboxReadDate`

- Официальный тип: https://core.telegram.org/type/OutboxReadDate
- Количество constructors: **1**

### `outboxReadDate`

- ID: `1001931436` / `0x3bb842ac`
- Сигнатура: `outboxReadDate(date:int) => OutboxReadDate`
- Официальная страница конструктора: https://core.telegram.org/constructor/outboxReadDate
- Поля:
  - `date`: `int`

## `Page`

- Официальный тип: https://core.telegram.org/type/Page
- Количество constructors: **1**

### `page`

- ID: `-1738178803` / `0x98657f0d`
- Сигнатура: `page(flags:#, part:flags.0?true, rtl:flags.1?true, v2:flags.2?true, url:string, blocks:Vector, photos:Vector, documents:Vector, views:flags.3?int) => Page`
- Официальная страница конструктора: https://core.telegram.org/constructor/page
- Поля:
  - `flags`: `#` - служебное поле flags
  - `part`: `flags.0?true` - optional через flags.0
  - `rtl`: `flags.1?true` - optional через flags.1
  - `v2`: `flags.2?true` - optional через flags.2
  - `url`: `string`
  - `blocks`: `Vector`
  - `photos`: `Vector`
  - `documents`: `Vector`
  - `views`: `flags.3?int` - optional через flags.3

## `PageBlock`

- Официальный тип: https://core.telegram.org/type/PageBlock
- Количество constructors: **29**

### `pageBlockAnchor`

- ID: `-837994576` / `0xce0d37b0`
- Сигнатура: `pageBlockAnchor(name:string) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockAnchor
- Поля:
  - `name`: `string`

### `pageBlockAudio`

- ID: `-2143067670` / `0x804361ea`
- Сигнатура: `pageBlockAudio(audio_id:long, caption:PageCaption) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockAudio
- Поля:
  - `audio_id`: `long`
  - `caption`: `PageCaption`

### `pageBlockAuthorDate`

- ID: `-1162877472` / `0xbaafe5e0`
- Сигнатура: `pageBlockAuthorDate(author:RichText, published_date:int) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockAuthorDate
- Поля:
  - `author`: `RichText`
  - `published_date`: `int`

### `pageBlockBlockquote`

- ID: `641563686` / `0x263d7c26`
- Сигнатура: `pageBlockBlockquote(text:RichText, caption:RichText) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockBlockquote
- Поля:
  - `text`: `RichText`
  - `caption`: `RichText`

### `pageBlockChannel`

- ID: `-283684427` / `0xef1751b5`
- Сигнатура: `pageBlockChannel(channel:Chat) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockChannel
- Поля:
  - `channel`: `Chat`

### `pageBlockCollage`

- ID: `1705048653` / `0x65a0fa4d`
- Сигнатура: `pageBlockCollage(items:Vector, caption:PageCaption) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockCollage
- Поля:
  - `items`: `Vector`
  - `caption`: `PageCaption`

### `pageBlockCover`

- ID: `972174080` / `0x39f23300`
- Сигнатура: `pageBlockCover(cover:PageBlock) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockCover
- Поля:
  - `cover`: `PageBlock`

### `pageBlockDetails`

- ID: `1987480557` / `0x76768bed`
- Сигнатура: `pageBlockDetails(flags:#, open:flags.0?true, blocks:Vector, title:RichText) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockDetails
- Поля:
  - `flags`: `#` - служебное поле flags
  - `open`: `flags.0?true` - optional через flags.0
  - `blocks`: `Vector`
  - `title`: `RichText`

### `pageBlockDivider`

- ID: `-618614392` / `0xdb20b188`
- Сигнатура: `pageBlockDivider() => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockDivider
- Поля:
  - Нет полей.

### `pageBlockEmbed`

- ID: `-1468953147` / `0xa8718dc5`
- Сигнатура: `pageBlockEmbed(flags:#, full_width:flags.0?true, allow_scrolling:flags.3?true, url:flags.1?string, html:flags.2?string, poster_photo_id:flags.4?long, w:flags.5?int, h:flags.5?int, caption:PageCaption) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockEmbed
- Поля:
  - `flags`: `#` - служебное поле flags
  - `full_width`: `flags.0?true` - optional через flags.0
  - `allow_scrolling`: `flags.3?true` - optional через flags.3
  - `url`: `flags.1?string` - optional через flags.1
  - `html`: `flags.2?string` - optional через flags.2
  - `poster_photo_id`: `flags.4?long` - optional через flags.4
  - `w`: `flags.5?int` - optional через flags.5
  - `h`: `flags.5?int` - optional через flags.5
  - `caption`: `PageCaption`

### `pageBlockEmbedPost`

- ID: `-229005301` / `0xf259a80b`
- Сигнатура: `pageBlockEmbedPost(url:string, webpage_id:long, author_photo_id:long, author:string, date:int, blocks:Vector, caption:PageCaption) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockEmbedPost
- Поля:
  - `url`: `string`
  - `webpage_id`: `long`
  - `author_photo_id`: `long`
  - `author`: `string`
  - `date`: `int`
  - `blocks`: `Vector`
  - `caption`: `PageCaption`

### `pageBlockFooter`

- ID: `1216809369` / `0x48870999`
- Сигнатура: `pageBlockFooter(text:RichText) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockFooter
- Поля:
  - `text`: `RichText`

### `pageBlockHeader`

- ID: `-1076861716` / `0xbfd064ec`
- Сигнатура: `pageBlockHeader(text:RichText) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockHeader
- Поля:
  - `text`: `RichText`

### `pageBlockKicker`

- ID: `504660880` / `0x1e148390`
- Сигнатура: `pageBlockKicker(text:RichText) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockKicker
- Поля:
  - `text`: `RichText`

### `pageBlockList`

- ID: `-454524911` / `0xe4e88011`
- Сигнатура: `pageBlockList(items:Vector) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockList
- Поля:
  - `items`: `Vector`

### `pageBlockMap`

- ID: `-1538310410` / `0xa44f3ef6`
- Сигнатура: `pageBlockMap(geo:GeoPoint, zoom:int, w:int, h:int, caption:PageCaption) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockMap
- Поля:
  - `geo`: `GeoPoint`
  - `zoom`: `int`
  - `w`: `int`
  - `h`: `int`
  - `caption`: `PageCaption`

### `pageBlockOrderedList`

- ID: `-1702174239` / `0x9a8ae1e1`
- Сигнатура: `pageBlockOrderedList(items:Vector) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockOrderedList
- Поля:
  - `items`: `Vector`

### `pageBlockParagraph`

- ID: `1182402406` / `0x467a0766`
- Сигнатура: `pageBlockParagraph(text:RichText) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockParagraph
- Поля:
  - `text`: `RichText`

### `pageBlockPhoto`

- ID: `391759200` / `0x1759c560`
- Сигнатура: `pageBlockPhoto(flags:#, photo_id:long, caption:PageCaption, url:flags.0?string, webpage_id:flags.0?long) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockPhoto
- Поля:
  - `flags`: `#` - служебное поле flags
  - `photo_id`: `long`
  - `caption`: `PageCaption`
  - `url`: `flags.0?string` - optional через flags.0
  - `webpage_id`: `flags.0?long` - optional через flags.0

### `pageBlockPreformatted`

- ID: `-1066346178` / `0xc070d93e`
- Сигнатура: `pageBlockPreformatted(text:RichText, language:string) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockPreformatted
- Поля:
  - `text`: `RichText`
  - `language`: `string`

### `pageBlockPullquote`

- ID: `1329878739` / `0x4f4456d3`
- Сигнатура: `pageBlockPullquote(text:RichText, caption:RichText) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockPullquote
- Поля:
  - `text`: `RichText`
  - `caption`: `RichText`

### `pageBlockRelatedArticles`

- ID: `370236054` / `0x16115a96`
- Сигнатура: `pageBlockRelatedArticles(title:RichText, articles:Vector) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockRelatedArticles
- Поля:
  - `title`: `RichText`
  - `articles`: `Vector`

### `pageBlockSlideshow`

- ID: `52401552` / `0x031f9590`
- Сигнатура: `pageBlockSlideshow(items:Vector, caption:PageCaption) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockSlideshow
- Поля:
  - `items`: `Vector`
  - `caption`: `PageCaption`

### `pageBlockSubheader`

- ID: `-248793375` / `0xf12bb6e1`
- Сигнатура: `pageBlockSubheader(text:RichText) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockSubheader
- Поля:
  - `text`: `RichText`

### `pageBlockSubtitle`

- ID: `-1879401953` / `0x8ffa9a1f`
- Сигнатура: `pageBlockSubtitle(text:RichText) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockSubtitle
- Поля:
  - `text`: `RichText`

### `pageBlockTable`

- ID: `-1085412734` / `0xbf4dea82`
- Сигнатура: `pageBlockTable(flags:#, bordered:flags.0?true, striped:flags.1?true, title:RichText, rows:Vector) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockTable
- Поля:
  - `flags`: `#` - служебное поле flags
  - `bordered`: `flags.0?true` - optional через flags.0
  - `striped`: `flags.1?true` - optional через flags.1
  - `title`: `RichText`
  - `rows`: `Vector`

### `pageBlockTitle`

- ID: `1890305021` / `0x70abc3fd`
- Сигнатура: `pageBlockTitle(text:RichText) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockTitle
- Поля:
  - `text`: `RichText`

### `pageBlockUnsupported`

- ID: `324435594` / `0x13567e8a`
- Сигнатура: `pageBlockUnsupported() => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockUnsupported
- Поля:
  - Нет полей.

### `pageBlockVideo`

- ID: `2089805750` / `0x7c8fe7b6`
- Сигнатура: `pageBlockVideo(flags:#, autoplay:flags.0?true, loop:flags.1?true, video_id:long, caption:PageCaption) => PageBlock`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageBlockVideo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `autoplay`: `flags.0?true` - optional через flags.0
  - `loop`: `flags.1?true` - optional через flags.1
  - `video_id`: `long`
  - `caption`: `PageCaption`

## `PageCaption`

- Официальный тип: https://core.telegram.org/type/PageCaption
- Количество constructors: **1**

### `pageCaption`

- ID: `1869903447` / `0x6f747657`
- Сигнатура: `pageCaption(text:RichText, credit:RichText) => PageCaption`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageCaption
- Поля:
  - `text`: `RichText`
  - `credit`: `RichText`

## `PageListItem`

- Официальный тип: https://core.telegram.org/type/PageListItem
- Количество constructors: **2**

### `pageListItemBlocks`

- ID: `635466748` / `0x25e073fc`
- Сигнатура: `pageListItemBlocks(blocks:Vector) => PageListItem`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageListItemBlocks
- Поля:
  - `blocks`: `Vector`

### `pageListItemText`

- ID: `-1188055347` / `0xb92fb6cd`
- Сигнатура: `pageListItemText(text:RichText) => PageListItem`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageListItemText
- Поля:
  - `text`: `RichText`

## `PageListOrderedItem`

- Официальный тип: https://core.telegram.org/type/PageListOrderedItem
- Количество constructors: **2**

### `pageListOrderedItemBlocks`

- ID: `-1730311882` / `0x98dd8936`
- Сигнатура: `pageListOrderedItemBlocks(num:string, blocks:Vector) => PageListOrderedItem`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageListOrderedItemBlocks
- Поля:
  - `num`: `string`
  - `blocks`: `Vector`

### `pageListOrderedItemText`

- ID: `1577484359` / `0x5e068047`
- Сигнатура: `pageListOrderedItemText(num:string, text:RichText) => PageListOrderedItem`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageListOrderedItemText
- Поля:
  - `num`: `string`
  - `text`: `RichText`

## `PageRelatedArticle`

- Официальный тип: https://core.telegram.org/type/PageRelatedArticle
- Количество constructors: **1**

### `pageRelatedArticle`

- ID: `-1282352120` / `0xb390dc08`
- Сигнатура: `pageRelatedArticle(flags:#, url:string, webpage_id:long, title:flags.0?string, description:flags.1?string, photo_id:flags.2?long, author:flags.3?string, published_date:flags.4?int) => PageRelatedArticle`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageRelatedArticle
- Поля:
  - `flags`: `#` - служебное поле flags
  - `url`: `string`
  - `webpage_id`: `long`
  - `title`: `flags.0?string` - optional через flags.0
  - `description`: `flags.1?string` - optional через flags.1
  - `photo_id`: `flags.2?long` - optional через flags.2
  - `author`: `flags.3?string` - optional через flags.3
  - `published_date`: `flags.4?int` - optional через flags.4

## `PageTableCell`

- Официальный тип: https://core.telegram.org/type/PageTableCell
- Количество constructors: **1**

### `pageTableCell`

- ID: `878078826` / `0x34566b6a`
- Сигнатура: `pageTableCell(flags:#, header:flags.0?true, align_center:flags.3?true, align_right:flags.4?true, valign_middle:flags.5?true, valign_bottom:flags.6?true, text:flags.7?RichText, colspan:flags.1?int, rowspan:flags.2?int) => PageTableCell`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageTableCell
- Поля:
  - `flags`: `#` - служебное поле flags
  - `header`: `flags.0?true` - optional через flags.0
  - `align_center`: `flags.3?true` - optional через flags.3
  - `align_right`: `flags.4?true` - optional через flags.4
  - `valign_middle`: `flags.5?true` - optional через flags.5
  - `valign_bottom`: `flags.6?true` - optional через flags.6
  - `text`: `flags.7?RichText` - optional через flags.7
  - `colspan`: `flags.1?int` - optional через flags.1
  - `rowspan`: `flags.2?int` - optional через flags.2

## `PageTableRow`

- Официальный тип: https://core.telegram.org/type/PageTableRow
- Количество constructors: **1**

### `pageTableRow`

- ID: `-524237339` / `0xe0c0c5e5`
- Сигнатура: `pageTableRow(cells:Vector) => PageTableRow`
- Официальная страница конструктора: https://core.telegram.org/constructor/pageTableRow
- Поля:
  - `cells`: `Vector`

## `PaidReactionPrivacy`

- Официальный тип: https://core.telegram.org/type/PaidReactionPrivacy
- Количество constructors: **3**

### `paidReactionPrivacyAnonymous`

- ID: `520887001` / `0x1f0c1ad9`
- Сигнатура: `paidReactionPrivacyAnonymous() => PaidReactionPrivacy`
- Официальная страница конструктора: https://core.telegram.org/constructor/paidReactionPrivacyAnonymous
- Поля:
  - Нет полей.

### `paidReactionPrivacyDefault`

- ID: `543872158` / `0x206ad49e`
- Сигнатура: `paidReactionPrivacyDefault() => PaidReactionPrivacy`
- Официальная страница конструктора: https://core.telegram.org/constructor/paidReactionPrivacyDefault
- Поля:
  - Нет полей.

### `paidReactionPrivacyPeer`

- ID: `-596837136` / `0xdc6cfcf0`
- Сигнатура: `paidReactionPrivacyPeer(peer:InputPeer) => PaidReactionPrivacy`
- Официальная страница конструктора: https://core.telegram.org/constructor/paidReactionPrivacyPeer
- Поля:
  - `peer`: `InputPeer`

## `PasswordKdfAlgo`

- Официальный тип: https://core.telegram.org/type/PasswordKdfAlgo
- Количество constructors: **2**

### `passwordKdfAlgoSHA256SHA256PBKDF2HMACSHA512iter100000SHA256ModPow`

- ID: `982592842` / `0x3a912d4a`
- Сигнатура: `passwordKdfAlgoSHA256SHA256PBKDF2HMACSHA512iter100000SHA256ModPow(salt1:bytes, salt2:bytes, g:int, p:bytes) => PasswordKdfAlgo`
- Официальная страница конструктора: https://core.telegram.org/constructor/passwordKdfAlgoSHA256SHA256PBKDF2HMACSHA512iter100000SHA256ModPow
- Поля:
  - `salt1`: `bytes`
  - `salt2`: `bytes`
  - `g`: `int`
  - `p`: `bytes`

### `passwordKdfAlgoUnknown`

- ID: `-732254058` / `0xd45ab096`
- Сигнатура: `passwordKdfAlgoUnknown() => PasswordKdfAlgo`
- Официальная страница конструктора: https://core.telegram.org/constructor/passwordKdfAlgoUnknown
- Поля:
  - Нет полей.

## `PaymentCharge`

- Официальный тип: https://core.telegram.org/type/PaymentCharge
- Количество constructors: **1**

### `paymentCharge`

- ID: `-368917890` / `0xea02c27e`
- Сигнатура: `paymentCharge(id:string, provider_charge_id:string) => PaymentCharge`
- Официальная страница конструктора: https://core.telegram.org/constructor/paymentCharge
- Поля:
  - `id`: `string`
  - `provider_charge_id`: `string`

## `PaymentFormMethod`

- Официальный тип: https://core.telegram.org/type/PaymentFormMethod
- Количество constructors: **1**

### `paymentFormMethod`

- ID: `-1996951013` / `0x88f8f21b`
- Сигнатура: `paymentFormMethod(url:string, title:string) => PaymentFormMethod`
- Официальная страница конструктора: https://core.telegram.org/constructor/paymentFormMethod
- Поля:
  - `url`: `string`
  - `title`: `string`

## `PaymentRequestedInfo`

- Официальный тип: https://core.telegram.org/type/PaymentRequestedInfo
- Количество constructors: **1**

### `paymentRequestedInfo`

- ID: `-1868808300` / `0x909c3f94`
- Сигнатура: `paymentRequestedInfo(flags:#, name:flags.0?string, phone:flags.1?string, email:flags.2?string, shipping_address:flags.3?PostAddress) => PaymentRequestedInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/paymentRequestedInfo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `name`: `flags.0?string` - optional через flags.0
  - `phone`: `flags.1?string` - optional через flags.1
  - `email`: `flags.2?string` - optional через flags.2
  - `shipping_address`: `flags.3?PostAddress` - optional через flags.3

## `PaymentSavedCredentials`

- Официальный тип: https://core.telegram.org/type/PaymentSavedCredentials
- Количество constructors: **1**

### `paymentSavedCredentialsCard`

- ID: `-842892769` / `0xcdc27a1f`
- Сигнатура: `paymentSavedCredentialsCard(id:string, title:string) => PaymentSavedCredentials`
- Официальная страница конструктора: https://core.telegram.org/constructor/paymentSavedCredentialsCard
- Поля:
  - `id`: `string`
  - `title`: `string`

## `Peer`

- Официальный тип: https://core.telegram.org/type/Peer
- Количество constructors: **3**

### `peerChannel`

- ID: `-1566230754` / `0xa2a5371e`
- Сигнатура: `peerChannel(channel_id:long) => Peer`
- Официальная страница конструктора: https://core.telegram.org/constructor/peerChannel
- Поля:
  - `channel_id`: `long`

### `peerChat`

- ID: `918946202` / `0x36c6019a`
- Сигнатура: `peerChat(chat_id:long) => Peer`
- Официальная страница конструктора: https://core.telegram.org/constructor/peerChat
- Поля:
  - `chat_id`: `long`

### `peerUser`

- ID: `1498486562` / `0x59511722`
- Сигнатура: `peerUser(user_id:long) => Peer`
- Официальная страница конструктора: https://core.telegram.org/constructor/peerUser
- Поля:
  - `user_id`: `long`

## `PeerBlocked`

- Официальный тип: https://core.telegram.org/type/PeerBlocked
- Количество constructors: **1**

### `peerBlocked`

- ID: `-386039788` / `0xe8fd8014`
- Сигнатура: `peerBlocked(peer_id:Peer, date:int) => PeerBlocked`
- Официальная страница конструктора: https://core.telegram.org/constructor/peerBlocked
- Поля:
  - `peer_id`: `Peer`
  - `date`: `int`

## `PeerColor`

- Официальный тип: https://core.telegram.org/type/PeerColor
- Количество constructors: **1**

### `peerColor`

- ID: `-1253352753` / `0xb54b5acf`
- Сигнатура: `peerColor(flags:#, color:flags.0?int, background_emoji_id:flags.1?long) => PeerColor`
- Официальная страница конструктора: https://core.telegram.org/constructor/peerColor
- Поля:
  - `flags`: `#` - служебное поле flags
  - `color`: `flags.0?int` - optional через flags.0
  - `background_emoji_id`: `flags.1?long` - optional через flags.1

## `PeerLocated`

- Официальный тип: https://core.telegram.org/type/PeerLocated
- Количество constructors: **2**

### `peerLocated`

- ID: `-901375139` / `0xca461b5d`
- Сигнатура: `peerLocated(peer:Peer, expires:int, distance:int) => PeerLocated`
- Официальная страница конструктора: https://core.telegram.org/constructor/peerLocated
- Поля:
  - `peer`: `Peer`
  - `expires`: `int`
  - `distance`: `int`

### `peerSelfLocated`

- ID: `-118740917` / `0xf8ec284b`
- Сигнатура: `peerSelfLocated(expires:int) => PeerLocated`
- Официальная страница конструктора: https://core.telegram.org/constructor/peerSelfLocated
- Поля:
  - `expires`: `int`

## `PeerNotifySettings`

- Официальный тип: https://core.telegram.org/type/PeerNotifySettings
- Количество constructors: **1**

### `peerNotifySettings`

- ID: `-1721619444` / `0x99622c0c`
- Сигнатура: `peerNotifySettings(flags:#, show_previews:flags.0?Bool, silent:flags.1?Bool, mute_until:flags.2?int, ios_sound:flags.3?NotificationSound, android_sound:flags.4?NotificationSound, other_sound:flags.5?NotificationSound, stories_muted:flags.6?Bool, stories_hide_sender:flags.7?Bool, stories_ios_sound:flags.8?NotificationSound, stories_android_sound:flags.9?NotificationSound, stories_other_sound:flags.10?NotificationSound) => PeerNotifySettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/peerNotifySettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `show_previews`: `flags.0?Bool` - optional через flags.0
  - `silent`: `flags.1?Bool` - optional через flags.1
  - `mute_until`: `flags.2?int` - optional через flags.2
  - `ios_sound`: `flags.3?NotificationSound` - optional через flags.3
  - `android_sound`: `flags.4?NotificationSound` - optional через flags.4
  - `other_sound`: `flags.5?NotificationSound` - optional через flags.5
  - `stories_muted`: `flags.6?Bool` - optional через flags.6
  - `stories_hide_sender`: `flags.7?Bool` - optional через flags.7
  - `stories_ios_sound`: `flags.8?NotificationSound` - optional через flags.8
  - `stories_android_sound`: `flags.9?NotificationSound` - optional через flags.9
  - `stories_other_sound`: `flags.10?NotificationSound` - optional через flags.10

## `PeerSettings`

- Официальный тип: https://core.telegram.org/type/PeerSettings
- Количество constructors: **1**

### `peerSettings`

- ID: `-193510921` / `0xf47741f7`
- Сигнатура: `peerSettings(flags:#, report_spam:flags.0?true, add_contact:flags.1?true, block_contact:flags.2?true, share_contact:flags.3?true, need_contacts_exception:flags.4?true, report_geo:flags.5?true, autoarchived:flags.7?true, invite_members:flags.8?true, request_chat_broadcast:flags.10?true, business_bot_paused:flags.11?true, business_bot_can_reply:flags.12?true, geo_distance:flags.6?int, request_chat_title:flags.9?string, request_chat_date:flags.9?int, business_bot_id:flags.13?long, business_bot_manage_url:flags.13?string, charge_paid_message_stars:flags.14?long, registration_month:flags.15?string, phone_country:flags.16?string, name_change_date:flags.17?int, photo_change_date:flags.18?int) => PeerSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/peerSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `report_spam`: `flags.0?true` - optional через flags.0
  - `add_contact`: `flags.1?true` - optional через flags.1
  - `block_contact`: `flags.2?true` - optional через flags.2
  - `share_contact`: `flags.3?true` - optional через flags.3
  - `need_contacts_exception`: `flags.4?true` - optional через flags.4
  - `report_geo`: `flags.5?true` - optional через flags.5
  - `autoarchived`: `flags.7?true` - optional через flags.7
  - `invite_members`: `flags.8?true` - optional через flags.8
  - `request_chat_broadcast`: `flags.10?true` - optional через flags.10
  - `business_bot_paused`: `flags.11?true` - optional через flags.11
  - `business_bot_can_reply`: `flags.12?true` - optional через flags.12
  - `geo_distance`: `flags.6?int` - optional через flags.6
  - `request_chat_title`: `flags.9?string` - optional через flags.9
  - `request_chat_date`: `flags.9?int` - optional через flags.9
  - `business_bot_id`: `flags.13?long` - optional через flags.13
  - `business_bot_manage_url`: `flags.13?string` - optional через flags.13
  - `charge_paid_message_stars`: `flags.14?long` - optional через flags.14
  - `registration_month`: `flags.15?string` - optional через flags.15
  - `phone_country`: `flags.16?string` - optional через flags.16
  - `name_change_date`: `flags.17?int` - optional через flags.17
  - `photo_change_date`: `flags.18?int` - optional через flags.18

## `PeerStories`

- Официальный тип: https://core.telegram.org/type/PeerStories
- Количество constructors: **1**

### `peerStories`

- ID: `-1707742823` / `0x9a35e999`
- Сигнатура: `peerStories(flags:#, peer:Peer, max_read_id:flags.0?int, stories:Vector) => PeerStories`
- Официальная страница конструктора: https://core.telegram.org/constructor/peerStories
- Поля:
  - `flags`: `#` - служебное поле flags
  - `peer`: `Peer`
  - `max_read_id`: `flags.0?int` - optional через flags.0
  - `stories`: `Vector`

## `PendingSuggestion`

- Официальный тип: https://core.telegram.org/type/PendingSuggestion
- Количество constructors: **1**

### `pendingSuggestion`

- ID: `-404214254` / `0xe7e82e12`
- Сигнатура: `pendingSuggestion(suggestion:string, title:TextWithEntities, description:TextWithEntities, url:string) => PendingSuggestion`
- Официальная страница конструктора: https://core.telegram.org/constructor/pendingSuggestion
- Поля:
  - `suggestion`: `string`
  - `title`: `TextWithEntities`
  - `description`: `TextWithEntities`
  - `url`: `string`

## `PhoneCall`

- Официальный тип: https://core.telegram.org/type/PhoneCall
- Количество constructors: **6**

### `phoneCall`

- ID: `810769141` / `0x30535af5`
- Сигнатура: `phoneCall(flags:#, p2p_allowed:flags.5?true, video:flags.6?true, conference_supported:flags.8?true, id:long, access_hash:long, date:int, admin_id:long, participant_id:long, g_a_or_b:bytes, key_fingerprint:long, protocol:PhoneCallProtocol, connections:Vector, start_date:int, custom_parameters:flags.7?DataJSON) => PhoneCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneCall
- Поля:
  - `flags`: `#` - служебное поле flags
  - `p2p_allowed`: `flags.5?true` - optional через flags.5
  - `video`: `flags.6?true` - optional через flags.6
  - `conference_supported`: `flags.8?true` - optional через flags.8
  - `id`: `long`
  - `access_hash`: `long`
  - `date`: `int`
  - `admin_id`: `long`
  - `participant_id`: `long`
  - `g_a_or_b`: `bytes`
  - `key_fingerprint`: `long`
  - `protocol`: `PhoneCallProtocol`
  - `connections`: `Vector`
  - `start_date`: `int`
  - `custom_parameters`: `flags.7?DataJSON` - optional через flags.7

### `phoneCallAccepted`

- ID: `912311057` / `0x3660c311`
- Сигнатура: `phoneCallAccepted(flags:#, video:flags.6?true, id:long, access_hash:long, date:int, admin_id:long, participant_id:long, g_b:bytes, protocol:PhoneCallProtocol) => PhoneCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneCallAccepted
- Поля:
  - `flags`: `#` - служебное поле flags
  - `video`: `flags.6?true` - optional через flags.6
  - `id`: `long`
  - `access_hash`: `long`
  - `date`: `int`
  - `admin_id`: `long`
  - `participant_id`: `long`
  - `g_b`: `bytes`
  - `protocol`: `PhoneCallProtocol`

### `phoneCallDiscarded`

- ID: `1355435489` / `0x50ca4de1`
- Сигнатура: `phoneCallDiscarded(flags:#, need_rating:flags.2?true, need_debug:flags.3?true, video:flags.6?true, id:long, reason:flags.0?PhoneCallDiscardReason, duration:flags.1?int) => PhoneCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneCallDiscarded
- Поля:
  - `flags`: `#` - служебное поле flags
  - `need_rating`: `flags.2?true` - optional через flags.2
  - `need_debug`: `flags.3?true` - optional через flags.3
  - `video`: `flags.6?true` - optional через flags.6
  - `id`: `long`
  - `reason`: `flags.0?PhoneCallDiscardReason` - optional через flags.0
  - `duration`: `flags.1?int` - optional через flags.1

### `phoneCallEmpty`

- ID: `1399245077` / `0x5366c915`
- Сигнатура: `phoneCallEmpty(id:long) => PhoneCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneCallEmpty
- Поля:
  - `id`: `long`

### `phoneCallRequested`

- ID: `347139340` / `0x14b0ed0c`
- Сигнатура: `phoneCallRequested(flags:#, video:flags.6?true, id:long, access_hash:long, date:int, admin_id:long, participant_id:long, g_a_hash:bytes, protocol:PhoneCallProtocol) => PhoneCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneCallRequested
- Поля:
  - `flags`: `#` - служебное поле flags
  - `video`: `flags.6?true` - optional через flags.6
  - `id`: `long`
  - `access_hash`: `long`
  - `date`: `int`
  - `admin_id`: `long`
  - `participant_id`: `long`
  - `g_a_hash`: `bytes`
  - `protocol`: `PhoneCallProtocol`

### `phoneCallWaiting`

- ID: `-987599081` / `0xc5226f17`
- Сигнатура: `phoneCallWaiting(flags:#, video:flags.6?true, id:long, access_hash:long, date:int, admin_id:long, participant_id:long, protocol:PhoneCallProtocol, receive_date:flags.0?int) => PhoneCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneCallWaiting
- Поля:
  - `flags`: `#` - служебное поле flags
  - `video`: `flags.6?true` - optional через flags.6
  - `id`: `long`
  - `access_hash`: `long`
  - `date`: `int`
  - `admin_id`: `long`
  - `participant_id`: `long`
  - `protocol`: `PhoneCallProtocol`
  - `receive_date`: `flags.0?int` - optional через flags.0

## `PhoneCallDiscardReason`

- Официальный тип: https://core.telegram.org/type/PhoneCallDiscardReason
- Количество constructors: **5**

### `phoneCallDiscardReasonBusy`

- ID: `-84416311` / `0xfaf7e8c9`
- Сигнатура: `phoneCallDiscardReasonBusy() => PhoneCallDiscardReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneCallDiscardReasonBusy
- Поля:
  - Нет полей.

### `phoneCallDiscardReasonDisconnect`

- ID: `-527056480` / `0xe095c1a0`
- Сигнатура: `phoneCallDiscardReasonDisconnect() => PhoneCallDiscardReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneCallDiscardReasonDisconnect
- Поля:
  - Нет полей.

### `phoneCallDiscardReasonHangup`

- ID: `1471006352` / `0x57adc690`
- Сигнатура: `phoneCallDiscardReasonHangup() => PhoneCallDiscardReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneCallDiscardReasonHangup
- Поля:
  - Нет полей.

### `phoneCallDiscardReasonMigrateConferenceCall`

- ID: `-1615072777` / `0x9fbbf1f7`
- Сигнатура: `phoneCallDiscardReasonMigrateConferenceCall(slug:string) => PhoneCallDiscardReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneCallDiscardReasonMigrateConferenceCall
- Поля:
  - `slug`: `string`

### `phoneCallDiscardReasonMissed`

- ID: `-2048646399` / `0x85e42301`
- Сигнатура: `phoneCallDiscardReasonMissed() => PhoneCallDiscardReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneCallDiscardReasonMissed
- Поля:
  - Нет полей.

## `PhoneCallProtocol`

- Официальный тип: https://core.telegram.org/type/PhoneCallProtocol
- Количество constructors: **1**

### `phoneCallProtocol`

- ID: `-58224696` / `0xfc878fc8`
- Сигнатура: `phoneCallProtocol(flags:#, udp_p2p:flags.0?true, udp_reflector:flags.1?true, min_layer:int, max_layer:int, library_versions:Vector) => PhoneCallProtocol`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneCallProtocol
- Поля:
  - `flags`: `#` - служебное поле flags
  - `udp_p2p`: `flags.0?true` - optional через flags.0
  - `udp_reflector`: `flags.1?true` - optional через flags.1
  - `min_layer`: `int`
  - `max_layer`: `int`
  - `library_versions`: `Vector`

## `PhoneConnection`

- Официальный тип: https://core.telegram.org/type/PhoneConnection
- Количество constructors: **2**

### `phoneConnection`

- ID: `-1665063993` / `0x9cc123c7`
- Сигнатура: `phoneConnection(flags:#, tcp:flags.0?true, id:long, ip:string, ipv6:string, port:int, peer_tag:bytes) => PhoneConnection`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneConnection
- Поля:
  - `flags`: `#` - служебное поле flags
  - `tcp`: `flags.0?true` - optional через flags.0
  - `id`: `long`
  - `ip`: `string`
  - `ipv6`: `string`
  - `port`: `int`
  - `peer_tag`: `bytes`

### `phoneConnectionWebrtc`

- ID: `1667228533` / `0x635fe375`
- Сигнатура: `phoneConnectionWebrtc(flags:#, turn:flags.0?true, stun:flags.1?true, id:long, ip:string, ipv6:string, port:int, username:string, password:string) => PhoneConnection`
- Официальная страница конструктора: https://core.telegram.org/constructor/phoneConnectionWebrtc
- Поля:
  - `flags`: `#` - служебное поле flags
  - `turn`: `flags.0?true` - optional через flags.0
  - `stun`: `flags.1?true` - optional через flags.1
  - `id`: `long`
  - `ip`: `string`
  - `ipv6`: `string`
  - `port`: `int`
  - `username`: `string`
  - `password`: `string`

## `Photo`

- Официальный тип: https://core.telegram.org/type/Photo
- Количество constructors: **2**

### `photo`

- ID: `-82216347` / `0xfb197a65`
- Сигнатура: `photo(flags:#, has_stickers:flags.0?true, id:long, access_hash:long, file_reference:bytes, date:int, sizes:Vector, video_sizes:flags.1?Vector, dc_id:int) => Photo`
- Официальная страница конструктора: https://core.telegram.org/constructor/photo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `has_stickers`: `flags.0?true` - optional через flags.0
  - `id`: `long`
  - `access_hash`: `long`
  - `file_reference`: `bytes`
  - `date`: `int`
  - `sizes`: `Vector`
  - `video_sizes`: `flags.1?Vector` - optional через flags.1
  - `dc_id`: `int`

### `photoEmpty`

- ID: `590459437` / `0x2331b22d`
- Сигнатура: `photoEmpty(id:long) => Photo`
- Официальная страница конструктора: https://core.telegram.org/constructor/photoEmpty
- Поля:
  - `id`: `long`

## `PhotoSize`

- Официальный тип: https://core.telegram.org/type/PhotoSize
- Количество constructors: **6**

### `photoCachedSize`

- ID: `35527382` / `0x021e1ad6`
- Сигнатура: `photoCachedSize(type:string, w:int, h:int, bytes:bytes) => PhotoSize`
- Официальная страница конструктора: https://core.telegram.org/constructor/photoCachedSize
- Поля:
  - `type`: `string`
  - `w`: `int`
  - `h`: `int`
  - `bytes`: `bytes`

### `photoPathSize`

- ID: `-668906175` / `0xd8214d41`
- Сигнатура: `photoPathSize(type:string, bytes:bytes) => PhotoSize`
- Официальная страница конструктора: https://core.telegram.org/constructor/photoPathSize
- Поля:
  - `type`: `string`
  - `bytes`: `bytes`

### `photoSize`

- ID: `1976012384` / `0x75c78e60`
- Сигнатура: `photoSize(type:string, w:int, h:int, size:int) => PhotoSize`
- Официальная страница конструктора: https://core.telegram.org/constructor/photoSize
- Поля:
  - `type`: `string`
  - `w`: `int`
  - `h`: `int`
  - `size`: `int`

### `photoSizeEmpty`

- ID: `236446268` / `0x0e17e23c`
- Сигнатура: `photoSizeEmpty(type:string) => PhotoSize`
- Официальная страница конструктора: https://core.telegram.org/constructor/photoSizeEmpty
- Поля:
  - `type`: `string`

### `photoSizeProgressive`

- ID: `-96535659` / `0xfa3efb95`
- Сигнатура: `photoSizeProgressive(type:string, w:int, h:int, sizes:Vector) => PhotoSize`
- Официальная страница конструктора: https://core.telegram.org/constructor/photoSizeProgressive
- Поля:
  - `type`: `string`
  - `w`: `int`
  - `h`: `int`
  - `sizes`: `Vector`

### `photoStrippedSize`

- ID: `-525288402` / `0xe0b0bc2e`
- Сигнатура: `photoStrippedSize(type:string, bytes:bytes) => PhotoSize`
- Официальная страница конструктора: https://core.telegram.org/constructor/photoStrippedSize
- Поля:
  - `type`: `string`
  - `bytes`: `bytes`

## `Poll`

- Официальный тип: https://core.telegram.org/type/Poll
- Количество constructors: **1**

### `poll`

- ID: `1484026161` / `0x58747131`
- Сигнатура: `poll(id:long, flags:#, closed:flags.0?true, public_voters:flags.1?true, multiple_choice:flags.2?true, quiz:flags.3?true, question:TextWithEntities, answers:Vector, close_period:flags.4?int, close_date:flags.5?int) => Poll`
- Официальная страница конструктора: https://core.telegram.org/constructor/poll
- Поля:
  - `id`: `long`
  - `flags`: `#` - служебное поле flags
  - `closed`: `flags.0?true` - optional через flags.0
  - `public_voters`: `flags.1?true` - optional через flags.1
  - `multiple_choice`: `flags.2?true` - optional через flags.2
  - `quiz`: `flags.3?true` - optional через flags.3
  - `question`: `TextWithEntities`
  - `answers`: `Vector`
  - `close_period`: `flags.4?int` - optional через flags.4
  - `close_date`: `flags.5?int` - optional через flags.5

## `PollAnswer`

- Официальный тип: https://core.telegram.org/type/PollAnswer
- Количество constructors: **1**

### `pollAnswer`

- ID: `-15277366` / `0xff16e2ca`
- Сигнатура: `pollAnswer(text:TextWithEntities, option:bytes) => PollAnswer`
- Официальная страница конструктора: https://core.telegram.org/constructor/pollAnswer
- Поля:
  - `text`: `TextWithEntities`
  - `option`: `bytes`

## `PollAnswerVoters`

- Официальный тип: https://core.telegram.org/type/PollAnswerVoters
- Количество constructors: **1**

### `pollAnswerVoters`

- ID: `997055186` / `0x3b6ddad2`
- Сигнатура: `pollAnswerVoters(flags:#, chosen:flags.0?true, correct:flags.1?true, option:bytes, voters:int) => PollAnswerVoters`
- Официальная страница конструктора: https://core.telegram.org/constructor/pollAnswerVoters
- Поля:
  - `flags`: `#` - служебное поле flags
  - `chosen`: `flags.0?true` - optional через flags.0
  - `correct`: `flags.1?true` - optional через flags.1
  - `option`: `bytes`
  - `voters`: `int`

## `PollResults`

- Официальный тип: https://core.telegram.org/type/PollResults
- Количество constructors: **1**

### `pollResults`

- ID: `2061444128` / `0x7adf2420`
- Сигнатура: `pollResults(flags:#, min:flags.0?true, results:flags.1?Vector, total_voters:flags.2?int, recent_voters:flags.3?Vector, solution:flags.4?string, solution_entities:flags.4?Vector) => PollResults`
- Официальная страница конструктора: https://core.telegram.org/constructor/pollResults
- Поля:
  - `flags`: `#` - служебное поле flags
  - `min`: `flags.0?true` - optional через flags.0
  - `results`: `flags.1?Vector` - optional через flags.1
  - `total_voters`: `flags.2?int` - optional через flags.2
  - `recent_voters`: `flags.3?Vector` - optional через flags.3
  - `solution`: `flags.4?string` - optional через flags.4
  - `solution_entities`: `flags.4?Vector` - optional через flags.4

## `PopularContact`

- Официальный тип: https://core.telegram.org/type/PopularContact
- Количество constructors: **1**

### `popularContact`

- ID: `1558266229` / `0x5ce14175`
- Сигнатура: `popularContact(client_id:long, importers:int) => PopularContact`
- Официальная страница конструктора: https://core.telegram.org/constructor/popularContact
- Поля:
  - `client_id`: `long`
  - `importers`: `int`

## `PostAddress`

- Официальный тип: https://core.telegram.org/type/PostAddress
- Количество constructors: **1**

### `postAddress`

- ID: `512535275` / `0x1e8caaeb`
- Сигнатура: `postAddress(street_line1:string, street_line2:string, city:string, state:string, country_iso2:string, post_code:string) => PostAddress`
- Официальная страница конструктора: https://core.telegram.org/constructor/postAddress
- Поля:
  - `street_line1`: `string`
  - `street_line2`: `string`
  - `city`: `string`
  - `state`: `string`
  - `country_iso2`: `string`
  - `post_code`: `string`

## `PostInteractionCounters`

- Официальный тип: https://core.telegram.org/type/PostInteractionCounters
- Количество constructors: **2**

### `postInteractionCountersMessage`

- ID: `-419066241` / `0xe7058e7f`
- Сигнатура: `postInteractionCountersMessage(msg_id:int, views:int, forwards:int, reactions:int) => PostInteractionCounters`
- Официальная страница конструктора: https://core.telegram.org/constructor/postInteractionCountersMessage
- Поля:
  - `msg_id`: `int`
  - `views`: `int`
  - `forwards`: `int`
  - `reactions`: `int`

### `postInteractionCountersStory`

- ID: `-1974989273` / `0x8a480e27`
- Сигнатура: `postInteractionCountersStory(story_id:int, views:int, forwards:int, reactions:int) => PostInteractionCounters`
- Официальная страница конструктора: https://core.telegram.org/constructor/postInteractionCountersStory
- Поля:
  - `story_id`: `int`
  - `views`: `int`
  - `forwards`: `int`
  - `reactions`: `int`

## `PremiumGiftCodeOption`

- Официальный тип: https://core.telegram.org/type/PremiumGiftCodeOption
- Количество constructors: **1**

### `premiumGiftCodeOption`

- ID: `629052971` / `0x257e962b`
- Сигнатура: `premiumGiftCodeOption(flags:#, users:int, months:int, store_product:flags.0?string, store_quantity:flags.1?int, currency:string, amount:long) => PremiumGiftCodeOption`
- Официальная страница конструктора: https://core.telegram.org/constructor/premiumGiftCodeOption
- Поля:
  - `flags`: `#` - служебное поле flags
  - `users`: `int`
  - `months`: `int`
  - `store_product`: `flags.0?string` - optional через flags.0
  - `store_quantity`: `flags.1?int` - optional через flags.1
  - `currency`: `string`
  - `amount`: `long`

## `PremiumSubscriptionOption`

- Официальный тип: https://core.telegram.org/type/PremiumSubscriptionOption
- Количество constructors: **1**

### `premiumSubscriptionOption`

- ID: `1596792306` / `0x5f2d1df2`
- Сигнатура: `premiumSubscriptionOption(flags:#, current:flags.1?true, can_purchase_upgrade:flags.2?true, transaction:flags.3?string, months:int, currency:string, amount:long, bot_url:string, store_product:flags.0?string) => PremiumSubscriptionOption`
- Официальная страница конструктора: https://core.telegram.org/constructor/premiumSubscriptionOption
- Поля:
  - `flags`: `#` - служебное поле flags
  - `current`: `flags.1?true` - optional через flags.1
  - `can_purchase_upgrade`: `flags.2?true` - optional через flags.2
  - `transaction`: `flags.3?string` - optional через flags.3
  - `months`: `int`
  - `currency`: `string`
  - `amount`: `long`
  - `bot_url`: `string`
  - `store_product`: `flags.0?string` - optional через flags.0

## `PrepaidGiveaway`

- Официальный тип: https://core.telegram.org/type/PrepaidGiveaway
- Количество constructors: **2**

### `prepaidGiveaway`

- ID: `-1303143084` / `0xb2539d54`
- Сигнатура: `prepaidGiveaway(id:long, months:int, quantity:int, date:int) => PrepaidGiveaway`
- Официальная страница конструктора: https://core.telegram.org/constructor/prepaidGiveaway
- Поля:
  - `id`: `long`
  - `months`: `int`
  - `quantity`: `int`
  - `date`: `int`

### `prepaidStarsGiveaway`

- ID: `-1700956192` / `0x9a9d77e0`
- Сигнатура: `prepaidStarsGiveaway(id:long, stars:long, quantity:int, boosts:int, date:int) => PrepaidGiveaway`
- Официальная страница конструктора: https://core.telegram.org/constructor/prepaidStarsGiveaway
- Поля:
  - `id`: `long`
  - `stars`: `long`
  - `quantity`: `int`
  - `boosts`: `int`
  - `date`: `int`

## `PrivacyKey`

- Официальный тип: https://core.telegram.org/type/PrivacyKey
- Количество constructors: **13**

### `privacyKeyAbout`

- ID: `-1534675103` / `0xa486b761`
- Сигнатура: `privacyKeyAbout() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyAbout
- Поля:
  - Нет полей.

### `privacyKeyAddedByPhone`

- ID: `1124062251` / `0x42ffd42b`
- Сигнатура: `privacyKeyAddedByPhone() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyAddedByPhone
- Поля:
  - Нет полей.

### `privacyKeyBirthday`

- ID: `536913176` / `0x2000a518`
- Сигнатура: `privacyKeyBirthday() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyBirthday
- Поля:
  - Нет полей.

### `privacyKeyChatInvite`

- ID: `1343122938` / `0x500e6dfa`
- Сигнатура: `privacyKeyChatInvite() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyChatInvite
- Поля:
  - Нет полей.

### `privacyKeyForwards`

- ID: `1777096355` / `0x69ec56a3`
- Сигнатура: `privacyKeyForwards() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyForwards
- Поля:
  - Нет полей.

### `privacyKeyNoPaidMessages`

- ID: `399722706` / `0x17d348d2`
- Сигнатура: `privacyKeyNoPaidMessages() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyNoPaidMessages
- Поля:
  - Нет полей.

### `privacyKeyPhoneCall`

- ID: `1030105979` / `0x3d662b7b`
- Сигнатура: `privacyKeyPhoneCall() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyPhoneCall
- Поля:
  - Нет полей.

### `privacyKeyPhoneNumber`

- ID: `-778378131` / `0xd19ae46d`
- Сигнатура: `privacyKeyPhoneNumber() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyPhoneNumber
- Поля:
  - Нет полей.

### `privacyKeyPhoneP2P`

- ID: `961092808` / `0x39491cc8`
- Сигнатура: `privacyKeyPhoneP2P() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyPhoneP2P
- Поля:
  - Нет полей.

### `privacyKeyProfilePhoto`

- ID: `-1777000467` / `0x96151fed`
- Сигнатура: `privacyKeyProfilePhoto() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyProfilePhoto
- Поля:
  - Нет полей.

### `privacyKeyStarGiftsAutoSave`

- ID: `749010424` / `0x2ca4fdf8`
- Сигнатура: `privacyKeyStarGiftsAutoSave() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyStarGiftsAutoSave
- Поля:
  - Нет полей.

### `privacyKeyStatusTimestamp`

- ID: `-1137792208` / `0xbc2eab30`
- Сигнатура: `privacyKeyStatusTimestamp() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyStatusTimestamp
- Поля:
  - Нет полей.

### `privacyKeyVoiceMessages`

- ID: `110621716` / `0x0697f414`
- Сигнатура: `privacyKeyVoiceMessages() => PrivacyKey`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyKeyVoiceMessages
- Поля:
  - Нет полей.

## `PrivacyRule`

- Официальный тип: https://core.telegram.org/type/PrivacyRule
- Количество constructors: **12**

### `privacyValueAllowAll`

- ID: `1698855810` / `0x65427b82`
- Сигнатура: `privacyValueAllowAll() => PrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyValueAllowAll
- Поля:
  - Нет полей.

### `privacyValueAllowBots`

- ID: `558242653` / `0x21461b5d`
- Сигнатура: `privacyValueAllowBots() => PrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyValueAllowBots
- Поля:
  - Нет полей.

### `privacyValueAllowChatParticipants`

- ID: `1796427406` / `0x6b134e8e`
- Сигнатура: `privacyValueAllowChatParticipants(chats:Vector) => PrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyValueAllowChatParticipants
- Поля:
  - `chats`: `Vector`

### `privacyValueAllowCloseFriends`

- ID: `-135735141` / `0xf7e8d89b`
- Сигнатура: `privacyValueAllowCloseFriends() => PrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyValueAllowCloseFriends
- Поля:
  - Нет полей.

### `privacyValueAllowContacts`

- ID: `-123988` / `0xfffe1bac`
- Сигнатура: `privacyValueAllowContacts() => PrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyValueAllowContacts
- Поля:
  - Нет полей.

### `privacyValueAllowPremium`

- ID: `-320241333` / `0xece9814b`
- Сигнатура: `privacyValueAllowPremium() => PrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyValueAllowPremium
- Поля:
  - Нет полей.

### `privacyValueAllowUsers`

- ID: `-1198497870` / `0xb8905fb2`
- Сигнатура: `privacyValueAllowUsers(users:Vector) => PrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyValueAllowUsers
- Поля:
  - `users`: `Vector`

### `privacyValueDisallowAll`

- ID: `-1955338397` / `0x8b73e763`
- Сигнатура: `privacyValueDisallowAll() => PrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyValueDisallowAll
- Поля:
  - Нет полей.

### `privacyValueDisallowBots`

- ID: `-156895185` / `0xf6a5f82f`
- Сигнатура: `privacyValueDisallowBots() => PrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyValueDisallowBots
- Поля:
  - Нет полей.

### `privacyValueDisallowChatParticipants`

- ID: `1103656293` / `0x41c87565`
- Сигнатура: `privacyValueDisallowChatParticipants(chats:Vector) => PrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyValueDisallowChatParticipants
- Поля:
  - `chats`: `Vector`

### `privacyValueDisallowContacts`

- ID: `-125240806` / `0xf888fa1a`
- Сигнатура: `privacyValueDisallowContacts() => PrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyValueDisallowContacts
- Поля:
  - Нет полей.

### `privacyValueDisallowUsers`

- ID: `-463335103` / `0xe4621141`
- Сигнатура: `privacyValueDisallowUsers(users:Vector) => PrivacyRule`
- Официальная страница конструктора: https://core.telegram.org/constructor/privacyValueDisallowUsers
- Поля:
  - `users`: `Vector`

## `ProfileTab`

- Официальный тип: https://core.telegram.org/type/ProfileTab
- Количество constructors: **8**

### `profileTabFiles`

- ID: `-1422681088` / `0xab339c00`
- Сигнатура: `profileTabFiles() => ProfileTab`
- Официальная страница конструктора: https://core.telegram.org/constructor/profileTabFiles
- Поля:
  - Нет полей.

### `profileTabGifs`

- ID: `-1564412267` / `0xa2c0f695`
- Сигнатура: `profileTabGifs() => ProfileTab`
- Официальная страница конструктора: https://core.telegram.org/constructor/profileTabGifs
- Поля:
  - Нет полей.

### `profileTabGifts`

- ID: `1296815210` / `0x4d4bd46a`
- Сигнатура: `profileTabGifts() => ProfileTab`
- Официальная страница конструктора: https://core.telegram.org/constructor/profileTabGifts
- Поля:
  - Нет полей.

### `profileTabLinks`

- ID: `-748329831` / `0xd3656499`
- Сигнатура: `profileTabLinks() => ProfileTab`
- Официальная страница конструктора: https://core.telegram.org/constructor/profileTabLinks
- Поля:
  - Нет полей.

### `profileTabMedia`

- ID: `1925597525` / `0x72c64955`
- Сигнатура: `profileTabMedia() => ProfileTab`
- Официальная страница конструктора: https://core.telegram.org/constructor/profileTabMedia
- Поля:
  - Нет полей.

### `profileTabMusic`

- ID: `-1624780178` / `0x9f27d26e`
- Сигнатура: `profileTabMusic() => ProfileTab`
- Официальная страница конструктора: https://core.telegram.org/constructor/profileTabMusic
- Поля:
  - Нет полей.

### `profileTabPosts`

- ID: `-1181952362` / `0xb98cd696`
- Сигнатура: `profileTabPosts() => ProfileTab`
- Официальная страница конструктора: https://core.telegram.org/constructor/profileTabPosts
- Поля:
  - Нет полей.

### `profileTabVoice`

- ID: `-461960914` / `0xe477092e`
- Сигнатура: `profileTabVoice() => ProfileTab`
- Официальная страница конструктора: https://core.telegram.org/constructor/profileTabVoice
- Поля:
  - Нет полей.

## `PublicForward`

- Официальный тип: https://core.telegram.org/type/PublicForward
- Количество constructors: **2**

### `publicForwardMessage`

- ID: `32685898` / `0x01f2bf4a`
- Сигнатура: `publicForwardMessage(message:Message) => PublicForward`
- Официальная страница конструктора: https://core.telegram.org/constructor/publicForwardMessage
- Поля:
  - `message`: `Message`

### `publicForwardStory`

- ID: `-302797360` / `0xedf3add0`
- Сигнатура: `publicForwardStory(peer:Peer, story:StoryItem) => PublicForward`
- Официальная страница конструктора: https://core.telegram.org/constructor/publicForwardStory
- Поля:
  - `peer`: `Peer`
  - `story`: `StoryItem`

## `QuickReply`

- Официальный тип: https://core.telegram.org/type/QuickReply
- Количество constructors: **1**

### `quickReply`

- ID: `110563371` / `0x0697102b`
- Сигнатура: `quickReply(shortcut_id:int, shortcut:string, top_message:int, count:int) => QuickReply`
- Официальная страница конструктора: https://core.telegram.org/constructor/quickReply
- Поля:
  - `shortcut_id`: `int`
  - `shortcut`: `string`
  - `top_message`: `int`
  - `count`: `int`

## `Reaction`

- Официальный тип: https://core.telegram.org/type/Reaction
- Количество constructors: **4**

### `reactionCustomEmoji`

- ID: `-1992950669` / `0x8935fc73`
- Сигнатура: `reactionCustomEmoji(document_id:long) => Reaction`
- Официальная страница конструктора: https://core.telegram.org/constructor/reactionCustomEmoji
- Поля:
  - `document_id`: `long`

### `reactionEmoji`

- ID: `455247544` / `0x1b2286b8`
- Сигнатура: `reactionEmoji(emoticon:string) => Reaction`
- Официальная страница конструктора: https://core.telegram.org/constructor/reactionEmoji
- Поля:
  - `emoticon`: `string`

### `reactionEmpty`

- ID: `2046153753` / `0x79f5d419`
- Сигнатура: `reactionEmpty() => Reaction`
- Официальная страница конструктора: https://core.telegram.org/constructor/reactionEmpty
- Поля:
  - Нет полей.

### `reactionPaid`

- ID: `1379771627` / `0x523da4eb`
- Сигнатура: `reactionPaid() => Reaction`
- Официальная страница конструктора: https://core.telegram.org/constructor/reactionPaid
- Поля:
  - Нет полей.

## `ReactionCount`

- Официальный тип: https://core.telegram.org/type/ReactionCount
- Количество constructors: **1**

### `reactionCount`

- ID: `-1546531968` / `0xa3d1cb80`
- Сигнатура: `reactionCount(flags:#, chosen_order:flags.0?int, reaction:Reaction, count:int) => ReactionCount`
- Официальная страница конструктора: https://core.telegram.org/constructor/reactionCount
- Поля:
  - `flags`: `#` - служебное поле flags
  - `chosen_order`: `flags.0?int` - optional через flags.0
  - `reaction`: `Reaction`
  - `count`: `int`

## `ReactionNotificationsFrom`

- Официальный тип: https://core.telegram.org/type/ReactionNotificationsFrom
- Количество constructors: **2**

### `reactionNotificationsFromAll`

- ID: `1268654752` / `0x4b9e22a0`
- Сигнатура: `reactionNotificationsFromAll() => ReactionNotificationsFrom`
- Официальная страница конструктора: https://core.telegram.org/constructor/reactionNotificationsFromAll
- Поля:
  - Нет полей.

### `reactionNotificationsFromContacts`

- ID: `-1161583078` / `0xbac3a61a`
- Сигнатура: `reactionNotificationsFromContacts() => ReactionNotificationsFrom`
- Официальная страница конструктора: https://core.telegram.org/constructor/reactionNotificationsFromContacts
- Поля:
  - Нет полей.

## `ReactionsNotifySettings`

- Официальный тип: https://core.telegram.org/type/ReactionsNotifySettings
- Количество constructors: **1**

### `reactionsNotifySettings`

- ID: `1457736048` / `0x56e34970`
- Сигнатура: `reactionsNotifySettings(flags:#, messages_notify_from:flags.0?ReactionNotificationsFrom, stories_notify_from:flags.1?ReactionNotificationsFrom, sound:NotificationSound, show_previews:Bool) => ReactionsNotifySettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/reactionsNotifySettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `messages_notify_from`: `flags.0?ReactionNotificationsFrom` - optional через flags.0
  - `stories_notify_from`: `flags.1?ReactionNotificationsFrom` - optional через flags.1
  - `sound`: `NotificationSound`
  - `show_previews`: `Bool`

## `ReadParticipantDate`

- Официальный тип: https://core.telegram.org/type/ReadParticipantDate
- Количество constructors: **1**

### `readParticipantDate`

- ID: `1246753138` / `0x4a4ff172`
- Сигнатура: `readParticipantDate(user_id:long, date:int) => ReadParticipantDate`
- Официальная страница конструктора: https://core.telegram.org/constructor/readParticipantDate
- Поля:
  - `user_id`: `long`
  - `date`: `int`

## `ReceivedNotifyMessage`

- Официальный тип: https://core.telegram.org/type/ReceivedNotifyMessage
- Количество constructors: **1**

### `receivedNotifyMessage`

- ID: `-1551583367` / `0xa384b779`
- Сигнатура: `receivedNotifyMessage(id:int, flags:int) => ReceivedNotifyMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/receivedNotifyMessage
- Поля:
  - `id`: `int`
  - `flags`: `int`

## `RecentMeUrl`

- Официальный тип: https://core.telegram.org/type/RecentMeUrl
- Количество constructors: **5**

### `recentMeUrlChat`

- ID: `-1294306862` / `0xb2da71d2`
- Сигнатура: `recentMeUrlChat(url:string, chat_id:long) => RecentMeUrl`
- Официальная страница конструктора: https://core.telegram.org/constructor/recentMeUrlChat
- Поля:
  - `url`: `string`
  - `chat_id`: `long`

### `recentMeUrlChatInvite`

- ID: `-347535331` / `0xeb49081d`
- Сигнатура: `recentMeUrlChatInvite(url:string, chat_invite:ChatInvite) => RecentMeUrl`
- Официальная страница конструктора: https://core.telegram.org/constructor/recentMeUrlChatInvite
- Поля:
  - `url`: `string`
  - `chat_invite`: `ChatInvite`

### `recentMeUrlStickerSet`

- ID: `-1140172836` / `0xbc0a57dc`
- Сигнатура: `recentMeUrlStickerSet(url:string, set:StickerSetCovered) => RecentMeUrl`
- Официальная страница конструктора: https://core.telegram.org/constructor/recentMeUrlStickerSet
- Поля:
  - `url`: `string`
  - `set`: `StickerSetCovered`

### `recentMeUrlUnknown`

- ID: `1189204285` / `0x46e1d13d`
- Сигнатура: `recentMeUrlUnknown(url:string) => RecentMeUrl`
- Официальная страница конструктора: https://core.telegram.org/constructor/recentMeUrlUnknown
- Поля:
  - `url`: `string`

### `recentMeUrlUser`

- ID: `-1188296222` / `0xb92c09e2`
- Сигнатура: `recentMeUrlUser(url:string, user_id:long) => RecentMeUrl`
- Официальная страница конструктора: https://core.telegram.org/constructor/recentMeUrlUser
- Поля:
  - `url`: `string`
  - `user_id`: `long`

## `ReplyMarkup`

- Официальный тип: https://core.telegram.org/type/ReplyMarkup
- Количество constructors: **4**

### `replyInlineMarkup`

- ID: `1218642516` / `0x48a30254`
- Сигнатура: `replyInlineMarkup(rows:Vector) => ReplyMarkup`
- Официальная страница конструктора: https://core.telegram.org/constructor/replyInlineMarkup
- Поля:
  - `rows`: `Vector`

### `replyKeyboardForceReply`

- ID: `-2035021048` / `0x86b40b08`
- Сигнатура: `replyKeyboardForceReply(flags:#, single_use:flags.1?true, selective:flags.2?true, placeholder:flags.3?string) => ReplyMarkup`
- Официальная страница конструктора: https://core.telegram.org/constructor/replyKeyboardForceReply
- Поля:
  - `flags`: `#` - служебное поле flags
  - `single_use`: `flags.1?true` - optional через flags.1
  - `selective`: `flags.2?true` - optional через flags.2
  - `placeholder`: `flags.3?string` - optional через flags.3

### `replyKeyboardHide`

- ID: `-1606526075` / `0xa03e5b85`
- Сигнатура: `replyKeyboardHide(flags:#, selective:flags.2?true) => ReplyMarkup`
- Официальная страница конструктора: https://core.telegram.org/constructor/replyKeyboardHide
- Поля:
  - `flags`: `#` - служебное поле flags
  - `selective`: `flags.2?true` - optional через flags.2

### `replyKeyboardMarkup`

- ID: `-2049074735` / `0x85dd99d1`
- Сигнатура: `replyKeyboardMarkup(flags:#, resize:flags.0?true, single_use:flags.1?true, selective:flags.2?true, persistent:flags.4?true, rows:Vector, placeholder:flags.3?string) => ReplyMarkup`
- Официальная страница конструктора: https://core.telegram.org/constructor/replyKeyboardMarkup
- Поля:
  - `flags`: `#` - служебное поле flags
  - `resize`: `flags.0?true` - optional через flags.0
  - `single_use`: `flags.1?true` - optional через flags.1
  - `selective`: `flags.2?true` - optional через flags.2
  - `persistent`: `flags.4?true` - optional через flags.4
  - `rows`: `Vector`
  - `placeholder`: `flags.3?string` - optional через flags.3

## `ReportReason`

- Официальный тип: https://core.telegram.org/type/ReportReason
- Количество constructors: **10**

### `inputReportReasonChildAbuse`

- ID: `-1376497949` / `0xadf44ee3`
- Сигнатура: `inputReportReasonChildAbuse() => ReportReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReportReasonChildAbuse
- Поля:
  - Нет полей.

### `inputReportReasonCopyright`

- ID: `-1685456582` / `0x9b89f93a`
- Сигнатура: `inputReportReasonCopyright() => ReportReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReportReasonCopyright
- Поля:
  - Нет полей.

### `inputReportReasonFake`

- ID: `-170010905` / `0xf5ddd6e7`
- Сигнатура: `inputReportReasonFake() => ReportReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReportReasonFake
- Поля:
  - Нет полей.

### `inputReportReasonGeoIrrelevant`

- ID: `-606798099` / `0xdbd4feed`
- Сигнатура: `inputReportReasonGeoIrrelevant() => ReportReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReportReasonGeoIrrelevant
- Поля:
  - Нет полей.

### `inputReportReasonIllegalDrugs`

- ID: `177124030` / `0x0a8eb2be`
- Сигнатура: `inputReportReasonIllegalDrugs() => ReportReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReportReasonIllegalDrugs
- Поля:
  - Нет полей.

### `inputReportReasonOther`

- ID: `-1041980751` / `0xc1e4a2b1`
- Сигнатура: `inputReportReasonOther() => ReportReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReportReasonOther
- Поля:
  - Нет полей.

### `inputReportReasonPersonalDetails`

- ID: `-1631091139` / `0x9ec7863d`
- Сигнатура: `inputReportReasonPersonalDetails() => ReportReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReportReasonPersonalDetails
- Поля:
  - Нет полей.

### `inputReportReasonPornography`

- ID: `777640226` / `0x2e59d922`
- Сигнатура: `inputReportReasonPornography() => ReportReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReportReasonPornography
- Поля:
  - Нет полей.

### `inputReportReasonSpam`

- ID: `1490799288` / `0x58dbcab8`
- Сигнатура: `inputReportReasonSpam() => ReportReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReportReasonSpam
- Поля:
  - Нет полей.

### `inputReportReasonViolence`

- ID: `505595789` / `0x1e22c78d`
- Сигнатура: `inputReportReasonViolence() => ReportReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/inputReportReasonViolence
- Поля:
  - Нет полей.

## `ReportResult`

- Официальный тип: https://core.telegram.org/type/ReportResult
- Количество constructors: **3**

### `reportResultAddComment`

- ID: `1862904881` / `0x6f09ac31`
- Сигнатура: `reportResultAddComment(flags:#, optional:flags.0?true, option:bytes) => ReportResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/reportResultAddComment
- Поля:
  - `flags`: `#` - служебное поле flags
  - `optional`: `flags.0?true` - optional через flags.0
  - `option`: `bytes`

### `reportResultChooseOption`

- ID: `-253435722` / `0xf0e4e0b6`
- Сигнатура: `reportResultChooseOption(title:string, options:Vector) => ReportResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/reportResultChooseOption
- Поля:
  - `title`: `string`
  - `options`: `Vector`

### `reportResultReported`

- ID: `-1917633461` / `0x8db33c4b`
- Сигнатура: `reportResultReported() => ReportResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/reportResultReported
- Поля:
  - Нет полей.

## `RequestPeerType`

- Официальный тип: https://core.telegram.org/type/RequestPeerType
- Количество constructors: **3**

### `requestPeerTypeBroadcast`

- ID: `865857388` / `0x339bef6c`
- Сигнатура: `requestPeerTypeBroadcast(flags:#, creator:flags.0?true, has_username:flags.3?Bool, user_admin_rights:flags.1?ChatAdminRights, bot_admin_rights:flags.2?ChatAdminRights) => RequestPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/requestPeerTypeBroadcast
- Поля:
  - `flags`: `#` - служебное поле flags
  - `creator`: `flags.0?true` - optional через flags.0
  - `has_username`: `flags.3?Bool` - optional через flags.3
  - `user_admin_rights`: `flags.1?ChatAdminRights` - optional через flags.1
  - `bot_admin_rights`: `flags.2?ChatAdminRights` - optional через flags.2

### `requestPeerTypeChat`

- ID: `-906990053` / `0xc9f06e1b`
- Сигнатура: `requestPeerTypeChat(flags:#, creator:flags.0?true, bot_participant:flags.5?true, has_username:flags.3?Bool, forum:flags.4?Bool, user_admin_rights:flags.1?ChatAdminRights, bot_admin_rights:flags.2?ChatAdminRights) => RequestPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/requestPeerTypeChat
- Поля:
  - `flags`: `#` - служебное поле flags
  - `creator`: `flags.0?true` - optional через flags.0
  - `bot_participant`: `flags.5?true` - optional через flags.5
  - `has_username`: `flags.3?Bool` - optional через flags.3
  - `forum`: `flags.4?Bool` - optional через flags.4
  - `user_admin_rights`: `flags.1?ChatAdminRights` - optional через flags.1
  - `bot_admin_rights`: `flags.2?ChatAdminRights` - optional через flags.2

### `requestPeerTypeUser`

- ID: `1597737472` / `0x5f3b8a00`
- Сигнатура: `requestPeerTypeUser(flags:#, bot:flags.0?Bool, premium:flags.1?Bool) => RequestPeerType`
- Официальная страница конструктора: https://core.telegram.org/constructor/requestPeerTypeUser
- Поля:
  - `flags`: `#` - служебное поле flags
  - `bot`: `flags.0?Bool` - optional через flags.0
  - `premium`: `flags.1?Bool` - optional через flags.1

## `RequestedPeer`

- Официальный тип: https://core.telegram.org/type/RequestedPeer
- Количество constructors: **3**

### `requestedPeerChannel`

- ID: `-1952185372` / `0x8ba403e4`
- Сигнатура: `requestedPeerChannel(flags:#, channel_id:long, title:flags.0?string, username:flags.1?string, photo:flags.2?Photo) => RequestedPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/requestedPeerChannel
- Поля:
  - `flags`: `#` - служебное поле flags
  - `channel_id`: `long`
  - `title`: `flags.0?string` - optional через flags.0
  - `username`: `flags.1?string` - optional через flags.1
  - `photo`: `flags.2?Photo` - optional через flags.2

### `requestedPeerChat`

- ID: `1929860175` / `0x7307544f`
- Сигнатура: `requestedPeerChat(flags:#, chat_id:long, title:flags.0?string, photo:flags.2?Photo) => RequestedPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/requestedPeerChat
- Поля:
  - `flags`: `#` - служебное поле flags
  - `chat_id`: `long`
  - `title`: `flags.0?string` - optional через flags.0
  - `photo`: `flags.2?Photo` - optional через flags.2

### `requestedPeerUser`

- ID: `-701500310` / `0xd62ff46a`
- Сигнатура: `requestedPeerUser(flags:#, user_id:long, first_name:flags.0?string, last_name:flags.0?string, username:flags.1?string, photo:flags.2?Photo) => RequestedPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/requestedPeerUser
- Поля:
  - `flags`: `#` - служебное поле flags
  - `user_id`: `long`
  - `first_name`: `flags.0?string` - optional через flags.0
  - `last_name`: `flags.0?string` - optional через flags.0
  - `username`: `flags.1?string` - optional через flags.1
  - `photo`: `flags.2?Photo` - optional через flags.2

## `RequirementToContact`

- Официальный тип: https://core.telegram.org/type/RequirementToContact
- Количество constructors: **3**

### `requirementToContactEmpty`

- ID: `84580409` / `0x050a9839`
- Сигнатура: `requirementToContactEmpty() => RequirementToContact`
- Официальная страница конструктора: https://core.telegram.org/constructor/requirementToContactEmpty
- Поля:
  - Нет полей.

### `requirementToContactPaidMessages`

- ID: `-1258914157` / `0xb4f67e93`
- Сигнатура: `requirementToContactPaidMessages(stars_amount:long) => RequirementToContact`
- Официальная страница конструктора: https://core.telegram.org/constructor/requirementToContactPaidMessages
- Поля:
  - `stars_amount`: `long`

### `requirementToContactPremium`

- ID: `-444472087` / `0xe581e4e9`
- Сигнатура: `requirementToContactPremium() => RequirementToContact`
- Официальная страница конструктора: https://core.telegram.org/constructor/requirementToContactPremium
- Поля:
  - Нет полей.

## `RestrictionReason`

- Официальный тип: https://core.telegram.org/type/RestrictionReason
- Количество constructors: **1**

### `restrictionReason`

- ID: `-797791052` / `0xd072acb4`
- Сигнатура: `restrictionReason(platform:string, reason:string, text:string) => RestrictionReason`
- Официальная страница конструктора: https://core.telegram.org/constructor/restrictionReason
- Поля:
  - `platform`: `string`
  - `reason`: `string`
  - `text`: `string`

## `RichText`

- Официальный тип: https://core.telegram.org/type/RichText
- Количество constructors: **16**

### `textAnchor`

- ID: `894777186` / `0x35553762`
- Сигнатура: `textAnchor(text:RichText, name:string) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textAnchor
- Поля:
  - `text`: `RichText`
  - `name`: `string`

### `textBold`

- ID: `1730456516` / `0x6724abc4`
- Сигнатура: `textBold(text:RichText) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textBold
- Поля:
  - `text`: `RichText`

### `textConcat`

- ID: `2120376535` / `0x7e6260d7`
- Сигнатура: `textConcat(texts:Vector) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textConcat
- Поля:
  - `texts`: `Vector`

### `textEmail`

- ID: `-564523562` / `0xde5a0dd6`
- Сигнатура: `textEmail(text:RichText, email:string) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textEmail
- Поля:
  - `text`: `RichText`
  - `email`: `string`

### `textEmpty`

- ID: `-599948721` / `0xdc3d824f`
- Сигнатура: `textEmpty() => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textEmpty
- Поля:
  - Нет полей.

### `textFixed`

- ID: `1816074681` / `0x6c3f19b9`
- Сигнатура: `textFixed(text:RichText) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textFixed
- Поля:
  - `text`: `RichText`

### `textImage`

- ID: `136105807` / `0x081ccf4f`
- Сигнатура: `textImage(document_id:long, w:int, h:int) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textImage
- Поля:
  - `document_id`: `long`
  - `w`: `int`
  - `h`: `int`

### `textItalic`

- ID: `-653089380` / `0xd912a59c`
- Сигнатура: `textItalic(text:RichText) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textItalic
- Поля:
  - `text`: `RichText`

### `textMarked`

- ID: `55281185` / `0x034b8621`
- Сигнатура: `textMarked(text:RichText) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textMarked
- Поля:
  - `text`: `RichText`

### `textPhone`

- ID: `483104362` / `0x1ccb966a`
- Сигнатура: `textPhone(text:RichText, phone:string) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textPhone
- Поля:
  - `text`: `RichText`
  - `phone`: `string`

### `textPlain`

- ID: `1950782688` / `0x744694e0`
- Сигнатура: `textPlain(text:string) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textPlain
- Поля:
  - `text`: `string`

### `textStrike`

- ID: `-1678197867` / `0x9bf8bb95`
- Сигнатура: `textStrike(text:RichText) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textStrike
- Поля:
  - `text`: `RichText`

### `textSubscript`

- ID: `-311786236` / `0xed6a8504`
- Сигнатура: `textSubscript(text:RichText) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textSubscript
- Поля:
  - `text`: `RichText`

### `textSuperscript`

- ID: `-939827711` / `0xc7fb5e01`
- Сигнатура: `textSuperscript(text:RichText) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textSuperscript
- Поля:
  - `text`: `RichText`

### `textUnderline`

- ID: `-1054465340` / `0xc12622c4`
- Сигнатура: `textUnderline(text:RichText) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textUnderline
- Поля:
  - `text`: `RichText`

### `textUrl`

- ID: `1009288385` / `0x3c2884c1`
- Сигнатура: `textUrl(text:RichText, url:string, webpage_id:long) => RichText`
- Официальная страница конструктора: https://core.telegram.org/constructor/textUrl
- Поля:
  - `text`: `RichText`
  - `url`: `string`
  - `webpage_id`: `long`

## `SavedContact`

- Официальный тип: https://core.telegram.org/type/SavedContact
- Количество constructors: **1**

### `savedPhoneContact`

- ID: `289586518` / `0x1142bd56`
- Сигнатура: `savedPhoneContact(phone:string, first_name:string, last_name:string, date:int) => SavedContact`
- Официальная страница конструктора: https://core.telegram.org/constructor/savedPhoneContact
- Поля:
  - `phone`: `string`
  - `first_name`: `string`
  - `last_name`: `string`
  - `date`: `int`

## `SavedDialog`

- Официальный тип: https://core.telegram.org/type/SavedDialog
- Количество constructors: **2**

### `monoForumDialog`

- ID: `1681948327` / `0x64407ea7`
- Сигнатура: `monoForumDialog(flags:#, unread_mark:flags.3?true, nopaid_messages_exception:flags.4?true, peer:Peer, top_message:int, read_inbox_max_id:int, read_outbox_max_id:int, unread_count:int, unread_reactions_count:int, draft:flags.1?DraftMessage) => SavedDialog`
- Официальная страница конструктора: https://core.telegram.org/constructor/monoForumDialog
- Поля:
  - `flags`: `#` - служебное поле flags
  - `unread_mark`: `flags.3?true` - optional через flags.3
  - `nopaid_messages_exception`: `flags.4?true` - optional через flags.4
  - `peer`: `Peer`
  - `top_message`: `int`
  - `read_inbox_max_id`: `int`
  - `read_outbox_max_id`: `int`
  - `unread_count`: `int`
  - `unread_reactions_count`: `int`
  - `draft`: `flags.1?DraftMessage` - optional через flags.1

### `savedDialog`

- ID: `-1115174036` / `0xbd87cb6c`
- Сигнатура: `savedDialog(flags:#, pinned:flags.2?true, peer:Peer, top_message:int) => SavedDialog`
- Официальная страница конструктора: https://core.telegram.org/constructor/savedDialog
- Поля:
  - `flags`: `#` - служебное поле flags
  - `pinned`: `flags.2?true` - optional через flags.2
  - `peer`: `Peer`
  - `top_message`: `int`

## `SavedReactionTag`

- Официальный тип: https://core.telegram.org/type/SavedReactionTag
- Количество constructors: **1**

### `savedReactionTag`

- ID: `-881854424` / `0xcb6ff828`
- Сигнатура: `savedReactionTag(flags:#, reaction:Reaction, title:flags.0?string, count:int) => SavedReactionTag`
- Официальная страница конструктора: https://core.telegram.org/constructor/savedReactionTag
- Поля:
  - `flags`: `#` - служебное поле flags
  - `reaction`: `Reaction`
  - `title`: `flags.0?string` - optional через flags.0
  - `count`: `int`

## `SavedStarGift`

- Официальный тип: https://core.telegram.org/type/SavedStarGift
- Количество constructors: **1**

### `savedStarGift`

- ID: `430552434` / `0x19a9b572`
- Сигнатура: `savedStarGift(flags:#, name_hidden:flags.0?true, unsaved:flags.5?true, refunded:flags.9?true, can_upgrade:flags.10?true, pinned_to_top:flags.12?true, upgrade_separate:flags.17?true, from_id:flags.1?Peer, date:int, gift:StarGift, message:flags.2?TextWithEntities, msg_id:flags.3?int, saved_id:flags.11?long, convert_stars:flags.4?long, upgrade_stars:flags.6?long, can_export_at:flags.7?int, transfer_stars:flags.8?long, can_transfer_at:flags.13?int, can_resell_at:flags.14?int, collection_id:flags.15?Vector, prepaid_upgrade_hash:flags.16?string) => SavedStarGift`
- Официальная страница конструктора: https://core.telegram.org/constructor/savedStarGift
- Поля:
  - `flags`: `#` - служебное поле flags
  - `name_hidden`: `flags.0?true` - optional через flags.0
  - `unsaved`: `flags.5?true` - optional через flags.5
  - `refunded`: `flags.9?true` - optional через flags.9
  - `can_upgrade`: `flags.10?true` - optional через flags.10
  - `pinned_to_top`: `flags.12?true` - optional через flags.12
  - `upgrade_separate`: `flags.17?true` - optional через flags.17
  - `from_id`: `flags.1?Peer` - optional через flags.1
  - `date`: `int`
  - `gift`: `StarGift`
  - `message`: `flags.2?TextWithEntities` - optional через flags.2
  - `msg_id`: `flags.3?int` - optional через flags.3
  - `saved_id`: `flags.11?long` - optional через flags.11
  - `convert_stars`: `flags.4?long` - optional через flags.4
  - `upgrade_stars`: `flags.6?long` - optional через flags.6
  - `can_export_at`: `flags.7?int` - optional через flags.7
  - `transfer_stars`: `flags.8?long` - optional через flags.8
  - `can_transfer_at`: `flags.13?int` - optional через flags.13
  - `can_resell_at`: `flags.14?int` - optional через flags.14
  - `collection_id`: `flags.15?Vector` - optional через flags.15
  - `prepaid_upgrade_hash`: `flags.16?string` - optional через flags.16

## `SearchPostsFlood`

- Официальный тип: https://core.telegram.org/type/SearchPostsFlood
- Количество constructors: **1**

### `searchPostsFlood`

- ID: `1040931690` / `0x3e0b5b6a`
- Сигнатура: `searchPostsFlood(flags:#, query_is_free:flags.0?true, total_daily:int, remains:int, wait_till:flags.1?int, stars_amount:long) => SearchPostsFlood`
- Официальная страница конструктора: https://core.telegram.org/constructor/searchPostsFlood
- Поля:
  - `flags`: `#` - служебное поле flags
  - `query_is_free`: `flags.0?true` - optional через flags.0
  - `total_daily`: `int`
  - `remains`: `int`
  - `wait_till`: `flags.1?int` - optional через flags.1
  - `stars_amount`: `long`

## `SearchResultsCalendarPeriod`

- Официальный тип: https://core.telegram.org/type/SearchResultsCalendarPeriod
- Количество constructors: **1**

### `searchResultsCalendarPeriod`

- ID: `-911191137` / `0xc9b0539f`
- Сигнатура: `searchResultsCalendarPeriod(date:int, min_msg_id:int, max_msg_id:int, count:int) => SearchResultsCalendarPeriod`
- Официальная страница конструктора: https://core.telegram.org/constructor/searchResultsCalendarPeriod
- Поля:
  - `date`: `int`
  - `min_msg_id`: `int`
  - `max_msg_id`: `int`
  - `count`: `int`

## `SearchResultsPosition`

- Официальный тип: https://core.telegram.org/type/SearchResultsPosition
- Количество constructors: **1**

### `searchResultPosition`

- ID: `2137295719` / `0x7f648b67`
- Сигнатура: `searchResultPosition(msg_id:int, date:int, offset:int) => SearchResultsPosition`
- Официальная страница конструктора: https://core.telegram.org/constructor/searchResultPosition
- Поля:
  - `msg_id`: `int`
  - `date`: `int`
  - `offset`: `int`

## `SecureCredentialsEncrypted`

- Официальный тип: https://core.telegram.org/type/SecureCredentialsEncrypted
- Количество constructors: **1**

### `secureCredentialsEncrypted`

- ID: `871426631` / `0x33f0ea47`
- Сигнатура: `secureCredentialsEncrypted(data:bytes, hash:bytes, secret:bytes) => SecureCredentialsEncrypted`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureCredentialsEncrypted
- Поля:
  - `data`: `bytes`
  - `hash`: `bytes`
  - `secret`: `bytes`

## `SecureData`

- Официальный тип: https://core.telegram.org/type/SecureData
- Количество constructors: **1**

### `secureData`

- ID: `-1964327229` / `0x8aeabec3`
- Сигнатура: `secureData(data:bytes, data_hash:bytes, secret:bytes) => SecureData`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureData
- Поля:
  - `data`: `bytes`
  - `data_hash`: `bytes`
  - `secret`: `bytes`

## `SecureFile`

- Официальный тип: https://core.telegram.org/type/SecureFile
- Количество constructors: **2**

### `secureFile`

- ID: `2097791614` / `0x7d09c27e`
- Сигнатура: `secureFile(id:long, access_hash:long, size:long, dc_id:int, date:int, file_hash:bytes, secret:bytes) => SecureFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureFile
- Поля:
  - `id`: `long`
  - `access_hash`: `long`
  - `size`: `long`
  - `dc_id`: `int`
  - `date`: `int`
  - `file_hash`: `bytes`
  - `secret`: `bytes`

### `secureFileEmpty`

- ID: `1679398724` / `0x64199744`
- Сигнатура: `secureFileEmpty() => SecureFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureFileEmpty
- Поля:
  - Нет полей.

## `SecurePasswordKdfAlgo`

- Официальный тип: https://core.telegram.org/type/SecurePasswordKdfAlgo
- Количество constructors: **3**

### `securePasswordKdfAlgoPBKDF2HMACSHA512iter100000`

- ID: `-1141711456` / `0xbbf2dda0`
- Сигнатура: `securePasswordKdfAlgoPBKDF2HMACSHA512iter100000(salt:bytes) => SecurePasswordKdfAlgo`
- Официальная страница конструктора: https://core.telegram.org/constructor/securePasswordKdfAlgoPBKDF2HMACSHA512iter100000
- Поля:
  - `salt`: `bytes`

### `securePasswordKdfAlgoSHA512`

- ID: `-2042159726` / `0x86471d92`
- Сигнатура: `securePasswordKdfAlgoSHA512(salt:bytes) => SecurePasswordKdfAlgo`
- Официальная страница конструктора: https://core.telegram.org/constructor/securePasswordKdfAlgoSHA512
- Поля:
  - `salt`: `bytes`

### `securePasswordKdfAlgoUnknown`

- ID: `4883767` / `0x004a8537`
- Сигнатура: `securePasswordKdfAlgoUnknown() => SecurePasswordKdfAlgo`
- Официальная страница конструктора: https://core.telegram.org/constructor/securePasswordKdfAlgoUnknown
- Поля:
  - Нет полей.

## `SecurePlainData`

- Официальный тип: https://core.telegram.org/type/SecurePlainData
- Количество constructors: **2**

### `securePlainEmail`

- ID: `569137759` / `0x21ec5a5f`
- Сигнатура: `securePlainEmail(email:string) => SecurePlainData`
- Официальная страница конструктора: https://core.telegram.org/constructor/securePlainEmail
- Поля:
  - `email`: `string`

### `securePlainPhone`

- ID: `2103482845` / `0x7d6099dd`
- Сигнатура: `securePlainPhone(phone:string) => SecurePlainData`
- Официальная страница конструктора: https://core.telegram.org/constructor/securePlainPhone
- Поля:
  - `phone`: `string`

## `SecureRequiredType`

- Официальный тип: https://core.telegram.org/type/SecureRequiredType
- Количество constructors: **2**

### `secureRequiredType`

- ID: `-2103600678` / `0x829d99da`
- Сигнатура: `secureRequiredType(flags:#, native_names:flags.0?true, selfie_required:flags.1?true, translation_required:flags.2?true, type:SecureValueType) => SecureRequiredType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureRequiredType
- Поля:
  - `flags`: `#` - служебное поле flags
  - `native_names`: `flags.0?true` - optional через flags.0
  - `selfie_required`: `flags.1?true` - optional через flags.1
  - `translation_required`: `flags.2?true` - optional через flags.2
  - `type`: `SecureValueType`

### `secureRequiredTypeOneOf`

- ID: `41187252` / `0x027477b4`
- Сигнатура: `secureRequiredTypeOneOf(types:Vector) => SecureRequiredType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureRequiredTypeOneOf
- Поля:
  - `types`: `Vector`

## `SecureSecretSettings`

- Официальный тип: https://core.telegram.org/type/SecureSecretSettings
- Количество constructors: **1**

### `secureSecretSettings`

- ID: `354925740` / `0x1527bcac`
- Сигнатура: `secureSecretSettings(secure_algo:SecurePasswordKdfAlgo, secure_secret:bytes, secure_secret_id:long) => SecureSecretSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureSecretSettings
- Поля:
  - `secure_algo`: `SecurePasswordKdfAlgo`
  - `secure_secret`: `bytes`
  - `secure_secret_id`: `long`

## `SecureValue`

- Официальный тип: https://core.telegram.org/type/SecureValue
- Количество constructors: **1**

### `secureValue`

- ID: `411017418` / `0x187fa0ca`
- Сигнатура: `secureValue(flags:#, type:SecureValueType, data:flags.0?SecureData, front_side:flags.1?SecureFile, reverse_side:flags.2?SecureFile, selfie:flags.3?SecureFile, translation:flags.6?Vector, files:flags.4?Vector, plain_data:flags.5?SecurePlainData, hash:bytes) => SecureValue`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValue
- Поля:
  - `flags`: `#` - служебное поле flags
  - `type`: `SecureValueType`
  - `data`: `flags.0?SecureData` - optional через flags.0
  - `front_side`: `flags.1?SecureFile` - optional через flags.1
  - `reverse_side`: `flags.2?SecureFile` - optional через flags.2
  - `selfie`: `flags.3?SecureFile` - optional через flags.3
  - `translation`: `flags.6?Vector` - optional через flags.6
  - `files`: `flags.4?Vector` - optional через flags.4
  - `plain_data`: `flags.5?SecurePlainData` - optional через flags.5
  - `hash`: `bytes`

## `SecureValueError`

- Официальный тип: https://core.telegram.org/type/SecureValueError
- Количество constructors: **9**

### `secureValueError`

- ID: `-2036501105` / `0x869d758f`
- Сигнатура: `secureValueError(type:SecureValueType, hash:bytes, text:string) => SecureValueError`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueError
- Поля:
  - `type`: `SecureValueType`
  - `hash`: `bytes`
  - `text`: `string`

### `secureValueErrorData`

- ID: `-391902247` / `0xe8a40bd9`
- Сигнатура: `secureValueErrorData(type:SecureValueType, data_hash:bytes, field:string, text:string) => SecureValueError`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueErrorData
- Поля:
  - `type`: `SecureValueType`
  - `data_hash`: `bytes`
  - `field`: `string`
  - `text`: `string`

### `secureValueErrorFile`

- ID: `2054162547` / `0x7a700873`
- Сигнатура: `secureValueErrorFile(type:SecureValueType, file_hash:bytes, text:string) => SecureValueError`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueErrorFile
- Поля:
  - `type`: `SecureValueType`
  - `file_hash`: `bytes`
  - `text`: `string`

### `secureValueErrorFiles`

- ID: `1717706985` / `0x666220e9`
- Сигнатура: `secureValueErrorFiles(type:SecureValueType, file_hash:Vector, text:string) => SecureValueError`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueErrorFiles
- Поля:
  - `type`: `SecureValueType`
  - `file_hash`: `Vector`
  - `text`: `string`

### `secureValueErrorFrontSide`

- ID: `12467706` / `0x00be3dfa`
- Сигнатура: `secureValueErrorFrontSide(type:SecureValueType, file_hash:bytes, text:string) => SecureValueError`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueErrorFrontSide
- Поля:
  - `type`: `SecureValueType`
  - `file_hash`: `bytes`
  - `text`: `string`

### `secureValueErrorReverseSide`

- ID: `-2037765467` / `0x868a2aa5`
- Сигнатура: `secureValueErrorReverseSide(type:SecureValueType, file_hash:bytes, text:string) => SecureValueError`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueErrorReverseSide
- Поля:
  - `type`: `SecureValueType`
  - `file_hash`: `bytes`
  - `text`: `string`

### `secureValueErrorSelfie`

- ID: `-449327402` / `0xe537ced6`
- Сигнатура: `secureValueErrorSelfie(type:SecureValueType, file_hash:bytes, text:string) => SecureValueError`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueErrorSelfie
- Поля:
  - `type`: `SecureValueType`
  - `file_hash`: `bytes`
  - `text`: `string`

### `secureValueErrorTranslationFile`

- ID: `-1592506512` / `0xa1144770`
- Сигнатура: `secureValueErrorTranslationFile(type:SecureValueType, file_hash:bytes, text:string) => SecureValueError`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueErrorTranslationFile
- Поля:
  - `type`: `SecureValueType`
  - `file_hash`: `bytes`
  - `text`: `string`

### `secureValueErrorTranslationFiles`

- ID: `878931416` / `0x34636dd8`
- Сигнатура: `secureValueErrorTranslationFiles(type:SecureValueType, file_hash:Vector, text:string) => SecureValueError`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueErrorTranslationFiles
- Поля:
  - `type`: `SecureValueType`
  - `file_hash`: `Vector`
  - `text`: `string`

## `SecureValueHash`

- Официальный тип: https://core.telegram.org/type/SecureValueHash
- Количество constructors: **1**

### `secureValueHash`

- ID: `-316748368` / `0xed1ecdb0`
- Сигнатура: `secureValueHash(type:SecureValueType, hash:bytes) => SecureValueHash`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueHash
- Поля:
  - `type`: `SecureValueType`
  - `hash`: `bytes`

## `SecureValueType`

- Официальный тип: https://core.telegram.org/type/SecureValueType
- Количество constructors: **13**

### `secureValueTypeAddress`

- ID: `-874308058` / `0xcbe31e26`
- Сигнатура: `secureValueTypeAddress() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypeAddress
- Поля:
  - Нет полей.

### `secureValueTypeBankStatement`

- ID: `-1995211763` / `0x89137c0d`
- Сигнатура: `secureValueTypeBankStatement() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypeBankStatement
- Поля:
  - Нет полей.

### `secureValueTypeDriverLicense`

- ID: `115615172` / `0x06e425c4`
- Сигнатура: `secureValueTypeDriverLicense() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypeDriverLicense
- Поля:
  - Нет полей.

### `secureValueTypeEmail`

- ID: `-1908627474` / `0x8e3ca7ee`
- Сигнатура: `secureValueTypeEmail() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypeEmail
- Поля:
  - Нет полей.

### `secureValueTypeIdentityCard`

- ID: `-1596951477` / `0xa0d0744b`
- Сигнатура: `secureValueTypeIdentityCard() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypeIdentityCard
- Поля:
  - Нет полей.

### `secureValueTypeInternalPassport`

- ID: `-1717268701` / `0x99a48f23`
- Сигнатура: `secureValueTypeInternalPassport() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypeInternalPassport
- Поля:
  - Нет полей.

### `secureValueTypePassport`

- ID: `1034709504` / `0x3dac6a00`
- Сигнатура: `secureValueTypePassport() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypePassport
- Поля:
  - Нет полей.

### `secureValueTypePassportRegistration`

- ID: `-1713143702` / `0x99e3806a`
- Сигнатура: `secureValueTypePassportRegistration() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypePassportRegistration
- Поля:
  - Нет полей.

### `secureValueTypePersonalDetails`

- ID: `-1658158621` / `0x9d2a81e3`
- Сигнатура: `secureValueTypePersonalDetails() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypePersonalDetails
- Поля:
  - Нет полей.

### `secureValueTypePhone`

- ID: `-1289704741` / `0xb320aadb`
- Сигнатура: `secureValueTypePhone() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypePhone
- Поля:
  - Нет полей.

### `secureValueTypeRentalAgreement`

- ID: `-1954007928` / `0x8b883488`
- Сигнатура: `secureValueTypeRentalAgreement() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypeRentalAgreement
- Поля:
  - Нет полей.

### `secureValueTypeTemporaryRegistration`

- ID: `-368907213` / `0xea02ec33`
- Сигнатура: `secureValueTypeTemporaryRegistration() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypeTemporaryRegistration
- Поля:
  - Нет полей.

### `secureValueTypeUtilityBill`

- ID: `-63531698` / `0xfc36954e`
- Сигнатура: `secureValueTypeUtilityBill() => SecureValueType`
- Официальная страница конструктора: https://core.telegram.org/constructor/secureValueTypeUtilityBill
- Поля:
  - Нет полей.

## `SendAsPeer`

- Официальный тип: https://core.telegram.org/type/SendAsPeer
- Количество constructors: **1**

### `sendAsPeer`

- ID: `-1206095820` / `0xb81c7034`
- Сигнатура: `sendAsPeer(flags:#, premium_required:flags.0?true, peer:Peer) => SendAsPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendAsPeer
- Поля:
  - `flags`: `#` - служебное поле flags
  - `premium_required`: `flags.0?true` - optional через flags.0
  - `peer`: `Peer`

## `SendMessageAction`

- Официальный тип: https://core.telegram.org/type/SendMessageAction
- Количество constructors: **18**

### `sendMessageCancelAction`

- ID: `-44119819` / `0xfd5ec8f5`
- Сигнатура: `sendMessageCancelAction() => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageCancelAction
- Поля:
  - Нет полей.

### `sendMessageChooseContactAction`

- ID: `1653390447` / `0x628cbc6f`
- Сигнатура: `sendMessageChooseContactAction() => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageChooseContactAction
- Поля:
  - Нет полей.

### `sendMessageChooseStickerAction`

- ID: `-1336228175` / `0xb05ac6b1`
- Сигнатура: `sendMessageChooseStickerAction() => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageChooseStickerAction
- Поля:
  - Нет полей.

### `sendMessageEmojiInteraction`

- ID: `630664139` / `0x25972bcb`
- Сигнатура: `sendMessageEmojiInteraction(emoticon:string, msg_id:int, interaction:DataJSON) => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageEmojiInteraction
- Поля:
  - `emoticon`: `string`
  - `msg_id`: `int`
  - `interaction`: `DataJSON`

### `sendMessageEmojiInteractionSeen`

- ID: `-1234857938` / `0xb665902e`
- Сигнатура: `sendMessageEmojiInteractionSeen(emoticon:string) => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageEmojiInteractionSeen
- Поля:
  - `emoticon`: `string`

### `sendMessageGamePlayAction`

- ID: `-580219064` / `0xdd6a8f48`
- Сигнатура: `sendMessageGamePlayAction() => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageGamePlayAction
- Поля:
  - Нет полей.

### `sendMessageGeoLocationAction`

- ID: `393186209` / `0x176f8ba1`
- Сигнатура: `sendMessageGeoLocationAction() => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageGeoLocationAction
- Поля:
  - Нет полей.

### `sendMessageHistoryImportAction`

- ID: `-606432698` / `0xdbda9246`
- Сигнатура: `sendMessageHistoryImportAction(progress:int) => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageHistoryImportAction
- Поля:
  - `progress`: `int`

### `sendMessageRecordAudioAction`

- ID: `-718310409` / `0xd52f73f7`
- Сигнатура: `sendMessageRecordAudioAction() => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageRecordAudioAction
- Поля:
  - Нет полей.

### `sendMessageRecordRoundAction`

- ID: `-1997373508` / `0x88f27fbc`
- Сигнатура: `sendMessageRecordRoundAction() => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageRecordRoundAction
- Поля:
  - Нет полей.

### `sendMessageRecordVideoAction`

- ID: `-1584933265` / `0xa187d66f`
- Сигнатура: `sendMessageRecordVideoAction() => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageRecordVideoAction
- Поля:
  - Нет полей.

### `sendMessageTypingAction`

- ID: `381645902` / `0x16bf744e`
- Сигнатура: `sendMessageTypingAction() => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageTypingAction
- Поля:
  - Нет полей.

### `sendMessageUploadAudioAction`

- ID: `-212740181` / `0xf351d7ab`
- Сигнатура: `sendMessageUploadAudioAction(progress:int) => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageUploadAudioAction
- Поля:
  - `progress`: `int`

### `sendMessageUploadDocumentAction`

- ID: `-1441998364` / `0xaa0cd9e4`
- Сигнатура: `sendMessageUploadDocumentAction(progress:int) => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageUploadDocumentAction
- Поля:
  - `progress`: `int`

### `sendMessageUploadPhotoAction`

- ID: `-774682074` / `0xd1d34a26`
- Сигнатура: `sendMessageUploadPhotoAction(progress:int) => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageUploadPhotoAction
- Поля:
  - `progress`: `int`

### `sendMessageUploadRoundAction`

- ID: `608050278` / `0x243e1c66`
- Сигнатура: `sendMessageUploadRoundAction(progress:int) => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageUploadRoundAction
- Поля:
  - `progress`: `int`

### `sendMessageUploadVideoAction`

- ID: `-378127636` / `0xe9763aec`
- Сигнатура: `sendMessageUploadVideoAction(progress:int) => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/sendMessageUploadVideoAction
- Поля:
  - `progress`: `int`

### `speakingInGroupCallAction`

- ID: `-651419003` / `0xd92c2285`
- Сигнатура: `speakingInGroupCallAction() => SendMessageAction`
- Официальная страница конструктора: https://core.telegram.org/constructor/speakingInGroupCallAction
- Поля:
  - Нет полей.

## `ShippingOption`

- Официальный тип: https://core.telegram.org/type/ShippingOption
- Количество constructors: **1**

### `shippingOption`

- ID: `-1239335713` / `0xb6213cdf`
- Сигнатура: `shippingOption(id:string, title:string, prices:Vector) => ShippingOption`
- Официальная страница конструктора: https://core.telegram.org/constructor/shippingOption
- Поля:
  - `id`: `string`
  - `title`: `string`
  - `prices`: `Vector`

## `SmsJob`

- Официальный тип: https://core.telegram.org/type/SmsJob
- Количество constructors: **1**

### `smsJob`

- ID: `-425595208` / `0xe6a1eeb8`
- Сигнатура: `smsJob(job_id:string, phone_number:string, text:string) => SmsJob`
- Официальная страница конструктора: https://core.telegram.org/constructor/smsJob
- Поля:
  - `job_id`: `string`
  - `phone_number`: `string`
  - `text`: `string`

## `SponsoredMessage`

- Официальный тип: https://core.telegram.org/type/SponsoredMessage
- Количество constructors: **1**

### `sponsoredMessage`

- ID: `2109703795` / `0x7dbf8673`
- Сигнатура: `sponsoredMessage(flags:#, recommended:flags.5?true, can_report:flags.12?true, random_id:bytes, url:string, title:string, message:string, entities:flags.1?Vector, photo:flags.6?Photo, media:flags.14?MessageMedia, color:flags.13?PeerColor, button_text:string, sponsor_info:flags.7?string, additional_info:flags.8?string, min_display_duration:flags.15?int, max_display_duration:flags.15?int) => SponsoredMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/sponsoredMessage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `recommended`: `flags.5?true` - optional через flags.5
  - `can_report`: `flags.12?true` - optional через flags.12
  - `random_id`: `bytes`
  - `url`: `string`
  - `title`: `string`
  - `message`: `string`
  - `entities`: `flags.1?Vector` - optional через flags.1
  - `photo`: `flags.6?Photo` - optional через flags.6
  - `media`: `flags.14?MessageMedia` - optional через flags.14
  - `color`: `flags.13?PeerColor` - optional через flags.13
  - `button_text`: `string`
  - `sponsor_info`: `flags.7?string` - optional через flags.7
  - `additional_info`: `flags.8?string` - optional через flags.8
  - `min_display_duration`: `flags.15?int` - optional через flags.15
  - `max_display_duration`: `flags.15?int` - optional через flags.15

## `SponsoredMessageReportOption`

- Официальный тип: https://core.telegram.org/type/SponsoredMessageReportOption
- Количество constructors: **1**

### `sponsoredMessageReportOption`

- ID: `1124938064` / `0x430d3150`
- Сигнатура: `sponsoredMessageReportOption(text:string, option:bytes) => SponsoredMessageReportOption`
- Официальная страница конструктора: https://core.telegram.org/constructor/sponsoredMessageReportOption
- Поля:
  - `text`: `string`
  - `option`: `bytes`

## `SponsoredPeer`

- Официальный тип: https://core.telegram.org/type/SponsoredPeer
- Количество constructors: **1**

### `sponsoredPeer`

- ID: `-963180333` / `0xc69708d3`
- Сигнатура: `sponsoredPeer(flags:#, random_id:bytes, peer:Peer, sponsor_info:flags.0?string, additional_info:flags.1?string) => SponsoredPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/sponsoredPeer
- Поля:
  - `flags`: `#` - служебное поле flags
  - `random_id`: `bytes`
  - `peer`: `Peer`
  - `sponsor_info`: `flags.0?string` - optional через flags.0
  - `additional_info`: `flags.1?string` - optional через flags.1

## `StarGift`

- Официальный тип: https://core.telegram.org/type/StarGift
- Количество constructors: **2**

### `starGift`

- ID: `-2136190013` / `0x80ac53c3`
- Сигнатура: `starGift(flags:#, limited:flags.0?true, sold_out:flags.1?true, birthday:flags.2?true, require_premium:flags.7?true, limited_per_user:flags.8?true, id:long, sticker:Document, stars:long, availability_remains:flags.0?int, availability_total:flags.0?int, availability_resale:flags.4?long, convert_stars:long, first_sale_date:flags.1?int, last_sale_date:flags.1?int, upgrade_stars:flags.3?long, resell_min_stars:flags.4?long, title:flags.5?string, released_by:flags.6?Peer, per_user_total:flags.8?int, per_user_remains:flags.8?int, locked_until_date:flags.9?int) => StarGift`
- Официальная страница конструктора: https://core.telegram.org/constructor/starGift
- Поля:
  - `flags`: `#` - служебное поле flags
  - `limited`: `flags.0?true` - optional через flags.0
  - `sold_out`: `flags.1?true` - optional через flags.1
  - `birthday`: `flags.2?true` - optional через flags.2
  - `require_premium`: `flags.7?true` - optional через flags.7
  - `limited_per_user`: `flags.8?true` - optional через flags.8
  - `id`: `long`
  - `sticker`: `Document`
  - `stars`: `long`
  - `availability_remains`: `flags.0?int` - optional через flags.0
  - `availability_total`: `flags.0?int` - optional через flags.0
  - `availability_resale`: `flags.4?long` - optional через flags.4
  - `convert_stars`: `long`
  - `first_sale_date`: `flags.1?int` - optional через flags.1
  - `last_sale_date`: `flags.1?int` - optional через flags.1
  - `upgrade_stars`: `flags.3?long` - optional через flags.3
  - `resell_min_stars`: `flags.4?long` - optional через flags.4
  - `title`: `flags.5?string` - optional через flags.5
  - `released_by`: `flags.6?Peer` - optional через flags.6
  - `per_user_total`: `flags.8?int` - optional через flags.8
  - `per_user_remains`: `flags.8?int` - optional через flags.8
  - `locked_until_date`: `flags.9?int` - optional через flags.9

### `starGiftUnique`

- ID: `468707429` / `0x1befe865`
- Сигнатура: `starGiftUnique(flags:#, require_premium:flags.6?true, resale_ton_only:flags.7?true, theme_available:flags.9?true, id:long, gift_id:long, title:string, slug:string, num:int, owner_id:flags.0?Peer, owner_name:flags.1?string, owner_address:flags.2?string, attributes:Vector, availability_issued:int, availability_total:int, gift_address:flags.3?string, resell_amount:flags.4?Vector, released_by:flags.5?Peer, value_amount:flags.8?long, value_currency:flags.8?string, theme_peer:flags.10?Peer) => StarGift`
- Официальная страница конструктора: https://core.telegram.org/constructor/starGiftUnique
- Поля:
  - `flags`: `#` - служебное поле flags
  - `require_premium`: `flags.6?true` - optional через flags.6
  - `resale_ton_only`: `flags.7?true` - optional через flags.7
  - `theme_available`: `flags.9?true` - optional через flags.9
  - `id`: `long`
  - `gift_id`: `long`
  - `title`: `string`
  - `slug`: `string`
  - `num`: `int`
  - `owner_id`: `flags.0?Peer` - optional через flags.0
  - `owner_name`: `flags.1?string` - optional через flags.1
  - `owner_address`: `flags.2?string` - optional через flags.2
  - `attributes`: `Vector`
  - `availability_issued`: `int`
  - `availability_total`: `int`
  - `gift_address`: `flags.3?string` - optional через flags.3
  - `resell_amount`: `flags.4?Vector` - optional через flags.4
  - `released_by`: `flags.5?Peer` - optional через flags.5
  - `value_amount`: `flags.8?long` - optional через flags.8
  - `value_currency`: `flags.8?string` - optional через flags.8
  - `theme_peer`: `flags.10?Peer` - optional через flags.10

## `StarGiftAttribute`

- Официальный тип: https://core.telegram.org/type/StarGiftAttribute
- Количество constructors: **4**

### `starGiftAttributeBackdrop`

- ID: `-650279524` / `0xd93d859c`
- Сигнатура: `starGiftAttributeBackdrop(name:string, backdrop_id:int, center_color:int, edge_color:int, pattern_color:int, text_color:int, rarity_permille:int) => StarGiftAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/starGiftAttributeBackdrop
- Поля:
  - `name`: `string`
  - `backdrop_id`: `int`
  - `center_color`: `int`
  - `edge_color`: `int`
  - `pattern_color`: `int`
  - `text_color`: `int`
  - `rarity_permille`: `int`

### `starGiftAttributeModel`

- ID: `970559507` / `0x39d99013`
- Сигнатура: `starGiftAttributeModel(name:string, document:Document, rarity_permille:int) => StarGiftAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/starGiftAttributeModel
- Поля:
  - `name`: `string`
  - `document`: `Document`
  - `rarity_permille`: `int`

### `starGiftAttributeOriginalDetails`

- ID: `-524291476` / `0xe0bff26c`
- Сигнатура: `starGiftAttributeOriginalDetails(flags:#, sender_id:flags.0?Peer, recipient_id:Peer, date:int, message:flags.1?TextWithEntities) => StarGiftAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/starGiftAttributeOriginalDetails
- Поля:
  - `flags`: `#` - служебное поле flags
  - `sender_id`: `flags.0?Peer` - optional через flags.0
  - `recipient_id`: `Peer`
  - `date`: `int`
  - `message`: `flags.1?TextWithEntities` - optional через flags.1

### `starGiftAttributePattern`

- ID: `330104601` / `0x13acff19`
- Сигнатура: `starGiftAttributePattern(name:string, document:Document, rarity_permille:int) => StarGiftAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/starGiftAttributePattern
- Поля:
  - `name`: `string`
  - `document`: `Document`
  - `rarity_permille`: `int`

## `StarGiftAttributeCounter`

- Официальный тип: https://core.telegram.org/type/StarGiftAttributeCounter
- Количество constructors: **1**

### `starGiftAttributeCounter`

- ID: `783398488` / `0x2eb1b658`
- Сигнатура: `starGiftAttributeCounter(attribute:StarGiftAttributeId, count:int) => StarGiftAttributeCounter`
- Официальная страница конструктора: https://core.telegram.org/constructor/starGiftAttributeCounter
- Поля:
  - `attribute`: `StarGiftAttributeId`
  - `count`: `int`

## `StarGiftAttributeId`

- Официальный тип: https://core.telegram.org/type/StarGiftAttributeId
- Количество constructors: **3**

### `starGiftAttributeIdBackdrop`

- ID: `520210263` / `0x1f01c757`
- Сигнатура: `starGiftAttributeIdBackdrop(backdrop_id:int) => StarGiftAttributeId`
- Официальная страница конструктора: https://core.telegram.org/constructor/starGiftAttributeIdBackdrop
- Поля:
  - `backdrop_id`: `int`

### `starGiftAttributeIdModel`

- ID: `1219145276` / `0x48aaae3c`
- Сигнатура: `starGiftAttributeIdModel(document_id:long) => StarGiftAttributeId`
- Официальная страница конструктора: https://core.telegram.org/constructor/starGiftAttributeIdModel
- Поля:
  - `document_id`: `long`

### `starGiftAttributeIdPattern`

- ID: `1242965043` / `0x4a162433`
- Сигнатура: `starGiftAttributeIdPattern(document_id:long) => StarGiftAttributeId`
- Официальная страница конструктора: https://core.telegram.org/constructor/starGiftAttributeIdPattern
- Поля:
  - `document_id`: `long`

## `StarGiftCollection`

- Официальный тип: https://core.telegram.org/type/StarGiftCollection
- Количество constructors: **1**

### `starGiftCollection`

- ID: `-1653926992` / `0x9d6b13b0`
- Сигнатура: `starGiftCollection(flags:#, collection_id:int, title:string, icon:flags.0?Document, gifts_count:int, hash:long) => StarGiftCollection`
- Официальная страница конструктора: https://core.telegram.org/constructor/starGiftCollection
- Поля:
  - `flags`: `#` - служебное поле flags
  - `collection_id`: `int`
  - `title`: `string`
  - `icon`: `flags.0?Document` - optional через flags.0
  - `gifts_count`: `int`
  - `hash`: `long`

## `StarRefProgram`

- Официальный тип: https://core.telegram.org/type/StarRefProgram
- Количество constructors: **1**

### `starRefProgram`

- ID: `-586389774` / `0xdd0c66f2`
- Сигнатура: `starRefProgram(flags:#, bot_id:long, commission_permille:int, duration_months:flags.0?int, end_date:flags.1?int, daily_revenue_per_user:flags.2?StarsAmount) => StarRefProgram`
- Официальная страница конструктора: https://core.telegram.org/constructor/starRefProgram
- Поля:
  - `flags`: `#` - служебное поле flags
  - `bot_id`: `long`
  - `commission_permille`: `int`
  - `duration_months`: `flags.0?int` - optional через flags.0
  - `end_date`: `flags.1?int` - optional через flags.1
  - `daily_revenue_per_user`: `flags.2?StarsAmount` - optional через flags.2

## `StarsAmount`

- Официальный тип: https://core.telegram.org/type/StarsAmount
- Количество constructors: **2**

### `starsAmount`

- ID: `-1145654109` / `0xbbb6b4a3`
- Сигнатура: `starsAmount(amount:long, nanos:int) => StarsAmount`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsAmount
- Поля:
  - `amount`: `long`
  - `nanos`: `int`

### `starsTonAmount`

- ID: `1957618656` / `0x74aee3e0`
- Сигнатура: `starsTonAmount(amount:long) => StarsAmount`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsTonAmount
- Поля:
  - `amount`: `long`

## `StarsGiftOption`

- Официальный тип: https://core.telegram.org/type/StarsGiftOption
- Количество constructors: **1**

### `starsGiftOption`

- ID: `1577421297` / `0x5e0589f1`
- Сигнатура: `starsGiftOption(flags:#, extended:flags.1?true, stars:long, store_product:flags.0?string, currency:string, amount:long) => StarsGiftOption`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsGiftOption
- Поля:
  - `flags`: `#` - служебное поле flags
  - `extended`: `flags.1?true` - optional через flags.1
  - `stars`: `long`
  - `store_product`: `flags.0?string` - optional через flags.0
  - `currency`: `string`
  - `amount`: `long`

## `StarsGiveawayOption`

- Официальный тип: https://core.telegram.org/type/StarsGiveawayOption
- Количество constructors: **1**

### `starsGiveawayOption`

- ID: `-1798404822` / `0x94ce852a`
- Сигнатура: `starsGiveawayOption(flags:#, extended:flags.0?true, default:flags.1?true, stars:long, yearly_boosts:int, store_product:flags.2?string, currency:string, amount:long, winners:Vector) => StarsGiveawayOption`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsGiveawayOption
- Поля:
  - `flags`: `#` - служебное поле flags
  - `extended`: `flags.0?true` - optional через flags.0
  - `default`: `flags.1?true` - optional через flags.1
  - `stars`: `long`
  - `yearly_boosts`: `int`
  - `store_product`: `flags.2?string` - optional через flags.2
  - `currency`: `string`
  - `amount`: `long`
  - `winners`: `Vector`

## `StarsGiveawayWinnersOption`

- Официальный тип: https://core.telegram.org/type/StarsGiveawayWinnersOption
- Количество constructors: **1**

### `starsGiveawayWinnersOption`

- ID: `1411605001` / `0x54236209`
- Сигнатура: `starsGiveawayWinnersOption(flags:#, default:flags.0?true, users:int, per_user_stars:long) => StarsGiveawayWinnersOption`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsGiveawayWinnersOption
- Поля:
  - `flags`: `#` - служебное поле flags
  - `default`: `flags.0?true` - optional через flags.0
  - `users`: `int`
  - `per_user_stars`: `long`

## `StarsRating`

- Официальный тип: https://core.telegram.org/type/StarsRating
- Количество constructors: **1**

### `starsRating`

- ID: `453922567` / `0x1b0e4f07`
- Сигнатура: `starsRating(flags:#, level:int, current_level_stars:long, stars:long, next_level_stars:flags.0?long) => StarsRating`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsRating
- Поля:
  - `flags`: `#` - служебное поле flags
  - `level`: `int`
  - `current_level_stars`: `long`
  - `stars`: `long`
  - `next_level_stars`: `flags.0?long` - optional через flags.0

## `StarsRevenueStatus`

- Официальный тип: https://core.telegram.org/type/StarsRevenueStatus
- Количество constructors: **1**

### `starsRevenueStatus`

- ID: `-21080943` / `0xfebe5491`
- Сигнатура: `starsRevenueStatus(flags:#, withdrawal_enabled:flags.0?true, current_balance:StarsAmount, available_balance:StarsAmount, overall_revenue:StarsAmount, next_withdrawal_at:flags.1?int) => StarsRevenueStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsRevenueStatus
- Поля:
  - `flags`: `#` - служебное поле flags
  - `withdrawal_enabled`: `flags.0?true` - optional через flags.0
  - `current_balance`: `StarsAmount`
  - `available_balance`: `StarsAmount`
  - `overall_revenue`: `StarsAmount`
  - `next_withdrawal_at`: `flags.1?int` - optional через flags.1

## `StarsSubscription`

- Официальный тип: https://core.telegram.org/type/StarsSubscription
- Количество constructors: **1**

### `starsSubscription`

- ID: `779004698` / `0x2e6eab1a`
- Сигнатура: `starsSubscription(flags:#, canceled:flags.0?true, can_refulfill:flags.1?true, missing_balance:flags.2?true, bot_canceled:flags.7?true, id:string, peer:Peer, until_date:int, pricing:StarsSubscriptionPricing, chat_invite_hash:flags.3?string, title:flags.4?string, photo:flags.5?WebDocument, invoice_slug:flags.6?string) => StarsSubscription`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsSubscription
- Поля:
  - `flags`: `#` - служебное поле flags
  - `canceled`: `flags.0?true` - optional через flags.0
  - `can_refulfill`: `flags.1?true` - optional через flags.1
  - `missing_balance`: `flags.2?true` - optional через flags.2
  - `bot_canceled`: `flags.7?true` - optional через flags.7
  - `id`: `string`
  - `peer`: `Peer`
  - `until_date`: `int`
  - `pricing`: `StarsSubscriptionPricing`
  - `chat_invite_hash`: `flags.3?string` - optional через flags.3
  - `title`: `flags.4?string` - optional через flags.4
  - `photo`: `flags.5?WebDocument` - optional через flags.5
  - `invoice_slug`: `flags.6?string` - optional через flags.6

## `StarsSubscriptionPricing`

- Официальный тип: https://core.telegram.org/type/StarsSubscriptionPricing
- Количество constructors: **1**

### `starsSubscriptionPricing`

- ID: `88173912` / `0x05416d58`
- Сигнатура: `starsSubscriptionPricing(period:int, amount:long) => StarsSubscriptionPricing`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsSubscriptionPricing
- Поля:
  - `period`: `int`
  - `amount`: `long`

## `StarsTopupOption`

- Официальный тип: https://core.telegram.org/type/StarsTopupOption
- Количество constructors: **1**

### `starsTopupOption`

- ID: `198776256` / `0x0bd915c0`
- Сигнатура: `starsTopupOption(flags:#, extended:flags.1?true, stars:long, store_product:flags.0?string, currency:string, amount:long) => StarsTopupOption`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsTopupOption
- Поля:
  - `flags`: `#` - служебное поле flags
  - `extended`: `flags.1?true` - optional через flags.1
  - `stars`: `long`
  - `store_product`: `flags.0?string` - optional через flags.0
  - `currency`: `string`
  - `amount`: `long`

## `StarsTransaction`

- Официальный тип: https://core.telegram.org/type/StarsTransaction
- Количество constructors: **1**

### `starsTransaction`

- ID: `325426864` / `0x13659eb0`
- Сигнатура: `starsTransaction(flags:#, refund:flags.3?true, pending:flags.4?true, failed:flags.6?true, gift:flags.10?true, reaction:flags.11?true, stargift_upgrade:flags.18?true, business_transfer:flags.21?true, stargift_resale:flags.22?true, posts_search:flags.24?true, stargift_prepaid_upgrade:flags.25?true, id:string, amount:StarsAmount, date:int, peer:StarsTransactionPeer, title:flags.0?string, description:flags.1?string, photo:flags.2?WebDocument, transaction_date:flags.5?int, transaction_url:flags.5?string, bot_payload:flags.7?bytes, msg_id:flags.8?int, extended_media:flags.9?Vector, subscription_period:flags.12?int, giveaway_post_id:flags.13?int, stargift:flags.14?StarGift, floodskip_number:flags.15?int, starref_commission_permille:flags.16?int, starref_peer:flags.17?Peer, starref_amount:flags.17?StarsAmount, paid_messages:flags.19?int, premium_gift_months:flags.20?int, ads_proceeds_from_date:flags.23?int, ads_proceeds_to_date:flags.23?int) => StarsTransaction`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsTransaction
- Поля:
  - `flags`: `#` - служебное поле flags
  - `refund`: `flags.3?true` - optional через flags.3
  - `pending`: `flags.4?true` - optional через flags.4
  - `failed`: `flags.6?true` - optional через flags.6
  - `gift`: `flags.10?true` - optional через flags.10
  - `reaction`: `flags.11?true` - optional через flags.11
  - `stargift_upgrade`: `flags.18?true` - optional через flags.18
  - `business_transfer`: `flags.21?true` - optional через flags.21
  - `stargift_resale`: `flags.22?true` - optional через flags.22
  - `posts_search`: `flags.24?true` - optional через flags.24
  - `stargift_prepaid_upgrade`: `flags.25?true` - optional через flags.25
  - `id`: `string`
  - `amount`: `StarsAmount`
  - `date`: `int`
  - `peer`: `StarsTransactionPeer`
  - `title`: `flags.0?string` - optional через flags.0
  - `description`: `flags.1?string` - optional через flags.1
  - `photo`: `flags.2?WebDocument` - optional через flags.2
  - `transaction_date`: `flags.5?int` - optional через flags.5
  - `transaction_url`: `flags.5?string` - optional через flags.5
  - `bot_payload`: `flags.7?bytes` - optional через flags.7
  - `msg_id`: `flags.8?int` - optional через flags.8
  - `extended_media`: `flags.9?Vector` - optional через flags.9
  - `subscription_period`: `flags.12?int` - optional через flags.12
  - `giveaway_post_id`: `flags.13?int` - optional через flags.13
  - `stargift`: `flags.14?StarGift` - optional через flags.14
  - `floodskip_number`: `flags.15?int` - optional через flags.15
  - `starref_commission_permille`: `flags.16?int` - optional через flags.16
  - `starref_peer`: `flags.17?Peer` - optional через flags.17
  - `starref_amount`: `flags.17?StarsAmount` - optional через flags.17
  - `paid_messages`: `flags.19?int` - optional через flags.19
  - `premium_gift_months`: `flags.20?int` - optional через flags.20
  - `ads_proceeds_from_date`: `flags.23?int` - optional через flags.23
  - `ads_proceeds_to_date`: `flags.23?int` - optional через flags.23

## `StarsTransactionPeer`

- Официальный тип: https://core.telegram.org/type/StarsTransactionPeer
- Количество constructors: **8**

### `starsTransactionPeer`

- ID: `-670195363` / `0xd80da15d`
- Сигнатура: `starsTransactionPeer(peer:Peer) => StarsTransactionPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsTransactionPeer
- Поля:
  - `peer`: `Peer`

### `starsTransactionPeerAPI`

- ID: `-110658899` / `0xf9677aad`
- Сигнатура: `starsTransactionPeerAPI() => StarsTransactionPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsTransactionPeerAPI
- Поля:
  - Нет полей.

### `starsTransactionPeerAds`

- ID: `1617438738` / `0x60682812`
- Сигнатура: `starsTransactionPeerAds() => StarsTransactionPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsTransactionPeerAds
- Поля:
  - Нет полей.

### `starsTransactionPeerAppStore`

- ID: `-1269320843` / `0xb457b375`
- Сигнатура: `starsTransactionPeerAppStore() => StarsTransactionPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsTransactionPeerAppStore
- Поля:
  - Нет полей.

### `starsTransactionPeerFragment`

- ID: `-382740222` / `0xe92fd902`
- Сигнатура: `starsTransactionPeerFragment() => StarsTransactionPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsTransactionPeerFragment
- Поля:
  - Нет полей.

### `starsTransactionPeerPlayMarket`

- ID: `2069236235` / `0x7b560a0b`
- Сигнатура: `starsTransactionPeerPlayMarket() => StarsTransactionPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsTransactionPeerPlayMarket
- Поля:
  - Нет полей.

### `starsTransactionPeerPremiumBot`

- ID: `621656824` / `0x250dbaf8`
- Сигнатура: `starsTransactionPeerPremiumBot() => StarsTransactionPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsTransactionPeerPremiumBot
- Поля:
  - Нет полей.

### `starsTransactionPeerUnsupported`

- ID: `-1779253276` / `0x95f2bfe4`
- Сигнатура: `starsTransactionPeerUnsupported() => StarsTransactionPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/starsTransactionPeerUnsupported
- Поля:
  - Нет полей.

## `StatsAbsValueAndPrev`

- Официальный тип: https://core.telegram.org/type/StatsAbsValueAndPrev
- Количество constructors: **1**

### `statsAbsValueAndPrev`

- ID: `-884757282` / `0xcb43acde`
- Сигнатура: `statsAbsValueAndPrev(current:double, previous:double) => StatsAbsValueAndPrev`
- Официальная страница конструктора: https://core.telegram.org/constructor/statsAbsValueAndPrev
- Поля:
  - `current`: `double`
  - `previous`: `double`

## `StatsDateRangeDays`

- Официальный тип: https://core.telegram.org/type/StatsDateRangeDays
- Количество constructors: **1**

### `statsDateRangeDays`

- ID: `-1237848657` / `0xb637edaf`
- Сигнатура: `statsDateRangeDays(min_date:int, max_date:int) => StatsDateRangeDays`
- Официальная страница конструктора: https://core.telegram.org/constructor/statsDateRangeDays
- Поля:
  - `min_date`: `int`
  - `max_date`: `int`

## `StatsGraph`

- Официальный тип: https://core.telegram.org/type/StatsGraph
- Количество constructors: **3**

### `statsGraph`

- ID: `-1901828938` / `0x8ea464b6`
- Сигнатура: `statsGraph(flags:#, json:DataJSON, zoom_token:flags.0?string) => StatsGraph`
- Официальная страница конструктора: https://core.telegram.org/constructor/statsGraph
- Поля:
  - `flags`: `#` - служебное поле flags
  - `json`: `DataJSON`
  - `zoom_token`: `flags.0?string` - optional через flags.0

### `statsGraphAsync`

- ID: `1244130093` / `0x4a27eb2d`
- Сигнатура: `statsGraphAsync(token:string) => StatsGraph`
- Официальная страница конструктора: https://core.telegram.org/constructor/statsGraphAsync
- Поля:
  - `token`: `string`

### `statsGraphError`

- ID: `-1092839390` / `0xbedc9822`
- Сигнатура: `statsGraphError(error:string) => StatsGraph`
- Официальная страница конструктора: https://core.telegram.org/constructor/statsGraphError
- Поля:
  - `error`: `string`

## `StatsGroupTopAdmin`

- Официальный тип: https://core.telegram.org/type/StatsGroupTopAdmin
- Количество constructors: **1**

### `statsGroupTopAdmin`

- ID: `-682079097` / `0xd7584c87`
- Сигнатура: `statsGroupTopAdmin(user_id:long, deleted:int, kicked:int, banned:int) => StatsGroupTopAdmin`
- Официальная страница конструктора: https://core.telegram.org/constructor/statsGroupTopAdmin
- Поля:
  - `user_id`: `long`
  - `deleted`: `int`
  - `kicked`: `int`
  - `banned`: `int`

## `StatsGroupTopInviter`

- Официальный тип: https://core.telegram.org/type/StatsGroupTopInviter
- Количество constructors: **1**

### `statsGroupTopInviter`

- ID: `1398765469` / `0x535f779d`
- Сигнатура: `statsGroupTopInviter(user_id:long, invitations:int) => StatsGroupTopInviter`
- Официальная страница конструктора: https://core.telegram.org/constructor/statsGroupTopInviter
- Поля:
  - `user_id`: `long`
  - `invitations`: `int`

## `StatsGroupTopPoster`

- Официальный тип: https://core.telegram.org/type/StatsGroupTopPoster
- Количество constructors: **1**

### `statsGroupTopPoster`

- ID: `-1660637285` / `0x9d04af9b`
- Сигнатура: `statsGroupTopPoster(user_id:long, messages:int, avg_chars:int) => StatsGroupTopPoster`
- Официальная страница конструктора: https://core.telegram.org/constructor/statsGroupTopPoster
- Поля:
  - `user_id`: `long`
  - `messages`: `int`
  - `avg_chars`: `int`

## `StatsPercentValue`

- Официальный тип: https://core.telegram.org/type/StatsPercentValue
- Количество constructors: **1**

### `statsPercentValue`

- ID: `-875679776` / `0xcbce2fe0`
- Сигнатура: `statsPercentValue(part:double, total:double) => StatsPercentValue`
- Официальная страница конструктора: https://core.telegram.org/constructor/statsPercentValue
- Поля:
  - `part`: `double`
  - `total`: `double`

## `StatsURL`

- Официальный тип: https://core.telegram.org/type/StatsURL
- Количество constructors: **1**

### `statsURL`

- ID: `1202287072` / `0x47a971e0`
- Сигнатура: `statsURL(url:string) => StatsURL`
- Официальная страница конструктора: https://core.telegram.org/constructor/statsURL
- Поля:
  - `url`: `string`

## `StickerKeyword`

- Официальный тип: https://core.telegram.org/type/StickerKeyword
- Количество constructors: **1**

### `stickerKeyword`

- ID: `-50416996` / `0xfcfeb29c`
- Сигнатура: `stickerKeyword(document_id:long, keyword:Vector) => StickerKeyword`
- Официальная страница конструктора: https://core.telegram.org/constructor/stickerKeyword
- Поля:
  - `document_id`: `long`
  - `keyword`: `Vector`

## `StickerPack`

- Официальный тип: https://core.telegram.org/type/StickerPack
- Количество constructors: **1**

### `stickerPack`

- ID: `313694676` / `0x12b299d4`
- Сигнатура: `stickerPack(emoticon:string, documents:Vector) => StickerPack`
- Официальная страница конструктора: https://core.telegram.org/constructor/stickerPack
- Поля:
  - `emoticon`: `string`
  - `documents`: `Vector`

## `StickerSet`

- Официальный тип: https://core.telegram.org/type/StickerSet
- Количество constructors: **1**

### `stickerSet`

- ID: `768691932` / `0x2dd14edc`
- Сигнатура: `stickerSet(flags:#, archived:flags.1?true, official:flags.2?true, masks:flags.3?true, emojis:flags.7?true, text_color:flags.9?true, channel_emoji_status:flags.10?true, creator:flags.11?true, installed_date:flags.0?int, id:long, access_hash:long, title:string, short_name:string, thumbs:flags.4?Vector, thumb_dc_id:flags.4?int, thumb_version:flags.4?int, thumb_document_id:flags.8?long, count:int, hash:int) => StickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/stickerSet
- Поля:
  - `flags`: `#` - служебное поле flags
  - `archived`: `flags.1?true` - optional через flags.1
  - `official`: `flags.2?true` - optional через flags.2
  - `masks`: `flags.3?true` - optional через flags.3
  - `emojis`: `flags.7?true` - optional через flags.7
  - `text_color`: `flags.9?true` - optional через flags.9
  - `channel_emoji_status`: `flags.10?true` - optional через flags.10
  - `creator`: `flags.11?true` - optional через flags.11
  - `installed_date`: `flags.0?int` - optional через flags.0
  - `id`: `long`
  - `access_hash`: `long`
  - `title`: `string`
  - `short_name`: `string`
  - `thumbs`: `flags.4?Vector` - optional через flags.4
  - `thumb_dc_id`: `flags.4?int` - optional через flags.4
  - `thumb_version`: `flags.4?int` - optional через flags.4
  - `thumb_document_id`: `flags.8?long` - optional через flags.8
  - `count`: `int`
  - `hash`: `int`

## `StickerSetCovered`

- Официальный тип: https://core.telegram.org/type/StickerSetCovered
- Количество constructors: **4**

### `stickerSetCovered`

- ID: `1678812626` / `0x6410a5d2`
- Сигнатура: `stickerSetCovered(set:StickerSet, cover:Document) => StickerSetCovered`
- Официальная страница конструктора: https://core.telegram.org/constructor/stickerSetCovered
- Поля:
  - `set`: `StickerSet`
  - `cover`: `Document`

### `stickerSetFullCovered`

- ID: `1087454222` / `0x40d13c0e`
- Сигнатура: `stickerSetFullCovered(set:StickerSet, packs:Vector, keywords:Vector, documents:Vector) => StickerSetCovered`
- Официальная страница конструктора: https://core.telegram.org/constructor/stickerSetFullCovered
- Поля:
  - `set`: `StickerSet`
  - `packs`: `Vector`
  - `keywords`: `Vector`
  - `documents`: `Vector`

### `stickerSetMultiCovered`

- ID: `872932635` / `0x3407e51b`
- Сигнатура: `stickerSetMultiCovered(set:StickerSet, covers:Vector) => StickerSetCovered`
- Официальная страница конструктора: https://core.telegram.org/constructor/stickerSetMultiCovered
- Поля:
  - `set`: `StickerSet`
  - `covers`: `Vector`

### `stickerSetNoCovered`

- ID: `2008112412` / `0x77b15d1c`
- Сигнатура: `stickerSetNoCovered(set:StickerSet) => StickerSetCovered`
- Официальная страница конструктора: https://core.telegram.org/constructor/stickerSetNoCovered
- Поля:
  - `set`: `StickerSet`

## `StoriesStealthMode`

- Официальный тип: https://core.telegram.org/type/StoriesStealthMode
- Количество constructors: **1**

### `storiesStealthMode`

- ID: `1898850301` / `0x712e27fd`
- Сигнатура: `storiesStealthMode(flags:#, active_until_date:flags.0?int, cooldown_until_date:flags.1?int) => StoriesStealthMode`
- Официальная страница конструктора: https://core.telegram.org/constructor/storiesStealthMode
- Поля:
  - `flags`: `#` - служебное поле flags
  - `active_until_date`: `flags.0?int` - optional через flags.0
  - `cooldown_until_date`: `flags.1?int` - optional через flags.1

## `StoryAlbum`

- Официальный тип: https://core.telegram.org/type/StoryAlbum
- Количество constructors: **1**

### `storyAlbum`

- ID: `-1826262950` / `0x9325705a`
- Сигнатура: `storyAlbum(flags:#, album_id:int, title:string, icon_photo:flags.0?Photo, icon_video:flags.1?Document) => StoryAlbum`
- Официальная страница конструктора: https://core.telegram.org/constructor/storyAlbum
- Поля:
  - `flags`: `#` - служебное поле flags
  - `album_id`: `int`
  - `title`: `string`
  - `icon_photo`: `flags.0?Photo` - optional через flags.0
  - `icon_video`: `flags.1?Document` - optional через flags.1

## `StoryFwdHeader`

- Официальный тип: https://core.telegram.org/type/StoryFwdHeader
- Количество constructors: **1**

### `storyFwdHeader`

- ID: `-1205411504` / `0xb826e150`
- Сигнатура: `storyFwdHeader(flags:#, modified:flags.3?true, from:flags.0?Peer, from_name:flags.1?string, story_id:flags.2?int) => StoryFwdHeader`
- Официальная страница конструктора: https://core.telegram.org/constructor/storyFwdHeader
- Поля:
  - `flags`: `#` - служебное поле flags
  - `modified`: `flags.3?true` - optional через flags.3
  - `from`: `flags.0?Peer` - optional через flags.0
  - `from_name`: `flags.1?string` - optional через flags.1
  - `story_id`: `flags.2?int` - optional через flags.2

## `StoryItem`

- Официальный тип: https://core.telegram.org/type/StoryItem
- Количество constructors: **3**

### `storyItem`

- ID: `-302947087` / `0xedf164f1`
- Сигнатура: `storyItem(flags:#, pinned:flags.5?true, public:flags.7?true, close_friends:flags.8?true, min:flags.9?true, noforwards:flags.10?true, edited:flags.11?true, contacts:flags.12?true, selected_contacts:flags.13?true, out:flags.16?true, id:int, date:int, from_id:flags.18?Peer, fwd_from:flags.17?StoryFwdHeader, expire_date:int, caption:flags.0?string, entities:flags.1?Vector, media:MessageMedia, media_areas:flags.14?Vector, privacy:flags.2?Vector, views:flags.3?StoryViews, sent_reaction:flags.15?Reaction, albums:flags.19?Vector) => StoryItem`
- Официальная страница конструктора: https://core.telegram.org/constructor/storyItem
- Поля:
  - `flags`: `#` - служебное поле flags
  - `pinned`: `flags.5?true` - optional через flags.5
  - `public`: `flags.7?true` - optional через flags.7
  - `close_friends`: `flags.8?true` - optional через flags.8
  - `min`: `flags.9?true` - optional через flags.9
  - `noforwards`: `flags.10?true` - optional через flags.10
  - `edited`: `flags.11?true` - optional через flags.11
  - `contacts`: `flags.12?true` - optional через flags.12
  - `selected_contacts`: `flags.13?true` - optional через flags.13
  - `out`: `flags.16?true` - optional через flags.16
  - `id`: `int`
  - `date`: `int`
  - `from_id`: `flags.18?Peer` - optional через flags.18
  - `fwd_from`: `flags.17?StoryFwdHeader` - optional через flags.17
  - `expire_date`: `int`
  - `caption`: `flags.0?string` - optional через flags.0
  - `entities`: `flags.1?Vector` - optional через flags.1
  - `media`: `MessageMedia`
  - `media_areas`: `flags.14?Vector` - optional через flags.14
  - `privacy`: `flags.2?Vector` - optional через flags.2
  - `views`: `flags.3?StoryViews` - optional через flags.3
  - `sent_reaction`: `flags.15?Reaction` - optional через flags.15
  - `albums`: `flags.19?Vector` - optional через flags.19

### `storyItemDeleted`

- ID: `1374088783` / `0x51e6ee4f`
- Сигнатура: `storyItemDeleted(id:int) => StoryItem`
- Официальная страница конструктора: https://core.telegram.org/constructor/storyItemDeleted
- Поля:
  - `id`: `int`

### `storyItemSkipped`

- ID: `-5388013` / `0xffadc913`
- Сигнатура: `storyItemSkipped(flags:#, close_friends:flags.8?true, id:int, date:int, expire_date:int) => StoryItem`
- Официальная страница конструктора: https://core.telegram.org/constructor/storyItemSkipped
- Поля:
  - `flags`: `#` - служебное поле flags
  - `close_friends`: `flags.8?true` - optional через flags.8
  - `id`: `int`
  - `date`: `int`
  - `expire_date`: `int`

## `StoryReaction`

- Официальный тип: https://core.telegram.org/type/StoryReaction
- Количество constructors: **3**

### `storyReaction`

- ID: `1620104917` / `0x6090d6d5`
- Сигнатура: `storyReaction(peer_id:Peer, date:int, reaction:Reaction) => StoryReaction`
- Официальная страница конструктора: https://core.telegram.org/constructor/storyReaction
- Поля:
  - `peer_id`: `Peer`
  - `date`: `int`
  - `reaction`: `Reaction`

### `storyReactionPublicForward`

- ID: `-1146411453` / `0xbbab2643`
- Сигнатура: `storyReactionPublicForward(message:Message) => StoryReaction`
- Официальная страница конструктора: https://core.telegram.org/constructor/storyReactionPublicForward
- Поля:
  - `message`: `Message`

### `storyReactionPublicRepost`

- ID: `-808644845` / `0xcfcd0f13`
- Сигнатура: `storyReactionPublicRepost(peer_id:Peer, story:StoryItem) => StoryReaction`
- Официальная страница конструктора: https://core.telegram.org/constructor/storyReactionPublicRepost
- Поля:
  - `peer_id`: `Peer`
  - `story`: `StoryItem`

## `StoryView`

- Официальный тип: https://core.telegram.org/type/StoryView
- Количество constructors: **3**

### `storyView`

- ID: `-1329730875` / `0xb0bdeac5`
- Сигнатура: `storyView(flags:#, blocked:flags.0?true, blocked_my_stories_from:flags.1?true, user_id:long, date:int, reaction:flags.2?Reaction) => StoryView`
- Официальная страница конструктора: https://core.telegram.org/constructor/storyView
- Поля:
  - `flags`: `#` - служебное поле flags
  - `blocked`: `flags.0?true` - optional через flags.0
  - `blocked_my_stories_from`: `flags.1?true` - optional через flags.1
  - `user_id`: `long`
  - `date`: `int`
  - `reaction`: `flags.2?Reaction` - optional через flags.2

### `storyViewPublicForward`

- ID: `-1870436597` / `0x9083670b`
- Сигнатура: `storyViewPublicForward(flags:#, blocked:flags.0?true, blocked_my_stories_from:flags.1?true, message:Message) => StoryView`
- Официальная страница конструктора: https://core.telegram.org/constructor/storyViewPublicForward
- Поля:
  - `flags`: `#` - служебное поле flags
  - `blocked`: `flags.0?true` - optional через flags.0
  - `blocked_my_stories_from`: `flags.1?true` - optional через flags.1
  - `message`: `Message`

### `storyViewPublicRepost`

- ID: `-1116418231` / `0xbd74cf49`
- Сигнатура: `storyViewPublicRepost(flags:#, blocked:flags.0?true, blocked_my_stories_from:flags.1?true, peer_id:Peer, story:StoryItem) => StoryView`
- Официальная страница конструктора: https://core.telegram.org/constructor/storyViewPublicRepost
- Поля:
  - `flags`: `#` - служебное поле flags
  - `blocked`: `flags.0?true` - optional через flags.0
  - `blocked_my_stories_from`: `flags.1?true` - optional через flags.1
  - `peer_id`: `Peer`
  - `story`: `StoryItem`

## `StoryViews`

- Официальный тип: https://core.telegram.org/type/StoryViews
- Количество constructors: **1**

### `storyViews`

- ID: `-1923523370` / `0x8d595cd6`
- Сигнатура: `storyViews(flags:#, has_viewers:flags.1?true, views_count:int, forwards_count:flags.2?int, reactions:flags.3?Vector, reactions_count:flags.4?int, recent_viewers:flags.0?Vector) => StoryViews`
- Официальная страница конструктора: https://core.telegram.org/constructor/storyViews
- Поля:
  - `flags`: `#` - служебное поле flags
  - `has_viewers`: `flags.1?true` - optional через flags.1
  - `views_count`: `int`
  - `forwards_count`: `flags.2?int` - optional через flags.2
  - `reactions`: `flags.3?Vector` - optional через flags.3
  - `reactions_count`: `flags.4?int` - optional через flags.4
  - `recent_viewers`: `flags.0?Vector` - optional через flags.0

## `SuggestedPost`

- Официальный тип: https://core.telegram.org/type/SuggestedPost
- Количество constructors: **1**

### `suggestedPost`

- ID: `244201445` / `0x0e8e37e5`
- Сигнатура: `suggestedPost(flags:#, accepted:flags.1?true, rejected:flags.2?true, price:flags.3?StarsAmount, schedule_date:flags.0?int) => SuggestedPost`
- Официальная страница конструктора: https://core.telegram.org/constructor/suggestedPost
- Поля:
  - `flags`: `#` - служебное поле flags
  - `accepted`: `flags.1?true` - optional через flags.1
  - `rejected`: `flags.2?true` - optional через flags.2
  - `price`: `flags.3?StarsAmount` - optional через flags.3
  - `schedule_date`: `flags.0?int` - optional через flags.0

## `TextWithEntities`

- Официальный тип: https://core.telegram.org/type/TextWithEntities
- Количество constructors: **1**

### `textWithEntities`

- ID: `1964978502` / `0x751f3146`
- Сигнатура: `textWithEntities(text:string, entities:Vector) => TextWithEntities`
- Официальная страница конструктора: https://core.telegram.org/constructor/textWithEntities
- Поля:
  - `text`: `string`
  - `entities`: `Vector`

## `Theme`

- Официальный тип: https://core.telegram.org/type/Theme
- Количество constructors: **1**

### `theme`

- ID: `-1609668650` / `0xa00e67d6`
- Сигнатура: `theme(flags:#, creator:flags.0?true, default:flags.1?true, for_chat:flags.5?true, id:long, access_hash:long, slug:string, title:string, document:flags.2?Document, settings:flags.3?Vector, emoticon:flags.6?string, installs_count:flags.4?int) => Theme`
- Официальная страница конструктора: https://core.telegram.org/constructor/theme
- Поля:
  - `flags`: `#` - служебное поле flags
  - `creator`: `flags.0?true` - optional через flags.0
  - `default`: `flags.1?true` - optional через flags.1
  - `for_chat`: `flags.5?true` - optional через flags.5
  - `id`: `long`
  - `access_hash`: `long`
  - `slug`: `string`
  - `title`: `string`
  - `document`: `flags.2?Document` - optional через flags.2
  - `settings`: `flags.3?Vector` - optional через flags.3
  - `emoticon`: `flags.6?string` - optional через flags.6
  - `installs_count`: `flags.4?int` - optional через flags.4

## `ThemeSettings`

- Официальный тип: https://core.telegram.org/type/ThemeSettings
- Количество constructors: **1**

### `themeSettings`

- ID: `-94849324` / `0xfa58b6d4`
- Сигнатура: `themeSettings(flags:#, message_colors_animated:flags.2?true, base_theme:BaseTheme, accent_color:int, outbox_accent_color:flags.3?int, message_colors:flags.0?Vector, wallpaper:flags.1?WallPaper) => ThemeSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/themeSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `message_colors_animated`: `flags.2?true` - optional через flags.2
  - `base_theme`: `BaseTheme`
  - `accent_color`: `int`
  - `outbox_accent_color`: `flags.3?int` - optional через flags.3
  - `message_colors`: `flags.0?Vector` - optional через flags.0
  - `wallpaper`: `flags.1?WallPaper` - optional через flags.1

## `Timezone`

- Официальный тип: https://core.telegram.org/type/Timezone
- Количество constructors: **1**

### `timezone`

- ID: `-7173643` / `0xff9289f5`
- Сигнатура: `timezone(id:string, name:string, utc_offset:int) => Timezone`
- Официальная страница конструктора: https://core.telegram.org/constructor/timezone
- Поля:
  - `id`: `string`
  - `name`: `string`
  - `utc_offset`: `int`

## `TodoCompletion`

- Официальный тип: https://core.telegram.org/type/TodoCompletion
- Количество constructors: **1**

### `todoCompletion`

- ID: `1287725239` / `0x4cc120b7`
- Сигнатура: `todoCompletion(id:int, completed_by:long, date:int) => TodoCompletion`
- Официальная страница конструктора: https://core.telegram.org/constructor/todoCompletion
- Поля:
  - `id`: `int`
  - `completed_by`: `long`
  - `date`: `int`

## `TodoItem`

- Официальный тип: https://core.telegram.org/type/TodoItem
- Количество constructors: **1**

### `todoItem`

- ID: `-878074577` / `0xcba9a52f`
- Сигнатура: `todoItem(id:int, title:TextWithEntities) => TodoItem`
- Официальная страница конструктора: https://core.telegram.org/constructor/todoItem
- Поля:
  - `id`: `int`
  - `title`: `TextWithEntities`

## `TodoList`

- Официальный тип: https://core.telegram.org/type/TodoList
- Количество constructors: **1**

### `todoList`

- ID: `1236871718` / `0x49b92a26`
- Сигнатура: `todoList(flags:#, others_can_append:flags.0?true, others_can_complete:flags.1?true, title:TextWithEntities, list:Vector) => TodoList`
- Официальная страница конструктора: https://core.telegram.org/constructor/todoList
- Поля:
  - `flags`: `#` - служебное поле flags
  - `others_can_append`: `flags.0?true` - optional через flags.0
  - `others_can_complete`: `flags.1?true` - optional через flags.1
  - `title`: `TextWithEntities`
  - `list`: `Vector`

## `TopPeer`

- Официальный тип: https://core.telegram.org/type/TopPeer
- Количество constructors: **1**

### `topPeer`

- ID: `-305282981` / `0xedcdc05b`
- Сигнатура: `topPeer(peer:Peer, rating:double) => TopPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/topPeer
- Поля:
  - `peer`: `Peer`
  - `rating`: `double`

## `TopPeerCategory`

- Официальный тип: https://core.telegram.org/type/TopPeerCategory
- Количество constructors: **9**

### `topPeerCategoryBotsApp`

- ID: `-39945236` / `0xfd9e7bec`
- Сигнатура: `topPeerCategoryBotsApp() => TopPeerCategory`
- Официальная страница конструктора: https://core.telegram.org/constructor/topPeerCategoryBotsApp
- Поля:
  - Нет полей.

### `topPeerCategoryBotsInline`

- ID: `344356834` / `0x148677e2`
- Сигнатура: `topPeerCategoryBotsInline() => TopPeerCategory`
- Официальная страница конструктора: https://core.telegram.org/constructor/topPeerCategoryBotsInline
- Поля:
  - Нет полей.

### `topPeerCategoryBotsPM`

- ID: `-1419371685` / `0xab661b5b`
- Сигнатура: `topPeerCategoryBotsPM() => TopPeerCategory`
- Официальная страница конструктора: https://core.telegram.org/constructor/topPeerCategoryBotsPM
- Поля:
  - Нет полей.

### `topPeerCategoryChannels`

- ID: `371037736` / `0x161d9628`
- Сигнатура: `topPeerCategoryChannels() => TopPeerCategory`
- Официальная страница конструктора: https://core.telegram.org/constructor/topPeerCategoryChannels
- Поля:
  - Нет полей.

### `topPeerCategoryCorrespondents`

- ID: `104314861` / `0x0637b7ed`
- Сигнатура: `topPeerCategoryCorrespondents() => TopPeerCategory`
- Официальная страница конструктора: https://core.telegram.org/constructor/topPeerCategoryCorrespondents
- Поля:
  - Нет полей.

### `topPeerCategoryForwardChats`

- ID: `-68239120` / `0xfbeec0f0`
- Сигнатура: `topPeerCategoryForwardChats() => TopPeerCategory`
- Официальная страница конструктора: https://core.telegram.org/constructor/topPeerCategoryForwardChats
- Поля:
  - Нет полей.

### `topPeerCategoryForwardUsers`

- ID: `-1472172887` / `0xa8406ca9`
- Сигнатура: `topPeerCategoryForwardUsers() => TopPeerCategory`
- Официальная страница конструктора: https://core.telegram.org/constructor/topPeerCategoryForwardUsers
- Поля:
  - Нет полей.

### `topPeerCategoryGroups`

- ID: `-1122524854` / `0xbd17a14a`
- Сигнатура: `topPeerCategoryGroups() => TopPeerCategory`
- Официальная страница конструктора: https://core.telegram.org/constructor/topPeerCategoryGroups
- Поля:
  - Нет полей.

### `topPeerCategoryPhoneCalls`

- ID: `511092620` / `0x1e76a78c`
- Сигнатура: `topPeerCategoryPhoneCalls() => TopPeerCategory`
- Официальная страница конструктора: https://core.telegram.org/constructor/topPeerCategoryPhoneCalls
- Поля:
  - Нет полей.

## `TopPeerCategoryPeers`

- Официальный тип: https://core.telegram.org/type/TopPeerCategoryPeers
- Количество constructors: **1**

### `topPeerCategoryPeers`

- ID: `-75283823` / `0xfb834291`
- Сигнатура: `topPeerCategoryPeers(category:TopPeerCategory, count:int, peers:Vector) => TopPeerCategoryPeers`
- Официальная страница конструктора: https://core.telegram.org/constructor/topPeerCategoryPeers
- Поля:
  - `category`: `TopPeerCategory`
  - `count`: `int`
  - `peers`: `Vector`

## `True`

- Официальный тип: https://core.telegram.org/type/True
- Количество constructors: **1**

### `true`

- ID: `1072550713` / `0x3fedd339`
- Сигнатура: `true() => True`
- Официальная страница конструктора: https://core.telegram.org/constructor/true
- Поля:
  - Нет полей.

## `Update`

- Официальный тип: https://core.telegram.org/type/Update
- Количество constructors: **145**

### `updateAttachMenuBots`

- ID: `397910539` / `0x17b7a20b`
- Сигнатура: `updateAttachMenuBots() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateAttachMenuBots
- Поля:
  - Нет полей.

### `updateAutoSaveSettings`

- ID: `-335171433` / `0xec05b097`
- Сигнатура: `updateAutoSaveSettings() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateAutoSaveSettings
- Поля:
  - Нет полей.

### `updateBotBusinessConnect`

- ID: `-1964652166` / `0x8ae5c97a`
- Сигнатура: `updateBotBusinessConnect(connection:BotBusinessConnection, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotBusinessConnect
- Поля:
  - `connection`: `BotBusinessConnection`
  - `qts`: `int`

### `updateBotCallbackQuery`

- ID: `-1177566067` / `0xb9cfc48d`
- Сигнатура: `updateBotCallbackQuery(flags:#, query_id:long, user_id:long, peer:Peer, msg_id:int, chat_instance:long, data:flags.0?bytes, game_short_name:flags.1?string) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotCallbackQuery
- Поля:
  - `flags`: `#` - служебное поле flags
  - `query_id`: `long`
  - `user_id`: `long`
  - `peer`: `Peer`
  - `msg_id`: `int`
  - `chat_instance`: `long`
  - `data`: `flags.0?bytes` - optional через flags.0
  - `game_short_name`: `flags.1?string` - optional через flags.1

### `updateBotChatBoost`

- ID: `-1873947492` / `0x904dd49c`
- Сигнатура: `updateBotChatBoost(peer:Peer, boost:Boost, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotChatBoost
- Поля:
  - `peer`: `Peer`
  - `boost`: `Boost`
  - `qts`: `int`

### `updateBotChatInviteRequester`

- ID: `299870598` / `0x11dfa986`
- Сигнатура: `updateBotChatInviteRequester(peer:Peer, date:int, user_id:long, about:string, invite:ExportedChatInvite, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotChatInviteRequester
- Поля:
  - `peer`: `Peer`
  - `date`: `int`
  - `user_id`: `long`
  - `about`: `string`
  - `invite`: `ExportedChatInvite`
  - `qts`: `int`

### `updateBotCommands`

- ID: `1299263278` / `0x4d712f2e`
- Сигнатура: `updateBotCommands(peer:Peer, bot_id:long, commands:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotCommands
- Поля:
  - `peer`: `Peer`
  - `bot_id`: `long`
  - `commands`: `Vector`

### `updateBotDeleteBusinessMessage`

- ID: `-1607821266` / `0xa02a982e`
- Сигнатура: `updateBotDeleteBusinessMessage(connection_id:string, peer:Peer, messages:Vector, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotDeleteBusinessMessage
- Поля:
  - `connection_id`: `string`
  - `peer`: `Peer`
  - `messages`: `Vector`
  - `qts`: `int`

### `updateBotEditBusinessMessage`

- ID: `132077692` / `0x07df587c`
- Сигнатура: `updateBotEditBusinessMessage(flags:#, connection_id:string, message:Message, reply_to_message:flags.0?Message, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotEditBusinessMessage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `connection_id`: `string`
  - `message`: `Message`
  - `reply_to_message`: `flags.0?Message` - optional через flags.0
  - `qts`: `int`

### `updateBotInlineQuery`

- ID: `1232025500` / `0x496f379c`
- Сигнатура: `updateBotInlineQuery(flags:#, query_id:long, user_id:long, query:string, geo:flags.0?GeoPoint, peer_type:flags.1?InlineQueryPeerType, offset:string) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotInlineQuery
- Поля:
  - `flags`: `#` - служебное поле flags
  - `query_id`: `long`
  - `user_id`: `long`
  - `query`: `string`
  - `geo`: `flags.0?GeoPoint` - optional через flags.0
  - `peer_type`: `flags.1?InlineQueryPeerType` - optional через flags.1
  - `offset`: `string`

### `updateBotInlineSend`

- ID: `317794823` / `0x12f12a07`
- Сигнатура: `updateBotInlineSend(flags:#, user_id:long, query:string, geo:flags.0?GeoPoint, id:string, msg_id:flags.1?InputBotInlineMessageID) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotInlineSend
- Поля:
  - `flags`: `#` - служебное поле flags
  - `user_id`: `long`
  - `query`: `string`
  - `geo`: `flags.0?GeoPoint` - optional через flags.0
  - `id`: `string`
  - `msg_id`: `flags.1?InputBotInlineMessageID` - optional через flags.1

### `updateBotMenuButton`

- ID: `347625491` / `0x14b85813`
- Сигнатура: `updateBotMenuButton(bot_id:long, button:BotMenuButton) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotMenuButton
- Поля:
  - `bot_id`: `long`
  - `button`: `BotMenuButton`

### `updateBotMessageReaction`

- ID: `-1407069234` / `0xac21d3ce`
- Сигнатура: `updateBotMessageReaction(peer:Peer, msg_id:int, date:int, actor:Peer, old_reactions:Vector, new_reactions:Vector, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotMessageReaction
- Поля:
  - `peer`: `Peer`
  - `msg_id`: `int`
  - `date`: `int`
  - `actor`: `Peer`
  - `old_reactions`: `Vector`
  - `new_reactions`: `Vector`
  - `qts`: `int`

### `updateBotMessageReactions`

- ID: `164329305` / `0x09cb7759`
- Сигнатура: `updateBotMessageReactions(peer:Peer, msg_id:int, date:int, reactions:Vector, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotMessageReactions
- Поля:
  - `peer`: `Peer`
  - `msg_id`: `int`
  - `date`: `int`
  - `reactions`: `Vector`
  - `qts`: `int`

### `updateBotNewBusinessMessage`

- ID: `-1646578564` / `0x9ddb347c`
- Сигнатура: `updateBotNewBusinessMessage(flags:#, connection_id:string, message:Message, reply_to_message:flags.0?Message, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotNewBusinessMessage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `connection_id`: `string`
  - `message`: `Message`
  - `reply_to_message`: `flags.0?Message` - optional через flags.0
  - `qts`: `int`

### `updateBotPrecheckoutQuery`

- ID: `-1934976362` / `0x8caa9a96`
- Сигнатура: `updateBotPrecheckoutQuery(flags:#, query_id:long, user_id:long, payload:bytes, info:flags.0?PaymentRequestedInfo, shipping_option_id:flags.1?string, currency:string, total_amount:long) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotPrecheckoutQuery
- Поля:
  - `flags`: `#` - служебное поле flags
  - `query_id`: `long`
  - `user_id`: `long`
  - `payload`: `bytes`
  - `info`: `flags.0?PaymentRequestedInfo` - optional через flags.0
  - `shipping_option_id`: `flags.1?string` - optional через flags.1
  - `currency`: `string`
  - `total_amount`: `long`

### `updateBotPurchasedPaidMedia`

- ID: `675009298` / `0x283bd312`
- Сигнатура: `updateBotPurchasedPaidMedia(user_id:long, payload:string, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotPurchasedPaidMedia
- Поля:
  - `user_id`: `long`
  - `payload`: `string`
  - `qts`: `int`

### `updateBotShippingQuery`

- ID: `-1246823043` / `0xb5aefd7d`
- Сигнатура: `updateBotShippingQuery(query_id:long, user_id:long, payload:bytes, shipping_address:PostAddress) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotShippingQuery
- Поля:
  - `query_id`: `long`
  - `user_id`: `long`
  - `payload`: `bytes`
  - `shipping_address`: `PostAddress`

### `updateBotStopped`

- ID: `-997782967` / `0xc4870a49`
- Сигнатура: `updateBotStopped(user_id:long, date:int, stopped:Bool, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotStopped
- Поля:
  - `user_id`: `long`
  - `date`: `int`
  - `stopped`: `Bool`
  - `qts`: `int`

### `updateBotWebhookJSON`

- ID: `-2095595325` / `0x8317c0c3`
- Сигнатура: `updateBotWebhookJSON(data:DataJSON) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotWebhookJSON
- Поля:
  - `data`: `DataJSON`

### `updateBotWebhookJSONQuery`

- ID: `-1684914010` / `0x9b9240a6`
- Сигнатура: `updateBotWebhookJSONQuery(query_id:long, data:DataJSON, timeout:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBotWebhookJSONQuery
- Поля:
  - `query_id`: `long`
  - `data`: `DataJSON`
  - `timeout`: `int`

### `updateBusinessBotCallbackQuery`

- ID: `513998247` / `0x1ea2fda7`
- Сигнатура: `updateBusinessBotCallbackQuery(flags:#, query_id:long, user_id:long, connection_id:string, message:Message, reply_to_message:flags.2?Message, chat_instance:long, data:flags.0?bytes) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateBusinessBotCallbackQuery
- Поля:
  - `flags`: `#` - служебное поле flags
  - `query_id`: `long`
  - `user_id`: `long`
  - `connection_id`: `string`
  - `message`: `Message`
  - `reply_to_message`: `flags.2?Message` - optional через flags.2
  - `chat_instance`: `long`
  - `data`: `flags.0?bytes` - optional через flags.0

### `updateChannel`

- ID: `1666927625` / `0x635b4c09`
- Сигнатура: `updateChannel(channel_id:long) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChannel
- Поля:
  - `channel_id`: `long`

### `updateChannelAvailableMessages`

- ID: `-1304443240` / `0xb23fc698`
- Сигнатура: `updateChannelAvailableMessages(channel_id:long, available_min_id:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChannelAvailableMessages
- Поля:
  - `channel_id`: `long`
  - `available_min_id`: `int`

### `updateChannelMessageForwards`

- ID: `-761649164` / `0xd29a27f4`
- Сигнатура: `updateChannelMessageForwards(channel_id:long, id:int, forwards:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChannelMessageForwards
- Поля:
  - `channel_id`: `long`
  - `id`: `int`
  - `forwards`: `int`

### `updateChannelMessageViews`

- ID: `-232346616` / `0xf226ac08`
- Сигнатура: `updateChannelMessageViews(channel_id:long, id:int, views:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChannelMessageViews
- Поля:
  - `channel_id`: `long`
  - `id`: `int`
  - `views`: `int`

### `updateChannelParticipant`

- ID: `-1738720581` / `0x985d3abb`
- Сигнатура: `updateChannelParticipant(flags:#, via_chatlist:flags.3?true, channel_id:long, date:int, actor_id:long, user_id:long, prev_participant:flags.0?ChannelParticipant, new_participant:flags.1?ChannelParticipant, invite:flags.2?ExportedChatInvite, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChannelParticipant
- Поля:
  - `flags`: `#` - служебное поле flags
  - `via_chatlist`: `flags.3?true` - optional через flags.3
  - `channel_id`: `long`
  - `date`: `int`
  - `actor_id`: `long`
  - `user_id`: `long`
  - `prev_participant`: `flags.0?ChannelParticipant` - optional через flags.0
  - `new_participant`: `flags.1?ChannelParticipant` - optional через flags.1
  - `invite`: `flags.2?ExportedChatInvite` - optional через flags.2
  - `qts`: `int`

### `updateChannelPinnedTopic`

- ID: `422509539` / `0x192efbe3`
- Сигнатура: `updateChannelPinnedTopic(flags:#, pinned:flags.0?true, channel_id:long, topic_id:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChannelPinnedTopic
- Поля:
  - `flags`: `#` - служебное поле flags
  - `pinned`: `flags.0?true` - optional через flags.0
  - `channel_id`: `long`
  - `topic_id`: `int`

### `updateChannelPinnedTopics`

- ID: `-31881726` / `0xfe198602`
- Сигнатура: `updateChannelPinnedTopics(flags:#, channel_id:long, order:flags.0?Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChannelPinnedTopics
- Поля:
  - `flags`: `#` - служебное поле flags
  - `channel_id`: `long`
  - `order`: `flags.0?Vector` - optional через flags.0

### `updateChannelReadMessagesContents`

- ID: `636691703` / `0x25f324f7`
- Сигнатура: `updateChannelReadMessagesContents(flags:#, channel_id:long, top_msg_id:flags.0?int, saved_peer_id:flags.1?Peer, messages:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChannelReadMessagesContents
- Поля:
  - `flags`: `#` - служебное поле flags
  - `channel_id`: `long`
  - `top_msg_id`: `flags.0?int` - optional через flags.0
  - `saved_peer_id`: `flags.1?Peer` - optional через flags.1
  - `messages`: `Vector`

### `updateChannelTooLong`

- ID: `277713951` / `0x108d941f`
- Сигнатура: `updateChannelTooLong(flags:#, channel_id:long, pts:flags.0?int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChannelTooLong
- Поля:
  - `flags`: `#` - служебное поле flags
  - `channel_id`: `long`
  - `pts`: `flags.0?int` - optional через flags.0

### `updateChannelUserTyping`

- ID: `-1937192669` / `0x8c88c923`
- Сигнатура: `updateChannelUserTyping(flags:#, channel_id:long, top_msg_id:flags.0?int, from_id:Peer, action:SendMessageAction) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChannelUserTyping
- Поля:
  - `flags`: `#` - служебное поле flags
  - `channel_id`: `long`
  - `top_msg_id`: `flags.0?int` - optional через flags.0
  - `from_id`: `Peer`
  - `action`: `SendMessageAction`

### `updateChannelViewForumAsMessages`

- ID: `129403168` / `0x07b68920`
- Сигнатура: `updateChannelViewForumAsMessages(channel_id:long, enabled:Bool) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChannelViewForumAsMessages
- Поля:
  - `channel_id`: `long`
  - `enabled`: `Bool`

### `updateChannelWebPage`

- ID: `791390623` / `0x2f2ba99f`
- Сигнатура: `updateChannelWebPage(channel_id:long, webpage:WebPage, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChannelWebPage
- Поля:
  - `channel_id`: `long`
  - `webpage`: `WebPage`
  - `pts`: `int`
  - `pts_count`: `int`

### `updateChat`

- ID: `-124097970` / `0xf89a6a4e`
- Сигнатура: `updateChat(chat_id:long) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChat
- Поля:
  - `chat_id`: `long`

### `updateChatDefaultBannedRights`

- ID: `1421875280` / `0x54c01850`
- Сигнатура: `updateChatDefaultBannedRights(peer:Peer, default_banned_rights:ChatBannedRights, version:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChatDefaultBannedRights
- Поля:
  - `peer`: `Peer`
  - `default_banned_rights`: `ChatBannedRights`
  - `version`: `int`

### `updateChatParticipant`

- ID: `-796432838` / `0xd087663a`
- Сигнатура: `updateChatParticipant(flags:#, chat_id:long, date:int, actor_id:long, user_id:long, prev_participant:flags.0?ChatParticipant, new_participant:flags.1?ChatParticipant, invite:flags.2?ExportedChatInvite, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChatParticipant
- Поля:
  - `flags`: `#` - служебное поле flags
  - `chat_id`: `long`
  - `date`: `int`
  - `actor_id`: `long`
  - `user_id`: `long`
  - `prev_participant`: `flags.0?ChatParticipant` - optional через flags.0
  - `new_participant`: `flags.1?ChatParticipant` - optional через flags.1
  - `invite`: `flags.2?ExportedChatInvite` - optional через flags.2
  - `qts`: `int`

### `updateChatParticipantAdd`

- ID: `1037718609` / `0x3dda5451`
- Сигнатура: `updateChatParticipantAdd(chat_id:long, user_id:long, inviter_id:long, date:int, version:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChatParticipantAdd
- Поля:
  - `chat_id`: `long`
  - `user_id`: `long`
  - `inviter_id`: `long`
  - `date`: `int`
  - `version`: `int`

### `updateChatParticipantAdmin`

- ID: `-674602590` / `0xd7ca61a2`
- Сигнатура: `updateChatParticipantAdmin(chat_id:long, user_id:long, is_admin:Bool, version:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChatParticipantAdmin
- Поля:
  - `chat_id`: `long`
  - `user_id`: `long`
  - `is_admin`: `Bool`
  - `version`: `int`

### `updateChatParticipantDelete`

- ID: `-483443337` / `0xe32f3d77`
- Сигнатура: `updateChatParticipantDelete(chat_id:long, user_id:long, version:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChatParticipantDelete
- Поля:
  - `chat_id`: `long`
  - `user_id`: `long`
  - `version`: `int`

### `updateChatParticipants`

- ID: `125178264` / `0x07761198`
- Сигнатура: `updateChatParticipants(participants:ChatParticipants) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChatParticipants
- Поля:
  - `participants`: `ChatParticipants`

### `updateChatUserTyping`

- ID: `-2092401936` / `0x83487af0`
- Сигнатура: `updateChatUserTyping(chat_id:long, from_id:Peer, action:SendMessageAction) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateChatUserTyping
- Поля:
  - `chat_id`: `long`
  - `from_id`: `Peer`
  - `action`: `SendMessageAction`

### `updateConfig`

- ID: `-1574314746` / `0xa229dd06`
- Сигнатура: `updateConfig() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateConfig
- Поля:
  - Нет полей.

### `updateContactsReset`

- ID: `1887741886` / `0x7084a7be`
- Сигнатура: `updateContactsReset() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateContactsReset
- Поля:
  - Нет полей.

### `updateDcOptions`

- ID: `-1906403213` / `0x8e5e9873`
- Сигнатура: `updateDcOptions(dc_options:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateDcOptions
- Поля:
  - `dc_options`: `Vector`

### `updateDeleteChannelMessages`

- ID: `-1020437742` / `0xc32d5b12`
- Сигнатура: `updateDeleteChannelMessages(channel_id:long, messages:Vector, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateDeleteChannelMessages
- Поля:
  - `channel_id`: `long`
  - `messages`: `Vector`
  - `pts`: `int`
  - `pts_count`: `int`

### `updateDeleteMessages`

- ID: `-1576161051` / `0xa20db0e5`
- Сигнатура: `updateDeleteMessages(messages:Vector, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateDeleteMessages
- Поля:
  - `messages`: `Vector`
  - `pts`: `int`
  - `pts_count`: `int`

### `updateDeleteQuickReply`

- ID: `1407644140` / `0x53e6f1ec`
- Сигнатура: `updateDeleteQuickReply(shortcut_id:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateDeleteQuickReply
- Поля:
  - `shortcut_id`: `int`

### `updateDeleteQuickReplyMessages`

- ID: `1450174413` / `0x566fe7cd`
- Сигнатура: `updateDeleteQuickReplyMessages(shortcut_id:int, messages:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateDeleteQuickReplyMessages
- Поля:
  - `shortcut_id`: `int`
  - `messages`: `Vector`

### `updateDeleteScheduledMessages`

- ID: `-223929981` / `0xf2a71983`
- Сигнатура: `updateDeleteScheduledMessages(flags:#, peer:Peer, messages:Vector, sent_messages:flags.0?Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateDeleteScheduledMessages
- Поля:
  - `flags`: `#` - служебное поле flags
  - `peer`: `Peer`
  - `messages`: `Vector`
  - `sent_messages`: `flags.0?Vector` - optional через flags.0

### `updateDialogFilter`

- ID: `654302845` / `0x26ffde7d`
- Сигнатура: `updateDialogFilter(flags:#, id:int, filter:flags.0?DialogFilter) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateDialogFilter
- Поля:
  - `flags`: `#` - служебное поле flags
  - `id`: `int`
  - `filter`: `flags.0?DialogFilter` - optional через flags.0

### `updateDialogFilterOrder`

- ID: `-1512627963` / `0xa5d72105`
- Сигнатура: `updateDialogFilterOrder(order:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateDialogFilterOrder
- Поля:
  - `order`: `Vector`

### `updateDialogFilters`

- ID: `889491791` / `0x3504914f`
- Сигнатура: `updateDialogFilters() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateDialogFilters
- Поля:
  - Нет полей.

### `updateDialogPinned`

- ID: `1852826908` / `0x6e6fe51c`
- Сигнатура: `updateDialogPinned(flags:#, pinned:flags.0?true, folder_id:flags.1?int, peer:DialogPeer) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateDialogPinned
- Поля:
  - `flags`: `#` - служебное поле flags
  - `pinned`: `flags.0?true` - optional через flags.0
  - `folder_id`: `flags.1?int` - optional через flags.1
  - `peer`: `DialogPeer`

### `updateDialogUnreadMark`

- ID: `-1235684802` / `0xb658f23e`
- Сигнатура: `updateDialogUnreadMark(flags:#, unread:flags.0?true, peer:DialogPeer, saved_peer_id:flags.1?Peer) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateDialogUnreadMark
- Поля:
  - `flags`: `#` - служебное поле flags
  - `unread`: `flags.0?true` - optional через flags.0
  - `peer`: `DialogPeer`
  - `saved_peer_id`: `flags.1?Peer` - optional через flags.1

### `updateDraftMessage`

- ID: `-302247650` / `0xedfc111e`
- Сигнатура: `updateDraftMessage(flags:#, peer:Peer, top_msg_id:flags.0?int, saved_peer_id:flags.1?Peer, draft:DraftMessage) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateDraftMessage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `peer`: `Peer`
  - `top_msg_id`: `flags.0?int` - optional через flags.0
  - `saved_peer_id`: `flags.1?Peer` - optional через flags.1
  - `draft`: `DraftMessage`

### `updateEditChannelMessage`

- ID: `457133559` / `0x1b3f4df7`
- Сигнатура: `updateEditChannelMessage(message:Message, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateEditChannelMessage
- Поля:
  - `message`: `Message`
  - `pts`: `int`
  - `pts_count`: `int`

### `updateEditMessage`

- ID: `-469536605` / `0xe40370a3`
- Сигнатура: `updateEditMessage(message:Message, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateEditMessage
- Поля:
  - `message`: `Message`
  - `pts`: `int`
  - `pts_count`: `int`

### `updateEncryptedChatTyping`

- ID: `386986326` / `0x1710f156`
- Сигнатура: `updateEncryptedChatTyping(chat_id:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateEncryptedChatTyping
- Поля:
  - `chat_id`: `int`

### `updateEncryptedMessagesRead`

- ID: `956179895` / `0x38fe25b7`
- Сигнатура: `updateEncryptedMessagesRead(chat_id:int, max_date:int, date:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateEncryptedMessagesRead
- Поля:
  - `chat_id`: `int`
  - `max_date`: `int`
  - `date`: `int`

### `updateEncryption`

- ID: `-1264392051` / `0xb4a2e88d`
- Сигнатура: `updateEncryption(chat:EncryptedChat, date:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateEncryption
- Поля:
  - `chat`: `EncryptedChat`
  - `date`: `int`

### `updateFavedStickers`

- ID: `-451831443` / `0xe511996d`
- Сигнатура: `updateFavedStickers() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateFavedStickers
- Поля:
  - Нет полей.

### `updateFolderPeers`

- ID: `422972864` / `0x19360dc0`
- Сигнатура: `updateFolderPeers(folder_peers:Vector, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateFolderPeers
- Поля:
  - `folder_peers`: `Vector`
  - `pts`: `int`
  - `pts_count`: `int`

### `updateGeoLiveViewed`

- ID: `-2027964103` / `0x871fb939`
- Сигнатура: `updateGeoLiveViewed(peer:Peer, msg_id:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateGeoLiveViewed
- Поля:
  - `peer`: `Peer`
  - `msg_id`: `int`

### `updateGroupCall`

- ID: `-1747565759` / `0x97d64341`
- Сигнатура: `updateGroupCall(flags:#, chat_id:flags.0?long, call:GroupCall) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateGroupCall
- Поля:
  - `flags`: `#` - служебное поле flags
  - `chat_id`: `flags.0?long` - optional через flags.0
  - `call`: `GroupCall`

### `updateGroupCallChainBlocks`

- ID: `-1535694705` / `0xa477288f`
- Сигнатура: `updateGroupCallChainBlocks(call:InputGroupCall, sub_chain_id:int, blocks:Vector, next_offset:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateGroupCallChainBlocks
- Поля:
  - `call`: `InputGroupCall`
  - `sub_chain_id`: `int`
  - `blocks`: `Vector`
  - `next_offset`: `int`

### `updateGroupCallConnection`

- ID: `192428418` / `0x0b783982`
- Сигнатура: `updateGroupCallConnection(flags:#, presentation:flags.0?true, params:DataJSON) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateGroupCallConnection
- Поля:
  - `flags`: `#` - служебное поле flags
  - `presentation`: `flags.0?true` - optional через flags.0
  - `params`: `DataJSON`

### `updateGroupCallParticipants`

- ID: `-219423922` / `0xf2ebdb4e`
- Сигнатура: `updateGroupCallParticipants(call:InputGroupCall, participants:Vector, version:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateGroupCallParticipants
- Поля:
  - `call`: `InputGroupCall`
  - `participants`: `Vector`
  - `version`: `int`

### `updateInlineBotCallbackQuery`

- ID: `1763610706` / `0x691e9052`
- Сигнатура: `updateInlineBotCallbackQuery(flags:#, query_id:long, user_id:long, msg_id:InputBotInlineMessageID, chat_instance:long, data:flags.0?bytes, game_short_name:flags.1?string) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateInlineBotCallbackQuery
- Поля:
  - `flags`: `#` - служебное поле flags
  - `query_id`: `long`
  - `user_id`: `long`
  - `msg_id`: `InputBotInlineMessageID`
  - `chat_instance`: `long`
  - `data`: `flags.0?bytes` - optional через flags.0
  - `game_short_name`: `flags.1?string` - optional через flags.1

### `updateLangPack`

- ID: `1442983757` / `0x56022f4d`
- Сигнатура: `updateLangPack(difference:LangPackDifference) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateLangPack
- Поля:
  - `difference`: `LangPackDifference`

### `updateLangPackTooLong`

- ID: `1180041828` / `0x46560264`
- Сигнатура: `updateLangPackTooLong(lang_code:string) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateLangPackTooLong
- Поля:
  - `lang_code`: `string`

### `updateLoginToken`

- ID: `1448076945` / `0x564fe691`
- Сигнатура: `updateLoginToken() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateLoginToken
- Поля:
  - Нет полей.

### `updateMessageExtendedMedia`

- ID: `-710666460` / `0xd5a41724`
- Сигнатура: `updateMessageExtendedMedia(peer:Peer, msg_id:int, extended_media:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateMessageExtendedMedia
- Поля:
  - `peer`: `Peer`
  - `msg_id`: `int`
  - `extended_media`: `Vector`

### `updateMessageID`

- ID: `1318109142` / `0x4e90bfd6`
- Сигнатура: `updateMessageID(id:int, random_id:long) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateMessageID
- Поля:
  - `id`: `int`
  - `random_id`: `long`

### `updateMessagePoll`

- ID: `-1398708869` / `0xaca1657b`
- Сигнатура: `updateMessagePoll(flags:#, poll_id:long, poll:flags.0?Poll, results:PollResults) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateMessagePoll
- Поля:
  - `flags`: `#` - служебное поле flags
  - `poll_id`: `long`
  - `poll`: `flags.0?Poll` - optional через flags.0
  - `results`: `PollResults`

### `updateMessagePollVote`

- ID: `619974263` / `0x24f40e77`
- Сигнатура: `updateMessagePollVote(poll_id:long, peer:Peer, options:Vector, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateMessagePollVote
- Поля:
  - `poll_id`: `long`
  - `peer`: `Peer`
  - `options`: `Vector`
  - `qts`: `int`

### `updateMessageReactions`

- ID: `506035194` / `0x1e297bfa`
- Сигнатура: `updateMessageReactions(flags:#, peer:Peer, msg_id:int, top_msg_id:flags.0?int, saved_peer_id:flags.1?Peer, reactions:MessageReactions) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateMessageReactions
- Поля:
  - `flags`: `#` - служебное поле flags
  - `peer`: `Peer`
  - `msg_id`: `int`
  - `top_msg_id`: `flags.0?int` - optional через flags.0
  - `saved_peer_id`: `flags.1?Peer` - optional через flags.1
  - `reactions`: `MessageReactions`

### `updateMonoForumNoPaidException`

- ID: `-1618924792` / `0x9f812b08`
- Сигнатура: `updateMonoForumNoPaidException(flags:#, exception:flags.0?true, channel_id:long, saved_peer_id:Peer) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateMonoForumNoPaidException
- Поля:
  - `flags`: `#` - служебное поле flags
  - `exception`: `flags.0?true` - optional через flags.0
  - `channel_id`: `long`
  - `saved_peer_id`: `Peer`

### `updateMoveStickerSetToTop`

- ID: `-2030252155` / `0x86fccf85`
- Сигнатура: `updateMoveStickerSetToTop(flags:#, masks:flags.0?true, emojis:flags.1?true, stickerset:long) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateMoveStickerSetToTop
- Поля:
  - `flags`: `#` - служебное поле flags
  - `masks`: `flags.0?true` - optional через flags.0
  - `emojis`: `flags.1?true` - optional через flags.1
  - `stickerset`: `long`

### `updateNewAuthorization`

- ID: `-1991136273` / `0x8951abef`
- Сигнатура: `updateNewAuthorization(flags:#, unconfirmed:flags.0?true, hash:long, date:flags.0?int, device:flags.0?string, location:flags.0?string) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateNewAuthorization
- Поля:
  - `flags`: `#` - служебное поле flags
  - `unconfirmed`: `flags.0?true` - optional через flags.0
  - `hash`: `long`
  - `date`: `flags.0?int` - optional через flags.0
  - `device`: `flags.0?string` - optional через flags.0
  - `location`: `flags.0?string` - optional через flags.0

### `updateNewChannelMessage`

- ID: `1656358105` / `0x62ba04d9`
- Сигнатура: `updateNewChannelMessage(message:Message, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateNewChannelMessage
- Поля:
  - `message`: `Message`
  - `pts`: `int`
  - `pts_count`: `int`

### `updateNewEncryptedMessage`

- ID: `314359194` / `0x12bcbd9a`
- Сигнатура: `updateNewEncryptedMessage(message:EncryptedMessage, qts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateNewEncryptedMessage
- Поля:
  - `message`: `EncryptedMessage`
  - `qts`: `int`

### `updateNewMessage`

- ID: `522914557` / `0x1f2b0afd`
- Сигнатура: `updateNewMessage(message:Message, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateNewMessage
- Поля:
  - `message`: `Message`
  - `pts`: `int`
  - `pts_count`: `int`

### `updateNewQuickReply`

- ID: `-180508905` / `0xf53da717`
- Сигнатура: `updateNewQuickReply(quick_reply:QuickReply) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateNewQuickReply
- Поля:
  - `quick_reply`: `QuickReply`

### `updateNewScheduledMessage`

- ID: `967122427` / `0x39a51dfb`
- Сигнатура: `updateNewScheduledMessage(message:Message) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateNewScheduledMessage
- Поля:
  - `message`: `Message`

### `updateNewStickerSet`

- ID: `1753886890` / `0x688a30aa`
- Сигнатура: `updateNewStickerSet(stickerset:messages.StickerSet) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateNewStickerSet
- Поля:
  - `stickerset`: `messages.StickerSet`

### `updateNewStoryReaction`

- ID: `405070859` / `0x1824e40b`
- Сигнатура: `updateNewStoryReaction(story_id:int, peer:Peer, reaction:Reaction) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateNewStoryReaction
- Поля:
  - `story_id`: `int`
  - `peer`: `Peer`
  - `reaction`: `Reaction`

### `updateNotifySettings`

- ID: `-1094555409` / `0xbec268ef`
- Сигнатура: `updateNotifySettings(peer:NotifyPeer, notify_settings:PeerNotifySettings) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateNotifySettings
- Поля:
  - `peer`: `NotifyPeer`
  - `notify_settings`: `PeerNotifySettings`

### `updatePaidReactionPrivacy`

- ID: `-1955438642` / `0x8b725fce`
- Сигнатура: `updatePaidReactionPrivacy(private:PaidReactionPrivacy) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePaidReactionPrivacy
- Поля:
  - `private`: `PaidReactionPrivacy`

### `updatePeerBlocked`

- ID: `-337610926` / `0xebe07752`
- Сигнатура: `updatePeerBlocked(flags:#, blocked:flags.0?true, blocked_my_stories_from:flags.1?true, peer_id:Peer) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePeerBlocked
- Поля:
  - `flags`: `#` - служебное поле flags
  - `blocked`: `flags.0?true` - optional через flags.0
  - `blocked_my_stories_from`: `flags.1?true` - optional через flags.1
  - `peer_id`: `Peer`

### `updatePeerHistoryTTL`

- ID: `-1147422299` / `0xbb9bb9a5`
- Сигнатура: `updatePeerHistoryTTL(flags:#, peer:Peer, ttl_period:flags.0?int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePeerHistoryTTL
- Поля:
  - `flags`: `#` - служебное поле flags
  - `peer`: `Peer`
  - `ttl_period`: `flags.0?int` - optional через flags.0

### `updatePeerLocated`

- ID: `-1263546448` / `0xb4afcfb0`
- Сигнатура: `updatePeerLocated(peers:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePeerLocated
- Поля:
  - `peers`: `Vector`

### `updatePeerSettings`

- ID: `1786671974` / `0x6a7e7366`
- Сигнатура: `updatePeerSettings(peer:Peer, settings:PeerSettings) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePeerSettings
- Поля:
  - `peer`: `Peer`
  - `settings`: `PeerSettings`

### `updatePeerWallpaper`

- ID: `-1371598819` / `0xae3f101d`
- Сигнатура: `updatePeerWallpaper(flags:#, wallpaper_overridden:flags.1?true, peer:Peer, wallpaper:flags.0?WallPaper) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePeerWallpaper
- Поля:
  - `flags`: `#` - служебное поле flags
  - `wallpaper_overridden`: `flags.1?true` - optional через flags.1
  - `peer`: `Peer`
  - `wallpaper`: `flags.0?WallPaper` - optional через flags.0

### `updatePendingJoinRequests`

- ID: `1885586395` / `0x7063c3db`
- Сигнатура: `updatePendingJoinRequests(peer:Peer, requests_pending:int, recent_requesters:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePendingJoinRequests
- Поля:
  - `peer`: `Peer`
  - `requests_pending`: `int`
  - `recent_requesters`: `Vector`

### `updatePhoneCall`

- ID: `-1425052898` / `0xab0f6b1e`
- Сигнатура: `updatePhoneCall(phone_call:PhoneCall) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePhoneCall
- Поля:
  - `phone_call`: `PhoneCall`

### `updatePhoneCallSignalingData`

- ID: `643940105` / `0x2661bf09`
- Сигнатура: `updatePhoneCallSignalingData(phone_call_id:long, data:bytes) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePhoneCallSignalingData
- Поля:
  - `phone_call_id`: `long`
  - `data`: `bytes`

### `updatePinnedChannelMessages`

- ID: `1538885128` / `0x5bb98608`
- Сигнатура: `updatePinnedChannelMessages(flags:#, pinned:flags.0?true, channel_id:long, messages:Vector, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePinnedChannelMessages
- Поля:
  - `flags`: `#` - служебное поле flags
  - `pinned`: `flags.0?true` - optional через flags.0
  - `channel_id`: `long`
  - `messages`: `Vector`
  - `pts`: `int`
  - `pts_count`: `int`

### `updatePinnedDialogs`

- ID: `-99664734` / `0xfa0f3ca2`
- Сигнатура: `updatePinnedDialogs(flags:#, folder_id:flags.1?int, order:flags.0?Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePinnedDialogs
- Поля:
  - `flags`: `#` - служебное поле flags
  - `folder_id`: `flags.1?int` - optional через flags.1
  - `order`: `flags.0?Vector` - optional через flags.0

### `updatePinnedMessages`

- ID: `-309990731` / `0xed85eab5`
- Сигнатура: `updatePinnedMessages(flags:#, pinned:flags.0?true, peer:Peer, messages:Vector, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePinnedMessages
- Поля:
  - `flags`: `#` - служебное поле flags
  - `pinned`: `flags.0?true` - optional через flags.0
  - `peer`: `Peer`
  - `messages`: `Vector`
  - `pts`: `int`
  - `pts_count`: `int`

### `updatePinnedSavedDialogs`

- ID: `1751942566` / `0x686c85a6`
- Сигнатура: `updatePinnedSavedDialogs(flags:#, order:flags.0?Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePinnedSavedDialogs
- Поля:
  - `flags`: `#` - служебное поле flags
  - `order`: `flags.0?Vector` - optional через flags.0

### `updatePrivacy`

- ID: `-298113238` / `0xee3b272a`
- Сигнатура: `updatePrivacy(key:PrivacyKey, rules:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePrivacy
- Поля:
  - `key`: `PrivacyKey`
  - `rules`: `Vector`

### `updatePtsChanged`

- ID: `861169551` / `0x3354678f`
- Сигнатура: `updatePtsChanged() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatePtsChanged
- Поля:
  - Нет полей.

### `updateQuickReplies`

- ID: `-112784718` / `0xf9470ab2`
- Сигнатура: `updateQuickReplies(quick_replies:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateQuickReplies
- Поля:
  - `quick_replies`: `Vector`

### `updateQuickReplyMessage`

- ID: `1040518415` / `0x3e050d0f`
- Сигнатура: `updateQuickReplyMessage(message:Message) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateQuickReplyMessage
- Поля:
  - `message`: `Message`

### `updateReadChannelDiscussionInbox`

- ID: `-693004986` / `0xd6b19546`
- Сигнатура: `updateReadChannelDiscussionInbox(flags:#, channel_id:long, top_msg_id:int, read_max_id:int, broadcast_id:flags.0?long, broadcast_post:flags.0?int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateReadChannelDiscussionInbox
- Поля:
  - `flags`: `#` - служебное поле flags
  - `channel_id`: `long`
  - `top_msg_id`: `int`
  - `read_max_id`: `int`
  - `broadcast_id`: `flags.0?long` - optional через flags.0
  - `broadcast_post`: `flags.0?int` - optional через flags.0

### `updateReadChannelDiscussionOutbox`

- ID: `1767677564` / `0x695c9e7c`
- Сигнатура: `updateReadChannelDiscussionOutbox(channel_id:long, top_msg_id:int, read_max_id:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateReadChannelDiscussionOutbox
- Поля:
  - `channel_id`: `long`
  - `top_msg_id`: `int`
  - `read_max_id`: `int`

### `updateReadChannelInbox`

- ID: `-1842450928` / `0x922e6e10`
- Сигнатура: `updateReadChannelInbox(flags:#, folder_id:flags.0?int, channel_id:long, max_id:int, still_unread_count:int, pts:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateReadChannelInbox
- Поля:
  - `flags`: `#` - служебное поле flags
  - `folder_id`: `flags.0?int` - optional через flags.0
  - `channel_id`: `long`
  - `max_id`: `int`
  - `still_unread_count`: `int`
  - `pts`: `int`

### `updateReadChannelOutbox`

- ID: `-1218471511` / `0xb75f99a9`
- Сигнатура: `updateReadChannelOutbox(channel_id:long, max_id:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateReadChannelOutbox
- Поля:
  - `channel_id`: `long`
  - `max_id`: `int`

### `updateReadFeaturedEmojiStickers`

- ID: `-78886548` / `0xfb4c496c`
- Сигнатура: `updateReadFeaturedEmojiStickers() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateReadFeaturedEmojiStickers
- Поля:
  - Нет полей.

### `updateReadFeaturedStickers`

- ID: `1461528386` / `0x571d2742`
- Сигнатура: `updateReadFeaturedStickers() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateReadFeaturedStickers
- Поля:
  - Нет полей.

### `updateReadHistoryInbox`

- ID: `-1667805217` / `0x9c974fdf`
- Сигнатура: `updateReadHistoryInbox(flags:#, folder_id:flags.0?int, peer:Peer, max_id:int, still_unread_count:int, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateReadHistoryInbox
- Поля:
  - `flags`: `#` - служебное поле flags
  - `folder_id`: `flags.0?int` - optional через flags.0
  - `peer`: `Peer`
  - `max_id`: `int`
  - `still_unread_count`: `int`
  - `pts`: `int`
  - `pts_count`: `int`

### `updateReadHistoryOutbox`

- ID: `791617983` / `0x2f2f21bf`
- Сигнатура: `updateReadHistoryOutbox(peer:Peer, max_id:int, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateReadHistoryOutbox
- Поля:
  - `peer`: `Peer`
  - `max_id`: `int`
  - `pts`: `int`
  - `pts_count`: `int`

### `updateReadMessagesContents`

- ID: `-131960447` / `0xf8227181`
- Сигнатура: `updateReadMessagesContents(flags:#, messages:Vector, pts:int, pts_count:int, date:flags.0?int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateReadMessagesContents
- Поля:
  - `flags`: `#` - служебное поле flags
  - `messages`: `Vector`
  - `pts`: `int`
  - `pts_count`: `int`
  - `date`: `flags.0?int` - optional через flags.0

### `updateReadMonoForumInbox`

- ID: `2008081266` / `0x77b0e372`
- Сигнатура: `updateReadMonoForumInbox(channel_id:long, saved_peer_id:Peer, read_max_id:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateReadMonoForumInbox
- Поля:
  - `channel_id`: `long`
  - `saved_peer_id`: `Peer`
  - `read_max_id`: `int`

### `updateReadMonoForumOutbox`

- ID: `-1532521610` / `0xa4a79376`
- Сигнатура: `updateReadMonoForumOutbox(channel_id:long, saved_peer_id:Peer, read_max_id:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateReadMonoForumOutbox
- Поля:
  - `channel_id`: `long`
  - `saved_peer_id`: `Peer`
  - `read_max_id`: `int`

### `updateReadStories`

- ID: `-145845461` / `0xf74e932b`
- Сигнатура: `updateReadStories(peer:Peer, max_id:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateReadStories
- Поля:
  - `peer`: `Peer`
  - `max_id`: `int`

### `updateRecentEmojiStatuses`

- ID: `821314523` / `0x30f443db`
- Сигнатура: `updateRecentEmojiStatuses() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateRecentEmojiStatuses
- Поля:
  - Нет полей.

### `updateRecentReactions`

- ID: `1870160884` / `0x6f7863f4`
- Сигнатура: `updateRecentReactions() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateRecentReactions
- Поля:
  - Нет полей.

### `updateRecentStickers`

- ID: `-1706939360` / `0x9a422c20`
- Сигнатура: `updateRecentStickers() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateRecentStickers
- Поля:
  - Нет полей.

### `updateSavedDialogPinned`

- ID: `-1364222348` / `0xaeaf9e74`
- Сигнатура: `updateSavedDialogPinned(flags:#, pinned:flags.0?true, peer:DialogPeer) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateSavedDialogPinned
- Поля:
  - `flags`: `#` - служебное поле flags
  - `pinned`: `flags.0?true` - optional через flags.0
  - `peer`: `DialogPeer`

### `updateSavedGifs`

- ID: `-1821035490` / `0x9375341e`
- Сигнатура: `updateSavedGifs() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateSavedGifs
- Поля:
  - Нет полей.

### `updateSavedReactionTags`

- ID: `969307186` / `0x39c67432`
- Сигнатура: `updateSavedReactionTags() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateSavedReactionTags
- Поля:
  - Нет полей.

### `updateSavedRingtones`

- ID: `1960361625` / `0x74d8be99`
- Сигнатура: `updateSavedRingtones() => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateSavedRingtones
- Поля:
  - Нет полей.

### `updateSentPhoneCode`

- ID: `1347068303` / `0x504aa18f`
- Сигнатура: `updateSentPhoneCode(sent_code:auth.SentCode) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateSentPhoneCode
- Поля:
  - `sent_code`: `auth.SentCode`

### `updateSentStoryReaction`

- ID: `2103604867` / `0x7d627683`
- Сигнатура: `updateSentStoryReaction(peer:Peer, story_id:int, reaction:Reaction) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateSentStoryReaction
- Поля:
  - `peer`: `Peer`
  - `story_id`: `int`
  - `reaction`: `Reaction`

### `updateServiceNotification`

- ID: `-337352679` / `0xebe46819`
- Сигнатура: `updateServiceNotification(flags:#, popup:flags.0?true, invert_media:flags.2?true, inbox_date:flags.1?int, type:string, message:string, media:MessageMedia, entities:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateServiceNotification
- Поля:
  - `flags`: `#` - служебное поле flags
  - `popup`: `flags.0?true` - optional через flags.0
  - `invert_media`: `flags.2?true` - optional через flags.2
  - `inbox_date`: `flags.1?int` - optional через flags.1
  - `type`: `string`
  - `message`: `string`
  - `media`: `MessageMedia`
  - `entities`: `Vector`

### `updateSmsJob`

- ID: `-245208620` / `0xf16269d4`
- Сигнатура: `updateSmsJob(job_id:string) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateSmsJob
- Поля:
  - `job_id`: `string`

### `updateStarsBalance`

- ID: `1317053305` / `0x4e80a379`
- Сигнатура: `updateStarsBalance(balance:StarsAmount) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateStarsBalance
- Поля:
  - `balance`: `StarsAmount`

### `updateStarsRevenueStatus`

- ID: `-1518030823` / `0xa584b019`
- Сигнатура: `updateStarsRevenueStatus(peer:Peer, status:StarsRevenueStatus) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateStarsRevenueStatus
- Поля:
  - `peer`: `Peer`
  - `status`: `StarsRevenueStatus`

### `updateStickerSets`

- ID: `834816008` / `0x31c24808`
- Сигнатура: `updateStickerSets(flags:#, masks:flags.0?true, emojis:flags.1?true) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateStickerSets
- Поля:
  - `flags`: `#` - служебное поле flags
  - `masks`: `flags.0?true` - optional через flags.0
  - `emojis`: `flags.1?true` - optional через flags.1

### `updateStickerSetsOrder`

- ID: `196268545` / `0x0bb2d201`
- Сигнатура: `updateStickerSetsOrder(flags:#, masks:flags.0?true, emojis:flags.1?true, order:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateStickerSetsOrder
- Поля:
  - `flags`: `#` - служебное поле flags
  - `masks`: `flags.0?true` - optional через flags.0
  - `emojis`: `flags.1?true` - optional через flags.1
  - `order`: `Vector`

### `updateStoriesStealthMode`

- ID: `738741697` / `0x2c084dc1`
- Сигнатура: `updateStoriesStealthMode(stealth_mode:StoriesStealthMode) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateStoriesStealthMode
- Поля:
  - `stealth_mode`: `StoriesStealthMode`

### `updateStory`

- ID: `1974712216` / `0x75b3b798`
- Сигнатура: `updateStory(peer:Peer, story:StoryItem) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateStory
- Поля:
  - `peer`: `Peer`
  - `story`: `StoryItem`

### `updateStoryID`

- ID: `468923833` / `0x1bf335b9`
- Сигнатура: `updateStoryID(id:int, random_id:long) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateStoryID
- Поля:
  - `id`: `int`
  - `random_id`: `long`

### `updateTheme`

- ID: `-2112423005` / `0x8216fba3`
- Сигнатура: `updateTheme(theme:Theme) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateTheme
- Поля:
  - `theme`: `Theme`

### `updateTranscribedAudio`

- ID: `8703322` / `0x0084cd5a`
- Сигнатура: `updateTranscribedAudio(flags:#, pending:flags.0?true, peer:Peer, msg_id:int, transcription_id:long, text:string) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateTranscribedAudio
- Поля:
  - `flags`: `#` - служебное поле flags
  - `pending`: `flags.0?true` - optional через flags.0
  - `peer`: `Peer`
  - `msg_id`: `int`
  - `transcription_id`: `long`
  - `text`: `string`

### `updateUser`

- ID: `542282808` / `0x20529438`
- Сигнатура: `updateUser(user_id:long) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateUser
- Поля:
  - `user_id`: `long`

### `updateUserEmojiStatus`

- ID: `674706841` / `0x28373599`
- Сигнатура: `updateUserEmojiStatus(user_id:long, emoji_status:EmojiStatus) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateUserEmojiStatus
- Поля:
  - `user_id`: `long`
  - `emoji_status`: `EmojiStatus`

### `updateUserName`

- ID: `-1484486364` / `0xa7848924`
- Сигнатура: `updateUserName(user_id:long, first_name:string, last_name:string, usernames:Vector) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateUserName
- Поля:
  - `user_id`: `long`
  - `first_name`: `string`
  - `last_name`: `string`
  - `usernames`: `Vector`

### `updateUserPhone`

- ID: `88680979` / `0x05492a13`
- Сигнатура: `updateUserPhone(user_id:long, phone:string) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateUserPhone
- Поля:
  - `user_id`: `long`
  - `phone`: `string`

### `updateUserStatus`

- ID: `-440534818` / `0xe5bdf8de`
- Сигнатура: `updateUserStatus(user_id:long, status:UserStatus) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateUserStatus
- Поля:
  - `user_id`: `long`
  - `status`: `UserStatus`

### `updateUserTyping`

- ID: `-1071741569` / `0xc01e857f`
- Сигнатура: `updateUserTyping(user_id:long, action:SendMessageAction) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateUserTyping
- Поля:
  - `user_id`: `long`
  - `action`: `SendMessageAction`

### `updateWebPage`

- ID: `2139689491` / `0x7f891213`
- Сигнатура: `updateWebPage(webpage:WebPage, pts:int, pts_count:int) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateWebPage
- Поля:
  - `webpage`: `WebPage`
  - `pts`: `int`
  - `pts_count`: `int`

### `updateWebViewResultSent`

- ID: `361936797` / `0x1592b79d`
- Сигнатура: `updateWebViewResultSent(query_id:long) => Update`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateWebViewResultSent
- Поля:
  - `query_id`: `long`

## `Updates`

- Официальный тип: https://core.telegram.org/type/Updates
- Количество constructors: **7**

### `updateShort`

- ID: `2027216577` / `0x78d4dec1`
- Сигнатура: `updateShort(update:Update, date:int) => Updates`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateShort
- Поля:
  - `update`: `Update`
  - `date`: `int`

### `updateShortChatMessage`

- ID: `1299050149` / `0x4d6deea5`
- Сигнатура: `updateShortChatMessage(flags:#, out:flags.1?true, mentioned:flags.4?true, media_unread:flags.5?true, silent:flags.13?true, id:int, from_id:long, chat_id:long, message:string, pts:int, pts_count:int, date:int, fwd_from:flags.2?MessageFwdHeader, via_bot_id:flags.11?long, reply_to:flags.3?MessageReplyHeader, entities:flags.7?Vector, ttl_period:flags.25?int) => Updates`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateShortChatMessage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `out`: `flags.1?true` - optional через flags.1
  - `mentioned`: `flags.4?true` - optional через flags.4
  - `media_unread`: `flags.5?true` - optional через flags.5
  - `silent`: `flags.13?true` - optional через flags.13
  - `id`: `int`
  - `from_id`: `long`
  - `chat_id`: `long`
  - `message`: `string`
  - `pts`: `int`
  - `pts_count`: `int`
  - `date`: `int`
  - `fwd_from`: `flags.2?MessageFwdHeader` - optional через flags.2
  - `via_bot_id`: `flags.11?long` - optional через flags.11
  - `reply_to`: `flags.3?MessageReplyHeader` - optional через flags.3
  - `entities`: `flags.7?Vector` - optional через flags.7
  - `ttl_period`: `flags.25?int` - optional через flags.25

### `updateShortMessage`

- ID: `826001400` / `0x313bc7f8`
- Сигнатура: `updateShortMessage(flags:#, out:flags.1?true, mentioned:flags.4?true, media_unread:flags.5?true, silent:flags.13?true, id:int, user_id:long, message:string, pts:int, pts_count:int, date:int, fwd_from:flags.2?MessageFwdHeader, via_bot_id:flags.11?long, reply_to:flags.3?MessageReplyHeader, entities:flags.7?Vector, ttl_period:flags.25?int) => Updates`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateShortMessage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `out`: `flags.1?true` - optional через flags.1
  - `mentioned`: `flags.4?true` - optional через flags.4
  - `media_unread`: `flags.5?true` - optional через flags.5
  - `silent`: `flags.13?true` - optional через flags.13
  - `id`: `int`
  - `user_id`: `long`
  - `message`: `string`
  - `pts`: `int`
  - `pts_count`: `int`
  - `date`: `int`
  - `fwd_from`: `flags.2?MessageFwdHeader` - optional через flags.2
  - `via_bot_id`: `flags.11?long` - optional через flags.11
  - `reply_to`: `flags.3?MessageReplyHeader` - optional через flags.3
  - `entities`: `flags.7?Vector` - optional через flags.7
  - `ttl_period`: `flags.25?int` - optional через flags.25

### `updateShortSentMessage`

- ID: `-1877614335` / `0x9015e101`
- Сигнатура: `updateShortSentMessage(flags:#, out:flags.1?true, id:int, pts:int, pts_count:int, date:int, media:flags.9?MessageMedia, entities:flags.7?Vector, ttl_period:flags.25?int) => Updates`
- Официальная страница конструктора: https://core.telegram.org/constructor/updateShortSentMessage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `out`: `flags.1?true` - optional через flags.1
  - `id`: `int`
  - `pts`: `int`
  - `pts_count`: `int`
  - `date`: `int`
  - `media`: `flags.9?MessageMedia` - optional через flags.9
  - `entities`: `flags.7?Vector` - optional через flags.7
  - `ttl_period`: `flags.25?int` - optional через flags.25

### `updates`

- ID: `1957577280` / `0x74ae4240`
- Сигнатура: `updates(updates:Vector, users:Vector, chats:Vector, date:int, seq:int) => Updates`
- Официальная страница конструктора: https://core.telegram.org/constructor/updates
- Поля:
  - `updates`: `Vector`
  - `users`: `Vector`
  - `chats`: `Vector`
  - `date`: `int`
  - `seq`: `int`

### `updatesCombined`

- ID: `1918567619` / `0x725b04c3`
- Сигнатура: `updatesCombined(updates:Vector, users:Vector, chats:Vector, date:int, seq_start:int, seq:int) => Updates`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatesCombined
- Поля:
  - `updates`: `Vector`
  - `users`: `Vector`
  - `chats`: `Vector`
  - `date`: `int`
  - `seq_start`: `int`
  - `seq`: `int`

### `updatesTooLong`

- ID: `-484987010` / `0xe317af7e`
- Сигнатура: `updatesTooLong() => Updates`
- Официальная страница конструктора: https://core.telegram.org/constructor/updatesTooLong
- Поля:
  - Нет полей.

## `UrlAuthResult`

- Официальный тип: https://core.telegram.org/type/UrlAuthResult
- Количество constructors: **3**

### `urlAuthResultAccepted`

- ID: `-1886646706` / `0x8f8c0e4e`
- Сигнатура: `urlAuthResultAccepted(url:string) => UrlAuthResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/urlAuthResultAccepted
- Поля:
  - `url`: `string`

### `urlAuthResultDefault`

- ID: `-1445536993` / `0xa9d6db1f`
- Сигнатура: `urlAuthResultDefault() => UrlAuthResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/urlAuthResultDefault
- Поля:
  - Нет полей.

### `urlAuthResultRequest`

- ID: `-1831650802` / `0x92d33a0e`
- Сигнатура: `urlAuthResultRequest(flags:#, request_write_access:flags.0?true, bot:User, domain:string) => UrlAuthResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/urlAuthResultRequest
- Поля:
  - `flags`: `#` - служебное поле flags
  - `request_write_access`: `flags.0?true` - optional через flags.0
  - `bot`: `User`
  - `domain`: `string`

## `User`

- Официальный тип: https://core.telegram.org/type/User
- Количество constructors: **2**

### `user`

- ID: `34280482` / `0x020b1422`
- Сигнатура: `user(flags:#, self:flags.10?true, contact:flags.11?true, mutual_contact:flags.12?true, deleted:flags.13?true, bot:flags.14?true, bot_chat_history:flags.15?true, bot_nochats:flags.16?true, verified:flags.17?true, restricted:flags.18?true, min:flags.20?true, bot_inline_geo:flags.21?true, support:flags.23?true, scam:flags.24?true, apply_min_photo:flags.25?true, fake:flags.26?true, bot_attach_menu:flags.27?true, premium:flags.28?true, attach_menu_enabled:flags.29?true, flags2:#, bot_can_edit:flags2.1?true, close_friend:flags2.2?true, stories_hidden:flags2.3?true, stories_unavailable:flags2.4?true, contact_require_premium:flags2.10?true, bot_business:flags2.11?true, bot_has_main_app:flags2.13?true, id:long, access_hash:flags.0?long, first_name:flags.1?string, last_name:flags.2?string, username:flags.3?string, phone:flags.4?string, photo:flags.5?UserProfilePhoto, status:flags.6?UserStatus, bot_info_version:flags.14?int, restriction_reason:flags.18?Vector, bot_inline_placeholder:flags.19?string, lang_code:flags.22?string, emoji_status:flags.30?EmojiStatus, usernames:flags2.0?Vector, stories_max_id:flags2.5?int, color:flags2.8?PeerColor, profile_color:flags2.9?PeerColor, bot_active_users:flags2.12?int, bot_verification_icon:flags2.14?long, send_paid_messages_stars:flags2.15?long) => User`
- Официальная страница конструктора: https://core.telegram.org/constructor/user
- Поля:
  - `flags`: `#` - служебное поле flags
  - `self`: `flags.10?true` - optional через flags.10
  - `contact`: `flags.11?true` - optional через flags.11
  - `mutual_contact`: `flags.12?true` - optional через flags.12
  - `deleted`: `flags.13?true` - optional через flags.13
  - `bot`: `flags.14?true` - optional через flags.14
  - `bot_chat_history`: `flags.15?true` - optional через flags.15
  - `bot_nochats`: `flags.16?true` - optional через flags.16
  - `verified`: `flags.17?true` - optional через flags.17
  - `restricted`: `flags.18?true` - optional через flags.18
  - `min`: `flags.20?true` - optional через flags.20
  - `bot_inline_geo`: `flags.21?true` - optional через flags.21
  - `support`: `flags.23?true` - optional через flags.23
  - `scam`: `flags.24?true` - optional через flags.24
  - `apply_min_photo`: `flags.25?true` - optional через flags.25
  - `fake`: `flags.26?true` - optional через flags.26
  - `bot_attach_menu`: `flags.27?true` - optional через flags.27
  - `premium`: `flags.28?true` - optional через flags.28
  - `attach_menu_enabled`: `flags.29?true` - optional через flags.29
  - `flags2`: `#` - служебное поле flags
  - `bot_can_edit`: `flags2.1?true` - optional через flags2.1
  - `close_friend`: `flags2.2?true` - optional через flags2.2
  - `stories_hidden`: `flags2.3?true` - optional через flags2.3
  - `stories_unavailable`: `flags2.4?true` - optional через flags2.4
  - `contact_require_premium`: `flags2.10?true` - optional через flags2.10
  - `bot_business`: `flags2.11?true` - optional через flags2.11
  - `bot_has_main_app`: `flags2.13?true` - optional через flags2.13
  - `id`: `long`
  - `access_hash`: `flags.0?long` - optional через flags.0
  - `first_name`: `flags.1?string` - optional через flags.1
  - `last_name`: `flags.2?string` - optional через flags.2
  - `username`: `flags.3?string` - optional через flags.3
  - `phone`: `flags.4?string` - optional через flags.4
  - `photo`: `flags.5?UserProfilePhoto` - optional через flags.5
  - `status`: `flags.6?UserStatus` - optional через flags.6
  - `bot_info_version`: `flags.14?int` - optional через flags.14
  - `restriction_reason`: `flags.18?Vector` - optional через flags.18
  - `bot_inline_placeholder`: `flags.19?string` - optional через flags.19
  - `lang_code`: `flags.22?string` - optional через flags.22
  - `emoji_status`: `flags.30?EmojiStatus` - optional через flags.30
  - `usernames`: `flags2.0?Vector` - optional через flags2.0
  - `stories_max_id`: `flags2.5?int` - optional через flags2.5
  - `color`: `flags2.8?PeerColor` - optional через flags2.8
  - `profile_color`: `flags2.9?PeerColor` - optional через flags2.9
  - `bot_active_users`: `flags2.12?int` - optional через flags2.12
  - `bot_verification_icon`: `flags2.14?long` - optional через flags2.14
  - `send_paid_messages_stars`: `flags2.15?long` - optional через flags2.15

### `userEmpty`

- ID: `-742634630` / `0xd3bc4b7a`
- Сигнатура: `userEmpty(id:long) => User`
- Официальная страница конструктора: https://core.telegram.org/constructor/userEmpty
- Поля:
  - `id`: `long`

## `UserFull`

- Официальный тип: https://core.telegram.org/type/UserFull
- Количество constructors: **1**

### `userFull`

- ID: `-982010451` / `0xc577b5ad`
- Сигнатура: `userFull(flags:#, blocked:flags.0?true, phone_calls_available:flags.4?true, phone_calls_private:flags.5?true, can_pin_message:flags.7?true, has_scheduled:flags.12?true, video_calls_available:flags.13?true, voice_messages_forbidden:flags.20?true, translations_disabled:flags.23?true, stories_pinned_available:flags.26?true, blocked_my_stories_from:flags.27?true, wallpaper_overridden:flags.28?true, contact_require_premium:flags.29?true, read_dates_private:flags.30?true, flags2:#, sponsored_enabled:flags2.7?true, can_view_revenue:flags2.9?true, bot_can_manage_emoji_status:flags2.10?true, display_gifts_button:flags2.16?true, id:long, about:flags.1?string, settings:PeerSettings, personal_photo:flags.21?Photo, profile_photo:flags.2?Photo, fallback_photo:flags.22?Photo, notify_settings:PeerNotifySettings, bot_info:flags.3?BotInfo, pinned_msg_id:flags.6?int, common_chats_count:int, folder_id:flags.11?int, ttl_period:flags.14?int, theme:flags.15?ChatTheme, private_forward_name:flags.16?string, bot_group_admin_rights:flags.17?ChatAdminRights, bot_broadcast_admin_rights:flags.18?ChatAdminRights, wallpaper:flags.24?WallPaper, stories:flags.25?PeerStories, business_work_hours:flags2.0?BusinessWorkHours, business_location:flags2.1?BusinessLocation, business_greeting_message:flags2.2?BusinessGreetingMessage, business_away_message:flags2.3?BusinessAwayMessage, business_intro:flags2.4?BusinessIntro, birthday:flags2.5?Birthday, personal_channel_id:flags2.6?long, personal_channel_message:flags2.6?int, stargifts_count:flags2.8?int, starref_program:flags2.11?StarRefProgram, bot_verification:flags2.12?BotVerification, send_paid_messages_stars:flags2.14?long, disallowed_gifts:flags2.15?DisallowedGiftsSettings, stars_rating:flags2.17?StarsRating, stars_my_pending_rating:flags2.18?StarsRating, stars_my_pending_rating_date:flags2.18?int, main_tab:flags2.20?ProfileTab, saved_music:flags2.21?Document) => UserFull`
- Официальная страница конструктора: https://core.telegram.org/constructor/userFull
- Поля:
  - `flags`: `#` - служебное поле flags
  - `blocked`: `flags.0?true` - optional через flags.0
  - `phone_calls_available`: `flags.4?true` - optional через flags.4
  - `phone_calls_private`: `flags.5?true` - optional через flags.5
  - `can_pin_message`: `flags.7?true` - optional через flags.7
  - `has_scheduled`: `flags.12?true` - optional через flags.12
  - `video_calls_available`: `flags.13?true` - optional через flags.13
  - `voice_messages_forbidden`: `flags.20?true` - optional через flags.20
  - `translations_disabled`: `flags.23?true` - optional через flags.23
  - `stories_pinned_available`: `flags.26?true` - optional через flags.26
  - `blocked_my_stories_from`: `flags.27?true` - optional через flags.27
  - `wallpaper_overridden`: `flags.28?true` - optional через flags.28
  - `contact_require_premium`: `flags.29?true` - optional через flags.29
  - `read_dates_private`: `flags.30?true` - optional через flags.30
  - `flags2`: `#` - служебное поле flags
  - `sponsored_enabled`: `flags2.7?true` - optional через flags2.7
  - `can_view_revenue`: `flags2.9?true` - optional через flags2.9
  - `bot_can_manage_emoji_status`: `flags2.10?true` - optional через flags2.10
  - `display_gifts_button`: `flags2.16?true` - optional через flags2.16
  - `id`: `long`
  - `about`: `flags.1?string` - optional через flags.1
  - `settings`: `PeerSettings`
  - `personal_photo`: `flags.21?Photo` - optional через flags.21
  - `profile_photo`: `flags.2?Photo` - optional через flags.2
  - `fallback_photo`: `flags.22?Photo` - optional через flags.22
  - `notify_settings`: `PeerNotifySettings`
  - `bot_info`: `flags.3?BotInfo` - optional через flags.3
  - `pinned_msg_id`: `flags.6?int` - optional через flags.6
  - `common_chats_count`: `int`
  - `folder_id`: `flags.11?int` - optional через flags.11
  - `ttl_period`: `flags.14?int` - optional через flags.14
  - `theme`: `flags.15?ChatTheme` - optional через flags.15
  - `private_forward_name`: `flags.16?string` - optional через flags.16
  - `bot_group_admin_rights`: `flags.17?ChatAdminRights` - optional через flags.17
  - `bot_broadcast_admin_rights`: `flags.18?ChatAdminRights` - optional через flags.18
  - `wallpaper`: `flags.24?WallPaper` - optional через flags.24
  - `stories`: `flags.25?PeerStories` - optional через flags.25
  - `business_work_hours`: `flags2.0?BusinessWorkHours` - optional через flags2.0
  - `business_location`: `flags2.1?BusinessLocation` - optional через flags2.1
  - `business_greeting_message`: `flags2.2?BusinessGreetingMessage` - optional через flags2.2
  - `business_away_message`: `flags2.3?BusinessAwayMessage` - optional через flags2.3
  - `business_intro`: `flags2.4?BusinessIntro` - optional через flags2.4
  - `birthday`: `flags2.5?Birthday` - optional через flags2.5
  - `personal_channel_id`: `flags2.6?long` - optional через flags2.6
  - `personal_channel_message`: `flags2.6?int` - optional через flags2.6
  - `stargifts_count`: `flags2.8?int` - optional через flags2.8
  - `starref_program`: `flags2.11?StarRefProgram` - optional через flags2.11
  - `bot_verification`: `flags2.12?BotVerification` - optional через flags2.12
  - `send_paid_messages_stars`: `flags2.14?long` - optional через flags2.14
  - `disallowed_gifts`: `flags2.15?DisallowedGiftsSettings` - optional через flags2.15
  - `stars_rating`: `flags2.17?StarsRating` - optional через flags2.17
  - `stars_my_pending_rating`: `flags2.18?StarsRating` - optional через flags2.18
  - `stars_my_pending_rating_date`: `flags2.18?int` - optional через flags2.18
  - `main_tab`: `flags2.20?ProfileTab` - optional через flags2.20
  - `saved_music`: `flags2.21?Document` - optional через flags2.21

## `UserProfilePhoto`

- Официальный тип: https://core.telegram.org/type/UserProfilePhoto
- Количество constructors: **2**

### `userProfilePhoto`

- ID: `-2100168954` / `0x82d1f706`
- Сигнатура: `userProfilePhoto(flags:#, has_video:flags.0?true, personal:flags.2?true, photo_id:long, stripped_thumb:flags.1?bytes, dc_id:int) => UserProfilePhoto`
- Официальная страница конструктора: https://core.telegram.org/constructor/userProfilePhoto
- Поля:
  - `flags`: `#` - служебное поле flags
  - `has_video`: `flags.0?true` - optional через flags.0
  - `personal`: `flags.2?true` - optional через flags.2
  - `photo_id`: `long`
  - `stripped_thumb`: `flags.1?bytes` - optional через flags.1
  - `dc_id`: `int`

### `userProfilePhotoEmpty`

- ID: `1326562017` / `0x4f11bae1`
- Сигнатура: `userProfilePhotoEmpty() => UserProfilePhoto`
- Официальная страница конструктора: https://core.telegram.org/constructor/userProfilePhotoEmpty
- Поля:
  - Нет полей.

## `UserStatus`

- Официальный тип: https://core.telegram.org/type/UserStatus
- Количество constructors: **6**

### `userStatusEmpty`

- ID: `164646985` / `0x09d05049`
- Сигнатура: `userStatusEmpty() => UserStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/userStatusEmpty
- Поля:
  - Нет полей.

### `userStatusLastMonth`

- ID: `1703516023` / `0x65899777`
- Сигнатура: `userStatusLastMonth(flags:#, by_me:flags.0?true) => UserStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/userStatusLastMonth
- Поля:
  - `flags`: `#` - служебное поле flags
  - `by_me`: `flags.0?true` - optional через flags.0

### `userStatusLastWeek`

- ID: `1410997530` / `0x541a1d1a`
- Сигнатура: `userStatusLastWeek(flags:#, by_me:flags.0?true) => UserStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/userStatusLastWeek
- Поля:
  - `flags`: `#` - служебное поле flags
  - `by_me`: `flags.0?true` - optional через flags.0

### `userStatusOffline`

- ID: `9203775` / `0x008c703f`
- Сигнатура: `userStatusOffline(was_online:int) => UserStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/userStatusOffline
- Поля:
  - `was_online`: `int`

### `userStatusOnline`

- ID: `-306628279` / `0xedb93949`
- Сигнатура: `userStatusOnline(expires:int) => UserStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/userStatusOnline
- Поля:
  - `expires`: `int`

### `userStatusRecently`

- ID: `2065268168` / `0x7b197dc8`
- Сигнатура: `userStatusRecently(flags:#, by_me:flags.0?true) => UserStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/userStatusRecently
- Поля:
  - `flags`: `#` - служебное поле flags
  - `by_me`: `flags.0?true` - optional через flags.0

## `Username`

- Официальный тип: https://core.telegram.org/type/Username
- Количество constructors: **1**

### `username`

- ID: `-1274595769` / `0xb4073647`
- Сигнатура: `username(flags:#, editable:flags.0?true, active:flags.1?true, username:string) => Username`
- Официальная страница конструктора: https://core.telegram.org/constructor/username
- Поля:
  - `flags`: `#` - служебное поле flags
  - `editable`: `flags.0?true` - optional через flags.0
  - `active`: `flags.1?true` - optional через flags.1
  - `username`: `string`

## `Vector t`

- Официальный тип: https://core.telegram.org/type/Vector t
- Количество constructors: **1**

### `vector`

- ID: `481674261` / `0x1cb5c415`
- Сигнатура: `vector() => Vector t`
- Официальная страница конструктора: https://core.telegram.org/constructor/vector
- Поля:
  - Нет полей.

## `VideoSize`

- Официальный тип: https://core.telegram.org/type/VideoSize
- Количество constructors: **3**

### `videoSize`

- ID: `-567037804` / `0xde33b094`
- Сигнатура: `videoSize(flags:#, type:string, w:int, h:int, size:int, video_start_ts:flags.0?double) => VideoSize`
- Официальная страница конструктора: https://core.telegram.org/constructor/videoSize
- Поля:
  - `flags`: `#` - служебное поле flags
  - `type`: `string`
  - `w`: `int`
  - `h`: `int`
  - `size`: `int`
  - `video_start_ts`: `flags.0?double` - optional через flags.0

### `videoSizeEmojiMarkup`

- ID: `-128171716` / `0xf85c413c`
- Сигнатура: `videoSizeEmojiMarkup(emoji_id:long, background_colors:Vector) => VideoSize`
- Официальная страница конструктора: https://core.telegram.org/constructor/videoSizeEmojiMarkup
- Поля:
  - `emoji_id`: `long`
  - `background_colors`: `Vector`

### `videoSizeStickerMarkup`

- ID: `228623102` / `0x0da082fe`
- Сигнатура: `videoSizeStickerMarkup(stickerset:InputStickerSet, sticker_id:long, background_colors:Vector) => VideoSize`
- Официальная страница конструктора: https://core.telegram.org/constructor/videoSizeStickerMarkup
- Поля:
  - `stickerset`: `InputStickerSet`
  - `sticker_id`: `long`
  - `background_colors`: `Vector`

## `WallPaper`

- Официальный тип: https://core.telegram.org/type/WallPaper
- Количество constructors: **2**

### `wallPaper`

- ID: `-1539849235` / `0xa437c3ed`
- Сигнатура: `wallPaper(id:long, flags:#, creator:flags.0?true, default:flags.1?true, pattern:flags.3?true, dark:flags.4?true, access_hash:long, slug:string, document:Document, settings:flags.2?WallPaperSettings) => WallPaper`
- Официальная страница конструктора: https://core.telegram.org/constructor/wallPaper
- Поля:
  - `id`: `long`
  - `flags`: `#` - служебное поле flags
  - `creator`: `flags.0?true` - optional через flags.0
  - `default`: `flags.1?true` - optional через flags.1
  - `pattern`: `flags.3?true` - optional через flags.3
  - `dark`: `flags.4?true` - optional через flags.4
  - `access_hash`: `long`
  - `slug`: `string`
  - `document`: `Document`
  - `settings`: `flags.2?WallPaperSettings` - optional через flags.2

### `wallPaperNoFile`

- ID: `-528465642` / `0xe0804116`
- Сигнатура: `wallPaperNoFile(id:long, flags:#, default:flags.1?true, dark:flags.4?true, settings:flags.2?WallPaperSettings) => WallPaper`
- Официальная страница конструктора: https://core.telegram.org/constructor/wallPaperNoFile
- Поля:
  - `id`: `long`
  - `flags`: `#` - служебное поле flags
  - `default`: `flags.1?true` - optional через flags.1
  - `dark`: `flags.4?true` - optional через flags.4
  - `settings`: `flags.2?WallPaperSettings` - optional через flags.2

## `WallPaperSettings`

- Официальный тип: https://core.telegram.org/type/WallPaperSettings
- Количество constructors: **1**

### `wallPaperSettings`

- ID: `925826256` / `0x372efcd0`
- Сигнатура: `wallPaperSettings(flags:#, blur:flags.1?true, motion:flags.2?true, background_color:flags.0?int, second_background_color:flags.4?int, third_background_color:flags.5?int, fourth_background_color:flags.6?int, intensity:flags.3?int, rotation:flags.4?int, emoticon:flags.7?string) => WallPaperSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/wallPaperSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `blur`: `flags.1?true` - optional через flags.1
  - `motion`: `flags.2?true` - optional через flags.2
  - `background_color`: `flags.0?int` - optional через flags.0
  - `second_background_color`: `flags.4?int` - optional через flags.4
  - `third_background_color`: `flags.5?int` - optional через flags.5
  - `fourth_background_color`: `flags.6?int` - optional через flags.6
  - `intensity`: `flags.3?int` - optional через flags.3
  - `rotation`: `flags.4?int` - optional через flags.4
  - `emoticon`: `flags.7?string` - optional через flags.7

## `WebAuthorization`

- Официальный тип: https://core.telegram.org/type/WebAuthorization
- Количество constructors: **1**

### `webAuthorization`

- ID: `-1493633966` / `0xa6f8f452`
- Сигнатура: `webAuthorization(hash:long, bot_id:long, domain:string, browser:string, platform:string, date_created:int, date_active:int, ip:string, region:string) => WebAuthorization`
- Официальная страница конструктора: https://core.telegram.org/constructor/webAuthorization
- Поля:
  - `hash`: `long`
  - `bot_id`: `long`
  - `domain`: `string`
  - `browser`: `string`
  - `platform`: `string`
  - `date_created`: `int`
  - `date_active`: `int`
  - `ip`: `string`
  - `region`: `string`

## `WebDocument`

- Официальный тип: https://core.telegram.org/type/WebDocument
- Количество constructors: **2**

### `webDocument`

- ID: `475467473` / `0x1c570ed1`
- Сигнатура: `webDocument(url:string, access_hash:long, size:int, mime_type:string, attributes:Vector) => WebDocument`
- Официальная страница конструктора: https://core.telegram.org/constructor/webDocument
- Поля:
  - `url`: `string`
  - `access_hash`: `long`
  - `size`: `int`
  - `mime_type`: `string`
  - `attributes`: `Vector`

### `webDocumentNoProxy`

- ID: `-104284986` / `0xf9c8bcc6`
- Сигнатура: `webDocumentNoProxy(url:string, size:int, mime_type:string, attributes:Vector) => WebDocument`
- Официальная страница конструктора: https://core.telegram.org/constructor/webDocumentNoProxy
- Поля:
  - `url`: `string`
  - `size`: `int`
  - `mime_type`: `string`
  - `attributes`: `Vector`

## `WebPage`

- Официальный тип: https://core.telegram.org/type/WebPage
- Количество constructors: **4**

### `webPage`

- ID: `-392411726` / `0xe89c45b2`
- Сигнатура: `webPage(flags:#, has_large_media:flags.13?true, video_cover_photo:flags.14?true, id:long, url:string, display_url:string, hash:int, type:flags.0?string, site_name:flags.1?string, title:flags.2?string, description:flags.3?string, photo:flags.4?Photo, embed_url:flags.5?string, embed_type:flags.5?string, embed_width:flags.6?int, embed_height:flags.6?int, duration:flags.7?int, author:flags.8?string, document:flags.9?Document, cached_page:flags.10?Page, attributes:flags.12?Vector) => WebPage`
- Официальная страница конструктора: https://core.telegram.org/constructor/webPage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `has_large_media`: `flags.13?true` - optional через flags.13
  - `video_cover_photo`: `flags.14?true` - optional через flags.14
  - `id`: `long`
  - `url`: `string`
  - `display_url`: `string`
  - `hash`: `int`
  - `type`: `flags.0?string` - optional через flags.0
  - `site_name`: `flags.1?string` - optional через flags.1
  - `title`: `flags.2?string` - optional через flags.2
  - `description`: `flags.3?string` - optional через flags.3
  - `photo`: `flags.4?Photo` - optional через flags.4
  - `embed_url`: `flags.5?string` - optional через flags.5
  - `embed_type`: `flags.5?string` - optional через flags.5
  - `embed_width`: `flags.6?int` - optional через flags.6
  - `embed_height`: `flags.6?int` - optional через flags.6
  - `duration`: `flags.7?int` - optional через flags.7
  - `author`: `flags.8?string` - optional через flags.8
  - `document`: `flags.9?Document` - optional через flags.9
  - `cached_page`: `flags.10?Page` - optional через flags.10
  - `attributes`: `flags.12?Vector` - optional через flags.12

### `webPageEmpty`

- ID: `555358088` / `0x211a1788`
- Сигнатура: `webPageEmpty(flags:#, id:long, url:flags.0?string) => WebPage`
- Официальная страница конструктора: https://core.telegram.org/constructor/webPageEmpty
- Поля:
  - `flags`: `#` - служебное поле flags
  - `id`: `long`
  - `url`: `flags.0?string` - optional через flags.0

### `webPageNotModified`

- ID: `1930545681` / `0x7311ca11`
- Сигнатура: `webPageNotModified(flags:#, cached_page_views:flags.0?int) => WebPage`
- Официальная страница конструктора: https://core.telegram.org/constructor/webPageNotModified
- Поля:
  - `flags`: `#` - служебное поле flags
  - `cached_page_views`: `flags.0?int` - optional через flags.0

### `webPagePending`

- ID: `-1328464313` / `0xb0d13e47`
- Сигнатура: `webPagePending(flags:#, id:long, url:flags.0?string, date:int) => WebPage`
- Официальная страница конструктора: https://core.telegram.org/constructor/webPagePending
- Поля:
  - `flags`: `#` - служебное поле flags
  - `id`: `long`
  - `url`: `flags.0?string` - optional через flags.0
  - `date`: `int`

## `WebPageAttribute`

- Официальный тип: https://core.telegram.org/type/WebPageAttribute
- Количество constructors: **5**

### `webPageAttributeStarGiftCollection`

- ID: `835375875` / `0x31cad303`
- Сигнатура: `webPageAttributeStarGiftCollection(icons:Vector) => WebPageAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/webPageAttributeStarGiftCollection
- Поля:
  - `icons`: `Vector`

### `webPageAttributeStickerSet`

- ID: `1355547603` / `0x50cc03d3`
- Сигнатура: `webPageAttributeStickerSet(flags:#, emojis:flags.0?true, text_color:flags.1?true, stickers:Vector) => WebPageAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/webPageAttributeStickerSet
- Поля:
  - `flags`: `#` - служебное поле flags
  - `emojis`: `flags.0?true` - optional через flags.0
  - `text_color`: `flags.1?true` - optional через flags.1
  - `stickers`: `Vector`

### `webPageAttributeStory`

- ID: `781501415` / `0x2e94c3e7`
- Сигнатура: `webPageAttributeStory(flags:#, peer:Peer, id:int, story:flags.0?StoryItem) => WebPageAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/webPageAttributeStory
- Поля:
  - `flags`: `#` - служебное поле flags
  - `peer`: `Peer`
  - `id`: `int`
  - `story`: `flags.0?StoryItem` - optional через flags.0

### `webPageAttributeTheme`

- ID: `1421174295` / `0x54b56617`
- Сигнатура: `webPageAttributeTheme(flags:#, documents:flags.0?Vector, settings:flags.1?ThemeSettings) => WebPageAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/webPageAttributeTheme
- Поля:
  - `flags`: `#` - служебное поле flags
  - `documents`: `flags.0?Vector` - optional через flags.0
  - `settings`: `flags.1?ThemeSettings` - optional через flags.1

### `webPageAttributeUniqueStarGift`

- ID: `-814781000` / `0xcf6f6db8`
- Сигнатура: `webPageAttributeUniqueStarGift(gift:StarGift) => WebPageAttribute`
- Официальная страница конструктора: https://core.telegram.org/constructor/webPageAttributeUniqueStarGift
- Поля:
  - `gift`: `StarGift`

## `WebViewMessageSent`

- Официальный тип: https://core.telegram.org/type/WebViewMessageSent
- Количество constructors: **1**

### `webViewMessageSent`

- ID: `211046684` / `0x0c94511c`
- Сигнатура: `webViewMessageSent(flags:#, msg_id:flags.0?InputBotInlineMessageID) => WebViewMessageSent`
- Официальная страница конструктора: https://core.telegram.org/constructor/webViewMessageSent
- Поля:
  - `flags`: `#` - служебное поле flags
  - `msg_id`: `flags.0?InputBotInlineMessageID` - optional через flags.0

## `WebViewResult`

- Официальный тип: https://core.telegram.org/type/WebViewResult
- Количество constructors: **1**

### `webViewResultUrl`

- ID: `1294139288` / `0x4d22ff98`
- Сигнатура: `webViewResultUrl(flags:#, fullsize:flags.1?true, fullscreen:flags.2?true, query_id:flags.0?long, url:string) => WebViewResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/webViewResultUrl
- Поля:
  - `flags`: `#` - служебное поле flags
  - `fullsize`: `flags.1?true` - optional через flags.1
  - `fullscreen`: `flags.2?true` - optional через flags.2
  - `query_id`: `flags.0?long` - optional через flags.0
  - `url`: `string`

## `account.AuthorizationForm`

- Официальный тип: https://core.telegram.org/type/account.AuthorizationForm
- Количество constructors: **1**

### `account.authorizationForm`

- ID: `-1389486888` / `0xad2e1cd8`
- Сигнатура: `account.authorizationForm(flags:#, required_types:Vector, values:Vector, errors:Vector, users:Vector, privacy_policy_url:flags.0?string) => account.AuthorizationForm`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.authorizationForm
- Поля:
  - `flags`: `#` - служебное поле flags
  - `required_types`: `Vector`
  - `values`: `Vector`
  - `errors`: `Vector`
  - `users`: `Vector`
  - `privacy_policy_url`: `flags.0?string` - optional через flags.0

## `account.Authorizations`

- Официальный тип: https://core.telegram.org/type/account.Authorizations
- Количество constructors: **1**

### `account.authorizations`

- ID: `1275039392` / `0x4bff8ea0`
- Сигнатура: `account.authorizations(authorization_ttl_days:int, authorizations:Vector) => account.Authorizations`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.authorizations
- Поля:
  - `authorization_ttl_days`: `int`
  - `authorizations`: `Vector`

## `account.AutoDownloadSettings`

- Официальный тип: https://core.telegram.org/type/account.AutoDownloadSettings
- Количество constructors: **1**

### `account.autoDownloadSettings`

- ID: `1674235686` / `0x63cacf26`
- Сигнатура: `account.autoDownloadSettings(low:AutoDownloadSettings, medium:AutoDownloadSettings, high:AutoDownloadSettings) => account.AutoDownloadSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.autoDownloadSettings
- Поля:
  - `low`: `AutoDownloadSettings`
  - `medium`: `AutoDownloadSettings`
  - `high`: `AutoDownloadSettings`

## `account.AutoSaveSettings`

- Официальный тип: https://core.telegram.org/type/account.AutoSaveSettings
- Количество constructors: **1**

### `account.autoSaveSettings`

- ID: `1279133341` / `0x4c3e069d`
- Сигнатура: `account.autoSaveSettings(users_settings:AutoSaveSettings, chats_settings:AutoSaveSettings, broadcasts_settings:AutoSaveSettings, exceptions:Vector, chats:Vector, users:Vector) => account.AutoSaveSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.autoSaveSettings
- Поля:
  - `users_settings`: `AutoSaveSettings`
  - `chats_settings`: `AutoSaveSettings`
  - `broadcasts_settings`: `AutoSaveSettings`
  - `exceptions`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `account.BusinessChatLinks`

- Официальный тип: https://core.telegram.org/type/account.BusinessChatLinks
- Количество constructors: **1**

### `account.businessChatLinks`

- ID: `-331111727` / `0xec43a2d1`
- Сигнатура: `account.businessChatLinks(links:Vector, chats:Vector, users:Vector) => account.BusinessChatLinks`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.businessChatLinks
- Поля:
  - `links`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `account.ChatThemes`

- Официальный тип: https://core.telegram.org/type/account.ChatThemes
- Количество constructors: **2**

### `account.chatThemes`

- ID: `373835863` / `0x16484857`
- Сигнатура: `account.chatThemes(flags:#, hash:long, themes:Vector, chats:Vector, users:Vector, next_offset:flags.0?int) => account.ChatThemes`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.chatThemes
- Поля:
  - `flags`: `#` - служебное поле flags
  - `hash`: `long`
  - `themes`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`
  - `next_offset`: `flags.0?int` - optional через flags.0

### `account.chatThemesNotModified`

- ID: `-535699004` / `0xe011e1c4`
- Сигнатура: `account.chatThemesNotModified() => account.ChatThemes`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.chatThemesNotModified
- Поля:
  - Нет полей.

## `account.ConnectedBots`

- Официальный тип: https://core.telegram.org/type/account.ConnectedBots
- Количество constructors: **1**

### `account.connectedBots`

- ID: `400029819` / `0x17d7f87b`
- Сигнатура: `account.connectedBots(connected_bots:Vector, users:Vector) => account.ConnectedBots`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.connectedBots
- Поля:
  - `connected_bots`: `Vector`
  - `users`: `Vector`

## `account.ContentSettings`

- Официальный тип: https://core.telegram.org/type/account.ContentSettings
- Количество constructors: **1**

### `account.contentSettings`

- ID: `1474462241` / `0x57e28221`
- Сигнатура: `account.contentSettings(flags:#, sensitive_enabled:flags.0?true, sensitive_can_change:flags.1?true) => account.ContentSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.contentSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `sensitive_enabled`: `flags.0?true` - optional через flags.0
  - `sensitive_can_change`: `flags.1?true` - optional через flags.1

## `account.EmailVerified`

- Официальный тип: https://core.telegram.org/type/account.EmailVerified
- Количество constructors: **2**

### `account.emailVerified`

- ID: `731303195` / `0x2b96cd1b`
- Сигнатура: `account.emailVerified(email:string) => account.EmailVerified`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.emailVerified
- Поля:
  - `email`: `string`

### `account.emailVerifiedLogin`

- ID: `-507835039` / `0xe1bb0d61`
- Сигнатура: `account.emailVerifiedLogin(email:string, sent_code:auth.SentCode) => account.EmailVerified`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.emailVerifiedLogin
- Поля:
  - `email`: `string`
  - `sent_code`: `auth.SentCode`

## `account.EmojiStatuses`

- Официальный тип: https://core.telegram.org/type/account.EmojiStatuses
- Количество constructors: **2**

### `account.emojiStatuses`

- ID: `-1866176559` / `0x90c467d1`
- Сигнатура: `account.emojiStatuses(hash:long, statuses:Vector) => account.EmojiStatuses`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.emojiStatuses
- Поля:
  - `hash`: `long`
  - `statuses`: `Vector`

### `account.emojiStatusesNotModified`

- ID: `-796072379` / `0xd08ce645`
- Сигнатура: `account.emojiStatusesNotModified() => account.EmojiStatuses`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.emojiStatusesNotModified
- Поля:
  - Нет полей.

## `account.PaidMessagesRevenue`

- Официальный тип: https://core.telegram.org/type/account.PaidMessagesRevenue
- Количество constructors: **1**

### `account.paidMessagesRevenue`

- ID: `504403720` / `0x1e109708`
- Сигнатура: `account.paidMessagesRevenue(stars_amount:long) => account.PaidMessagesRevenue`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.paidMessagesRevenue
- Поля:
  - `stars_amount`: `long`

## `account.Password`

- Официальный тип: https://core.telegram.org/type/account.Password
- Количество constructors: **1**

### `account.password`

- ID: `-1787080453` / `0x957b50fb`
- Сигнатура: `account.password(flags:#, has_recovery:flags.0?true, has_secure_values:flags.1?true, has_password:flags.2?true, current_algo:flags.2?PasswordKdfAlgo, srp_B:flags.2?bytes, srp_id:flags.2?long, hint:flags.3?string, email_unconfirmed_pattern:flags.4?string, new_algo:PasswordKdfAlgo, new_secure_algo:SecurePasswordKdfAlgo, secure_random:bytes, pending_reset_date:flags.5?int, login_email_pattern:flags.6?string) => account.Password`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.password
- Поля:
  - `flags`: `#` - служебное поле flags
  - `has_recovery`: `flags.0?true` - optional через flags.0
  - `has_secure_values`: `flags.1?true` - optional через flags.1
  - `has_password`: `flags.2?true` - optional через flags.2
  - `current_algo`: `flags.2?PasswordKdfAlgo` - optional через flags.2
  - `srp_B`: `flags.2?bytes` - optional через flags.2
  - `srp_id`: `flags.2?long` - optional через flags.2
  - `hint`: `flags.3?string` - optional через flags.3
  - `email_unconfirmed_pattern`: `flags.4?string` - optional через flags.4
  - `new_algo`: `PasswordKdfAlgo`
  - `new_secure_algo`: `SecurePasswordKdfAlgo`
  - `secure_random`: `bytes`
  - `pending_reset_date`: `flags.5?int` - optional через flags.5
  - `login_email_pattern`: `flags.6?string` - optional через flags.6

## `account.PasswordInputSettings`

- Официальный тип: https://core.telegram.org/type/account.PasswordInputSettings
- Количество constructors: **1**

### `account.passwordInputSettings`

- ID: `-1036572727` / `0xc23727c9`
- Сигнатура: `account.passwordInputSettings(flags:#, new_algo:flags.0?PasswordKdfAlgo, new_password_hash:flags.0?bytes, hint:flags.0?string, email:flags.1?string, new_secure_settings:flags.2?SecureSecretSettings) => account.PasswordInputSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.passwordInputSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `new_algo`: `flags.0?PasswordKdfAlgo` - optional через flags.0
  - `new_password_hash`: `flags.0?bytes` - optional через flags.0
  - `hint`: `flags.0?string` - optional через flags.0
  - `email`: `flags.1?string` - optional через flags.1
  - `new_secure_settings`: `flags.2?SecureSecretSettings` - optional через flags.2

## `account.PasswordSettings`

- Официальный тип: https://core.telegram.org/type/account.PasswordSettings
- Количество constructors: **1**

### `account.passwordSettings`

- ID: `-1705233435` / `0x9a5c33e5`
- Сигнатура: `account.passwordSettings(flags:#, email:flags.0?string, secure_settings:flags.1?SecureSecretSettings) => account.PasswordSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.passwordSettings
- Поля:
  - `flags`: `#` - служебное поле flags
  - `email`: `flags.0?string` - optional через flags.0
  - `secure_settings`: `flags.1?SecureSecretSettings` - optional через flags.1

## `account.PrivacyRules`

- Официальный тип: https://core.telegram.org/type/account.PrivacyRules
- Количество constructors: **1**

### `account.privacyRules`

- ID: `1352683077` / `0x50a04e45`
- Сигнатура: `account.privacyRules(rules:Vector, chats:Vector, users:Vector) => account.PrivacyRules`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.privacyRules
- Поля:
  - `rules`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `account.ResetPasswordResult`

- Официальный тип: https://core.telegram.org/type/account.ResetPasswordResult
- Количество constructors: **3**

### `account.resetPasswordFailedWait`

- ID: `-478701471` / `0xe3779861`
- Сигнатура: `account.resetPasswordFailedWait(retry_date:int) => account.ResetPasswordResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.resetPasswordFailedWait
- Поля:
  - `retry_date`: `int`

### `account.resetPasswordOk`

- ID: `-383330754` / `0xe926d63e`
- Сигнатура: `account.resetPasswordOk() => account.ResetPasswordResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.resetPasswordOk
- Поля:
  - Нет полей.

### `account.resetPasswordRequestedWait`

- ID: `-370148227` / `0xe9effc7d`
- Сигнатура: `account.resetPasswordRequestedWait(until_date:int) => account.ResetPasswordResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.resetPasswordRequestedWait
- Поля:
  - `until_date`: `int`

## `account.ResolvedBusinessChatLinks`

- Официальный тип: https://core.telegram.org/type/account.ResolvedBusinessChatLinks
- Количество constructors: **1**

### `account.resolvedBusinessChatLinks`

- ID: `-1708937439` / `0x9a23af21`
- Сигнатура: `account.resolvedBusinessChatLinks(flags:#, peer:Peer, message:string, entities:flags.0?Vector, chats:Vector, users:Vector) => account.ResolvedBusinessChatLinks`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.resolvedBusinessChatLinks
- Поля:
  - `flags`: `#` - служебное поле flags
  - `peer`: `Peer`
  - `message`: `string`
  - `entities`: `flags.0?Vector` - optional через flags.0
  - `chats`: `Vector`
  - `users`: `Vector`

## `account.SavedMusicIds`

- Официальный тип: https://core.telegram.org/type/account.SavedMusicIds
- Количество constructors: **2**

### `account.savedMusicIds`

- ID: `-1718786506` / `0x998d6636`
- Сигнатура: `account.savedMusicIds(ids:Vector) => account.SavedMusicIds`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.savedMusicIds
- Поля:
  - `ids`: `Vector`

### `account.savedMusicIdsNotModified`

- ID: `1338514798` / `0x4fc81d6e`
- Сигнатура: `account.savedMusicIdsNotModified() => account.SavedMusicIds`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.savedMusicIdsNotModified
- Поля:
  - Нет полей.

## `account.SavedRingtone`

- Официальный тип: https://core.telegram.org/type/account.SavedRingtone
- Количество constructors: **2**

### `account.savedRingtone`

- ID: `-1222230163` / `0xb7263f6d`
- Сигнатура: `account.savedRingtone() => account.SavedRingtone`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.savedRingtone
- Поля:
  - Нет полей.

### `account.savedRingtoneConverted`

- ID: `523271863` / `0x1f307eb7`
- Сигнатура: `account.savedRingtoneConverted(document:Document) => account.SavedRingtone`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.savedRingtoneConverted
- Поля:
  - `document`: `Document`

## `account.SavedRingtones`

- Официальный тип: https://core.telegram.org/type/account.SavedRingtones
- Количество constructors: **2**

### `account.savedRingtones`

- ID: `-1041683259` / `0xc1e92cc5`
- Сигнатура: `account.savedRingtones(hash:long, ringtones:Vector) => account.SavedRingtones`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.savedRingtones
- Поля:
  - `hash`: `long`
  - `ringtones`: `Vector`

### `account.savedRingtonesNotModified`

- ID: `-67704655` / `0xfbf6e8b1`
- Сигнатура: `account.savedRingtonesNotModified() => account.SavedRingtones`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.savedRingtonesNotModified
- Поля:
  - Нет полей.

## `account.SentEmailCode`

- Официальный тип: https://core.telegram.org/type/account.SentEmailCode
- Количество constructors: **1**

### `account.sentEmailCode`

- ID: `-2128640689` / `0x811f854f`
- Сигнатура: `account.sentEmailCode(email_pattern:string, length:int) => account.SentEmailCode`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.sentEmailCode
- Поля:
  - `email_pattern`: `string`
  - `length`: `int`

## `account.Takeout`

- Официальный тип: https://core.telegram.org/type/account.Takeout
- Количество constructors: **1**

### `account.takeout`

- ID: `1304052993` / `0x4dba4501`
- Сигнатура: `account.takeout(id:long) => account.Takeout`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.takeout
- Поля:
  - `id`: `long`

## `account.Themes`

- Официальный тип: https://core.telegram.org/type/account.Themes
- Количество constructors: **2**

### `account.themes`

- ID: `-1707242387` / `0x9a3d8c6d`
- Сигнатура: `account.themes(hash:long, themes:Vector) => account.Themes`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.themes
- Поля:
  - `hash`: `long`
  - `themes`: `Vector`

### `account.themesNotModified`

- ID: `-199313886` / `0xf41eb622`
- Сигнатура: `account.themesNotModified() => account.Themes`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.themesNotModified
- Поля:
  - Нет полей.

## `account.TmpPassword`

- Официальный тип: https://core.telegram.org/type/account.TmpPassword
- Количество constructors: **1**

### `account.tmpPassword`

- ID: `-614138572` / `0xdb64fd34`
- Сигнатура: `account.tmpPassword(tmp_password:bytes, valid_until:int) => account.TmpPassword`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.tmpPassword
- Поля:
  - `tmp_password`: `bytes`
  - `valid_until`: `int`

## `account.WallPapers`

- Официальный тип: https://core.telegram.org/type/account.WallPapers
- Количество constructors: **2**

### `account.wallPapers`

- ID: `-842824308` / `0xcdc3858c`
- Сигнатура: `account.wallPapers(hash:long, wallpapers:Vector) => account.WallPapers`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.wallPapers
- Поля:
  - `hash`: `long`
  - `wallpapers`: `Vector`

### `account.wallPapersNotModified`

- ID: `471437699` / `0x1c199183`
- Сигнатура: `account.wallPapersNotModified() => account.WallPapers`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.wallPapersNotModified
- Поля:
  - Нет полей.

## `account.WebAuthorizations`

- Официальный тип: https://core.telegram.org/type/account.WebAuthorizations
- Количество constructors: **1**

### `account.webAuthorizations`

- ID: `-313079300` / `0xed56c9fc`
- Сигнатура: `account.webAuthorizations(authorizations:Vector, users:Vector) => account.WebAuthorizations`
- Официальная страница конструктора: https://core.telegram.org/constructor/account.webAuthorizations
- Поля:
  - `authorizations`: `Vector`
  - `users`: `Vector`

## `auth.Authorization`

- Официальный тип: https://core.telegram.org/type/auth.Authorization
- Количество constructors: **2**

### `auth.authorization`

- ID: `782418132` / `0x2ea2c0d4`
- Сигнатура: `auth.authorization(flags:#, setup_password_required:flags.1?true, otherwise_relogin_days:flags.1?int, tmp_sessions:flags.0?int, future_auth_token:flags.2?bytes, user:User) => auth.Authorization`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.authorization
- Поля:
  - `flags`: `#` - служебное поле flags
  - `setup_password_required`: `flags.1?true` - optional через flags.1
  - `otherwise_relogin_days`: `flags.1?int` - optional через flags.1
  - `tmp_sessions`: `flags.0?int` - optional через flags.0
  - `future_auth_token`: `flags.2?bytes` - optional через flags.2
  - `user`: `User`

### `auth.authorizationSignUpRequired`

- ID: `1148485274` / `0x44747e9a`
- Сигнатура: `auth.authorizationSignUpRequired(flags:#, terms_of_service:flags.0?help.TermsOfService) => auth.Authorization`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.authorizationSignUpRequired
- Поля:
  - `flags`: `#` - служебное поле flags
  - `terms_of_service`: `flags.0?help.TermsOfService` - optional через flags.0

## `auth.CodeType`

- Официальный тип: https://core.telegram.org/type/auth.CodeType
- Количество constructors: **5**

### `auth.codeTypeCall`

- ID: `1948046307` / `0x741cd3e3`
- Сигнатура: `auth.codeTypeCall() => auth.CodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.codeTypeCall
- Поля:
  - Нет полей.

### `auth.codeTypeFlashCall`

- ID: `577556219` / `0x226ccefb`
- Сигнатура: `auth.codeTypeFlashCall() => auth.CodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.codeTypeFlashCall
- Поля:
  - Нет полей.

### `auth.codeTypeFragmentSms`

- ID: `116234636` / `0x06ed998c`
- Сигнатура: `auth.codeTypeFragmentSms() => auth.CodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.codeTypeFragmentSms
- Поля:
  - Нет полей.

### `auth.codeTypeMissedCall`

- ID: `-702884114` / `0xd61ad6ee`
- Сигнатура: `auth.codeTypeMissedCall() => auth.CodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.codeTypeMissedCall
- Поля:
  - Нет полей.

### `auth.codeTypeSms`

- ID: `1923290508` / `0x72a3158c`
- Сигнатура: `auth.codeTypeSms() => auth.CodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.codeTypeSms
- Поля:
  - Нет полей.

## `auth.ExportedAuthorization`

- Официальный тип: https://core.telegram.org/type/auth.ExportedAuthorization
- Количество constructors: **1**

### `auth.exportedAuthorization`

- ID: `-1271602504` / `0xb434e2b8`
- Сигнатура: `auth.exportedAuthorization(id:long, bytes:bytes) => auth.ExportedAuthorization`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.exportedAuthorization
- Поля:
  - `id`: `long`
  - `bytes`: `bytes`

## `auth.LoggedOut`

- Официальный тип: https://core.telegram.org/type/auth.LoggedOut
- Количество constructors: **1**

### `auth.loggedOut`

- ID: `-1012759713` / `0xc3a2835f`
- Сигнатура: `auth.loggedOut(flags:#, future_auth_token:flags.0?bytes) => auth.LoggedOut`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.loggedOut
- Поля:
  - `flags`: `#` - служебное поле flags
  - `future_auth_token`: `flags.0?bytes` - optional через flags.0

## `auth.LoginToken`

- Официальный тип: https://core.telegram.org/type/auth.LoginToken
- Количество constructors: **3**

### `auth.loginToken`

- ID: `1654593920` / `0x629f1980`
- Сигнатура: `auth.loginToken(expires:int, token:bytes) => auth.LoginToken`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.loginToken
- Поля:
  - `expires`: `int`
  - `token`: `bytes`

### `auth.loginTokenMigrateTo`

- ID: `110008598` / `0x068e9916`
- Сигнатура: `auth.loginTokenMigrateTo(dc_id:int, token:bytes) => auth.LoginToken`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.loginTokenMigrateTo
- Поля:
  - `dc_id`: `int`
  - `token`: `bytes`

### `auth.loginTokenSuccess`

- ID: `957176926` / `0x390d5c5e`
- Сигнатура: `auth.loginTokenSuccess(authorization:auth.Authorization) => auth.LoginToken`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.loginTokenSuccess
- Поля:
  - `authorization`: `auth.Authorization`

## `auth.PasswordRecovery`

- Официальный тип: https://core.telegram.org/type/auth.PasswordRecovery
- Количество constructors: **1**

### `auth.passwordRecovery`

- ID: `326715557` / `0x137948a5`
- Сигнатура: `auth.passwordRecovery(email_pattern:string) => auth.PasswordRecovery`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.passwordRecovery
- Поля:
  - `email_pattern`: `string`

## `auth.SentCode`

- Официальный тип: https://core.telegram.org/type/auth.SentCode
- Количество constructors: **3**

### `auth.sentCode`

- ID: `1577067778` / `0x5e002502`
- Сигнатура: `auth.sentCode(flags:#, type:auth.SentCodeType, phone_code_hash:string, next_type:flags.1?auth.CodeType, timeout:flags.2?int) => auth.SentCode`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCode
- Поля:
  - `flags`: `#` - служебное поле flags
  - `type`: `auth.SentCodeType`
  - `phone_code_hash`: `string`
  - `next_type`: `flags.1?auth.CodeType` - optional через flags.1
  - `timeout`: `flags.2?int` - optional через flags.2

### `auth.sentCodePaymentRequired`

- ID: `-677184263` / `0xd7a2fcf9`
- Сигнатура: `auth.sentCodePaymentRequired(store_product:string, phone_code_hash:string, support_email_address:string, support_email_subject:string) => auth.SentCode`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodePaymentRequired
- Поля:
  - `store_product`: `string`
  - `phone_code_hash`: `string`
  - `support_email_address`: `string`
  - `support_email_subject`: `string`

### `auth.sentCodeSuccess`

- ID: `596704836` / `0x2390fe44`
- Сигнатура: `auth.sentCodeSuccess(authorization:auth.Authorization) => auth.SentCode`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodeSuccess
- Поля:
  - `authorization`: `auth.Authorization`

## `auth.SentCodeType`

- Официальный тип: https://core.telegram.org/type/auth.SentCodeType
- Количество constructors: **11**

### `auth.sentCodeTypeApp`

- ID: `1035688326` / `0x3dbb5986`
- Сигнатура: `auth.sentCodeTypeApp(length:int) => auth.SentCodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodeTypeApp
- Поля:
  - `length`: `int`

### `auth.sentCodeTypeCall`

- ID: `1398007207` / `0x5353e5a7`
- Сигнатура: `auth.sentCodeTypeCall(length:int) => auth.SentCodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodeTypeCall
- Поля:
  - `length`: `int`

### `auth.sentCodeTypeEmailCode`

- ID: `-196020837` / `0xf450f59b`
- Сигнатура: `auth.sentCodeTypeEmailCode(flags:#, apple_signin_allowed:flags.0?true, google_signin_allowed:flags.1?true, email_pattern:string, length:int, reset_available_period:flags.3?int, reset_pending_date:flags.4?int) => auth.SentCodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodeTypeEmailCode
- Поля:
  - `flags`: `#` - служебное поле flags
  - `apple_signin_allowed`: `flags.0?true` - optional через flags.0
  - `google_signin_allowed`: `flags.1?true` - optional через flags.1
  - `email_pattern`: `string`
  - `length`: `int`
  - `reset_available_period`: `flags.3?int` - optional через flags.3
  - `reset_pending_date`: `flags.4?int` - optional через flags.4

### `auth.sentCodeTypeFirebaseSms`

- ID: `10475318` / `0x009fd736`
- Сигнатура: `auth.sentCodeTypeFirebaseSms(flags:#, nonce:flags.0?bytes, play_integrity_project_id:flags.2?long, play_integrity_nonce:flags.2?bytes, receipt:flags.1?string, push_timeout:flags.1?int, length:int) => auth.SentCodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodeTypeFirebaseSms
- Поля:
  - `flags`: `#` - служебное поле flags
  - `nonce`: `flags.0?bytes` - optional через flags.0
  - `play_integrity_project_id`: `flags.2?long` - optional через flags.2
  - `play_integrity_nonce`: `flags.2?bytes` - optional через flags.2
  - `receipt`: `flags.1?string` - optional через flags.1
  - `push_timeout`: `flags.1?int` - optional через flags.1
  - `length`: `int`

### `auth.sentCodeTypeFlashCall`

- ID: `-1425815847` / `0xab03c6d9`
- Сигнатура: `auth.sentCodeTypeFlashCall(pattern:string) => auth.SentCodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodeTypeFlashCall
- Поля:
  - `pattern`: `string`

### `auth.sentCodeTypeFragmentSms`

- ID: `-648651719` / `0xd9565c39`
- Сигнатура: `auth.sentCodeTypeFragmentSms(url:string, length:int) => auth.SentCodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodeTypeFragmentSms
- Поля:
  - `url`: `string`
  - `length`: `int`

### `auth.sentCodeTypeMissedCall`

- ID: `-2113903484` / `0x82006484`
- Сигнатура: `auth.sentCodeTypeMissedCall(prefix:string, length:int) => auth.SentCodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodeTypeMissedCall
- Поля:
  - `prefix`: `string`
  - `length`: `int`

### `auth.sentCodeTypeSetUpEmailRequired`

- ID: `-1521934870` / `0xa5491dea`
- Сигнатура: `auth.sentCodeTypeSetUpEmailRequired(flags:#, apple_signin_allowed:flags.0?true, google_signin_allowed:flags.1?true) => auth.SentCodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodeTypeSetUpEmailRequired
- Поля:
  - `flags`: `#` - служебное поле flags
  - `apple_signin_allowed`: `flags.0?true` - optional через flags.0
  - `google_signin_allowed`: `flags.1?true` - optional через flags.1

### `auth.sentCodeTypeSms`

- ID: `-1073693790` / `0xc000bba2`
- Сигнатура: `auth.sentCodeTypeSms(length:int) => auth.SentCodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodeTypeSms
- Поля:
  - `length`: `int`

### `auth.sentCodeTypeSmsPhrase`

- ID: `-1284008785` / `0xb37794af`
- Сигнатура: `auth.sentCodeTypeSmsPhrase(flags:#, beginning:flags.0?string) => auth.SentCodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodeTypeSmsPhrase
- Поля:
  - `flags`: `#` - служебное поле flags
  - `beginning`: `flags.0?string` - optional через flags.0

### `auth.sentCodeTypeSmsWord`

- ID: `-1542017919` / `0xa416ac81`
- Сигнатура: `auth.sentCodeTypeSmsWord(flags:#, beginning:flags.0?string) => auth.SentCodeType`
- Официальная страница конструктора: https://core.telegram.org/constructor/auth.sentCodeTypeSmsWord
- Поля:
  - `flags`: `#` - служебное поле flags
  - `beginning`: `flags.0?string` - optional через flags.0

## `bots.BotInfo`

- Официальный тип: https://core.telegram.org/type/bots.BotInfo
- Количество constructors: **1**

### `bots.botInfo`

- ID: `-391678544` / `0xe8a775b0`
- Сигнатура: `bots.botInfo(name:string, about:string, description:string) => bots.BotInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/bots.botInfo
- Поля:
  - `name`: `string`
  - `about`: `string`
  - `description`: `string`

## `bots.PopularAppBots`

- Официальный тип: https://core.telegram.org/type/bots.PopularAppBots
- Количество constructors: **1**

### `bots.popularAppBots`

- ID: `428978491` / `0x1991b13b`
- Сигнатура: `bots.popularAppBots(flags:#, next_offset:flags.0?string, users:Vector) => bots.PopularAppBots`
- Официальная страница конструктора: https://core.telegram.org/constructor/bots.popularAppBots
- Поля:
  - `flags`: `#` - служебное поле flags
  - `next_offset`: `flags.0?string` - optional через flags.0
  - `users`: `Vector`

## `bots.PreviewInfo`

- Официальный тип: https://core.telegram.org/type/bots.PreviewInfo
- Количество constructors: **1**

### `bots.previewInfo`

- ID: `212278628` / `0x0ca71d64`
- Сигнатура: `bots.previewInfo(media:Vector, lang_codes:Vector) => bots.PreviewInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/bots.previewInfo
- Поля:
  - `media`: `Vector`
  - `lang_codes`: `Vector`

## `channels.AdminLogResults`

- Официальный тип: https://core.telegram.org/type/channels.AdminLogResults
- Количество constructors: **1**

### `channels.adminLogResults`

- ID: `-309659827` / `0xed8af74d`
- Сигнатура: `channels.adminLogResults(events:Vector, chats:Vector, users:Vector) => channels.AdminLogResults`
- Официальная страница конструктора: https://core.telegram.org/constructor/channels.adminLogResults
- Поля:
  - `events`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `channels.ChannelParticipant`

- Официальный тип: https://core.telegram.org/type/channels.ChannelParticipant
- Количество constructors: **1**

### `channels.channelParticipant`

- ID: `-541588713` / `0xdfb80317`
- Сигнатура: `channels.channelParticipant(participant:ChannelParticipant, chats:Vector, users:Vector) => channels.ChannelParticipant`
- Официальная страница конструктора: https://core.telegram.org/constructor/channels.channelParticipant
- Поля:
  - `participant`: `ChannelParticipant`
  - `chats`: `Vector`
  - `users`: `Vector`

## `channels.ChannelParticipants`

- Официальный тип: https://core.telegram.org/type/channels.ChannelParticipants
- Количество constructors: **2**

### `channels.channelParticipants`

- ID: `-1699676497` / `0x9ab0feaf`
- Сигнатура: `channels.channelParticipants(count:int, participants:Vector, chats:Vector, users:Vector) => channels.ChannelParticipants`
- Официальная страница конструктора: https://core.telegram.org/constructor/channels.channelParticipants
- Поля:
  - `count`: `int`
  - `participants`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `channels.channelParticipantsNotModified`

- ID: `-266911767` / `0xf0173fe9`
- Сигнатура: `channels.channelParticipantsNotModified() => channels.ChannelParticipants`
- Официальная страница конструктора: https://core.telegram.org/constructor/channels.channelParticipantsNotModified
- Поля:
  - Нет полей.

## `channels.SendAsPeers`

- Официальный тип: https://core.telegram.org/type/channels.SendAsPeers
- Количество constructors: **1**

### `channels.sendAsPeers`

- ID: `-191450938` / `0xf496b0c6`
- Сигнатура: `channels.sendAsPeers(peers:Vector, chats:Vector, users:Vector) => channels.SendAsPeers`
- Официальная страница конструктора: https://core.telegram.org/constructor/channels.sendAsPeers
- Поля:
  - `peers`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `channels.SponsoredMessageReportResult`

- Официальный тип: https://core.telegram.org/type/channels.SponsoredMessageReportResult
- Количество constructors: **3**

### `channels.sponsoredMessageReportResultAdsHidden`

- ID: `1044107055` / `0x3e3bcf2f`
- Сигнатура: `channels.sponsoredMessageReportResultAdsHidden() => channels.SponsoredMessageReportResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/channels.sponsoredMessageReportResultAdsHidden
- Поля:
  - Нет полей.

### `channels.sponsoredMessageReportResultChooseOption`

- ID: `-2073059774` / `0x846f9e42`
- Сигнатура: `channels.sponsoredMessageReportResultChooseOption(title:string, options:Vector) => channels.SponsoredMessageReportResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/channels.sponsoredMessageReportResultChooseOption
- Поля:
  - `title`: `string`
  - `options`: `Vector`

### `channels.sponsoredMessageReportResultReported`

- ID: `-1384544183` / `0xad798849`
- Сигнатура: `channels.sponsoredMessageReportResultReported() => channels.SponsoredMessageReportResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/channels.sponsoredMessageReportResultReported
- Поля:
  - Нет полей.

## `chatlists.ChatlistInvite`

- Официальный тип: https://core.telegram.org/type/chatlists.ChatlistInvite
- Количество constructors: **2**

### `chatlists.chatlistInvite`

- ID: `-250687953` / `0xf10ece2f`
- Сигнатура: `chatlists.chatlistInvite(flags:#, title_noanimate:flags.1?true, title:TextWithEntities, emoticon:flags.0?string, peers:Vector, chats:Vector, users:Vector) => chatlists.ChatlistInvite`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatlists.chatlistInvite
- Поля:
  - `flags`: `#` - служебное поле flags
  - `title_noanimate`: `flags.1?true` - optional через flags.1
  - `title`: `TextWithEntities`
  - `emoticon`: `flags.0?string` - optional через flags.0
  - `peers`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `chatlists.chatlistInviteAlready`

- ID: `-91752871` / `0xfa87f659`
- Сигнатура: `chatlists.chatlistInviteAlready(filter_id:int, missing_peers:Vector, already_peers:Vector, chats:Vector, users:Vector) => chatlists.ChatlistInvite`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatlists.chatlistInviteAlready
- Поля:
  - `filter_id`: `int`
  - `missing_peers`: `Vector`
  - `already_peers`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `chatlists.ChatlistUpdates`

- Официальный тип: https://core.telegram.org/type/chatlists.ChatlistUpdates
- Количество constructors: **1**

### `chatlists.chatlistUpdates`

- ID: `-1816295539` / `0x93bd878d`
- Сигнатура: `chatlists.chatlistUpdates(missing_peers:Vector, chats:Vector, users:Vector) => chatlists.ChatlistUpdates`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatlists.chatlistUpdates
- Поля:
  - `missing_peers`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `chatlists.ExportedChatlistInvite`

- Официальный тип: https://core.telegram.org/type/chatlists.ExportedChatlistInvite
- Количество constructors: **1**

### `chatlists.exportedChatlistInvite`

- ID: `283567014` / `0x10e6e3a6`
- Сигнатура: `chatlists.exportedChatlistInvite(filter:DialogFilter, invite:ExportedChatlistInvite) => chatlists.ExportedChatlistInvite`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatlists.exportedChatlistInvite
- Поля:
  - `filter`: `DialogFilter`
  - `invite`: `ExportedChatlistInvite`

## `chatlists.ExportedInvites`

- Официальный тип: https://core.telegram.org/type/chatlists.ExportedInvites
- Количество constructors: **1**

### `chatlists.exportedInvites`

- ID: `279670215` / `0x10ab6dc7`
- Сигнатура: `chatlists.exportedInvites(invites:Vector, chats:Vector, users:Vector) => chatlists.ExportedInvites`
- Официальная страница конструктора: https://core.telegram.org/constructor/chatlists.exportedInvites
- Поля:
  - `invites`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `contacts.Blocked`

- Официальный тип: https://core.telegram.org/type/contacts.Blocked
- Количество constructors: **2**

### `contacts.blocked`

- ID: `182326673` / `0x0ade1591`
- Сигнатура: `contacts.blocked(blocked:Vector, chats:Vector, users:Vector) => contacts.Blocked`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.blocked
- Поля:
  - `blocked`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `contacts.blockedSlice`

- ID: `-513392236` / `0xe1664194`
- Сигнатура: `contacts.blockedSlice(count:int, blocked:Vector, chats:Vector, users:Vector) => contacts.Blocked`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.blockedSlice
- Поля:
  - `count`: `int`
  - `blocked`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `contacts.ContactBirthdays`

- Официальный тип: https://core.telegram.org/type/contacts.ContactBirthdays
- Количество constructors: **1**

### `contacts.contactBirthdays`

- ID: `290452237` / `0x114ff30d`
- Сигнатура: `contacts.contactBirthdays(contacts:Vector, users:Vector) => contacts.ContactBirthdays`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.contactBirthdays
- Поля:
  - `contacts`: `Vector`
  - `users`: `Vector`

## `contacts.Contacts`

- Официальный тип: https://core.telegram.org/type/contacts.Contacts
- Количество constructors: **2**

### `contacts.contacts`

- ID: `-353862078` / `0xeae87e42`
- Сигнатура: `contacts.contacts(contacts:Vector, saved_count:int, users:Vector) => contacts.Contacts`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.contacts
- Поля:
  - `contacts`: `Vector`
  - `saved_count`: `int`
  - `users`: `Vector`

### `contacts.contactsNotModified`

- ID: `-1219778094` / `0xb74ba9d2`
- Сигнатура: `contacts.contactsNotModified() => contacts.Contacts`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.contactsNotModified
- Поля:
  - Нет полей.

## `contacts.Found`

- Официальный тип: https://core.telegram.org/type/contacts.Found
- Количество constructors: **1**

### `contacts.found`

- ID: `-1290580579` / `0xb3134d9d`
- Сигнатура: `contacts.found(my_results:Vector, results:Vector, chats:Vector, users:Vector) => contacts.Found`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.found
- Поля:
  - `my_results`: `Vector`
  - `results`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `contacts.ImportedContacts`

- Официальный тип: https://core.telegram.org/type/contacts.ImportedContacts
- Количество constructors: **1**

### `contacts.importedContacts`

- ID: `2010127419` / `0x77d01c3b`
- Сигнатура: `contacts.importedContacts(imported:Vector, popular_invites:Vector, retry_contacts:Vector, users:Vector) => contacts.ImportedContacts`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.importedContacts
- Поля:
  - `imported`: `Vector`
  - `popular_invites`: `Vector`
  - `retry_contacts`: `Vector`
  - `users`: `Vector`

## `contacts.ResolvedPeer`

- Официальный тип: https://core.telegram.org/type/contacts.ResolvedPeer
- Количество constructors: **1**

### `contacts.resolvedPeer`

- ID: `2131196633` / `0x7f077ad9`
- Сигнатура: `contacts.resolvedPeer(peer:Peer, chats:Vector, users:Vector) => contacts.ResolvedPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.resolvedPeer
- Поля:
  - `peer`: `Peer`
  - `chats`: `Vector`
  - `users`: `Vector`

## `contacts.SponsoredPeers`

- Официальный тип: https://core.telegram.org/type/contacts.SponsoredPeers
- Количество constructors: **2**

### `contacts.sponsoredPeers`

- ID: `-352114556` / `0xeb032884`
- Сигнатура: `contacts.sponsoredPeers(peers:Vector, chats:Vector, users:Vector) => contacts.SponsoredPeers`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.sponsoredPeers
- Поля:
  - `peers`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `contacts.sponsoredPeersEmpty`

- ID: `-365775695` / `0xea32b4b1`
- Сигнатура: `contacts.sponsoredPeersEmpty() => contacts.SponsoredPeers`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.sponsoredPeersEmpty
- Поля:
  - Нет полей.

## `contacts.TopPeers`

- Официальный тип: https://core.telegram.org/type/contacts.TopPeers
- Количество constructors: **3**

### `contacts.topPeers`

- ID: `1891070632` / `0x70b772a8`
- Сигнатура: `contacts.topPeers(categories:Vector, chats:Vector, users:Vector) => contacts.TopPeers`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.topPeers
- Поля:
  - `categories`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `contacts.topPeersDisabled`

- ID: `-1255369827` / `0xb52c939d`
- Сигнатура: `contacts.topPeersDisabled() => contacts.TopPeers`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.topPeersDisabled
- Поля:
  - Нет полей.

### `contacts.topPeersNotModified`

- ID: `-567906571` / `0xde266ef5`
- Сигнатура: `contacts.topPeersNotModified() => contacts.TopPeers`
- Официальная страница конструктора: https://core.telegram.org/constructor/contacts.topPeersNotModified
- Поля:
  - Нет полей.

## `fragment.CollectibleInfo`

- Официальный тип: https://core.telegram.org/type/fragment.CollectibleInfo
- Количество constructors: **1**

### `fragment.collectibleInfo`

- ID: `1857945489` / `0x6ebdff91`
- Сигнатура: `fragment.collectibleInfo(purchase_date:int, currency:string, amount:long, crypto_currency:string, crypto_amount:long, url:string) => fragment.CollectibleInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/fragment.collectibleInfo
- Поля:
  - `purchase_date`: `int`
  - `currency`: `string`
  - `amount`: `long`
  - `crypto_currency`: `string`
  - `crypto_amount`: `long`
  - `url`: `string`

## `help.AppConfig`

- Официальный тип: https://core.telegram.org/type/help.AppConfig
- Количество constructors: **2**

### `help.appConfig`

- ID: `-585598930` / `0xdd18782e`
- Сигнатура: `help.appConfig(hash:int, config:JSONValue) => help.AppConfig`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.appConfig
- Поля:
  - `hash`: `int`
  - `config`: `JSONValue`

### `help.appConfigNotModified`

- ID: `2094949405` / `0x7cde641d`
- Сигнатура: `help.appConfigNotModified() => help.AppConfig`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.appConfigNotModified
- Поля:
  - Нет полей.

## `help.AppUpdate`

- Официальный тип: https://core.telegram.org/type/help.AppUpdate
- Количество constructors: **2**

### `help.appUpdate`

- ID: `-860107216` / `0xccbbce30`
- Сигнатура: `help.appUpdate(flags:#, can_not_skip:flags.0?true, id:int, version:string, text:string, entities:Vector, document:flags.1?Document, url:flags.2?string, sticker:flags.3?Document) => help.AppUpdate`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.appUpdate
- Поля:
  - `flags`: `#` - служебное поле flags
  - `can_not_skip`: `flags.0?true` - optional через flags.0
  - `id`: `int`
  - `version`: `string`
  - `text`: `string`
  - `entities`: `Vector`
  - `document`: `flags.1?Document` - optional через flags.1
  - `url`: `flags.2?string` - optional через flags.2
  - `sticker`: `flags.3?Document` - optional через flags.3

### `help.noAppUpdate`

- ID: `-1000708810` / `0xc45a6536`
- Сигнатура: `help.noAppUpdate() => help.AppUpdate`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.noAppUpdate
- Поля:
  - Нет полей.

## `help.CountriesList`

- Официальный тип: https://core.telegram.org/type/help.CountriesList
- Количество constructors: **2**

### `help.countriesList`

- ID: `-2016381538` / `0x87d0759e`
- Сигнатура: `help.countriesList(countries:Vector, hash:int) => help.CountriesList`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.countriesList
- Поля:
  - `countries`: `Vector`
  - `hash`: `int`

### `help.countriesListNotModified`

- ID: `-1815339214` / `0x93cc1f32`
- Сигнатура: `help.countriesListNotModified() => help.CountriesList`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.countriesListNotModified
- Поля:
  - Нет полей.

## `help.Country`

- Официальный тип: https://core.telegram.org/type/help.Country
- Количество constructors: **1**

### `help.country`

- ID: `-1014526429` / `0xc3878e23`
- Сигнатура: `help.country(flags:#, hidden:flags.0?true, iso2:string, default_name:string, name:flags.1?string, country_codes:Vector) => help.Country`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.country
- Поля:
  - `flags`: `#` - служебное поле flags
  - `hidden`: `flags.0?true` - optional через flags.0
  - `iso2`: `string`
  - `default_name`: `string`
  - `name`: `flags.1?string` - optional через flags.1
  - `country_codes`: `Vector`

## `help.CountryCode`

- Официальный тип: https://core.telegram.org/type/help.CountryCode
- Количество constructors: **1**

### `help.countryCode`

- ID: `1107543535` / `0x4203c5ef`
- Сигнатура: `help.countryCode(flags:#, country_code:string, prefixes:flags.0?Vector, patterns:flags.1?Vector) => help.CountryCode`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.countryCode
- Поля:
  - `flags`: `#` - служебное поле flags
  - `country_code`: `string`
  - `prefixes`: `flags.0?Vector` - optional через flags.0
  - `patterns`: `flags.1?Vector` - optional через flags.1

## `help.DeepLinkInfo`

- Официальный тип: https://core.telegram.org/type/help.DeepLinkInfo
- Количество constructors: **2**

### `help.deepLinkInfo`

- ID: `1783556146` / `0x6a4ee832`
- Сигнатура: `help.deepLinkInfo(flags:#, update_app:flags.0?true, message:string, entities:flags.1?Vector) => help.DeepLinkInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.deepLinkInfo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `update_app`: `flags.0?true` - optional через flags.0
  - `message`: `string`
  - `entities`: `flags.1?Vector` - optional через flags.1

### `help.deepLinkInfoEmpty`

- ID: `1722786150` / `0x66afa166`
- Сигнатура: `help.deepLinkInfoEmpty() => help.DeepLinkInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.deepLinkInfoEmpty
- Поля:
  - Нет полей.

## `help.InviteText`

- Официальный тип: https://core.telegram.org/type/help.InviteText
- Количество constructors: **1**

### `help.inviteText`

- ID: `415997816` / `0x18cb9f78`
- Сигнатура: `help.inviteText(message:string) => help.InviteText`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.inviteText
- Поля:
  - `message`: `string`

## `help.PassportConfig`

- Официальный тип: https://core.telegram.org/type/help.PassportConfig
- Количество constructors: **2**

### `help.passportConfig`

- ID: `-1600596305` / `0xa098d6af`
- Сигнатура: `help.passportConfig(hash:int, countries_langs:DataJSON) => help.PassportConfig`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.passportConfig
- Поля:
  - `hash`: `int`
  - `countries_langs`: `DataJSON`

### `help.passportConfigNotModified`

- ID: `-1078332329` / `0xbfb9f457`
- Сигнатура: `help.passportConfigNotModified() => help.PassportConfig`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.passportConfigNotModified
- Поля:
  - Нет полей.

## `help.PeerColorOption`

- Официальный тип: https://core.telegram.org/type/help.PeerColorOption
- Количество constructors: **1**

### `help.peerColorOption`

- ID: `-1377014082` / `0xadec6ebe`
- Сигнатура: `help.peerColorOption(flags:#, hidden:flags.0?true, color_id:int, colors:flags.1?help.PeerColorSet, dark_colors:flags.2?help.PeerColorSet, channel_min_level:flags.3?int, group_min_level:flags.4?int) => help.PeerColorOption`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.peerColorOption
- Поля:
  - `flags`: `#` - служебное поле flags
  - `hidden`: `flags.0?true` - optional через flags.0
  - `color_id`: `int`
  - `colors`: `flags.1?help.PeerColorSet` - optional через flags.1
  - `dark_colors`: `flags.2?help.PeerColorSet` - optional через flags.2
  - `channel_min_level`: `flags.3?int` - optional через flags.3
  - `group_min_level`: `flags.4?int` - optional через flags.4

## `help.PeerColorSet`

- Официальный тип: https://core.telegram.org/type/help.PeerColorSet
- Количество constructors: **2**

### `help.peerColorProfileSet`

- ID: `1987928555` / `0x767d61eb`
- Сигнатура: `help.peerColorProfileSet(palette_colors:Vector, bg_colors:Vector, story_colors:Vector) => help.PeerColorSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.peerColorProfileSet
- Поля:
  - `palette_colors`: `Vector`
  - `bg_colors`: `Vector`
  - `story_colors`: `Vector`

### `help.peerColorSet`

- ID: `639736408` / `0x26219a58`
- Сигнатура: `help.peerColorSet(colors:Vector) => help.PeerColorSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.peerColorSet
- Поля:
  - `colors`: `Vector`

## `help.PeerColors`

- Официальный тип: https://core.telegram.org/type/help.PeerColors
- Количество constructors: **2**

### `help.peerColors`

- ID: `16313608` / `0x00f8ed08`
- Сигнатура: `help.peerColors(hash:int, colors:Vector) => help.PeerColors`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.peerColors
- Поля:
  - `hash`: `int`
  - `colors`: `Vector`

### `help.peerColorsNotModified`

- ID: `732034510` / `0x2ba1f5ce`
- Сигнатура: `help.peerColorsNotModified() => help.PeerColors`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.peerColorsNotModified
- Поля:
  - Нет полей.

## `help.PremiumPromo`

- Официальный тип: https://core.telegram.org/type/help.PremiumPromo
- Количество constructors: **1**

### `help.premiumPromo`

- ID: `1395946908` / `0x5334759c`
- Сигнатура: `help.premiumPromo(status_text:string, status_entities:Vector, video_sections:Vector, videos:Vector, period_options:Vector, users:Vector) => help.PremiumPromo`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.premiumPromo
- Поля:
  - `status_text`: `string`
  - `status_entities`: `Vector`
  - `video_sections`: `Vector`
  - `videos`: `Vector`
  - `period_options`: `Vector`
  - `users`: `Vector`

## `help.PromoData`

- Официальный тип: https://core.telegram.org/type/help.PromoData
- Количество constructors: **2**

### `help.promoData`

- ID: `145021050` / `0x08a4d87a`
- Сигнатура: `help.promoData(flags:#, proxy:flags.0?true, expires:int, peer:flags.3?Peer, psa_type:flags.1?string, psa_message:flags.2?string, pending_suggestions:Vector, dismissed_suggestions:Vector, custom_pending_suggestion:flags.4?PendingSuggestion, chats:Vector, users:Vector) => help.PromoData`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.promoData
- Поля:
  - `flags`: `#` - служебное поле flags
  - `proxy`: `flags.0?true` - optional через flags.0
  - `expires`: `int`
  - `peer`: `flags.3?Peer` - optional через flags.3
  - `psa_type`: `flags.1?string` - optional через flags.1
  - `psa_message`: `flags.2?string` - optional через flags.2
  - `pending_suggestions`: `Vector`
  - `dismissed_suggestions`: `Vector`
  - `custom_pending_suggestion`: `flags.4?PendingSuggestion` - optional через flags.4
  - `chats`: `Vector`
  - `users`: `Vector`

### `help.promoDataEmpty`

- ID: `-1728664459` / `0x98f6ac75`
- Сигнатура: `help.promoDataEmpty(expires:int) => help.PromoData`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.promoDataEmpty
- Поля:
  - `expires`: `int`

## `help.RecentMeUrls`

- Официальный тип: https://core.telegram.org/type/help.RecentMeUrls
- Количество constructors: **1**

### `help.recentMeUrls`

- ID: `235081943` / `0x0e0310d7`
- Сигнатура: `help.recentMeUrls(urls:Vector, chats:Vector, users:Vector) => help.RecentMeUrls`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.recentMeUrls
- Поля:
  - `urls`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `help.Support`

- Официальный тип: https://core.telegram.org/type/help.Support
- Количество constructors: **1**

### `help.support`

- ID: `398898678` / `0x17c6b5f6`
- Сигнатура: `help.support(phone_number:string, user:User) => help.Support`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.support
- Поля:
  - `phone_number`: `string`
  - `user`: `User`

## `help.SupportName`

- Официальный тип: https://core.telegram.org/type/help.SupportName
- Количество constructors: **1**

### `help.supportName`

- ID: `-1945767479` / `0x8c05f1c9`
- Сигнатура: `help.supportName(name:string) => help.SupportName`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.supportName
- Поля:
  - `name`: `string`

## `help.TermsOfService`

- Официальный тип: https://core.telegram.org/type/help.TermsOfService
- Количество constructors: **1**

### `help.termsOfService`

- ID: `2013922064` / `0x780a0310`
- Сигнатура: `help.termsOfService(flags:#, popup:flags.0?true, id:DataJSON, text:string, entities:Vector, min_age_confirm:flags.1?int) => help.TermsOfService`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.termsOfService
- Поля:
  - `flags`: `#` - служебное поле flags
  - `popup`: `flags.0?true` - optional через flags.0
  - `id`: `DataJSON`
  - `text`: `string`
  - `entities`: `Vector`
  - `min_age_confirm`: `flags.1?int` - optional через flags.1

## `help.TermsOfServiceUpdate`

- Официальный тип: https://core.telegram.org/type/help.TermsOfServiceUpdate
- Количество constructors: **2**

### `help.termsOfServiceUpdate`

- ID: `686618977` / `0x28ecf961`
- Сигнатура: `help.termsOfServiceUpdate(expires:int, terms_of_service:help.TermsOfService) => help.TermsOfServiceUpdate`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.termsOfServiceUpdate
- Поля:
  - `expires`: `int`
  - `terms_of_service`: `help.TermsOfService`

### `help.termsOfServiceUpdateEmpty`

- ID: `-483352705` / `0xe3309f7f`
- Сигнатура: `help.termsOfServiceUpdateEmpty(expires:int) => help.TermsOfServiceUpdate`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.termsOfServiceUpdateEmpty
- Поля:
  - `expires`: `int`

## `help.TimezonesList`

- Официальный тип: https://core.telegram.org/type/help.TimezonesList
- Количество constructors: **2**

### `help.timezonesList`

- ID: `2071260529` / `0x7b74ed71`
- Сигнатура: `help.timezonesList(timezones:Vector, hash:int) => help.TimezonesList`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.timezonesList
- Поля:
  - `timezones`: `Vector`
  - `hash`: `int`

### `help.timezonesListNotModified`

- ID: `-1761146676` / `0x970708cc`
- Сигнатура: `help.timezonesListNotModified() => help.TimezonesList`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.timezonesListNotModified
- Поля:
  - Нет полей.

## `help.UserInfo`

- Официальный тип: https://core.telegram.org/type/help.UserInfo
- Количество constructors: **2**

### `help.userInfo`

- ID: `32192344` / `0x01eb3758`
- Сигнатура: `help.userInfo(message:string, entities:Vector, author:string, date:int) => help.UserInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.userInfo
- Поля:
  - `message`: `string`
  - `entities`: `Vector`
  - `author`: `string`
  - `date`: `int`

### `help.userInfoEmpty`

- ID: `-206688531` / `0xf3ae2eed`
- Сигнатура: `help.userInfoEmpty() => help.UserInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/help.userInfoEmpty
- Поля:
  - Нет полей.

## `messages.AffectedFoundMessages`

- Официальный тип: https://core.telegram.org/type/messages.AffectedFoundMessages
- Количество constructors: **1**

### `messages.affectedFoundMessages`

- ID: `-275956116` / `0xef8d3e6c`
- Сигнатура: `messages.affectedFoundMessages(pts:int, pts_count:int, offset:int, messages:Vector) => messages.AffectedFoundMessages`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.affectedFoundMessages
- Поля:
  - `pts`: `int`
  - `pts_count`: `int`
  - `offset`: `int`
  - `messages`: `Vector`

## `messages.AffectedHistory`

- Официальный тип: https://core.telegram.org/type/messages.AffectedHistory
- Количество constructors: **1**

### `messages.affectedHistory`

- ID: `-1269012015` / `0xb45c69d1`
- Сигнатура: `messages.affectedHistory(pts:int, pts_count:int, offset:int) => messages.AffectedHistory`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.affectedHistory
- Поля:
  - `pts`: `int`
  - `pts_count`: `int`
  - `offset`: `int`

## `messages.AffectedMessages`

- Официальный тип: https://core.telegram.org/type/messages.AffectedMessages
- Количество constructors: **1**

### `messages.affectedMessages`

- ID: `-2066640507` / `0x84d19185`
- Сигнатура: `messages.affectedMessages(pts:int, pts_count:int) => messages.AffectedMessages`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.affectedMessages
- Поля:
  - `pts`: `int`
  - `pts_count`: `int`

## `messages.AllStickers`

- Официальный тип: https://core.telegram.org/type/messages.AllStickers
- Количество constructors: **2**

### `messages.allStickers`

- ID: `-843329861` / `0xcdbbcebb`
- Сигнатура: `messages.allStickers(hash:long, sets:Vector) => messages.AllStickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.allStickers
- Поля:
  - `hash`: `long`
  - `sets`: `Vector`

### `messages.allStickersNotModified`

- ID: `-395967805` / `0xe86602c3`
- Сигнатура: `messages.allStickersNotModified() => messages.AllStickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.allStickersNotModified
- Поля:
  - Нет полей.

## `messages.ArchivedStickers`

- Официальный тип: https://core.telegram.org/type/messages.ArchivedStickers
- Количество constructors: **1**

### `messages.archivedStickers`

- ID: `1338747336` / `0x4fcba9c8`
- Сигнатура: `messages.archivedStickers(count:int, sets:Vector) => messages.ArchivedStickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.archivedStickers
- Поля:
  - `count`: `int`
  - `sets`: `Vector`

## `messages.AvailableEffects`

- Официальный тип: https://core.telegram.org/type/messages.AvailableEffects
- Количество constructors: **2**

### `messages.availableEffects`

- ID: `-1109696146` / `0xbddb616e`
- Сигнатура: `messages.availableEffects(hash:int, effects:Vector, documents:Vector) => messages.AvailableEffects`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.availableEffects
- Поля:
  - `hash`: `int`
  - `effects`: `Vector`
  - `documents`: `Vector`

### `messages.availableEffectsNotModified`

- ID: `-772957605` / `0xd1ed9a5b`
- Сигнатура: `messages.availableEffectsNotModified() => messages.AvailableEffects`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.availableEffectsNotModified
- Поля:
  - Нет полей.

## `messages.AvailableReactions`

- Официальный тип: https://core.telegram.org/type/messages.AvailableReactions
- Количество constructors: **2**

### `messages.availableReactions`

- ID: `1989032621` / `0x768e3aad`
- Сигнатура: `messages.availableReactions(hash:int, reactions:Vector) => messages.AvailableReactions`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.availableReactions
- Поля:
  - `hash`: `int`
  - `reactions`: `Vector`

### `messages.availableReactionsNotModified`

- ID: `-1626924713` / `0x9f071957`
- Сигнатура: `messages.availableReactionsNotModified() => messages.AvailableReactions`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.availableReactionsNotModified
- Поля:
  - Нет полей.

## `messages.BotApp`

- Официальный тип: https://core.telegram.org/type/messages.BotApp
- Количество constructors: **1**

### `messages.botApp`

- ID: `-347034123` / `0xeb50adf5`
- Сигнатура: `messages.botApp(flags:#, inactive:flags.0?true, request_write_access:flags.1?true, has_settings:flags.2?true, app:BotApp) => messages.BotApp`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.botApp
- Поля:
  - `flags`: `#` - служебное поле flags
  - `inactive`: `flags.0?true` - optional через flags.0
  - `request_write_access`: `flags.1?true` - optional через flags.1
  - `has_settings`: `flags.2?true` - optional через flags.2
  - `app`: `BotApp`

## `messages.BotCallbackAnswer`

- Официальный тип: https://core.telegram.org/type/messages.BotCallbackAnswer
- Количество constructors: **1**

### `messages.botCallbackAnswer`

- ID: `911761060` / `0x36585ea4`
- Сигнатура: `messages.botCallbackAnswer(flags:#, alert:flags.1?true, has_url:flags.3?true, native_ui:flags.4?true, message:flags.0?string, url:flags.2?string, cache_time:int) => messages.BotCallbackAnswer`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.botCallbackAnswer
- Поля:
  - `flags`: `#` - служебное поле flags
  - `alert`: `flags.1?true` - optional через flags.1
  - `has_url`: `flags.3?true` - optional через flags.3
  - `native_ui`: `flags.4?true` - optional через flags.4
  - `message`: `flags.0?string` - optional через flags.0
  - `url`: `flags.2?string` - optional через flags.2
  - `cache_time`: `int`

## `messages.BotPreparedInlineMessage`

- Официальный тип: https://core.telegram.org/type/messages.BotPreparedInlineMessage
- Количество constructors: **1**

### `messages.botPreparedInlineMessage`

- ID: `-1899035375` / `0x8ecf0511`
- Сигнатура: `messages.botPreparedInlineMessage(id:string, expire_date:int) => messages.BotPreparedInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.botPreparedInlineMessage
- Поля:
  - `id`: `string`
  - `expire_date`: `int`

## `messages.BotResults`

- Официальный тип: https://core.telegram.org/type/messages.BotResults
- Количество constructors: **1**

### `messages.botResults`

- ID: `-534646026` / `0xe021f2f6`
- Сигнатура: `messages.botResults(flags:#, gallery:flags.0?true, query_id:long, next_offset:flags.1?string, switch_pm:flags.2?InlineBotSwitchPM, switch_webview:flags.3?InlineBotWebView, results:Vector, cache_time:int, users:Vector) => messages.BotResults`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.botResults
- Поля:
  - `flags`: `#` - служебное поле flags
  - `gallery`: `flags.0?true` - optional через flags.0
  - `query_id`: `long`
  - `next_offset`: `flags.1?string` - optional через flags.1
  - `switch_pm`: `flags.2?InlineBotSwitchPM` - optional через flags.2
  - `switch_webview`: `flags.3?InlineBotWebView` - optional через flags.3
  - `results`: `Vector`
  - `cache_time`: `int`
  - `users`: `Vector`

## `messages.ChatAdminsWithInvites`

- Официальный тип: https://core.telegram.org/type/messages.ChatAdminsWithInvites
- Количество constructors: **1**

### `messages.chatAdminsWithInvites`

- ID: `-1231326505` / `0xb69b72d7`
- Сигнатура: `messages.chatAdminsWithInvites(admins:Vector, users:Vector) => messages.ChatAdminsWithInvites`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.chatAdminsWithInvites
- Поля:
  - `admins`: `Vector`
  - `users`: `Vector`

## `messages.ChatFull`

- Официальный тип: https://core.telegram.org/type/messages.ChatFull
- Количество constructors: **1**

### `messages.chatFull`

- ID: `-438840932` / `0xe5d7d19c`
- Сигнатура: `messages.chatFull(full_chat:ChatFull, chats:Vector, users:Vector) => messages.ChatFull`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.chatFull
- Поля:
  - `full_chat`: `ChatFull`
  - `chats`: `Vector`
  - `users`: `Vector`

## `messages.ChatInviteImporters`

- Официальный тип: https://core.telegram.org/type/messages.ChatInviteImporters
- Количество constructors: **1**

### `messages.chatInviteImporters`

- ID: `-2118733814` / `0x81b6b00a`
- Сигнатура: `messages.chatInviteImporters(count:int, importers:Vector, users:Vector) => messages.ChatInviteImporters`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.chatInviteImporters
- Поля:
  - `count`: `int`
  - `importers`: `Vector`
  - `users`: `Vector`

## `messages.Chats`

- Официальный тип: https://core.telegram.org/type/messages.Chats
- Количество constructors: **2**

### `messages.chats`

- ID: `1694474197` / `0x64ff9fd5`
- Сигнатура: `messages.chats(chats:Vector) => messages.Chats`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.chats
- Поля:
  - `chats`: `Vector`

### `messages.chatsSlice`

- ID: `-1663561404` / `0x9cd81144`
- Сигнатура: `messages.chatsSlice(count:int, chats:Vector) => messages.Chats`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.chatsSlice
- Поля:
  - `count`: `int`
  - `chats`: `Vector`

## `messages.CheckedHistoryImportPeer`

- Официальный тип: https://core.telegram.org/type/messages.CheckedHistoryImportPeer
- Количество constructors: **1**

### `messages.checkedHistoryImportPeer`

- ID: `-1571952873` / `0xa24de717`
- Сигнатура: `messages.checkedHistoryImportPeer(confirm_text:string) => messages.CheckedHistoryImportPeer`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.checkedHistoryImportPeer
- Поля:
  - `confirm_text`: `string`

## `messages.DhConfig`

- Официальный тип: https://core.telegram.org/type/messages.DhConfig
- Количество constructors: **2**

### `messages.dhConfig`

- ID: `740433629` / `0x2c221edd`
- Сигнатура: `messages.dhConfig(g:int, p:bytes, version:int, random:bytes) => messages.DhConfig`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.dhConfig
- Поля:
  - `g`: `int`
  - `p`: `bytes`
  - `version`: `int`
  - `random`: `bytes`

### `messages.dhConfigNotModified`

- ID: `-1058912715` / `0xc0e24635`
- Сигнатура: `messages.dhConfigNotModified(random:bytes) => messages.DhConfig`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.dhConfigNotModified
- Поля:
  - `random`: `bytes`

## `messages.DialogFilters`

- Официальный тип: https://core.telegram.org/type/messages.DialogFilters
- Количество constructors: **1**

### `messages.dialogFilters`

- ID: `718878489` / `0x2ad93719`
- Сигнатура: `messages.dialogFilters(flags:#, tags_enabled:flags.0?true, filters:Vector) => messages.DialogFilters`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.dialogFilters
- Поля:
  - `flags`: `#` - служебное поле flags
  - `tags_enabled`: `flags.0?true` - optional через flags.0
  - `filters`: `Vector`

## `messages.Dialogs`

- Официальный тип: https://core.telegram.org/type/messages.Dialogs
- Количество constructors: **3**

### `messages.dialogs`

- ID: `364538944` / `0x15ba6c40`
- Сигнатура: `messages.dialogs(dialogs:Vector, messages:Vector, chats:Vector, users:Vector) => messages.Dialogs`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.dialogs
- Поля:
  - `dialogs`: `Vector`
  - `messages`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `messages.dialogsNotModified`

- ID: `-253500010` / `0xf0e3e596`
- Сигнатура: `messages.dialogsNotModified(count:int) => messages.Dialogs`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.dialogsNotModified
- Поля:
  - `count`: `int`

### `messages.dialogsSlice`

- ID: `1910543603` / `0x71e094f3`
- Сигнатура: `messages.dialogsSlice(count:int, dialogs:Vector, messages:Vector, chats:Vector, users:Vector) => messages.Dialogs`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.dialogsSlice
- Поля:
  - `count`: `int`
  - `dialogs`: `Vector`
  - `messages`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `messages.DiscussionMessage`

- Официальный тип: https://core.telegram.org/type/messages.DiscussionMessage
- Количество constructors: **1**

### `messages.discussionMessage`

- ID: `-1506535550` / `0xa6341782`
- Сигнатура: `messages.discussionMessage(flags:#, messages:Vector, max_id:flags.0?int, read_inbox_max_id:flags.1?int, read_outbox_max_id:flags.2?int, unread_count:int, chats:Vector, users:Vector) => messages.DiscussionMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.discussionMessage
- Поля:
  - `flags`: `#` - служебное поле flags
  - `messages`: `Vector`
  - `max_id`: `flags.0?int` - optional через flags.0
  - `read_inbox_max_id`: `flags.1?int` - optional через flags.1
  - `read_outbox_max_id`: `flags.2?int` - optional через flags.2
  - `unread_count`: `int`
  - `chats`: `Vector`
  - `users`: `Vector`

## `messages.EmojiGroups`

- Официальный тип: https://core.telegram.org/type/messages.EmojiGroups
- Количество constructors: **2**

### `messages.emojiGroups`

- ID: `-2011186869` / `0x881fb94b`
- Сигнатура: `messages.emojiGroups(hash:int, groups:Vector) => messages.EmojiGroups`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.emojiGroups
- Поля:
  - `hash`: `int`
  - `groups`: `Vector`

### `messages.emojiGroupsNotModified`

- ID: `1874111879` / `0x6fb4ad87`
- Сигнатура: `messages.emojiGroupsNotModified() => messages.EmojiGroups`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.emojiGroupsNotModified
- Поля:
  - Нет полей.

## `messages.ExportedChatInvite`

- Официальный тип: https://core.telegram.org/type/messages.ExportedChatInvite
- Количество constructors: **2**

### `messages.exportedChatInvite`

- ID: `410107472` / `0x1871be50`
- Сигнатура: `messages.exportedChatInvite(invite:ExportedChatInvite, users:Vector) => messages.ExportedChatInvite`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.exportedChatInvite
- Поля:
  - `invite`: `ExportedChatInvite`
  - `users`: `Vector`

### `messages.exportedChatInviteReplaced`

- ID: `572915951` / `0x222600ef`
- Сигнатура: `messages.exportedChatInviteReplaced(invite:ExportedChatInvite, new_invite:ExportedChatInvite, users:Vector) => messages.ExportedChatInvite`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.exportedChatInviteReplaced
- Поля:
  - `invite`: `ExportedChatInvite`
  - `new_invite`: `ExportedChatInvite`
  - `users`: `Vector`

## `messages.ExportedChatInvites`

- Официальный тип: https://core.telegram.org/type/messages.ExportedChatInvites
- Количество constructors: **1**

### `messages.exportedChatInvites`

- ID: `-1111085620` / `0xbdc62dcc`
- Сигнатура: `messages.exportedChatInvites(count:int, invites:Vector, users:Vector) => messages.ExportedChatInvites`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.exportedChatInvites
- Поля:
  - `count`: `int`
  - `invites`: `Vector`
  - `users`: `Vector`

## `messages.FavedStickers`

- Официальный тип: https://core.telegram.org/type/messages.FavedStickers
- Количество constructors: **2**

### `messages.favedStickers`

- ID: `750063767` / `0x2cb51097`
- Сигнатура: `messages.favedStickers(hash:long, packs:Vector, stickers:Vector) => messages.FavedStickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.favedStickers
- Поля:
  - `hash`: `long`
  - `packs`: `Vector`
  - `stickers`: `Vector`

### `messages.favedStickersNotModified`

- ID: `-1634752813` / `0x9e8fa6d3`
- Сигнатура: `messages.favedStickersNotModified() => messages.FavedStickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.favedStickersNotModified
- Поля:
  - Нет полей.

## `messages.FeaturedStickers`

- Официальный тип: https://core.telegram.org/type/messages.FeaturedStickers
- Количество constructors: **2**

### `messages.featuredStickers`

- ID: `-1103615738` / `0xbe382906`
- Сигнатура: `messages.featuredStickers(flags:#, premium:flags.0?true, hash:long, count:int, sets:Vector, unread:Vector) => messages.FeaturedStickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.featuredStickers
- Поля:
  - `flags`: `#` - служебное поле flags
  - `premium`: `flags.0?true` - optional через flags.0
  - `hash`: `long`
  - `count`: `int`
  - `sets`: `Vector`
  - `unread`: `Vector`

### `messages.featuredStickersNotModified`

- ID: `-958657434` / `0xc6dc0c66`
- Сигнатура: `messages.featuredStickersNotModified(count:int) => messages.FeaturedStickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.featuredStickersNotModified
- Поля:
  - `count`: `int`

## `messages.ForumTopics`

- Официальный тип: https://core.telegram.org/type/messages.ForumTopics
- Количество constructors: **1**

### `messages.forumTopics`

- ID: `913709011` / `0x367617d3`
- Сигнатура: `messages.forumTopics(flags:#, order_by_create_date:flags.0?true, count:int, topics:Vector, messages:Vector, chats:Vector, users:Vector, pts:int) => messages.ForumTopics`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.forumTopics
- Поля:
  - `flags`: `#` - служебное поле flags
  - `order_by_create_date`: `flags.0?true` - optional через flags.0
  - `count`: `int`
  - `topics`: `Vector`
  - `messages`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`
  - `pts`: `int`

## `messages.FoundStickerSets`

- Официальный тип: https://core.telegram.org/type/messages.FoundStickerSets
- Количество constructors: **2**

### `messages.foundStickerSets`

- ID: `-1963942446` / `0x8af09dd2`
- Сигнатура: `messages.foundStickerSets(hash:long, sets:Vector) => messages.FoundStickerSets`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.foundStickerSets
- Поля:
  - `hash`: `long`
  - `sets`: `Vector`

### `messages.foundStickerSetsNotModified`

- ID: `223655517` / `0x0d54b65d`
- Сигнатура: `messages.foundStickerSetsNotModified() => messages.FoundStickerSets`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.foundStickerSetsNotModified
- Поля:
  - Нет полей.

## `messages.FoundStickers`

- Официальный тип: https://core.telegram.org/type/messages.FoundStickers
- Количество constructors: **2**

### `messages.foundStickers`

- ID: `-2100698480` / `0x82c9e290`
- Сигнатура: `messages.foundStickers(flags:#, next_offset:flags.0?int, hash:long, stickers:Vector) => messages.FoundStickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.foundStickers
- Поля:
  - `flags`: `#` - служебное поле flags
  - `next_offset`: `flags.0?int` - optional через flags.0
  - `hash`: `long`
  - `stickers`: `Vector`

### `messages.foundStickersNotModified`

- ID: `1611711796` / `0x6010c534`
- Сигнатура: `messages.foundStickersNotModified(flags:#, next_offset:flags.0?int) => messages.FoundStickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.foundStickersNotModified
- Поля:
  - `flags`: `#` - служебное поле flags
  - `next_offset`: `flags.0?int` - optional через flags.0

## `messages.HighScores`

- Официальный тип: https://core.telegram.org/type/messages.HighScores
- Количество constructors: **1**

### `messages.highScores`

- ID: `-1707344487` / `0x9a3bfd99`
- Сигнатура: `messages.highScores(scores:Vector, users:Vector) => messages.HighScores`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.highScores
- Поля:
  - `scores`: `Vector`
  - `users`: `Vector`

## `messages.HistoryImport`

- Официальный тип: https://core.telegram.org/type/messages.HistoryImport
- Количество constructors: **1**

### `messages.historyImport`

- ID: `375566091` / `0x1662af0b`
- Сигнатура: `messages.historyImport(id:long) => messages.HistoryImport`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.historyImport
- Поля:
  - `id`: `long`

## `messages.HistoryImportParsed`

- Официальный тип: https://core.telegram.org/type/messages.HistoryImportParsed
- Количество constructors: **1**

### `messages.historyImportParsed`

- ID: `1578088377` / `0x5e0fb7b9`
- Сигнатура: `messages.historyImportParsed(flags:#, pm:flags.0?true, group:flags.1?true, title:flags.2?string) => messages.HistoryImportParsed`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.historyImportParsed
- Поля:
  - `flags`: `#` - служебное поле flags
  - `pm`: `flags.0?true` - optional через flags.0
  - `group`: `flags.1?true` - optional через flags.1
  - `title`: `flags.2?string` - optional через flags.2

## `messages.InactiveChats`

- Официальный тип: https://core.telegram.org/type/messages.InactiveChats
- Количество constructors: **1**

### `messages.inactiveChats`

- ID: `-1456996667` / `0xa927fec5`
- Сигнатура: `messages.inactiveChats(dates:Vector, chats:Vector, users:Vector) => messages.InactiveChats`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.inactiveChats
- Поля:
  - `dates`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `messages.InvitedUsers`

- Официальный тип: https://core.telegram.org/type/messages.InvitedUsers
- Количество constructors: **1**

### `messages.invitedUsers`

- ID: `2136862630` / `0x7f5defa6`
- Сигнатура: `messages.invitedUsers(updates:Updates, missing_invitees:Vector) => messages.InvitedUsers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.invitedUsers
- Поля:
  - `updates`: `Updates`
  - `missing_invitees`: `Vector`

## `messages.MessageEditData`

- Официальный тип: https://core.telegram.org/type/messages.MessageEditData
- Количество constructors: **1**

### `messages.messageEditData`

- ID: `649453030` / `0x26b5dde6`
- Сигнатура: `messages.messageEditData(flags:#, caption:flags.0?true) => messages.MessageEditData`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.messageEditData
- Поля:
  - `flags`: `#` - служебное поле flags
  - `caption`: `flags.0?true` - optional через flags.0

## `messages.MessageReactionsList`

- Официальный тип: https://core.telegram.org/type/messages.MessageReactionsList
- Количество constructors: **1**

### `messages.messageReactionsList`

- ID: `834488621` / `0x31bd492d`
- Сигнатура: `messages.messageReactionsList(flags:#, count:int, reactions:Vector, chats:Vector, users:Vector, next_offset:flags.0?string) => messages.MessageReactionsList`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.messageReactionsList
- Поля:
  - `flags`: `#` - служебное поле flags
  - `count`: `int`
  - `reactions`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`
  - `next_offset`: `flags.0?string` - optional через flags.0

## `messages.MessageViews`

- Официальный тип: https://core.telegram.org/type/messages.MessageViews
- Количество constructors: **1**

### `messages.messageViews`

- ID: `-1228606141` / `0xb6c4f543`
- Сигнатура: `messages.messageViews(views:Vector, chats:Vector, users:Vector) => messages.MessageViews`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.messageViews
- Поля:
  - `views`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `messages.Messages`

- Официальный тип: https://core.telegram.org/type/messages.Messages
- Количество constructors: **4**

### `messages.channelMessages`

- ID: `-948520370` / `0xc776ba4e`
- Сигнатура: `messages.channelMessages(flags:#, inexact:flags.1?true, pts:int, count:int, offset_id_offset:flags.2?int, messages:Vector, topics:Vector, chats:Vector, users:Vector) => messages.Messages`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.channelMessages
- Поля:
  - `flags`: `#` - служебное поле flags
  - `inexact`: `flags.1?true` - optional через flags.1
  - `pts`: `int`
  - `count`: `int`
  - `offset_id_offset`: `flags.2?int` - optional через flags.2
  - `messages`: `Vector`
  - `topics`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `messages.messages`

- ID: `-1938715001` / `0x8c718e87`
- Сигнатура: `messages.messages(messages:Vector, chats:Vector, users:Vector) => messages.Messages`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.messages
- Поля:
  - `messages`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `messages.messagesNotModified`

- ID: `1951620897` / `0x74535f21`
- Сигнатура: `messages.messagesNotModified(count:int) => messages.Messages`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.messagesNotModified
- Поля:
  - `count`: `int`

### `messages.messagesSlice`

- ID: `1982539325` / `0x762b263d`
- Сигнатура: `messages.messagesSlice(flags:#, inexact:flags.1?true, count:int, next_rate:flags.0?int, offset_id_offset:flags.2?int, search_flood:flags.3?SearchPostsFlood, messages:Vector, chats:Vector, users:Vector) => messages.Messages`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.messagesSlice
- Поля:
  - `flags`: `#` - служебное поле flags
  - `inexact`: `flags.1?true` - optional через flags.1
  - `count`: `int`
  - `next_rate`: `flags.0?int` - optional через flags.0
  - `offset_id_offset`: `flags.2?int` - optional через flags.2
  - `search_flood`: `flags.3?SearchPostsFlood` - optional через flags.3
  - `messages`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `messages.MyStickers`

- Официальный тип: https://core.telegram.org/type/messages.MyStickers
- Количество constructors: **1**

### `messages.myStickers`

- ID: `-83926371` / `0xfaff629d`
- Сигнатура: `messages.myStickers(count:int, sets:Vector) => messages.MyStickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.myStickers
- Поля:
  - `count`: `int`
  - `sets`: `Vector`

## `messages.PeerDialogs`

- Официальный тип: https://core.telegram.org/type/messages.PeerDialogs
- Количество constructors: **1**

### `messages.peerDialogs`

- ID: `863093588` / `0x3371c354`
- Сигнатура: `messages.peerDialogs(dialogs:Vector, messages:Vector, chats:Vector, users:Vector, state:updates.State) => messages.PeerDialogs`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.peerDialogs
- Поля:
  - `dialogs`: `Vector`
  - `messages`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`
  - `state`: `updates.State`

## `messages.PeerSettings`

- Официальный тип: https://core.telegram.org/type/messages.PeerSettings
- Количество constructors: **1**

### `messages.peerSettings`

- ID: `1753266509` / `0x6880b94d`
- Сигнатура: `messages.peerSettings(settings:PeerSettings, chats:Vector, users:Vector) => messages.PeerSettings`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.peerSettings
- Поля:
  - `settings`: `PeerSettings`
  - `chats`: `Vector`
  - `users`: `Vector`

## `messages.PreparedInlineMessage`

- Официальный тип: https://core.telegram.org/type/messages.PreparedInlineMessage
- Количество constructors: **1**

### `messages.preparedInlineMessage`

- ID: `-11046771` / `0xff57708d`
- Сигнатура: `messages.preparedInlineMessage(query_id:long, result:BotInlineResult, peer_types:Vector, cache_time:int, users:Vector) => messages.PreparedInlineMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.preparedInlineMessage
- Поля:
  - `query_id`: `long`
  - `result`: `BotInlineResult`
  - `peer_types`: `Vector`
  - `cache_time`: `int`
  - `users`: `Vector`

## `messages.QuickReplies`

- Официальный тип: https://core.telegram.org/type/messages.QuickReplies
- Количество constructors: **2**

### `messages.quickReplies`

- ID: `-963811691` / `0xc68d6695`
- Сигнатура: `messages.quickReplies(quick_replies:Vector, messages:Vector, chats:Vector, users:Vector) => messages.QuickReplies`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.quickReplies
- Поля:
  - `quick_replies`: `Vector`
  - `messages`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `messages.quickRepliesNotModified`

- ID: `1603398491` / `0x5f91eb5b`
- Сигнатура: `messages.quickRepliesNotModified() => messages.QuickReplies`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.quickRepliesNotModified
- Поля:
  - Нет полей.

## `messages.Reactions`

- Официальный тип: https://core.telegram.org/type/messages.Reactions
- Количество constructors: **2**

### `messages.reactions`

- ID: `-352454890` / `0xeafdf716`
- Сигнатура: `messages.reactions(hash:long, reactions:Vector) => messages.Reactions`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.reactions
- Поля:
  - `hash`: `long`
  - `reactions`: `Vector`

### `messages.reactionsNotModified`

- ID: `-1334846497` / `0xb06fdbdf`
- Сигнатура: `messages.reactionsNotModified() => messages.Reactions`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.reactionsNotModified
- Поля:
  - Нет полей.

## `messages.RecentStickers`

- Официальный тип: https://core.telegram.org/type/messages.RecentStickers
- Количество constructors: **2**

### `messages.recentStickers`

- ID: `-1999405994` / `0x88d37c56`
- Сигнатура: `messages.recentStickers(hash:long, packs:Vector, stickers:Vector, dates:Vector) => messages.RecentStickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.recentStickers
- Поля:
  - `hash`: `long`
  - `packs`: `Vector`
  - `stickers`: `Vector`
  - `dates`: `Vector`

### `messages.recentStickersNotModified`

- ID: `186120336` / `0x0b17f890`
- Сигнатура: `messages.recentStickersNotModified() => messages.RecentStickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.recentStickersNotModified
- Поля:
  - Нет полей.

## `messages.SavedDialogs`

- Официальный тип: https://core.telegram.org/type/messages.SavedDialogs
- Количество constructors: **3**

### `messages.savedDialogs`

- ID: `-130358751` / `0xf83ae221`
- Сигнатура: `messages.savedDialogs(dialogs:Vector, messages:Vector, chats:Vector, users:Vector) => messages.SavedDialogs`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.savedDialogs
- Поля:
  - `dialogs`: `Vector`
  - `messages`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `messages.savedDialogsNotModified`

- ID: `-1071681560` / `0xc01f6fe8`
- Сигнатура: `messages.savedDialogsNotModified(count:int) => messages.SavedDialogs`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.savedDialogsNotModified
- Поля:
  - `count`: `int`

### `messages.savedDialogsSlice`

- ID: `1153080793` / `0x44ba9dd9`
- Сигнатура: `messages.savedDialogsSlice(count:int, dialogs:Vector, messages:Vector, chats:Vector, users:Vector) => messages.SavedDialogs`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.savedDialogsSlice
- Поля:
  - `count`: `int`
  - `dialogs`: `Vector`
  - `messages`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `messages.SavedGifs`

- Официальный тип: https://core.telegram.org/type/messages.SavedGifs
- Количество constructors: **2**

### `messages.savedGifs`

- ID: `-2069878259` / `0x84a02a0d`
- Сигнатура: `messages.savedGifs(hash:long, gifs:Vector) => messages.SavedGifs`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.savedGifs
- Поля:
  - `hash`: `long`
  - `gifs`: `Vector`

### `messages.savedGifsNotModified`

- ID: `-402498398` / `0xe8025ca2`
- Сигнатура: `messages.savedGifsNotModified() => messages.SavedGifs`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.savedGifsNotModified
- Поля:
  - Нет полей.

## `messages.SavedReactionTags`

- Официальный тип: https://core.telegram.org/type/messages.SavedReactionTags
- Количество constructors: **2**

### `messages.savedReactionTags`

- ID: `844731658` / `0x3259950a`
- Сигнатура: `messages.savedReactionTags(tags:Vector, hash:long) => messages.SavedReactionTags`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.savedReactionTags
- Поля:
  - `tags`: `Vector`
  - `hash`: `long`

### `messages.savedReactionTagsNotModified`

- ID: `-2003084817` / `0x889b59ef`
- Сигнатура: `messages.savedReactionTagsNotModified() => messages.SavedReactionTags`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.savedReactionTagsNotModified
- Поля:
  - Нет полей.

## `messages.SearchCounter`

- Официальный тип: https://core.telegram.org/type/messages.SearchCounter
- Количество constructors: **1**

### `messages.searchCounter`

- ID: `-398136321` / `0xe844ebff`
- Сигнатура: `messages.searchCounter(flags:#, inexact:flags.1?true, filter:MessagesFilter, count:int) => messages.SearchCounter`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.searchCounter
- Поля:
  - `flags`: `#` - служебное поле flags
  - `inexact`: `flags.1?true` - optional через flags.1
  - `filter`: `MessagesFilter`
  - `count`: `int`

## `messages.SearchResultsCalendar`

- Официальный тип: https://core.telegram.org/type/messages.SearchResultsCalendar
- Количество constructors: **1**

### `messages.searchResultsCalendar`

- ID: `343859772` / `0x147ee23c`
- Сигнатура: `messages.searchResultsCalendar(flags:#, inexact:flags.0?true, count:int, min_date:int, min_msg_id:int, offset_id_offset:flags.1?int, periods:Vector, messages:Vector, chats:Vector, users:Vector) => messages.SearchResultsCalendar`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.searchResultsCalendar
- Поля:
  - `flags`: `#` - служебное поле flags
  - `inexact`: `flags.0?true` - optional через flags.0
  - `count`: `int`
  - `min_date`: `int`
  - `min_msg_id`: `int`
  - `offset_id_offset`: `flags.1?int` - optional через flags.1
  - `periods`: `Vector`
  - `messages`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `messages.SearchResultsPositions`

- Официальный тип: https://core.telegram.org/type/messages.SearchResultsPositions
- Количество constructors: **1**

### `messages.searchResultsPositions`

- ID: `1404185519` / `0x53b22baf`
- Сигнатура: `messages.searchResultsPositions(count:int, positions:Vector) => messages.SearchResultsPositions`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.searchResultsPositions
- Поля:
  - `count`: `int`
  - `positions`: `Vector`

## `messages.SentEncryptedMessage`

- Официальный тип: https://core.telegram.org/type/messages.SentEncryptedMessage
- Количество constructors: **2**

### `messages.sentEncryptedFile`

- ID: `-1802240206` / `0x9493ff32`
- Сигнатура: `messages.sentEncryptedFile(date:int, file:EncryptedFile) => messages.SentEncryptedMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.sentEncryptedFile
- Поля:
  - `date`: `int`
  - `file`: `EncryptedFile`

### `messages.sentEncryptedMessage`

- ID: `1443858741` / `0x560f8935`
- Сигнатура: `messages.sentEncryptedMessage(date:int) => messages.SentEncryptedMessage`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.sentEncryptedMessage
- Поля:
  - `date`: `int`

## `messages.SponsoredMessages`

- Официальный тип: https://core.telegram.org/type/messages.SponsoredMessages
- Количество constructors: **2**

### `messages.sponsoredMessages`

- ID: `-2464403` / `0xffda656d`
- Сигнатура: `messages.sponsoredMessages(flags:#, posts_between:flags.0?int, start_delay:flags.1?int, between_delay:flags.2?int, messages:Vector, chats:Vector, users:Vector) => messages.SponsoredMessages`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.sponsoredMessages
- Поля:
  - `flags`: `#` - служебное поле flags
  - `posts_between`: `flags.0?int` - optional через flags.0
  - `start_delay`: `flags.1?int` - optional через flags.1
  - `between_delay`: `flags.2?int` - optional через flags.2
  - `messages`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `messages.sponsoredMessagesEmpty`

- ID: `406407439` / `0x1839490f`
- Сигнатура: `messages.sponsoredMessagesEmpty() => messages.SponsoredMessages`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.sponsoredMessagesEmpty
- Поля:
  - Нет полей.

## `messages.StickerSet`

- Официальный тип: https://core.telegram.org/type/messages.StickerSet
- Количество constructors: **2**

### `messages.stickerSet`

- ID: `1846886166` / `0x6e153f16`
- Сигнатура: `messages.stickerSet(set:StickerSet, packs:Vector, keywords:Vector, documents:Vector) => messages.StickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.stickerSet
- Поля:
  - `set`: `StickerSet`
  - `packs`: `Vector`
  - `keywords`: `Vector`
  - `documents`: `Vector`

### `messages.stickerSetNotModified`

- ID: `-738646805` / `0xd3f924eb`
- Сигнатура: `messages.stickerSetNotModified() => messages.StickerSet`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.stickerSetNotModified
- Поля:
  - Нет полей.

## `messages.StickerSetInstallResult`

- Официальный тип: https://core.telegram.org/type/messages.StickerSetInstallResult
- Количество constructors: **2**

### `messages.stickerSetInstallResultArchive`

- ID: `904138920` / `0x35e410a8`
- Сигнатура: `messages.stickerSetInstallResultArchive(sets:Vector) => messages.StickerSetInstallResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.stickerSetInstallResultArchive
- Поля:
  - `sets`: `Vector`

### `messages.stickerSetInstallResultSuccess`

- ID: `946083368` / `0x38641628`
- Сигнатура: `messages.stickerSetInstallResultSuccess() => messages.StickerSetInstallResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.stickerSetInstallResultSuccess
- Поля:
  - Нет полей.

## `messages.Stickers`

- Официальный тип: https://core.telegram.org/type/messages.Stickers
- Количество constructors: **2**

### `messages.stickers`

- ID: `816245886` / `0x30a6ec7e`
- Сигнатура: `messages.stickers(hash:long, stickers:Vector) => messages.Stickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.stickers
- Поля:
  - `hash`: `long`
  - `stickers`: `Vector`

### `messages.stickersNotModified`

- ID: `-244016606` / `0xf1749a22`
- Сигнатура: `messages.stickersNotModified() => messages.Stickers`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.stickersNotModified
- Поля:
  - Нет полей.

## `messages.TranscribedAudio`

- Официальный тип: https://core.telegram.org/type/messages.TranscribedAudio
- Количество constructors: **1**

### `messages.transcribedAudio`

- ID: `-809903785` / `0xcfb9d957`
- Сигнатура: `messages.transcribedAudio(flags:#, pending:flags.0?true, transcription_id:long, text:string, trial_remains_num:flags.1?int, trial_remains_until_date:flags.1?int) => messages.TranscribedAudio`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.transcribedAudio
- Поля:
  - `flags`: `#` - служебное поле flags
  - `pending`: `flags.0?true` - optional через flags.0
  - `transcription_id`: `long`
  - `text`: `string`
  - `trial_remains_num`: `flags.1?int` - optional через flags.1
  - `trial_remains_until_date`: `flags.1?int` - optional через flags.1

## `messages.TranslatedText`

- Официальный тип: https://core.telegram.org/type/messages.TranslatedText
- Количество constructors: **1**

### `messages.translateResult`

- ID: `870003448` / `0x33db32f8`
- Сигнатура: `messages.translateResult(result:Vector) => messages.TranslatedText`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.translateResult
- Поля:
  - `result`: `Vector`

## `messages.VotesList`

- Официальный тип: https://core.telegram.org/type/messages.VotesList
- Количество constructors: **1**

### `messages.votesList`

- ID: `1218005070` / `0x4899484e`
- Сигнатура: `messages.votesList(flags:#, count:int, votes:Vector, chats:Vector, users:Vector, next_offset:flags.0?string) => messages.VotesList`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.votesList
- Поля:
  - `flags`: `#` - служебное поле flags
  - `count`: `int`
  - `votes`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`
  - `next_offset`: `flags.0?string` - optional через flags.0

## `messages.WebPage`

- Официальный тип: https://core.telegram.org/type/messages.WebPage
- Количество constructors: **1**

### `messages.webPage`

- ID: `-44166467` / `0xfd5e12bd`
- Сигнатура: `messages.webPage(webpage:WebPage, chats:Vector, users:Vector) => messages.WebPage`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.webPage
- Поля:
  - `webpage`: `WebPage`
  - `chats`: `Vector`
  - `users`: `Vector`

## `messages.WebPagePreview`

- Официальный тип: https://core.telegram.org/type/messages.WebPagePreview
- Количество constructors: **1**

### `messages.webPagePreview`

- ID: `-1936029524` / `0x8c9a88ac`
- Сигнатура: `messages.webPagePreview(media:MessageMedia, chats:Vector, users:Vector) => messages.WebPagePreview`
- Официальная страница конструктора: https://core.telegram.org/constructor/messages.webPagePreview
- Поля:
  - `media`: `MessageMedia`
  - `chats`: `Vector`
  - `users`: `Vector`

## `payments.BankCardData`

- Официальный тип: https://core.telegram.org/type/payments.BankCardData
- Количество constructors: **1**

### `payments.bankCardData`

- ID: `1042605427` / `0x3e24e573`
- Сигнатура: `payments.bankCardData(title:string, open_urls:Vector) => payments.BankCardData`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.bankCardData
- Поля:
  - `title`: `string`
  - `open_urls`: `Vector`

## `payments.CheckCanSendGiftResult`

- Официальный тип: https://core.telegram.org/type/payments.CheckCanSendGiftResult
- Количество constructors: **2**

### `payments.checkCanSendGiftResultFail`

- ID: `-706379148` / `0xd5e58274`
- Сигнатура: `payments.checkCanSendGiftResultFail(reason:TextWithEntities) => payments.CheckCanSendGiftResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.checkCanSendGiftResultFail
- Поля:
  - `reason`: `TextWithEntities`

### `payments.checkCanSendGiftResultOk`

- ID: `927967149` / `0x374fa7ad`
- Сигнатура: `payments.checkCanSendGiftResultOk() => payments.CheckCanSendGiftResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.checkCanSendGiftResultOk
- Поля:
  - Нет полей.

## `payments.CheckedGiftCode`

- Официальный тип: https://core.telegram.org/type/payments.CheckedGiftCode
- Количество constructors: **1**

### `payments.checkedGiftCode`

- ID: `675942550` / `0x284a1096`
- Сигнатура: `payments.checkedGiftCode(flags:#, via_giveaway:flags.2?true, from_id:flags.4?Peer, giveaway_msg_id:flags.3?int, to_id:flags.0?long, date:int, months:int, used_date:flags.1?int, chats:Vector, users:Vector) => payments.CheckedGiftCode`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.checkedGiftCode
- Поля:
  - `flags`: `#` - служебное поле flags
  - `via_giveaway`: `flags.2?true` - optional через flags.2
  - `from_id`: `flags.4?Peer` - optional через flags.4
  - `giveaway_msg_id`: `flags.3?int` - optional через flags.3
  - `to_id`: `flags.0?long` - optional через flags.0
  - `date`: `int`
  - `months`: `int`
  - `used_date`: `flags.1?int` - optional через flags.1
  - `chats`: `Vector`
  - `users`: `Vector`

## `payments.ConnectedStarRefBots`

- Официальный тип: https://core.telegram.org/type/payments.ConnectedStarRefBots
- Количество constructors: **1**

### `payments.connectedStarRefBots`

- ID: `-1730811363` / `0x98d5ea1d`
- Сигнатура: `payments.connectedStarRefBots(count:int, connected_bots:Vector, users:Vector) => payments.ConnectedStarRefBots`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.connectedStarRefBots
- Поля:
  - `count`: `int`
  - `connected_bots`: `Vector`
  - `users`: `Vector`

## `payments.ExportedInvoice`

- Официальный тип: https://core.telegram.org/type/payments.ExportedInvoice
- Количество constructors: **1**

### `payments.exportedInvoice`

- ID: `-1362048039` / `0xaed0cbd9`
- Сигнатура: `payments.exportedInvoice(url:string) => payments.ExportedInvoice`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.exportedInvoice
- Поля:
  - `url`: `string`

## `payments.GiveawayInfo`

- Официальный тип: https://core.telegram.org/type/payments.GiveawayInfo
- Количество constructors: **2**

### `payments.giveawayInfo`

- ID: `1130879648` / `0x4367daa0`
- Сигнатура: `payments.giveawayInfo(flags:#, participating:flags.0?true, preparing_results:flags.3?true, start_date:int, joined_too_early_date:flags.1?int, admin_disallowed_chat_id:flags.2?long, disallowed_country:flags.4?string) => payments.GiveawayInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.giveawayInfo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `participating`: `flags.0?true` - optional через flags.0
  - `preparing_results`: `flags.3?true` - optional через flags.3
  - `start_date`: `int`
  - `joined_too_early_date`: `flags.1?int` - optional через flags.1
  - `admin_disallowed_chat_id`: `flags.2?long` - optional через flags.2
  - `disallowed_country`: `flags.4?string` - optional через flags.4

### `payments.giveawayInfoResults`

- ID: `-512366993` / `0xe175e66f`
- Сигнатура: `payments.giveawayInfoResults(flags:#, winner:flags.0?true, refunded:flags.1?true, start_date:int, gift_code_slug:flags.3?string, stars_prize:flags.4?long, finish_date:int, winners_count:int, activated_count:flags.2?int) => payments.GiveawayInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.giveawayInfoResults
- Поля:
  - `flags`: `#` - служебное поле flags
  - `winner`: `flags.0?true` - optional через flags.0
  - `refunded`: `flags.1?true` - optional через flags.1
  - `start_date`: `int`
  - `gift_code_slug`: `flags.3?string` - optional через flags.3
  - `stars_prize`: `flags.4?long` - optional через flags.4
  - `finish_date`: `int`
  - `winners_count`: `int`
  - `activated_count`: `flags.2?int` - optional через flags.2

## `payments.PaymentForm`

- Официальный тип: https://core.telegram.org/type/payments.PaymentForm
- Количество constructors: **3**

### `payments.paymentForm`

- ID: `-1610250415` / `0xa0058751`
- Сигнатура: `payments.paymentForm(flags:#, can_save_credentials:flags.2?true, password_missing:flags.3?true, form_id:long, bot_id:long, title:string, description:string, photo:flags.5?WebDocument, invoice:Invoice, provider_id:long, url:string, native_provider:flags.4?string, native_params:flags.4?DataJSON, additional_methods:flags.6?Vector, saved_info:flags.0?PaymentRequestedInfo, saved_credentials:flags.1?Vector, users:Vector) => payments.PaymentForm`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.paymentForm
- Поля:
  - `flags`: `#` - служебное поле flags
  - `can_save_credentials`: `flags.2?true` - optional через flags.2
  - `password_missing`: `flags.3?true` - optional через flags.3
  - `form_id`: `long`
  - `bot_id`: `long`
  - `title`: `string`
  - `description`: `string`
  - `photo`: `flags.5?WebDocument` - optional через flags.5
  - `invoice`: `Invoice`
  - `provider_id`: `long`
  - `url`: `string`
  - `native_provider`: `flags.4?string` - optional через flags.4
  - `native_params`: `flags.4?DataJSON` - optional через flags.4
  - `additional_methods`: `flags.6?Vector` - optional через flags.6
  - `saved_info`: `flags.0?PaymentRequestedInfo` - optional через flags.0
  - `saved_credentials`: `flags.1?Vector` - optional через flags.1
  - `users`: `Vector`

### `payments.paymentFormStarGift`

- ID: `-1272590367` / `0xb425cfe1`
- Сигнатура: `payments.paymentFormStarGift(form_id:long, invoice:Invoice) => payments.PaymentForm`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.paymentFormStarGift
- Поля:
  - `form_id`: `long`
  - `invoice`: `Invoice`

### `payments.paymentFormStars`

- ID: `2079764828` / `0x7bf6b15c`
- Сигнатура: `payments.paymentFormStars(flags:#, form_id:long, bot_id:long, title:string, description:string, photo:flags.5?WebDocument, invoice:Invoice, users:Vector) => payments.PaymentForm`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.paymentFormStars
- Поля:
  - `flags`: `#` - служебное поле flags
  - `form_id`: `long`
  - `bot_id`: `long`
  - `title`: `string`
  - `description`: `string`
  - `photo`: `flags.5?WebDocument` - optional через flags.5
  - `invoice`: `Invoice`
  - `users`: `Vector`

## `payments.PaymentReceipt`

- Официальный тип: https://core.telegram.org/type/payments.PaymentReceipt
- Количество constructors: **2**

### `payments.paymentReceipt`

- ID: `1891958275` / `0x70c4fe03`
- Сигнатура: `payments.paymentReceipt(flags:#, date:int, bot_id:long, provider_id:long, title:string, description:string, photo:flags.2?WebDocument, invoice:Invoice, info:flags.0?PaymentRequestedInfo, shipping:flags.1?ShippingOption, tip_amount:flags.3?long, currency:string, total_amount:long, credentials_title:string, users:Vector) => payments.PaymentReceipt`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.paymentReceipt
- Поля:
  - `flags`: `#` - служебное поле flags
  - `date`: `int`
  - `bot_id`: `long`
  - `provider_id`: `long`
  - `title`: `string`
  - `description`: `string`
  - `photo`: `flags.2?WebDocument` - optional через flags.2
  - `invoice`: `Invoice`
  - `info`: `flags.0?PaymentRequestedInfo` - optional через flags.0
  - `shipping`: `flags.1?ShippingOption` - optional через flags.1
  - `tip_amount`: `flags.3?long` - optional через flags.3
  - `currency`: `string`
  - `total_amount`: `long`
  - `credentials_title`: `string`
  - `users`: `Vector`

### `payments.paymentReceiptStars`

- ID: `-625215430` / `0xdabbf83a`
- Сигнатура: `payments.paymentReceiptStars(flags:#, date:int, bot_id:long, title:string, description:string, photo:flags.2?WebDocument, invoice:Invoice, currency:string, total_amount:long, transaction_id:string, users:Vector) => payments.PaymentReceipt`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.paymentReceiptStars
- Поля:
  - `flags`: `#` - служебное поле flags
  - `date`: `int`
  - `bot_id`: `long`
  - `title`: `string`
  - `description`: `string`
  - `photo`: `flags.2?WebDocument` - optional через flags.2
  - `invoice`: `Invoice`
  - `currency`: `string`
  - `total_amount`: `long`
  - `transaction_id`: `string`
  - `users`: `Vector`

## `payments.PaymentResult`

- Официальный тип: https://core.telegram.org/type/payments.PaymentResult
- Количество constructors: **2**

### `payments.paymentResult`

- ID: `1314881805` / `0x4e5f810d`
- Сигнатура: `payments.paymentResult(updates:Updates) => payments.PaymentResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.paymentResult
- Поля:
  - `updates`: `Updates`

### `payments.paymentVerificationNeeded`

- ID: `-666824391` / `0xd8411139`
- Сигнатура: `payments.paymentVerificationNeeded(url:string) => payments.PaymentResult`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.paymentVerificationNeeded
- Поля:
  - `url`: `string`

## `payments.ResaleStarGifts`

- Официальный тип: https://core.telegram.org/type/payments.ResaleStarGifts
- Количество constructors: **1**

### `payments.resaleStarGifts`

- ID: `-1803939105` / `0x947a12df`
- Сигнатура: `payments.resaleStarGifts(flags:#, count:int, gifts:Vector, next_offset:flags.0?string, attributes:flags.1?Vector, attributes_hash:flags.1?long, chats:Vector, counters:flags.2?Vector, users:Vector) => payments.ResaleStarGifts`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.resaleStarGifts
- Поля:
  - `flags`: `#` - служебное поле flags
  - `count`: `int`
  - `gifts`: `Vector`
  - `next_offset`: `flags.0?string` - optional через flags.0
  - `attributes`: `flags.1?Vector` - optional через flags.1
  - `attributes_hash`: `flags.1?long` - optional через flags.1
  - `chats`: `Vector`
  - `counters`: `flags.2?Vector` - optional через flags.2
  - `users`: `Vector`

## `payments.SavedInfo`

- Официальный тип: https://core.telegram.org/type/payments.SavedInfo
- Количество constructors: **1**

### `payments.savedInfo`

- ID: `-74456004` / `0xfb8fe43c`
- Сигнатура: `payments.savedInfo(flags:#, has_saved_credentials:flags.1?true, saved_info:flags.0?PaymentRequestedInfo) => payments.SavedInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.savedInfo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `has_saved_credentials`: `flags.1?true` - optional через flags.1
  - `saved_info`: `flags.0?PaymentRequestedInfo` - optional через flags.0

## `payments.SavedStarGifts`

- Официальный тип: https://core.telegram.org/type/payments.SavedStarGifts
- Количество constructors: **1**

### `payments.savedStarGifts`

- ID: `-1779201615` / `0x95f389b1`
- Сигнатура: `payments.savedStarGifts(flags:#, count:int, chat_notifications_enabled:flags.1?Bool, gifts:Vector, next_offset:flags.0?string, chats:Vector, users:Vector) => payments.SavedStarGifts`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.savedStarGifts
- Поля:
  - `flags`: `#` - служебное поле flags
  - `count`: `int`
  - `chat_notifications_enabled`: `flags.1?Bool` - optional через flags.1
  - `gifts`: `Vector`
  - `next_offset`: `flags.0?string` - optional через flags.0
  - `chats`: `Vector`
  - `users`: `Vector`

## `payments.StarGiftCollections`

- Официальный тип: https://core.telegram.org/type/payments.StarGiftCollections
- Количество constructors: **2**

### `payments.starGiftCollections`

- ID: `-1977011469` / `0x8a2932f3`
- Сигнатура: `payments.starGiftCollections(collections:Vector) => payments.StarGiftCollections`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.starGiftCollections
- Поля:
  - `collections`: `Vector`

### `payments.starGiftCollectionsNotModified`

- ID: `-1598402793` / `0xa0ba4f17`
- Сигнатура: `payments.starGiftCollectionsNotModified() => payments.StarGiftCollections`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.starGiftCollectionsNotModified
- Поля:
  - Нет полей.

## `payments.StarGiftUpgradePreview`

- Официальный тип: https://core.telegram.org/type/payments.StarGiftUpgradePreview
- Количество constructors: **1**

### `payments.starGiftUpgradePreview`

- ID: `377215243` / `0x167bd90b`
- Сигнатура: `payments.starGiftUpgradePreview(sample_attributes:Vector) => payments.StarGiftUpgradePreview`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.starGiftUpgradePreview
- Поля:
  - `sample_attributes`: `Vector`

## `payments.StarGiftWithdrawalUrl`

- Официальный тип: https://core.telegram.org/type/payments.StarGiftWithdrawalUrl
- Количество constructors: **1**

### `payments.starGiftWithdrawalUrl`

- ID: `-2069218660` / `0x84aa3a9c`
- Сигнатура: `payments.starGiftWithdrawalUrl(url:string) => payments.StarGiftWithdrawalUrl`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.starGiftWithdrawalUrl
- Поля:
  - `url`: `string`

## `payments.StarGifts`

- Официальный тип: https://core.telegram.org/type/payments.StarGifts
- Количество constructors: **2**

### `payments.starGifts`

- ID: `785918357` / `0x2ed82995`
- Сигнатура: `payments.starGifts(hash:int, gifts:Vector, chats:Vector, users:Vector) => payments.StarGifts`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.starGifts
- Поля:
  - `hash`: `int`
  - `gifts`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `payments.starGiftsNotModified`

- ID: `-1551326360` / `0xa388a368`
- Сигнатура: `payments.starGiftsNotModified() => payments.StarGifts`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.starGiftsNotModified
- Поля:
  - Нет полей.

## `payments.StarsRevenueAdsAccountUrl`

- Официальный тип: https://core.telegram.org/type/payments.StarsRevenueAdsAccountUrl
- Количество constructors: **1**

### `payments.starsRevenueAdsAccountUrl`

- ID: `961445665` / `0x394e7f21`
- Сигнатура: `payments.starsRevenueAdsAccountUrl(url:string) => payments.StarsRevenueAdsAccountUrl`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.starsRevenueAdsAccountUrl
- Поля:
  - `url`: `string`

## `payments.StarsRevenueStats`

- Официальный тип: https://core.telegram.org/type/payments.StarsRevenueStats
- Количество constructors: **1**

### `payments.starsRevenueStats`

- ID: `1814066038` / `0x6c207376`
- Сигнатура: `payments.starsRevenueStats(flags:#, top_hours_graph:flags.0?StatsGraph, revenue_graph:StatsGraph, status:StarsRevenueStatus, usd_rate:double) => payments.StarsRevenueStats`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.starsRevenueStats
- Поля:
  - `flags`: `#` - служебное поле flags
  - `top_hours_graph`: `flags.0?StatsGraph` - optional через flags.0
  - `revenue_graph`: `StatsGraph`
  - `status`: `StarsRevenueStatus`
  - `usd_rate`: `double`

## `payments.StarsRevenueWithdrawalUrl`

- Официальный тип: https://core.telegram.org/type/payments.StarsRevenueWithdrawalUrl
- Количество constructors: **1**

### `payments.starsRevenueWithdrawalUrl`

- ID: `497778871` / `0x1dab80b7`
- Сигнатура: `payments.starsRevenueWithdrawalUrl(url:string) => payments.StarsRevenueWithdrawalUrl`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.starsRevenueWithdrawalUrl
- Поля:
  - `url`: `string`

## `payments.StarsStatus`

- Официальный тип: https://core.telegram.org/type/payments.StarsStatus
- Количество constructors: **1**

### `payments.starsStatus`

- ID: `1822222573` / `0x6c9ce8ed`
- Сигнатура: `payments.starsStatus(flags:#, balance:StarsAmount, subscriptions:flags.1?Vector, subscriptions_next_offset:flags.2?string, subscriptions_missing_balance:flags.4?long, history:flags.3?Vector, next_offset:flags.0?string, chats:Vector, users:Vector) => payments.StarsStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.starsStatus
- Поля:
  - `flags`: `#` - служебное поле flags
  - `balance`: `StarsAmount`
  - `subscriptions`: `flags.1?Vector` - optional через flags.1
  - `subscriptions_next_offset`: `flags.2?string` - optional через flags.2
  - `subscriptions_missing_balance`: `flags.4?long` - optional через flags.4
  - `history`: `flags.3?Vector` - optional через flags.3
  - `next_offset`: `flags.0?string` - optional через flags.0
  - `chats`: `Vector`
  - `users`: `Vector`

## `payments.SuggestedStarRefBots`

- Официальный тип: https://core.telegram.org/type/payments.SuggestedStarRefBots
- Количество constructors: **1**

### `payments.suggestedStarRefBots`

- ID: `-1261053863` / `0xb4d5d859`
- Сигнатура: `payments.suggestedStarRefBots(flags:#, count:int, suggested_bots:Vector, users:Vector, next_offset:flags.0?string) => payments.SuggestedStarRefBots`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.suggestedStarRefBots
- Поля:
  - `flags`: `#` - служебное поле flags
  - `count`: `int`
  - `suggested_bots`: `Vector`
  - `users`: `Vector`
  - `next_offset`: `flags.0?string` - optional через flags.0

## `payments.UniqueStarGift`

- Официальный тип: https://core.telegram.org/type/payments.UniqueStarGift
- Количество constructors: **1**

### `payments.uniqueStarGift`

- ID: `1097619176` / `0x416c56e8`
- Сигнатура: `payments.uniqueStarGift(gift:StarGift, chats:Vector, users:Vector) => payments.UniqueStarGift`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.uniqueStarGift
- Поля:
  - `gift`: `StarGift`
  - `chats`: `Vector`
  - `users`: `Vector`

## `payments.UniqueStarGiftValueInfo`

- Официальный тип: https://core.telegram.org/type/payments.UniqueStarGiftValueInfo
- Количество constructors: **1**

### `payments.uniqueStarGiftValueInfo`

- ID: `1362093126` / `0x512fe446`
- Сигнатура: `payments.uniqueStarGiftValueInfo(flags:#, last_sale_on_fragment:flags.1?true, value_is_average:flags.6?true, currency:string, value:long, initial_sale_date:int, initial_sale_stars:long, initial_sale_price:long, last_sale_date:flags.0?int, last_sale_price:flags.0?long, floor_price:flags.2?long, average_price:flags.3?long, listed_count:flags.4?int, fragment_listed_count:flags.5?int, fragment_listed_url:flags.5?string) => payments.UniqueStarGiftValueInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.uniqueStarGiftValueInfo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `last_sale_on_fragment`: `flags.1?true` - optional через flags.1
  - `value_is_average`: `flags.6?true` - optional через flags.6
  - `currency`: `string`
  - `value`: `long`
  - `initial_sale_date`: `int`
  - `initial_sale_stars`: `long`
  - `initial_sale_price`: `long`
  - `last_sale_date`: `flags.0?int` - optional через flags.0
  - `last_sale_price`: `flags.0?long` - optional через flags.0
  - `floor_price`: `flags.2?long` - optional через flags.2
  - `average_price`: `flags.3?long` - optional через flags.3
  - `listed_count`: `flags.4?int` - optional через flags.4
  - `fragment_listed_count`: `flags.5?int` - optional через flags.5
  - `fragment_listed_url`: `flags.5?string` - optional через flags.5

## `payments.ValidatedRequestedInfo`

- Официальный тип: https://core.telegram.org/type/payments.ValidatedRequestedInfo
- Количество constructors: **1**

### `payments.validatedRequestedInfo`

- ID: `-784000893` / `0xd1451883`
- Сигнатура: `payments.validatedRequestedInfo(flags:#, id:flags.0?string, shipping_options:flags.1?Vector) => payments.ValidatedRequestedInfo`
- Официальная страница конструктора: https://core.telegram.org/constructor/payments.validatedRequestedInfo
- Поля:
  - `flags`: `#` - служебное поле flags
  - `id`: `flags.0?string` - optional через flags.0
  - `shipping_options`: `flags.1?Vector` - optional через flags.1

## `phone.ExportedGroupCallInvite`

- Официальный тип: https://core.telegram.org/type/phone.ExportedGroupCallInvite
- Количество constructors: **1**

### `phone.exportedGroupCallInvite`

- ID: `541839704` / `0x204bd158`
- Сигнатура: `phone.exportedGroupCallInvite(link:string) => phone.ExportedGroupCallInvite`
- Официальная страница конструктора: https://core.telegram.org/constructor/phone.exportedGroupCallInvite
- Поля:
  - `link`: `string`

## `phone.GroupCall`

- Официальный тип: https://core.telegram.org/type/phone.GroupCall
- Количество constructors: **1**

### `phone.groupCall`

- ID: `-1636664659` / `0x9e727aad`
- Сигнатура: `phone.groupCall(call:GroupCall, participants:Vector, participants_next_offset:string, chats:Vector, users:Vector) => phone.GroupCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/phone.groupCall
- Поля:
  - `call`: `GroupCall`
  - `participants`: `Vector`
  - `participants_next_offset`: `string`
  - `chats`: `Vector`
  - `users`: `Vector`

## `phone.GroupCallStreamChannels`

- Официальный тип: https://core.telegram.org/type/phone.GroupCallStreamChannels
- Количество constructors: **1**

### `phone.groupCallStreamChannels`

- ID: `-790330702` / `0xd0e482b2`
- Сигнатура: `phone.groupCallStreamChannels(channels:Vector) => phone.GroupCallStreamChannels`
- Официальная страница конструктора: https://core.telegram.org/constructor/phone.groupCallStreamChannels
- Поля:
  - `channels`: `Vector`

## `phone.GroupCallStreamRtmpUrl`

- Официальный тип: https://core.telegram.org/type/phone.GroupCallStreamRtmpUrl
- Количество constructors: **1**

### `phone.groupCallStreamRtmpUrl`

- ID: `767505458` / `0x2dbf3432`
- Сигнатура: `phone.groupCallStreamRtmpUrl(url:string, key:string) => phone.GroupCallStreamRtmpUrl`
- Официальная страница конструктора: https://core.telegram.org/constructor/phone.groupCallStreamRtmpUrl
- Поля:
  - `url`: `string`
  - `key`: `string`

## `phone.GroupParticipants`

- Официальный тип: https://core.telegram.org/type/phone.GroupParticipants
- Количество constructors: **1**

### `phone.groupParticipants`

- ID: `-193506890` / `0xf47751b6`
- Сигнатура: `phone.groupParticipants(count:int, participants:Vector, next_offset:string, chats:Vector, users:Vector, version:int) => phone.GroupParticipants`
- Официальная страница конструктора: https://core.telegram.org/constructor/phone.groupParticipants
- Поля:
  - `count`: `int`
  - `participants`: `Vector`
  - `next_offset`: `string`
  - `chats`: `Vector`
  - `users`: `Vector`
  - `version`: `int`

## `phone.JoinAsPeers`

- Официальный тип: https://core.telegram.org/type/phone.JoinAsPeers
- Количество constructors: **1**

### `phone.joinAsPeers`

- ID: `-1343921601` / `0xafe5623f`
- Сигнатура: `phone.joinAsPeers(peers:Vector, chats:Vector, users:Vector) => phone.JoinAsPeers`
- Официальная страница конструктора: https://core.telegram.org/constructor/phone.joinAsPeers
- Поля:
  - `peers`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `phone.PhoneCall`

- Официальный тип: https://core.telegram.org/type/phone.PhoneCall
- Количество constructors: **1**

### `phone.phoneCall`

- ID: `-326966976` / `0xec82e140`
- Сигнатура: `phone.phoneCall(phone_call:PhoneCall, users:Vector) => phone.PhoneCall`
- Официальная страница конструктора: https://core.telegram.org/constructor/phone.phoneCall
- Поля:
  - `phone_call`: `PhoneCall`
  - `users`: `Vector`

## `photos.Photo`

- Официальный тип: https://core.telegram.org/type/photos.Photo
- Количество constructors: **1**

### `photos.photo`

- ID: `539045032` / `0x20212ca8`
- Сигнатура: `photos.photo(photo:Photo, users:Vector) => photos.Photo`
- Официальная страница конструктора: https://core.telegram.org/constructor/photos.photo
- Поля:
  - `photo`: `Photo`
  - `users`: `Vector`

## `photos.Photos`

- Официальный тип: https://core.telegram.org/type/photos.Photos
- Количество constructors: **2**

### `photos.photos`

- ID: `-1916114267` / `0x8dca6aa5`
- Сигнатура: `photos.photos(photos:Vector, users:Vector) => photos.Photos`
- Официальная страница конструктора: https://core.telegram.org/constructor/photos.photos
- Поля:
  - `photos`: `Vector`
  - `users`: `Vector`

### `photos.photosSlice`

- ID: `352657236` / `0x15051f54`
- Сигнатура: `photos.photosSlice(count:int, photos:Vector, users:Vector) => photos.Photos`
- Официальная страница конструктора: https://core.telegram.org/constructor/photos.photosSlice
- Поля:
  - `count`: `int`
  - `photos`: `Vector`
  - `users`: `Vector`

## `premium.BoostsList`

- Официальный тип: https://core.telegram.org/type/premium.BoostsList
- Количество constructors: **1**

### `premium.boostsList`

- ID: `-2030542532` / `0x86f8613c`
- Сигнатура: `premium.boostsList(flags:#, count:int, boosts:Vector, next_offset:flags.0?string, users:Vector) => premium.BoostsList`
- Официальная страница конструктора: https://core.telegram.org/constructor/premium.boostsList
- Поля:
  - `flags`: `#` - служебное поле flags
  - `count`: `int`
  - `boosts`: `Vector`
  - `next_offset`: `flags.0?string` - optional через flags.0
  - `users`: `Vector`

## `premium.BoostsStatus`

- Официальный тип: https://core.telegram.org/type/premium.BoostsStatus
- Количество constructors: **1**

### `premium.boostsStatus`

- ID: `1230586490` / `0x4959427a`
- Сигнатура: `premium.boostsStatus(flags:#, my_boost:flags.2?true, level:int, current_level_boosts:int, boosts:int, gift_boosts:flags.4?int, next_level_boosts:flags.0?int, premium_audience:flags.1?StatsPercentValue, boost_url:string, prepaid_giveaways:flags.3?Vector, my_boost_slots:flags.2?Vector) => premium.BoostsStatus`
- Официальная страница конструктора: https://core.telegram.org/constructor/premium.boostsStatus
- Поля:
  - `flags`: `#` - служебное поле flags
  - `my_boost`: `flags.2?true` - optional через flags.2
  - `level`: `int`
  - `current_level_boosts`: `int`
  - `boosts`: `int`
  - `gift_boosts`: `flags.4?int` - optional через flags.4
  - `next_level_boosts`: `flags.0?int` - optional через flags.0
  - `premium_audience`: `flags.1?StatsPercentValue` - optional через flags.1
  - `boost_url`: `string`
  - `prepaid_giveaways`: `flags.3?Vector` - optional через flags.3
  - `my_boost_slots`: `flags.2?Vector` - optional через flags.2

## `premium.MyBoosts`

- Официальный тип: https://core.telegram.org/type/premium.MyBoosts
- Количество constructors: **1**

### `premium.myBoosts`

- ID: `-1696454430` / `0x9ae228e2`
- Сигнатура: `premium.myBoosts(my_boosts:Vector, chats:Vector, users:Vector) => premium.MyBoosts`
- Официальная страница конструктора: https://core.telegram.org/constructor/premium.myBoosts
- Поля:
  - `my_boosts`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `smsjobs.EligibilityToJoin`

- Официальный тип: https://core.telegram.org/type/smsjobs.EligibilityToJoin
- Количество constructors: **1**

### `smsjobs.eligibleToJoin`

- ID: `-594852657` / `0xdc8b44cf`
- Сигнатура: `smsjobs.eligibleToJoin(terms_url:string, monthly_sent_sms:int) => smsjobs.EligibilityToJoin`
- Официальная страница конструктора: https://core.telegram.org/constructor/smsjobs.eligibleToJoin
- Поля:
  - `terms_url`: `string`
  - `monthly_sent_sms`: `int`

## `smsjobs.Status`

- Официальный тип: https://core.telegram.org/type/smsjobs.Status
- Количество constructors: **1**

### `smsjobs.status`

- ID: `720277905` / `0x2aee9191`
- Сигнатура: `smsjobs.status(flags:#, allow_international:flags.0?true, recent_sent:int, recent_since:int, recent_remains:int, total_sent:int, total_since:int, last_gift_slug:flags.1?string, terms_url:string) => smsjobs.Status`
- Официальная страница конструктора: https://core.telegram.org/constructor/smsjobs.status
- Поля:
  - `flags`: `#` - служебное поле flags
  - `allow_international`: `flags.0?true` - optional через flags.0
  - `recent_sent`: `int`
  - `recent_since`: `int`
  - `recent_remains`: `int`
  - `total_sent`: `int`
  - `total_since`: `int`
  - `last_gift_slug`: `flags.1?string` - optional через flags.1
  - `terms_url`: `string`

## `stats.BroadcastStats`

- Официальный тип: https://core.telegram.org/type/stats.BroadcastStats
- Количество constructors: **1**

### `stats.broadcastStats`

- ID: `963421692` / `0x396ca5fc`
- Сигнатура: `stats.broadcastStats(period:StatsDateRangeDays, followers:StatsAbsValueAndPrev, views_per_post:StatsAbsValueAndPrev, shares_per_post:StatsAbsValueAndPrev, reactions_per_post:StatsAbsValueAndPrev, views_per_story:StatsAbsValueAndPrev, shares_per_story:StatsAbsValueAndPrev, reactions_per_story:StatsAbsValueAndPrev, enabled_notifications:StatsPercentValue, growth_graph:StatsGraph, followers_graph:StatsGraph, mute_graph:StatsGraph, top_hours_graph:StatsGraph, interactions_graph:StatsGraph, iv_interactions_graph:StatsGraph, views_by_source_graph:StatsGraph, new_followers_by_source_graph:StatsGraph, languages_graph:StatsGraph, reactions_by_emotion_graph:StatsGraph, story_interactions_graph:StatsGraph, story_reactions_by_emotion_graph:StatsGraph, recent_posts_interactions:Vector) => stats.BroadcastStats`
- Официальная страница конструктора: https://core.telegram.org/constructor/stats.broadcastStats
- Поля:
  - `period`: `StatsDateRangeDays`
  - `followers`: `StatsAbsValueAndPrev`
  - `views_per_post`: `StatsAbsValueAndPrev`
  - `shares_per_post`: `StatsAbsValueAndPrev`
  - `reactions_per_post`: `StatsAbsValueAndPrev`
  - `views_per_story`: `StatsAbsValueAndPrev`
  - `shares_per_story`: `StatsAbsValueAndPrev`
  - `reactions_per_story`: `StatsAbsValueAndPrev`
  - `enabled_notifications`: `StatsPercentValue`
  - `growth_graph`: `StatsGraph`
  - `followers_graph`: `StatsGraph`
  - `mute_graph`: `StatsGraph`
  - `top_hours_graph`: `StatsGraph`
  - `interactions_graph`: `StatsGraph`
  - `iv_interactions_graph`: `StatsGraph`
  - `views_by_source_graph`: `StatsGraph`
  - `new_followers_by_source_graph`: `StatsGraph`
  - `languages_graph`: `StatsGraph`
  - `reactions_by_emotion_graph`: `StatsGraph`
  - `story_interactions_graph`: `StatsGraph`
  - `story_reactions_by_emotion_graph`: `StatsGraph`
  - `recent_posts_interactions`: `Vector`

## `stats.MegagroupStats`

- Официальный тип: https://core.telegram.org/type/stats.MegagroupStats
- Количество constructors: **1**

### `stats.megagroupStats`

- ID: `-276825834` / `0xef7ff916`
- Сигнатура: `stats.megagroupStats(period:StatsDateRangeDays, members:StatsAbsValueAndPrev, messages:StatsAbsValueAndPrev, viewers:StatsAbsValueAndPrev, posters:StatsAbsValueAndPrev, growth_graph:StatsGraph, members_graph:StatsGraph, new_members_by_source_graph:StatsGraph, languages_graph:StatsGraph, messages_graph:StatsGraph, actions_graph:StatsGraph, top_hours_graph:StatsGraph, weekdays_graph:StatsGraph, top_posters:Vector, top_admins:Vector, top_inviters:Vector, users:Vector) => stats.MegagroupStats`
- Официальная страница конструктора: https://core.telegram.org/constructor/stats.megagroupStats
- Поля:
  - `period`: `StatsDateRangeDays`
  - `members`: `StatsAbsValueAndPrev`
  - `messages`: `StatsAbsValueAndPrev`
  - `viewers`: `StatsAbsValueAndPrev`
  - `posters`: `StatsAbsValueAndPrev`
  - `growth_graph`: `StatsGraph`
  - `members_graph`: `StatsGraph`
  - `new_members_by_source_graph`: `StatsGraph`
  - `languages_graph`: `StatsGraph`
  - `messages_graph`: `StatsGraph`
  - `actions_graph`: `StatsGraph`
  - `top_hours_graph`: `StatsGraph`
  - `weekdays_graph`: `StatsGraph`
  - `top_posters`: `Vector`
  - `top_admins`: `Vector`
  - `top_inviters`: `Vector`
  - `users`: `Vector`

## `stats.MessageStats`

- Официальный тип: https://core.telegram.org/type/stats.MessageStats
- Количество constructors: **1**

### `stats.messageStats`

- ID: `2145983508` / `0x7fe91c14`
- Сигнатура: `stats.messageStats(views_graph:StatsGraph, reactions_by_emotion_graph:StatsGraph) => stats.MessageStats`
- Официальная страница конструктора: https://core.telegram.org/constructor/stats.messageStats
- Поля:
  - `views_graph`: `StatsGraph`
  - `reactions_by_emotion_graph`: `StatsGraph`

## `stats.PublicForwards`

- Официальный тип: https://core.telegram.org/type/stats.PublicForwards
- Количество constructors: **1**

### `stats.publicForwards`

- ID: `-1828487648` / `0x93037e20`
- Сигнатура: `stats.publicForwards(flags:#, count:int, forwards:Vector, next_offset:flags.0?string, chats:Vector, users:Vector) => stats.PublicForwards`
- Официальная страница конструктора: https://core.telegram.org/constructor/stats.publicForwards
- Поля:
  - `flags`: `#` - служебное поле flags
  - `count`: `int`
  - `forwards`: `Vector`
  - `next_offset`: `flags.0?string` - optional через flags.0
  - `chats`: `Vector`
  - `users`: `Vector`

## `stats.StoryStats`

- Официальный тип: https://core.telegram.org/type/stats.StoryStats
- Количество constructors: **1**

### `stats.storyStats`

- ID: `1355613820` / `0x50cd067c`
- Сигнатура: `stats.storyStats(views_graph:StatsGraph, reactions_by_emotion_graph:StatsGraph) => stats.StoryStats`
- Официальная страница конструктора: https://core.telegram.org/constructor/stats.storyStats
- Поля:
  - `views_graph`: `StatsGraph`
  - `reactions_by_emotion_graph`: `StatsGraph`

## `stickers.SuggestedShortName`

- Официальный тип: https://core.telegram.org/type/stickers.SuggestedShortName
- Количество constructors: **1**

### `stickers.suggestedShortName`

- ID: `-2046910401` / `0x85fea03f`
- Сигнатура: `stickers.suggestedShortName(short_name:string) => stickers.SuggestedShortName`
- Официальная страница конструктора: https://core.telegram.org/constructor/stickers.suggestedShortName
- Поля:
  - `short_name`: `string`

## `storage.FileType`

- Официальный тип: https://core.telegram.org/type/storage.FileType
- Количество constructors: **10**

### `storage.fileGif`

- ID: `-891180321` / `0xcae1aadf`
- Сигнатура: `storage.fileGif() => storage.FileType`
- Официальная страница конструктора: https://core.telegram.org/constructor/storage.fileGif
- Поля:
  - Нет полей.

### `storage.fileJpeg`

- ID: `8322574` / `0x007efe0e`
- Сигнатура: `storage.fileJpeg() => storage.FileType`
- Официальная страница конструктора: https://core.telegram.org/constructor/storage.fileJpeg
- Поля:
  - Нет полей.

### `storage.fileMov`

- ID: `1258941372` / `0x4b09ebbc`
- Сигнатура: `storage.fileMov() => storage.FileType`
- Официальная страница конструктора: https://core.telegram.org/constructor/storage.fileMov
- Поля:
  - Нет полей.

### `storage.fileMp3`

- ID: `1384777335` / `0x528a0677`
- Сигнатура: `storage.fileMp3() => storage.FileType`
- Официальная страница конструктора: https://core.telegram.org/constructor/storage.fileMp3
- Поля:
  - Нет полей.

### `storage.fileMp4`

- ID: `-1278304028` / `0xb3cea0e4`
- Сигнатура: `storage.fileMp4() => storage.FileType`
- Официальная страница конструктора: https://core.telegram.org/constructor/storage.fileMp4
- Поля:
  - Нет полей.

### `storage.filePartial`

- ID: `1086091090` / `0x40bc6f52`
- Сигнатура: `storage.filePartial() => storage.FileType`
- Официальная страница конструктора: https://core.telegram.org/constructor/storage.filePartial
- Поля:
  - Нет полей.

### `storage.filePdf`

- ID: `-1373745011` / `0xae1e508d`
- Сигнатура: `storage.filePdf() => storage.FileType`
- Официальная страница конструктора: https://core.telegram.org/constructor/storage.filePdf
- Поля:
  - Нет полей.

### `storage.filePng`

- ID: `172975040` / `0x0a4f63c0`
- Сигнатура: `storage.filePng() => storage.FileType`
- Официальная страница конструктора: https://core.telegram.org/constructor/storage.filePng
- Поля:
  - Нет полей.

### `storage.fileUnknown`

- ID: `-1432995067` / `0xaa963b05`
- Сигнатура: `storage.fileUnknown() => storage.FileType`
- Официальная страница конструктора: https://core.telegram.org/constructor/storage.fileUnknown
- Поля:
  - Нет полей.

### `storage.fileWebp`

- ID: `276907596` / `0x1081464c`
- Сигнатура: `storage.fileWebp() => storage.FileType`
- Официальная страница конструктора: https://core.telegram.org/constructor/storage.fileWebp
- Поля:
  - Нет полей.

## `stories.Albums`

- Официальный тип: https://core.telegram.org/type/stories.Albums
- Количество constructors: **2**

### `stories.albums`

- ID: `-1013417414` / `0xc3987a3a`
- Сигнатура: `stories.albums(hash:long, albums:Vector) => stories.Albums`
- Официальная страница конструктора: https://core.telegram.org/constructor/stories.albums
- Поля:
  - `hash`: `long`
  - `albums`: `Vector`

### `stories.albumsNotModified`

- ID: `1448008427` / `0x564edaeb`
- Сигнатура: `stories.albumsNotModified() => stories.Albums`
- Официальная страница конструктора: https://core.telegram.org/constructor/stories.albumsNotModified
- Поля:
  - Нет полей.

## `stories.AllStories`

- Официальный тип: https://core.telegram.org/type/stories.AllStories
- Количество constructors: **2**

### `stories.allStories`

- ID: `1862033025` / `0x6efc5e81`
- Сигнатура: `stories.allStories(flags:#, has_more:flags.0?true, count:int, state:string, peer_stories:Vector, chats:Vector, users:Vector, stealth_mode:StoriesStealthMode) => stories.AllStories`
- Официальная страница конструктора: https://core.telegram.org/constructor/stories.allStories
- Поля:
  - `flags`: `#` - служебное поле flags
  - `has_more`: `flags.0?true` - optional через flags.0
  - `count`: `int`
  - `state`: `string`
  - `peer_stories`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`
  - `stealth_mode`: `StoriesStealthMode`

### `stories.allStoriesNotModified`

- ID: `291044926` / `0x1158fe3e`
- Сигнатура: `stories.allStoriesNotModified(flags:#, state:string, stealth_mode:StoriesStealthMode) => stories.AllStories`
- Официальная страница конструктора: https://core.telegram.org/constructor/stories.allStoriesNotModified
- Поля:
  - `flags`: `#` - служебное поле flags
  - `state`: `string`
  - `stealth_mode`: `StoriesStealthMode`

## `stories.CanSendStoryCount`

- Официальный тип: https://core.telegram.org/type/stories.CanSendStoryCount
- Количество constructors: **1**

### `stories.canSendStoryCount`

- ID: `-1014513586` / `0xc387c04e`
- Сигнатура: `stories.canSendStoryCount(count_remains:int) => stories.CanSendStoryCount`
- Официальная страница конструктора: https://core.telegram.org/constructor/stories.canSendStoryCount
- Поля:
  - `count_remains`: `int`

## `stories.FoundStories`

- Официальный тип: https://core.telegram.org/type/stories.FoundStories
- Количество constructors: **1**

### `stories.foundStories`

- ID: `-488736969` / `0xe2de7737`
- Сигнатура: `stories.foundStories(flags:#, count:int, stories:Vector, next_offset:flags.0?string, chats:Vector, users:Vector) => stories.FoundStories`
- Официальная страница конструктора: https://core.telegram.org/constructor/stories.foundStories
- Поля:
  - `flags`: `#` - служебное поле flags
  - `count`: `int`
  - `stories`: `Vector`
  - `next_offset`: `flags.0?string` - optional через flags.0
  - `chats`: `Vector`
  - `users`: `Vector`

## `stories.PeerStories`

- Официальный тип: https://core.telegram.org/type/stories.PeerStories
- Количество constructors: **1**

### `stories.peerStories`

- ID: `-890861720` / `0xcae68768`
- Сигнатура: `stories.peerStories(stories:PeerStories, chats:Vector, users:Vector) => stories.PeerStories`
- Официальная страница конструктора: https://core.telegram.org/constructor/stories.peerStories
- Поля:
  - `stories`: `PeerStories`
  - `chats`: `Vector`
  - `users`: `Vector`

## `stories.Stories`

- Официальный тип: https://core.telegram.org/type/stories.Stories
- Количество constructors: **1**

### `stories.stories`

- ID: `1673780490` / `0x63c3dd0a`
- Сигнатура: `stories.stories(flags:#, count:int, stories:Vector, pinned_to_top:flags.0?Vector, chats:Vector, users:Vector) => stories.Stories`
- Официальная страница конструктора: https://core.telegram.org/constructor/stories.stories
- Поля:
  - `flags`: `#` - служебное поле flags
  - `count`: `int`
  - `stories`: `Vector`
  - `pinned_to_top`: `flags.0?Vector` - optional через flags.0
  - `chats`: `Vector`
  - `users`: `Vector`

## `stories.StoryReactionsList`

- Официальный тип: https://core.telegram.org/type/stories.StoryReactionsList
- Количество constructors: **1**

### `stories.storyReactionsList`

- ID: `-1436583780` / `0xaa5f789c`
- Сигнатура: `stories.storyReactionsList(flags:#, count:int, reactions:Vector, chats:Vector, users:Vector, next_offset:flags.0?string) => stories.StoryReactionsList`
- Официальная страница конструктора: https://core.telegram.org/constructor/stories.storyReactionsList
- Поля:
  - `flags`: `#` - служебное поле flags
  - `count`: `int`
  - `reactions`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`
  - `next_offset`: `flags.0?string` - optional через flags.0

## `stories.StoryViews`

- Официальный тип: https://core.telegram.org/type/stories.StoryViews
- Количество constructors: **1**

### `stories.storyViews`

- ID: `-560009955` / `0xde9eed1d`
- Сигнатура: `stories.storyViews(views:Vector, users:Vector) => stories.StoryViews`
- Официальная страница конструктора: https://core.telegram.org/constructor/stories.storyViews
- Поля:
  - `views`: `Vector`
  - `users`: `Vector`

## `stories.StoryViewsList`

- Официальный тип: https://core.telegram.org/type/stories.StoryViewsList
- Количество constructors: **1**

### `stories.storyViewsList`

- ID: `1507299269` / `0x59d78fc5`
- Сигнатура: `stories.storyViewsList(flags:#, count:int, views_count:int, forwards_count:int, reactions_count:int, views:Vector, chats:Vector, users:Vector, next_offset:flags.0?string) => stories.StoryViewsList`
- Официальная страница конструктора: https://core.telegram.org/constructor/stories.storyViewsList
- Поля:
  - `flags`: `#` - служебное поле flags
  - `count`: `int`
  - `views_count`: `int`
  - `forwards_count`: `int`
  - `reactions_count`: `int`
  - `views`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`
  - `next_offset`: `flags.0?string` - optional через flags.0

## `updates.ChannelDifference`

- Официальный тип: https://core.telegram.org/type/updates.ChannelDifference
- Количество constructors: **3**

### `updates.channelDifference`

- ID: `543450958` / `0x2064674e`
- Сигнатура: `updates.channelDifference(flags:#, final:flags.0?true, pts:int, timeout:flags.1?int, new_messages:Vector, other_updates:Vector, chats:Vector, users:Vector) => updates.ChannelDifference`
- Официальная страница конструктора: https://core.telegram.org/constructor/updates.channelDifference
- Поля:
  - `flags`: `#` - служебное поле flags
  - `final`: `flags.0?true` - optional через flags.0
  - `pts`: `int`
  - `timeout`: `flags.1?int` - optional через flags.1
  - `new_messages`: `Vector`
  - `other_updates`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

### `updates.channelDifferenceEmpty`

- ID: `1041346555` / `0x3e11affb`
- Сигнатура: `updates.channelDifferenceEmpty(flags:#, final:flags.0?true, pts:int, timeout:flags.1?int) => updates.ChannelDifference`
- Официальная страница конструктора: https://core.telegram.org/constructor/updates.channelDifferenceEmpty
- Поля:
  - `flags`: `#` - служебное поле flags
  - `final`: `flags.0?true` - optional через flags.0
  - `pts`: `int`
  - `timeout`: `flags.1?int` - optional через flags.1

### `updates.channelDifferenceTooLong`

- ID: `-1531132162` / `0xa4bcc6fe`
- Сигнатура: `updates.channelDifferenceTooLong(flags:#, final:flags.0?true, timeout:flags.1?int, dialog:Dialog, messages:Vector, chats:Vector, users:Vector) => updates.ChannelDifference`
- Официальная страница конструктора: https://core.telegram.org/constructor/updates.channelDifferenceTooLong
- Поля:
  - `flags`: `#` - служебное поле flags
  - `final`: `flags.0?true` - optional через flags.0
  - `timeout`: `flags.1?int` - optional через flags.1
  - `dialog`: `Dialog`
  - `messages`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`

## `updates.Difference`

- Официальный тип: https://core.telegram.org/type/updates.Difference
- Количество constructors: **4**

### `updates.difference`

- ID: `16030880` / `0x00f49ca0`
- Сигнатура: `updates.difference(new_messages:Vector, new_encrypted_messages:Vector, other_updates:Vector, chats:Vector, users:Vector, state:updates.State) => updates.Difference`
- Официальная страница конструктора: https://core.telegram.org/constructor/updates.difference
- Поля:
  - `new_messages`: `Vector`
  - `new_encrypted_messages`: `Vector`
  - `other_updates`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`
  - `state`: `updates.State`

### `updates.differenceEmpty`

- ID: `1567990072` / `0x5d75a138`
- Сигнатура: `updates.differenceEmpty(date:int, seq:int) => updates.Difference`
- Официальная страница конструктора: https://core.telegram.org/constructor/updates.differenceEmpty
- Поля:
  - `date`: `int`
  - `seq`: `int`

### `updates.differenceSlice`

- ID: `-1459938943` / `0xa8fb1981`
- Сигнатура: `updates.differenceSlice(new_messages:Vector, new_encrypted_messages:Vector, other_updates:Vector, chats:Vector, users:Vector, intermediate_state:updates.State) => updates.Difference`
- Официальная страница конструктора: https://core.telegram.org/constructor/updates.differenceSlice
- Поля:
  - `new_messages`: `Vector`
  - `new_encrypted_messages`: `Vector`
  - `other_updates`: `Vector`
  - `chats`: `Vector`
  - `users`: `Vector`
  - `intermediate_state`: `updates.State`

### `updates.differenceTooLong`

- ID: `1258196845` / `0x4afe8f6d`
- Сигнатура: `updates.differenceTooLong(pts:int) => updates.Difference`
- Официальная страница конструктора: https://core.telegram.org/constructor/updates.differenceTooLong
- Поля:
  - `pts`: `int`

## `updates.State`

- Официальный тип: https://core.telegram.org/type/updates.State
- Количество constructors: **1**

### `updates.state`

- ID: `-1519637954` / `0xa56c2a3e`
- Сигнатура: `updates.state(pts:int, qts:int, date:int, seq:int, unread_count:int) => updates.State`
- Официальная страница конструктора: https://core.telegram.org/constructor/updates.state
- Поля:
  - `pts`: `int`
  - `qts`: `int`
  - `date`: `int`
  - `seq`: `int`
  - `unread_count`: `int`

## `upload.CdnFile`

- Официальный тип: https://core.telegram.org/type/upload.CdnFile
- Количество constructors: **2**

### `upload.cdnFile`

- ID: `-1449145777` / `0xa99fca4f`
- Сигнатура: `upload.cdnFile(bytes:bytes) => upload.CdnFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/upload.cdnFile
- Поля:
  - `bytes`: `bytes`

### `upload.cdnFileReuploadNeeded`

- ID: `-290921362` / `0xeea8e46e`
- Сигнатура: `upload.cdnFileReuploadNeeded(request_token:bytes) => upload.CdnFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/upload.cdnFileReuploadNeeded
- Поля:
  - `request_token`: `bytes`

## `upload.File`

- Официальный тип: https://core.telegram.org/type/upload.File
- Количество constructors: **2**

### `upload.file`

- ID: `157948117` / `0x096a18d5`
- Сигнатура: `upload.file(type:storage.FileType, mtime:int, bytes:bytes) => upload.File`
- Официальная страница конструктора: https://core.telegram.org/constructor/upload.file
- Поля:
  - `type`: `storage.FileType`
  - `mtime`: `int`
  - `bytes`: `bytes`

### `upload.fileCdnRedirect`

- ID: `-242427324` / `0xf18cda44`
- Сигнатура: `upload.fileCdnRedirect(dc_id:int, file_token:bytes, encryption_key:bytes, encryption_iv:bytes, file_hashes:Vector) => upload.File`
- Официальная страница конструктора: https://core.telegram.org/constructor/upload.fileCdnRedirect
- Поля:
  - `dc_id`: `int`
  - `file_token`: `bytes`
  - `encryption_key`: `bytes`
  - `encryption_iv`: `bytes`
  - `file_hashes`: `Vector`

## `upload.WebFile`

- Официальный тип: https://core.telegram.org/type/upload.WebFile
- Количество constructors: **1**

### `upload.webFile`

- ID: `568808380` / `0x21e753bc`
- Сигнатура: `upload.webFile(size:int, mime_type:string, file_type:storage.FileType, mtime:int, bytes:bytes) => upload.WebFile`
- Официальная страница конструктора: https://core.telegram.org/constructor/upload.webFile
- Поля:
  - `size`: `int`
  - `mime_type`: `string`
  - `file_type`: `storage.FileType`
  - `mtime`: `int`
  - `bytes`: `bytes`

## `users.SavedMusic`

- Официальный тип: https://core.telegram.org/type/users.SavedMusic
- Количество constructors: **2**

### `users.savedMusic`

- ID: `883094167` / `0x34a2f297`
- Сигнатура: `users.savedMusic(count:int, documents:Vector) => users.SavedMusic`
- Официальная страница конструктора: https://core.telegram.org/constructor/users.savedMusic
- Поля:
  - `count`: `int`
  - `documents`: `Vector`

### `users.savedMusicNotModified`

- ID: `-477656412` / `0xe3878aa4`
- Сигнатура: `users.savedMusicNotModified(count:int) => users.SavedMusic`
- Официальная страница конструктора: https://core.telegram.org/constructor/users.savedMusicNotModified
- Поля:
  - `count`: `int`

## `users.UserFull`

- Официальный тип: https://core.telegram.org/type/users.UserFull
- Количество constructors: **1**

### `users.userFull`

- ID: `997004590` / `0x3b6d152e`
- Сигнатура: `users.userFull(full_user:UserFull, chats:Vector, users:Vector) => users.UserFull`
- Официальная страница конструктора: https://core.telegram.org/constructor/users.userFull
- Поля:
  - `full_user`: `UserFull`
  - `chats`: `Vector`
  - `users`: `Vector`

## `users.Users`

- Официальный тип: https://core.telegram.org/type/users.Users
- Количество constructors: **2**

### `users.users`

- ID: `1658259128` / `0x62d706b8`
- Сигнатура: `users.users(users:Vector) => users.Users`
- Официальная страница конструктора: https://core.telegram.org/constructor/users.users
- Поля:
  - `users`: `Vector`

### `users.usersSlice`

- ID: `828000628` / `0x315a4974`
- Сигнатура: `users.usersSlice(count:int, users:Vector) => users.Users`
- Официальная страница конструктора: https://core.telegram.org/constructor/users.usersSlice
- Поля:
  - `count`: `int`
  - `users`: `Vector`
