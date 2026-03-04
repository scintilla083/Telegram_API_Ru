# Telegram MTProto API — полная русская документация по методам

Источник структуры: официальный индекс Methods + официальный detailed schema JSON.

- Layer: **214**
- Методов: **727**
- Пространств имён методов: **23**

## Как читать сигнатуры

- Формат: `namespace.method(param:type, ...) -> ReturnType`.
- `#` = служебное поле flags.
- `flags.N?Type` = опциональное поле, включаемое битом `N` в наборе `flags`.
- `true` = флажок-признак без самостоятельного значения.
- `!X` / `X` = generic-тип в TL.
- В официальном structured JSON Telegram не всегда отдельно сохраняет тип элемента внутри `Vector`; для точной TL-строки используй ссылку на официальную страницу метода.

## Содержание

- [account](#account) - 119 методов
- [auth](#auth) - 23 методов
- [bots](#bots) - 30 методов
- [channels](#channels) - 66 методов
- [chatlists](#chatlists) - 11 методов
- [contacts](#contacts) - 27 методов
- [core](#core) - 11 методов
- [folders](#folders) - 1 методов
- [fragment](#fragment) - 1 методов
- [help](#help) - 25 методов
- [langpack](#langpack) - 5 методов
- [messages](#messages) - 230 методов
- [payments](#payments) - 57 методов
- [phone](#phone) - 37 методов
- [photos](#photos) - 5 методов
- [premium](#premium) - 5 методов
- [smsjobs](#smsjobs) - 7 методов
- [stats](#stats) - 7 методов
- [stickers](#stickers) - 11 методов
- [stories](#stories) - 32 методов
- [updates](#updates) - 3 методов
- [upload](#upload) - 8 методов
- [users](#users) - 6 методов

## account

### `account.acceptAuthorization`

- Кратко: Принять авторизацию/сессию.
- ID: `-202552205` / `0xf3ed4c73`
- Return type: `Bool`
- Сигнатура: `account.acceptAuthorization(bot_id:long, scope:string, public_key:string, value_hashes:Vector, credentials:SecureCredentialsEncrypted) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.acceptAuthorization
- Параметры:
  - `bot_id`: `long`
  - `scope`: `string`
  - `public_key`: `string`
  - `value_hashes`: `Vector`
  - `credentials`: `SecureCredentialsEncrypted`

### `account.cancelPasswordEmail`

- Кратко: Операция с cancel пароль email.
- ID: `-1043606090` / `0xc1cbd5b6`
- Return type: `Bool`
- Сигнатура: `account.cancelPasswordEmail() -> Bool`
- Официальная страница: https://core.telegram.org/method/account.cancelPasswordEmail
- Параметры:
  - Нет параметров.

### `account.changeAuthorizationSettings`

- Кратко: Операция с change авторизацию/сессию настройки.
- ID: `1089766498` / `0x40f48462`
- Return type: `Bool`
- Сигнатура: `account.changeAuthorizationSettings(flags:#, confirmed:flags.3?true, hash:long, encrypted_requests_disabled:flags.0?Bool, call_requests_disabled:flags.1?Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.changeAuthorizationSettings
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `confirmed`: `flags.3?true` - optional через flags.3
  - `hash`: `long`
  - `encrypted_requests_disabled`: `flags.0?Bool` - optional через flags.0
  - `call_requests_disabled`: `flags.1?Bool` - optional через flags.1

### `account.changePhone`

- Кратко: Операция с change телефон.
- ID: `1891839707` / `0x70c32edb`
- Return type: `User`
- Сигнатура: `account.changePhone(phone_number:string, phone_code_hash:string, phone_code:string) -> User`
- Официальная страница: https://core.telegram.org/method/account.changePhone
- Параметры:
  - `phone_number`: `string`
  - `phone_code_hash`: `string`
  - `phone_code`: `string`

### `account.checkUsername`

- Кратко: Проверить username.
- ID: `655677548` / `0x2714d86c`
- Return type: `Bool`
- Сигнатура: `account.checkUsername(username:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.checkUsername
- Параметры:
  - `username`: `string`

### `account.clearRecentEmojiStatuses`

- Кратко: Операция с clear недавние эмодзи статусы.
- ID: `404757166` / `0x18201aae`
- Return type: `Bool`
- Сигнатура: `account.clearRecentEmojiStatuses() -> Bool`
- Официальная страница: https://core.telegram.org/method/account.clearRecentEmojiStatuses
- Параметры:
  - Нет параметров.

### `account.confirmPasswordEmail`

- Кратко: Подтвердить пароль email.
- ID: `-1881204448` / `0x8fdf1920`
- Return type: `Bool`
- Сигнатура: `account.confirmPasswordEmail(code:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.confirmPasswordEmail
- Параметры:
  - `code`: `string`

### `account.confirmPhone`

- Кратко: Подтвердить телефон.
- ID: `1596029123` / `0x5f2178c3`
- Return type: `Bool`
- Сигнатура: `account.confirmPhone(phone_code_hash:string, phone_code:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.confirmPhone
- Параметры:
  - `phone_code_hash`: `string`
  - `phone_code`: `string`

### `account.createBusinessChatLink`

- Кратко: Создать бизнес чат ссылку.
- ID: `-2007898482` / `0x8851e68e`
- Return type: `BusinessChatLink`
- Сигнатура: `account.createBusinessChatLink(link:InputBusinessChatLink) -> BusinessChatLink`
- Официальная страница: https://core.telegram.org/method/account.createBusinessChatLink
- Параметры:
  - `link`: `InputBusinessChatLink`

### `account.createTheme`

- Кратко: Создать тему.
- ID: `1697530880` / `0x652e4400`
- Return type: `Theme`
- Сигнатура: `account.createTheme(flags:#, slug:string, title:string, document:flags.2?InputDocument, settings:flags.3?Vector) -> Theme`
- Официальная страница: https://core.telegram.org/method/account.createTheme
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `slug`: `string`
  - `title`: `string`
  - `document`: `flags.2?InputDocument` - optional через flags.2
  - `settings`: `flags.3?Vector` - optional через flags.3

### `account.declinePasswordReset`

- Кратко: Отклонить пароль reset.
- ID: `1284770294` / `0x4c9409f6`
- Return type: `Bool`
- Сигнатура: `account.declinePasswordReset() -> Bool`
- Официальная страница: https://core.telegram.org/method/account.declinePasswordReset
- Параметры:
  - Нет параметров.

### `account.deleteAccount`

- Кратко: Удалить account.
- ID: `-1564422284` / `0xa2c0cf74`
- Return type: `Bool`
- Сигнатура: `account.deleteAccount(flags:#, reason:string, password:flags.0?InputCheckPasswordSRP) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.deleteAccount
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `reason`: `string`
  - `password`: `flags.0?InputCheckPasswordSRP` - optional через flags.0

### `account.deleteAutoSaveExceptions`

- Кратко: Удалить auto save исключения.
- ID: `1404829728` / `0x53bc0020`
- Return type: `Bool`
- Сигнатура: `account.deleteAutoSaveExceptions() -> Bool`
- Официальная страница: https://core.telegram.org/method/account.deleteAutoSaveExceptions
- Параметры:
  - Нет параметров.

### `account.deleteBusinessChatLink`

- Кратко: Удалить бизнес чат ссылку.
- ID: `1611085428` / `0x60073674`
- Return type: `Bool`
- Сигнатура: `account.deleteBusinessChatLink(slug:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.deleteBusinessChatLink
- Параметры:
  - `slug`: `string`

### `account.deleteSecureValue`

- Кратко: Удалить secure value.
- ID: `-1199522741` / `0xb880bc4b`
- Return type: `Bool`
- Сигнатура: `account.deleteSecureValue(types:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.deleteSecureValue
- Параметры:
  - `types`: `Vector`

### `account.disablePeerConnectedBot`

- Кратко: Отключить peer/диалог подключённого бота.
- ID: `1581481689` / `0x5e437ed9`
- Return type: `Bool`
- Сигнатура: `account.disablePeerConnectedBot(peer:InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.disablePeerConnectedBot
- Параметры:
  - `peer`: `InputPeer`

### `account.editBusinessChatLink`

- Кратко: Изменить бизнес чат ссылку.
- ID: `-1942744913` / `0x8c3410af`
- Return type: `BusinessChatLink`
- Сигнатура: `account.editBusinessChatLink(slug:string, link:InputBusinessChatLink) -> BusinessChatLink`
- Официальная страница: https://core.telegram.org/method/account.editBusinessChatLink
- Параметры:
  - `slug`: `string`
  - `link`: `InputBusinessChatLink`

### `account.finishTakeoutSession`

- Кратко: Завершить takeout session.
- ID: `489050862` / `0x1d2652ee`
- Return type: `Bool`
- Сигнатура: `account.finishTakeoutSession(flags:#, success:flags.0?true) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.finishTakeoutSession
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `success`: `flags.0?true` - optional через flags.0

### `account.getAccountTTL`

- Кратко: Получить account TTL/срок жизни.
- ID: `150761757` / `0x08fc711d`
- Return type: `AccountDaysTTL`
- Сигнатура: `account.getAccountTTL() -> AccountDaysTTL`
- Официальная страница: https://core.telegram.org/method/account.getAccountTTL
- Параметры:
  - Нет параметров.

### `account.getAllSecureValues`

- Кратко: Получить все secure values.
- ID: `-1299661699` / `0xb288bc7d`
- Return type: `Vector`
- Сигнатура: `account.getAllSecureValues() -> Vector`
- Официальная страница: https://core.telegram.org/method/account.getAllSecureValues
- Параметры:
  - Нет параметров.

### `account.getAuthorizationForm`

- Кратко: Получить авторизацию/сессию form.
- ID: `-1456907910` / `0xa929597a`
- Return type: `account.AuthorizationForm`
- Сигнатура: `account.getAuthorizationForm(bot_id:long, scope:string, public_key:string) -> account.AuthorizationForm`
- Официальная страница: https://core.telegram.org/method/account.getAuthorizationForm
- Параметры:
  - `bot_id`: `long`
  - `scope`: `string`
  - `public_key`: `string`

### `account.getAuthorizations`

- Кратко: Получить авторизации/сессии.
- ID: `-484392616` / `0xe320c158`
- Return type: `account.Authorizations`
- Сигнатура: `account.getAuthorizations() -> account.Authorizations`
- Официальная страница: https://core.telegram.org/method/account.getAuthorizations
- Параметры:
  - Нет параметров.

### `account.getAutoDownloadSettings`

- Кратко: Получить auto download настройки.
- ID: `1457130303` / `0x56da0b3f`
- Return type: `account.AutoDownloadSettings`
- Сигнатура: `account.getAutoDownloadSettings() -> account.AutoDownloadSettings`
- Официальная страница: https://core.telegram.org/method/account.getAutoDownloadSettings
- Параметры:
  - Нет параметров.

### `account.getAutoSaveSettings`

- Кратко: Получить auto save настройки.
- ID: `-1379156774` / `0xadcbbcda`
- Return type: `account.AutoSaveSettings`
- Сигнатура: `account.getAutoSaveSettings() -> account.AutoSaveSettings`
- Официальная страница: https://core.telegram.org/method/account.getAutoSaveSettings
- Параметры:
  - Нет параметров.

### `account.getBotBusinessConnection`

- Кратко: Получить бота бизнес подключение.
- ID: `1990746736` / `0x76a86270`
- Return type: `Updates`
- Сигнатура: `account.getBotBusinessConnection(connection_id:string) -> Updates`
- Официальная страница: https://core.telegram.org/method/account.getBotBusinessConnection
- Параметры:
  - `connection_id`: `string`

### `account.getBusinessChatLinks`

- Кратко: Получить бизнес чат ссылки.
- ID: `1869667809` / `0x6f70dde1`
- Return type: `account.BusinessChatLinks`
- Сигнатура: `account.getBusinessChatLinks() -> account.BusinessChatLinks`
- Официальная страница: https://core.telegram.org/method/account.getBusinessChatLinks
- Параметры:
  - Нет параметров.

### `account.getChannelDefaultEmojiStatuses`

- Кратко: Получить канал default эмодзи статусы.
- ID: `1999087573` / `0x7727a7d5`
- Return type: `account.EmojiStatuses`
- Сигнатура: `account.getChannelDefaultEmojiStatuses(hash:long) -> account.EmojiStatuses`
- Официальная страница: https://core.telegram.org/method/account.getChannelDefaultEmojiStatuses
- Параметры:
  - `hash`: `long`

### `account.getChannelRestrictedStatusEmojis`

- Кратко: Получить канал restricted статус emojis.
- ID: `900325589` / `0x35a9e0d5`
- Return type: `EmojiList`
- Сигнатура: `account.getChannelRestrictedStatusEmojis(hash:long) -> EmojiList`
- Официальная страница: https://core.telegram.org/method/account.getChannelRestrictedStatusEmojis
- Параметры:
  - `hash`: `long`

### `account.getChatThemes`

- Кратко: Получить чат темы.
- ID: `-700916087` / `0xd638de89`
- Return type: `account.Themes`
- Сигнатура: `account.getChatThemes(hash:long) -> account.Themes`
- Официальная страница: https://core.telegram.org/method/account.getChatThemes
- Параметры:
  - `hash`: `long`

### `account.getCollectibleEmojiStatuses`

- Кратко: Получить коллекционный объект эмодзи статусы.
- ID: `779830595` / `0x2e7b4543`
- Return type: `account.EmojiStatuses`
- Сигнатура: `account.getCollectibleEmojiStatuses(hash:long) -> account.EmojiStatuses`
- Официальная страница: https://core.telegram.org/method/account.getCollectibleEmojiStatuses
- Параметры:
  - `hash`: `long`

### `account.getConnectedBots`

- Кратко: Получить подключённого ботов.
- ID: `1319421967` / `0x4ea4c80f`
- Return type: `account.ConnectedBots`
- Сигнатура: `account.getConnectedBots() -> account.ConnectedBots`
- Официальная страница: https://core.telegram.org/method/account.getConnectedBots
- Параметры:
  - Нет параметров.

### `account.getContactSignUpNotification`

- Кратко: Получить контакт sign up notification.
- ID: `-1626880216` / `0x9f07c728`
- Return type: `Bool`
- Сигнатура: `account.getContactSignUpNotification() -> Bool`
- Официальная страница: https://core.telegram.org/method/account.getContactSignUpNotification
- Параметры:
  - Нет параметров.

### `account.getContentSettings`

- Кратко: Получить контент настройки.
- ID: `-1952756306` / `0x8b9b4dae`
- Return type: `account.ContentSettings`
- Сигнатура: `account.getContentSettings() -> account.ContentSettings`
- Официальная страница: https://core.telegram.org/method/account.getContentSettings
- Параметры:
  - Нет параметров.

### `account.getDefaultBackgroundEmojis`

- Кратко: Получить default background emojis.
- ID: `-1509246514` / `0xa60ab9ce`
- Return type: `EmojiList`
- Сигнатура: `account.getDefaultBackgroundEmojis(hash:long) -> EmojiList`
- Официальная страница: https://core.telegram.org/method/account.getDefaultBackgroundEmojis
- Параметры:
  - `hash`: `long`

### `account.getDefaultEmojiStatuses`

- Кратко: Получить default эмодзи статусы.
- ID: `-696962170` / `0xd6753386`
- Return type: `account.EmojiStatuses`
- Сигнатура: `account.getDefaultEmojiStatuses(hash:long) -> account.EmojiStatuses`
- Официальная страница: https://core.telegram.org/method/account.getDefaultEmojiStatuses
- Параметры:
  - `hash`: `long`

### `account.getDefaultGroupPhotoEmojis`

- Кратко: Получить default группу фото emojis.
- ID: `-1856479058` / `0x915860ae`
- Return type: `EmojiList`
- Сигнатура: `account.getDefaultGroupPhotoEmojis(hash:long) -> EmojiList`
- Официальная страница: https://core.telegram.org/method/account.getDefaultGroupPhotoEmojis
- Параметры:
  - `hash`: `long`

### `account.getDefaultProfilePhotoEmojis`

- Кратко: Получить default профиль фото emojis.
- ID: `-495647960` / `0xe2750328`
- Return type: `EmojiList`
- Сигнатура: `account.getDefaultProfilePhotoEmojis(hash:long) -> EmojiList`
- Официальная страница: https://core.telegram.org/method/account.getDefaultProfilePhotoEmojis
- Параметры:
  - `hash`: `long`

### `account.getGlobalPrivacySettings`

- Кратко: Получить глобальные приватность настройки.
- ID: `-349483786` / `0xeb2b4cf6`
- Return type: `GlobalPrivacySettings`
- Сигнатура: `account.getGlobalPrivacySettings() -> GlobalPrivacySettings`
- Официальная страница: https://core.telegram.org/method/account.getGlobalPrivacySettings
- Параметры:
  - Нет параметров.

### `account.getMultiWallPapers`

- Кратко: Получить multi wall papers.
- ID: `1705865692` / `0x65ad71dc`
- Return type: `Vector`
- Сигнатура: `account.getMultiWallPapers(wallpapers:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/account.getMultiWallPapers
- Параметры:
  - `wallpapers`: `Vector`

### `account.getNotifyExceptions`

- Кратко: Получить уведомления исключения.
- ID: `1398240377` / `0x53577479`
- Return type: `Updates`
- Сигнатура: `account.getNotifyExceptions(flags:#, compare_sound:flags.1?true, compare_stories:flags.2?true, peer:flags.0?InputNotifyPeer) -> Updates`
- Официальная страница: https://core.telegram.org/method/account.getNotifyExceptions
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `compare_sound`: `flags.1?true` - optional через flags.1
  - `compare_stories`: `flags.2?true` - optional через flags.2
  - `peer`: `flags.0?InputNotifyPeer` - optional через flags.0

### `account.getNotifySettings`

- Кратко: Получить уведомления настройки.
- ID: `313765169` / `0x12b3ad31`
- Return type: `PeerNotifySettings`
- Сигнатура: `account.getNotifySettings(peer:InputNotifyPeer) -> PeerNotifySettings`
- Официальная страница: https://core.telegram.org/method/account.getNotifySettings
- Параметры:
  - `peer`: `InputNotifyPeer`

### `account.getPaidMessagesRevenue`

- Кратко: Получить платные сообщения доход.
- ID: `431639143` / `0x19ba4a67`
- Return type: `account.PaidMessagesRevenue`
- Сигнатура: `account.getPaidMessagesRevenue(flags:#, parent_peer:flags.0?InputPeer, user_id:InputUser) -> account.PaidMessagesRevenue`
- Официальная страница: https://core.telegram.org/method/account.getPaidMessagesRevenue
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `parent_peer`: `flags.0?InputPeer` - optional через flags.0
  - `user_id`: `InputUser`

### `account.getPassword`

- Кратко: Получить пароль.
- ID: `1418342645` / `0x548a30f5`
- Return type: `account.Password`
- Сигнатура: `account.getPassword() -> account.Password`
- Официальная страница: https://core.telegram.org/method/account.getPassword
- Параметры:
  - Нет параметров.

### `account.getPasswordSettings`

- Кратко: Получить пароль настройки.
- ID: `-1663767815` / `0x9cd4eaf9`
- Return type: `account.PasswordSettings`
- Сигнатура: `account.getPasswordSettings(password:InputCheckPasswordSRP) -> account.PasswordSettings`
- Официальная страница: https://core.telegram.org/method/account.getPasswordSettings
- Параметры:
  - `password`: `InputCheckPasswordSRP`

### `account.getPrivacy`

- Кратко: Получить приватность.
- ID: `-623130288` / `0xdadbc950`
- Return type: `account.PrivacyRules`
- Сигнатура: `account.getPrivacy(key:InputPrivacyKey) -> account.PrivacyRules`
- Официальная страница: https://core.telegram.org/method/account.getPrivacy
- Параметры:
  - `key`: `InputPrivacyKey`

### `account.getReactionsNotifySettings`

- Кратко: Получить реакции уведомления настройки.
- ID: `115172684` / `0x06dd654c`
- Return type: `ReactionsNotifySettings`
- Сигнатура: `account.getReactionsNotifySettings() -> ReactionsNotifySettings`
- Официальная страница: https://core.telegram.org/method/account.getReactionsNotifySettings
- Параметры:
  - Нет параметров.

### `account.getRecentEmojiStatuses`

- Кратко: Получить недавние эмодзи статусы.
- ID: `257392901` / `0x0f578105`
- Return type: `account.EmojiStatuses`
- Сигнатура: `account.getRecentEmojiStatuses(hash:long) -> account.EmojiStatuses`
- Официальная страница: https://core.telegram.org/method/account.getRecentEmojiStatuses
- Параметры:
  - `hash`: `long`

### `account.getSavedMusicIds`

- Кратко: Получить сохранённые музыку ids.
- ID: `-526557265` / `0xe09d5faf`
- Return type: `account.SavedMusicIds`
- Сигнатура: `account.getSavedMusicIds(hash:long) -> account.SavedMusicIds`
- Официальная страница: https://core.telegram.org/method/account.getSavedMusicIds
- Параметры:
  - `hash`: `long`

### `account.getSavedRingtones`

- Кратко: Получить сохранённые рингтоны.
- ID: `-510647672` / `0xe1902288`
- Return type: `account.SavedRingtones`
- Сигнатура: `account.getSavedRingtones(hash:long) -> account.SavedRingtones`
- Официальная страница: https://core.telegram.org/method/account.getSavedRingtones
- Параметры:
  - `hash`: `long`

### `account.getSecureValue`

- Кратко: Получить secure value.
- ID: `1936088002` / `0x73665bc2`
- Return type: `Vector`
- Сигнатура: `account.getSecureValue(types:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/account.getSecureValue
- Параметры:
  - `types`: `Vector`

### `account.getTheme`

- Кратко: Получить тему.
- ID: `978872812` / `0x3a5869ec`
- Return type: `Theme`
- Сигнатура: `account.getTheme(format:string, theme:InputTheme) -> Theme`
- Официальная страница: https://core.telegram.org/method/account.getTheme
- Параметры:
  - `format`: `string`
  - `theme`: `InputTheme`

### `account.getThemes`

- Кратко: Получить темы.
- ID: `1913054296` / `0x7206e458`
- Return type: `account.Themes`
- Сигнатура: `account.getThemes(format:string, hash:long) -> account.Themes`
- Официальная страница: https://core.telegram.org/method/account.getThemes
- Параметры:
  - `format`: `string`
  - `hash`: `long`

### `account.getTmpPassword`

- Кратко: Получить tmp пароль.
- ID: `1151208273` / `0x449e0b51`
- Return type: `account.TmpPassword`
- Сигнатура: `account.getTmpPassword(password:InputCheckPasswordSRP, period:int) -> account.TmpPassword`
- Официальная страница: https://core.telegram.org/method/account.getTmpPassword
- Параметры:
  - `password`: `InputCheckPasswordSRP`
  - `period`: `int`

### `account.getUniqueGiftChatThemes`

- Кратко: Получить unique подарок чат темы.
- ID: `-25890913` / `0xfe74ef9f`
- Return type: `account.ChatThemes`
- Сигнатура: `account.getUniqueGiftChatThemes(offset:int, limit:int, hash:long) -> account.ChatThemes`
- Официальная страница: https://core.telegram.org/method/account.getUniqueGiftChatThemes
- Параметры:
  - `offset`: `int`
  - `limit`: `int`
  - `hash`: `long`

### `account.getWallPaper`

- Кратко: Получить wall paper.
- ID: `-57811990` / `0xfc8ddbea`
- Return type: `WallPaper`
- Сигнатура: `account.getWallPaper(wallpaper:InputWallPaper) -> WallPaper`
- Официальная страница: https://core.telegram.org/method/account.getWallPaper
- Параметры:
  - `wallpaper`: `InputWallPaper`

### `account.getWallPapers`

- Кратко: Получить wall papers.
- ID: `127302966` / `0x07967d36`
- Return type: `account.WallPapers`
- Сигнатура: `account.getWallPapers(hash:long) -> account.WallPapers`
- Официальная страница: https://core.telegram.org/method/account.getWallPapers
- Параметры:
  - `hash`: `long`

### `account.getWebAuthorizations`

- Кратко: Получить веб авторизации/сессии.
- ID: `405695855` / `0x182e6d6f`
- Return type: `account.WebAuthorizations`
- Сигнатура: `account.getWebAuthorizations() -> account.WebAuthorizations`
- Официальная страница: https://core.telegram.org/method/account.getWebAuthorizations
- Параметры:
  - Нет параметров.

### `account.initTakeoutSession`

- Кратко: Операция с init takeout session.
- ID: `-1896617296` / `0x8ef3eab0`
- Return type: `account.Takeout`
- Сигнатура: `account.initTakeoutSession(flags:#, contacts:flags.0?true, message_users:flags.1?true, message_chats:flags.2?true, message_megagroups:flags.3?true, message_channels:flags.4?true, files:flags.5?true, file_max_size:flags.5?long) -> account.Takeout`
- Официальная страница: https://core.telegram.org/method/account.initTakeoutSession
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `contacts`: `flags.0?true` - optional через flags.0
  - `message_users`: `flags.1?true` - optional через flags.1
  - `message_chats`: `flags.2?true` - optional через flags.2
  - `message_megagroups`: `flags.3?true` - optional через flags.3
  - `message_channels`: `flags.4?true` - optional через flags.4
  - `files`: `flags.5?true` - optional через flags.5
  - `file_max_size`: `flags.5?long` - optional через flags.5

### `account.installTheme`

- Кратко: Установить тему.
- ID: `-953697477` / `0xc727bb3b`
- Return type: `Bool`
- Сигнатура: `account.installTheme(flags:#, dark:flags.0?true, theme:flags.1?InputTheme, format:flags.2?string, base_theme:flags.3?BaseTheme) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.installTheme
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `dark`: `flags.0?true` - optional через flags.0
  - `theme`: `flags.1?InputTheme` - optional через flags.1
  - `format`: `flags.2?string` - optional через flags.2
  - `base_theme`: `flags.3?BaseTheme` - optional через flags.3

### `account.installWallPaper`

- Кратко: Установить wall paper.
- ID: `-18000023` / `0xfeed5769`
- Return type: `Bool`
- Сигнатура: `account.installWallPaper(wallpaper:InputWallPaper, settings:WallPaperSettings) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.installWallPaper
- Параметры:
  - `wallpaper`: `InputWallPaper`
  - `settings`: `WallPaperSettings`

### `account.invalidateSignInCodes`

- Кратко: Операция с invalidate sign in коды.
- ID: `-896866118` / `0xca8ae8ba`
- Return type: `Bool`
- Сигнатура: `account.invalidateSignInCodes(codes:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.invalidateSignInCodes
- Параметры:
  - `codes`: `Vector`

### `account.registerDevice`

- Кратко: Зарегистрировать устройство.
- ID: `-326762118` / `0xec86017a`
- Return type: `Bool`
- Сигнатура: `account.registerDevice(flags:#, no_muted:flags.0?true, token_type:int, token:string, app_sandbox:Bool, secret:bytes, other_uids:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.registerDevice
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `no_muted`: `flags.0?true` - optional через flags.0
  - `token_type`: `int`
  - `token`: `string`
  - `app_sandbox`: `Bool`
  - `secret`: `bytes`
  - `other_uids`: `Vector`

### `account.reorderUsernames`

- Кратко: Изменить порядок username.
- ID: `-279966037` / `0xef500eab`
- Return type: `Bool`
- Сигнатура: `account.reorderUsernames(order:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.reorderUsernames
- Параметры:
  - `order`: `Vector`

### `account.reportPeer`

- Кратко: Пожаловаться / сообщить о peer/диалог.
- ID: `-977650298` / `0xc5ba3d86`
- Return type: `Bool`
- Сигнатура: `account.reportPeer(peer:InputPeer, reason:ReportReason, message:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.reportPeer
- Параметры:
  - `peer`: `InputPeer`
  - `reason`: `ReportReason`
  - `message`: `string`

### `account.reportProfilePhoto`

- Кратко: Пожаловаться / сообщить о профиль фото.
- ID: `-91437323` / `0xfa8cc6f5`
- Return type: `Bool`
- Сигнатура: `account.reportProfilePhoto(peer:InputPeer, photo_id:InputPhoto, reason:ReportReason, message:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.reportProfilePhoto
- Параметры:
  - `peer`: `InputPeer`
  - `photo_id`: `InputPhoto`
  - `reason`: `ReportReason`
  - `message`: `string`

### `account.resendPasswordEmail`

- Кратко: Операция с resend пароль email.
- ID: `2055154197` / `0x7a7f2a15`
- Return type: `Bool`
- Сигнатура: `account.resendPasswordEmail() -> Bool`
- Официальная страница: https://core.telegram.org/method/account.resendPasswordEmail
- Параметры:
  - Нет параметров.

### `account.resetAuthorization`

- Кратко: Сбросить авторизацию/сессию.
- ID: `-545786948` / `0xdf77f3bc`
- Return type: `Bool`
- Сигнатура: `account.resetAuthorization(hash:long) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.resetAuthorization
- Параметры:
  - `hash`: `long`

### `account.resetNotifySettings`

- Кратко: Сбросить уведомления настройки.
- ID: `-612493497` / `0xdb7e1747`
- Return type: `Bool`
- Сигнатура: `account.resetNotifySettings() -> Bool`
- Официальная страница: https://core.telegram.org/method/account.resetNotifySettings
- Параметры:
  - Нет параметров.

### `account.resetPassword`

- Кратко: Сбросить пароль.
- ID: `-1828139493` / `0x9308ce1b`
- Return type: `account.ResetPasswordResult`
- Сигнатура: `account.resetPassword() -> account.ResetPasswordResult`
- Официальная страница: https://core.telegram.org/method/account.resetPassword
- Параметры:
  - Нет параметров.

### `account.resetWallPapers`

- Кратко: Сбросить wall papers.
- ID: `-1153722364` / `0xbb3b9804`
- Return type: `Bool`
- Сигнатура: `account.resetWallPapers() -> Bool`
- Официальная страница: https://core.telegram.org/method/account.resetWallPapers
- Параметры:
  - Нет параметров.

### `account.resetWebAuthorization`

- Кратко: Сбросить веб авторизацию/сессию.
- ID: `755087855` / `0x2d01b9ef`
- Return type: `Bool`
- Сигнатура: `account.resetWebAuthorization(hash:long) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.resetWebAuthorization
- Параметры:
  - `hash`: `long`

### `account.resetWebAuthorizations`

- Кратко: Сбросить веб авторизации/сессии.
- ID: `1747789204` / `0x682d2594`
- Return type: `Bool`
- Сигнатура: `account.resetWebAuthorizations() -> Bool`
- Официальная страница: https://core.telegram.org/method/account.resetWebAuthorizations
- Параметры:
  - Нет параметров.

### `account.resolveBusinessChatLink`

- Кратко: Разрешить / получить по ссылке бизнес чат ссылку.
- ID: `1418913262` / `0x5492e5ee`
- Return type: `account.ResolvedBusinessChatLinks`
- Сигнатура: `account.resolveBusinessChatLink(slug:string) -> account.ResolvedBusinessChatLinks`
- Официальная страница: https://core.telegram.org/method/account.resolveBusinessChatLink
- Параметры:
  - `slug`: `string`

### `account.saveAutoDownloadSettings`

- Кратко: Сохранить auto download настройки.
- ID: `1995661875` / `0x76f36233`
- Return type: `Bool`
- Сигнатура: `account.saveAutoDownloadSettings(flags:#, low:flags.0?true, high:flags.1?true, settings:AutoDownloadSettings) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.saveAutoDownloadSettings
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `low`: `flags.0?true` - optional через flags.0
  - `high`: `flags.1?true` - optional через flags.1
  - `settings`: `AutoDownloadSettings`

### `account.saveAutoSaveSettings`

- Кратко: Сохранить auto save настройки.
- ID: `-694451359` / `0xd69b8361`
- Return type: `Bool`
- Сигнатура: `account.saveAutoSaveSettings(flags:#, users:flags.0?true, chats:flags.1?true, broadcasts:flags.2?true, peer:flags.3?InputPeer, settings:AutoSaveSettings) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.saveAutoSaveSettings
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `users`: `flags.0?true` - optional через flags.0
  - `chats`: `flags.1?true` - optional через flags.1
  - `broadcasts`: `flags.2?true` - optional через flags.2
  - `peer`: `flags.3?InputPeer` - optional через flags.3
  - `settings`: `AutoSaveSettings`

### `account.saveMusic`

- Кратко: Сохранить музыку.
- ID: `-1301859671` / `0xb26732a9`
- Return type: `Bool`
- Сигнатура: `account.saveMusic(flags:#, unsave:flags.0?true, id:InputDocument, after_id:flags.1?InputDocument) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.saveMusic
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `unsave`: `flags.0?true` - optional через flags.0
  - `id`: `InputDocument`
  - `after_id`: `flags.1?InputDocument` - optional через flags.1

### `account.saveRingtone`

- Кратко: Сохранить рингтон.
- ID: `1038768899` / `0x3dea5b03`
- Return type: `account.SavedRingtone`
- Сигнатура: `account.saveRingtone(id:InputDocument, unsave:Bool) -> account.SavedRingtone`
- Официальная страница: https://core.telegram.org/method/account.saveRingtone
- Параметры:
  - `id`: `InputDocument`
  - `unsave`: `Bool`

### `account.saveSecureValue`

- Кратко: Сохранить secure value.
- ID: `-1986010339` / `0x899fe31d`
- Return type: `SecureValue`
- Сигнатура: `account.saveSecureValue(value:InputSecureValue, secure_secret_id:long) -> SecureValue`
- Официальная страница: https://core.telegram.org/method/account.saveSecureValue
- Параметры:
  - `value`: `InputSecureValue`
  - `secure_secret_id`: `long`

### `account.saveTheme`

- Кратко: Сохранить тему.
- ID: `-229175188` / `0xf257106c`
- Return type: `Bool`
- Сигнатура: `account.saveTheme(theme:InputTheme, unsave:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.saveTheme
- Параметры:
  - `theme`: `InputTheme`
  - `unsave`: `Bool`

### `account.saveWallPaper`

- Кратко: Сохранить wall paper.
- ID: `1817860919` / `0x6c5a5b37`
- Return type: `Bool`
- Сигнатура: `account.saveWallPaper(wallpaper:InputWallPaper, unsave:Bool, settings:WallPaperSettings) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.saveWallPaper
- Параметры:
  - `wallpaper`: `InputWallPaper`
  - `unsave`: `Bool`
  - `settings`: `WallPaperSettings`

### `account.sendChangePhoneCode`

- Кратко: Отправить change телефон код.
- ID: `-2108208411` / `0x82574ae5`
- Return type: `auth.SentCode`
- Сигнатура: `account.sendChangePhoneCode(phone_number:string, settings:CodeSettings) -> auth.SentCode`
- Официальная страница: https://core.telegram.org/method/account.sendChangePhoneCode
- Параметры:
  - `phone_number`: `string`
  - `settings`: `CodeSettings`

### `account.sendConfirmPhoneCode`

- Кратко: Отправить confirm телефон код.
- ID: `457157256` / `0x1b3faa88`
- Return type: `auth.SentCode`
- Сигнатура: `account.sendConfirmPhoneCode(hash:string, settings:CodeSettings) -> auth.SentCode`
- Официальная страница: https://core.telegram.org/method/account.sendConfirmPhoneCode
- Параметры:
  - `hash`: `string`
  - `settings`: `CodeSettings`

### `account.sendVerifyEmailCode`

- Кратко: Отправить verify email код.
- ID: `-1730136133` / `0x98e037bb`
- Return type: `account.SentEmailCode`
- Сигнатура: `account.sendVerifyEmailCode(purpose:EmailVerifyPurpose, email:string) -> account.SentEmailCode`
- Официальная страница: https://core.telegram.org/method/account.sendVerifyEmailCode
- Параметры:
  - `purpose`: `EmailVerifyPurpose`
  - `email`: `string`

### `account.sendVerifyPhoneCode`

- Кратко: Отправить verify телефон код.
- ID: `-1516022023` / `0xa5a356f9`
- Return type: `auth.SentCode`
- Сигнатура: `account.sendVerifyPhoneCode(phone_number:string, settings:CodeSettings) -> auth.SentCode`
- Официальная страница: https://core.telegram.org/method/account.sendVerifyPhoneCode
- Параметры:
  - `phone_number`: `string`
  - `settings`: `CodeSettings`

### `account.setAccountTTL`

- Кратко: Установить account TTL/срок жизни.
- ID: `608323678` / `0x2442485e`
- Return type: `Bool`
- Сигнатура: `account.setAccountTTL(ttl:AccountDaysTTL) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.setAccountTTL
- Параметры:
  - `ttl`: `AccountDaysTTL`

### `account.setAuthorizationTTL`

- Кратко: Установить авторизацию/сессию TTL/срок жизни.
- ID: `-1081501024` / `0xbf899aa0`
- Return type: `Bool`
- Сигнатура: `account.setAuthorizationTTL(authorization_ttl_days:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.setAuthorizationTTL
- Параметры:
  - `authorization_ttl_days`: `int`

### `account.setContactSignUpNotification`

- Кратко: Установить контакт sign up notification.
- ID: `-806076575` / `0xcff43f61`
- Return type: `Bool`
- Сигнатура: `account.setContactSignUpNotification(silent:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.setContactSignUpNotification
- Параметры:
  - `silent`: `Bool`

### `account.setContentSettings`

- Кратко: Установить контент настройки.
- ID: `-1250643605` / `0xb574b16b`
- Return type: `Bool`
- Сигнатура: `account.setContentSettings(flags:#, sensitive_enabled:flags.0?true) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.setContentSettings
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `sensitive_enabled`: `flags.0?true` - optional через flags.0

### `account.setGlobalPrivacySettings`

- Кратко: Установить глобальные приватность настройки.
- ID: `517647042` / `0x1edaaac2`
- Return type: `GlobalPrivacySettings`
- Сигнатура: `account.setGlobalPrivacySettings(settings:GlobalPrivacySettings) -> GlobalPrivacySettings`
- Официальная страница: https://core.telegram.org/method/account.setGlobalPrivacySettings
- Параметры:
  - `settings`: `GlobalPrivacySettings`

### `account.setMainProfileTab`

- Кратко: Установить основное профиль tab.
- ID: `1575909552` / `0x5dee78b0`
- Return type: `Bool`
- Сигнатура: `account.setMainProfileTab(tab:ProfileTab) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.setMainProfileTab
- Параметры:
  - `tab`: `ProfileTab`

### `account.setPrivacy`

- Кратко: Установить приватность.
- ID: `-906486552` / `0xc9f81ce8`
- Return type: `account.PrivacyRules`
- Сигнатура: `account.setPrivacy(key:InputPrivacyKey, rules:Vector) -> account.PrivacyRules`
- Официальная страница: https://core.telegram.org/method/account.setPrivacy
- Параметры:
  - `key`: `InputPrivacyKey`
  - `rules`: `Vector`

### `account.setReactionsNotifySettings`

- Кратко: Установить реакции уведомления настройки.
- ID: `829220168` / `0x316ce548`
- Return type: `ReactionsNotifySettings`
- Сигнатура: `account.setReactionsNotifySettings(settings:ReactionsNotifySettings) -> ReactionsNotifySettings`
- Официальная страница: https://core.telegram.org/method/account.setReactionsNotifySettings
- Параметры:
  - `settings`: `ReactionsNotifySettings`

### `account.toggleConnectedBotPaused`

- Кратко: Включить/выключить подключённого бота на паузе.
- ID: `1684934807` / `0x646e1097`
- Return type: `Bool`
- Сигнатура: `account.toggleConnectedBotPaused(peer:InputPeer, paused:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.toggleConnectedBotPaused
- Параметры:
  - `peer`: `InputPeer`
  - `paused`: `Bool`

### `account.toggleNoPaidMessagesException`

- Кратко: Включить/выключить no платные сообщения exception.
- ID: `-30483850` / `0xfe2eda76`
- Return type: `Bool`
- Сигнатура: `account.toggleNoPaidMessagesException(flags:#, refund_charged:flags.0?true, require_payment:flags.2?true, parent_peer:flags.1?InputPeer, user_id:InputUser) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.toggleNoPaidMessagesException
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `refund_charged`: `flags.0?true` - optional через flags.0
  - `require_payment`: `flags.2?true` - optional через flags.2
  - `parent_peer`: `flags.1?InputPeer` - optional через flags.1
  - `user_id`: `InputUser`

### `account.toggleSponsoredMessages`

- Кратко: Включить/выключить спонсируемые сообщения.
- ID: `-1176919155` / `0xb9d9a38d`
- Return type: `Bool`
- Сигнатура: `account.toggleSponsoredMessages(enabled:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.toggleSponsoredMessages
- Параметры:
  - `enabled`: `Bool`

### `account.toggleUsername`

- Кратко: Включить/выключить username.
- ID: `1490465654` / `0x58d6b376`
- Return type: `Bool`
- Сигнатура: `account.toggleUsername(username:string, active:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.toggleUsername
- Параметры:
  - `username`: `string`
  - `active`: `Bool`

### `account.unregisterDevice`

- Кратко: Удалить регистрацию устройство.
- ID: `1779249670` / `0x6a0d3206`
- Return type: `Bool`
- Сигнатура: `account.unregisterDevice(token_type:int, token:string, other_uids:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.unregisterDevice
- Параметры:
  - `token_type`: `int`
  - `token`: `string`
  - `other_uids`: `Vector`

### `account.updateBirthday`

- Кратко: Обновить birthday.
- ID: `-865203183` / `0xcc6e0c11`
- Return type: `Bool`
- Сигнатура: `account.updateBirthday(flags:#, birthday:flags.0?Birthday) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updateBirthday
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `birthday`: `flags.0?Birthday` - optional через flags.0

### `account.updateBusinessAwayMessage`

- Кратко: Обновить бизнес away сообщение.
- ID: `-1570078811` / `0xa26a7fa5`
- Return type: `Bool`
- Сигнатура: `account.updateBusinessAwayMessage(flags:#, message:flags.0?InputBusinessAwayMessage) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updateBusinessAwayMessage
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `message`: `flags.0?InputBusinessAwayMessage` - optional через flags.0

### `account.updateBusinessGreetingMessage`

- Кратко: Обновить бизнес greeting сообщение.
- ID: `1724755908` / `0x66cdafc4`
- Return type: `Bool`
- Сигнатура: `account.updateBusinessGreetingMessage(flags:#, message:flags.0?InputBusinessGreetingMessage) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updateBusinessGreetingMessage
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `message`: `flags.0?InputBusinessGreetingMessage` - optional через flags.0

### `account.updateBusinessIntro`

- Кратко: Обновить бизнес вступление.
- ID: `-1508585420` / `0xa614d034`
- Return type: `Bool`
- Сигнатура: `account.updateBusinessIntro(flags:#, intro:flags.0?InputBusinessIntro) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updateBusinessIntro
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `intro`: `flags.0?InputBusinessIntro` - optional через flags.0

### `account.updateBusinessLocation`

- Кратко: Обновить бизнес локацию.
- ID: `-1637149926` / `0x9e6b131a`
- Return type: `Bool`
- Сигнатура: `account.updateBusinessLocation(flags:#, geo_point:flags.1?InputGeoPoint, address:flags.0?string) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updateBusinessLocation
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `geo_point`: `flags.1?InputGeoPoint` - optional через flags.1
  - `address`: `flags.0?string` - optional через flags.0

### `account.updateBusinessWorkHours`

- Кратко: Обновить бизнес work hours.
- ID: `1258348646` / `0x4b00e066`
- Return type: `Bool`
- Сигнатура: `account.updateBusinessWorkHours(flags:#, business_work_hours:flags.0?BusinessWorkHours) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updateBusinessWorkHours
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `business_work_hours`: `flags.0?BusinessWorkHours` - optional через flags.0

### `account.updateColor`

- Кратко: Обновить color.
- ID: `2096079197` / `0x7cefa15d`
- Return type: `Bool`
- Сигнатура: `account.updateColor(flags:#, for_profile:flags.1?true, color:flags.2?int, background_emoji_id:flags.0?long) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updateColor
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `for_profile`: `flags.1?true` - optional через flags.1
  - `color`: `flags.2?int` - optional через flags.2
  - `background_emoji_id`: `flags.0?long` - optional через flags.0

### `account.updateConnectedBot`

- Кратко: Обновить подключённого бота.
- ID: `1721797758` / `0x66a08c7e`
- Return type: `Updates`
- Сигнатура: `account.updateConnectedBot(flags:#, deleted:flags.1?true, rights:flags.0?BusinessBotRights, bot:InputUser, recipients:InputBusinessBotRecipients) -> Updates`
- Официальная страница: https://core.telegram.org/method/account.updateConnectedBot
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `deleted`: `flags.1?true` - optional через flags.1
  - `rights`: `flags.0?BusinessBotRights` - optional через flags.0
  - `bot`: `InputUser`
  - `recipients`: `InputBusinessBotRecipients`

### `account.updateDeviceLocked`

- Кратко: Обновить устройство locked.
- ID: `954152242` / `0x38df3532`
- Return type: `Bool`
- Сигнатура: `account.updateDeviceLocked(period:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updateDeviceLocked
- Параметры:
  - `period`: `int`

### `account.updateEmojiStatus`

- Кратко: Обновить эмодзи статус.
- ID: `-70001045` / `0xfbd3de6b`
- Return type: `Bool`
- Сигнатура: `account.updateEmojiStatus(emoji_status:EmojiStatus) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updateEmojiStatus
- Параметры:
  - `emoji_status`: `EmojiStatus`

### `account.updateNotifySettings`

- Кратко: Обновить уведомления настройки.
- ID: `-2067899501` / `0x84be5b93`
- Return type: `Bool`
- Сигнатура: `account.updateNotifySettings(peer:InputNotifyPeer, settings:InputPeerNotifySettings) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updateNotifySettings
- Параметры:
  - `peer`: `InputNotifyPeer`
  - `settings`: `InputPeerNotifySettings`

### `account.updatePasswordSettings`

- Кратко: Обновить пароль настройки.
- ID: `-1516564433` / `0xa59b102f`
- Return type: `Bool`
- Сигнатура: `account.updatePasswordSettings(password:InputCheckPasswordSRP, new_settings:account.PasswordInputSettings) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updatePasswordSettings
- Параметры:
  - `password`: `InputCheckPasswordSRP`
  - `new_settings`: `account.PasswordInputSettings`

### `account.updatePersonalChannel`

- Кратко: Обновить personal канал.
- ID: `-649919008` / `0xd94305e0`
- Return type: `Bool`
- Сигнатура: `account.updatePersonalChannel(channel:InputChannel) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updatePersonalChannel
- Параметры:
  - `channel`: `InputChannel`

### `account.updateProfile`

- Кратко: Обновить профиль.
- ID: `2018596725` / `0x78515775`
- Return type: `User`
- Сигнатура: `account.updateProfile(flags:#, first_name:flags.0?string, last_name:flags.1?string, about:flags.2?string) -> User`
- Официальная страница: https://core.telegram.org/method/account.updateProfile
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `first_name`: `flags.0?string` - optional через flags.0
  - `last_name`: `flags.1?string` - optional через flags.1
  - `about`: `flags.2?string` - optional через flags.2

### `account.updateStatus`

- Кратко: Обновить статус.
- ID: `1713919532` / `0x6628562c`
- Return type: `Bool`
- Сигнатура: `account.updateStatus(offline:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.updateStatus
- Параметры:
  - `offline`: `Bool`

### `account.updateTheme`

- Кратко: Обновить тему.
- ID: `737414348` / `0x2bf40ccc`
- Return type: `Theme`
- Сигнатура: `account.updateTheme(flags:#, format:string, theme:InputTheme, slug:flags.0?string, title:flags.1?string, document:flags.2?InputDocument, settings:flags.3?Vector) -> Theme`
- Официальная страница: https://core.telegram.org/method/account.updateTheme
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `format`: `string`
  - `theme`: `InputTheme`
  - `slug`: `flags.0?string` - optional через flags.0
  - `title`: `flags.1?string` - optional через flags.1
  - `document`: `flags.2?InputDocument` - optional через flags.2
  - `settings`: `flags.3?Vector` - optional через flags.3

### `account.updateUsername`

- Кратко: Обновить username.
- ID: `1040964988` / `0x3e0bdd7c`
- Return type: `User`
- Сигнатура: `account.updateUsername(username:string) -> User`
- Официальная страница: https://core.telegram.org/method/account.updateUsername
- Параметры:
  - `username`: `string`

### `account.uploadRingtone`

- Кратко: Загрузить рингтон.
- ID: `-2095414366` / `0x831a83a2`
- Return type: `Document`
- Сигнатура: `account.uploadRingtone(file:InputFile, file_name:string, mime_type:string) -> Document`
- Официальная страница: https://core.telegram.org/method/account.uploadRingtone
- Параметры:
  - `file`: `InputFile`
  - `file_name`: `string`
  - `mime_type`: `string`

### `account.uploadTheme`

- Кратко: Загрузить тему.
- ID: `473805619` / `0x1c3db333`
- Return type: `Document`
- Сигнатура: `account.uploadTheme(flags:#, file:InputFile, thumb:flags.0?InputFile, file_name:string, mime_type:string) -> Document`
- Официальная страница: https://core.telegram.org/method/account.uploadTheme
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `file`: `InputFile`
  - `thumb`: `flags.0?InputFile` - optional через flags.0
  - `file_name`: `string`
  - `mime_type`: `string`

### `account.uploadWallPaper`

- Кратко: Загрузить wall paper.
- ID: `-476410109` / `0xe39a8f03`
- Return type: `WallPaper`
- Сигнатура: `account.uploadWallPaper(flags:#, for_chat:flags.0?true, file:InputFile, mime_type:string, settings:WallPaperSettings) -> WallPaper`
- Официальная страница: https://core.telegram.org/method/account.uploadWallPaper
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `for_chat`: `flags.0?true` - optional через flags.0
  - `file`: `InputFile`
  - `mime_type`: `string`
  - `settings`: `WallPaperSettings`

### `account.verifyEmail`

- Кратко: Проверить / верифицировать email.
- ID: `53322959` / `0x032da4cf`
- Return type: `account.EmailVerified`
- Сигнатура: `account.verifyEmail(purpose:EmailVerifyPurpose, verification:EmailVerification) -> account.EmailVerified`
- Официальная страница: https://core.telegram.org/method/account.verifyEmail
- Параметры:
  - `purpose`: `EmailVerifyPurpose`
  - `verification`: `EmailVerification`

### `account.verifyPhone`

- Кратко: Проверить / верифицировать телефон.
- ID: `1305716726` / `0x4dd3a7f6`
- Return type: `Bool`
- Сигнатура: `account.verifyPhone(phone_number:string, phone_code_hash:string, phone_code:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/account.verifyPhone
- Параметры:
  - `phone_number`: `string`
  - `phone_code_hash`: `string`
  - `phone_code`: `string`

## auth

### `auth.acceptLoginToken`

- Кратко: Принять логин токен.
- ID: `-392909491` / `0xe894ad4d`
- Return type: `Authorization`
- Сигнатура: `auth.acceptLoginToken(token:bytes) -> Authorization`
- Официальная страница: https://core.telegram.org/method/auth.acceptLoginToken
- Параметры:
  - `token`: `bytes`

### `auth.bindTempAuthKey`

- Кратко: Привязать временный авторизации ключ.
- ID: `-841733627` / `0xcdd42a05`
- Return type: `Bool`
- Сигнатура: `auth.bindTempAuthKey(perm_auth_key_id:long, nonce:long, expires_at:int, encrypted_message:bytes) -> Bool`
- Официальная страница: https://core.telegram.org/method/auth.bindTempAuthKey
- Параметры:
  - `perm_auth_key_id`: `long`
  - `nonce`: `long`
  - `expires_at`: `int`
  - `encrypted_message`: `bytes`

### `auth.cancelCode`

- Кратко: Операция с cancel код.
- ID: `520357240` / `0x1f040578`
- Return type: `Bool`
- Сигнатура: `auth.cancelCode(phone_number:string, phone_code_hash:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/auth.cancelCode
- Параметры:
  - `phone_number`: `string`
  - `phone_code_hash`: `string`

### `auth.checkPassword`

- Кратко: Проверить пароль.
- ID: `-779399914` / `0xd18b4d16`
- Return type: `auth.Authorization`
- Сигнатура: `auth.checkPassword(password:InputCheckPasswordSRP) -> auth.Authorization`
- Официальная страница: https://core.telegram.org/method/auth.checkPassword
- Параметры:
  - `password`: `InputCheckPasswordSRP`

### `auth.checkRecoveryPassword`

- Кратко: Проверить восстановление пароль.
- ID: `221691769` / `0x0d36bf79`
- Return type: `Bool`
- Сигнатура: `auth.checkRecoveryPassword(code:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/auth.checkRecoveryPassword
- Параметры:
  - `code`: `string`

### `auth.dropTempAuthKeys`

- Кратко: Удалить временный авторизации ключи.
- ID: `-1907842680` / `0x8e48a188`
- Return type: `Bool`
- Сигнатура: `auth.dropTempAuthKeys(except_auth_keys:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/auth.dropTempAuthKeys
- Параметры:
  - `except_auth_keys`: `Vector`

### `auth.exportAuthorization`

- Кратко: Экспортировать авторизацию/сессию.
- ID: `-440401971` / `0xe5bfffcd`
- Return type: `auth.ExportedAuthorization`
- Сигнатура: `auth.exportAuthorization(dc_id:int) -> auth.ExportedAuthorization`
- Официальная страница: https://core.telegram.org/method/auth.exportAuthorization
- Параметры:
  - `dc_id`: `int`

### `auth.exportLoginToken`

- Кратко: Экспортировать логин токен.
- ID: `-1210022402` / `0xb7e085fe`
- Return type: `auth.LoginToken`
- Сигнатура: `auth.exportLoginToken(api_id:int, api_hash:string, except_ids:Vector) -> auth.LoginToken`
- Официальная страница: https://core.telegram.org/method/auth.exportLoginToken
- Параметры:
  - `api_id`: `int`
  - `api_hash`: `string`
  - `except_ids`: `Vector`

### `auth.importAuthorization`

- Кратко: Импортировать авторизацию/сессию.
- ID: `-1518699091` / `0xa57a7dad`
- Return type: `auth.Authorization`
- Сигнатура: `auth.importAuthorization(id:long, bytes:bytes) -> auth.Authorization`
- Официальная страница: https://core.telegram.org/method/auth.importAuthorization
- Параметры:
  - `id`: `long`
  - `bytes`: `bytes`

### `auth.importBotAuthorization`

- Кратко: Импортировать бота авторизацию/сессию.
- ID: `1738800940` / `0x67a3ff2c`
- Return type: `auth.Authorization`
- Сигнатура: `auth.importBotAuthorization(flags:int, api_id:int, api_hash:string, bot_auth_token:string) -> auth.Authorization`
- Официальная страница: https://core.telegram.org/method/auth.importBotAuthorization
- Параметры:
  - `flags`: `int`
  - `api_id`: `int`
  - `api_hash`: `string`
  - `bot_auth_token`: `string`

### `auth.importLoginToken`

- Кратко: Импортировать логин токен.
- ID: `-1783866140` / `0x95ac5ce4`
- Return type: `auth.LoginToken`
- Сигнатура: `auth.importLoginToken(token:bytes) -> auth.LoginToken`
- Официальная страница: https://core.telegram.org/method/auth.importLoginToken
- Параметры:
  - `token`: `bytes`

### `auth.importWebTokenAuthorization`

- Кратко: Импортировать веб токен авторизацию/сессию.
- ID: `767062953` / `0x2db873a9`
- Return type: `auth.Authorization`
- Сигнатура: `auth.importWebTokenAuthorization(api_id:int, api_hash:string, web_auth_token:string) -> auth.Authorization`
- Официальная страница: https://core.telegram.org/method/auth.importWebTokenAuthorization
- Параметры:
  - `api_id`: `int`
  - `api_hash`: `string`
  - `web_auth_token`: `string`

### `auth.logOut`

- Кратко: Выйти из данными.
- ID: `1047706137` / `0x3e72ba19`
- Return type: `auth.LoggedOut`
- Сигнатура: `auth.logOut() -> auth.LoggedOut`
- Официальная страница: https://core.telegram.org/method/auth.logOut
- Параметры:
  - Нет параметров.

### `auth.recoverPassword`

- Кратко: Операция с recover пароль.
- ID: `923364464` / `0x37096c70`
- Return type: `auth.Authorization`
- Сигнатура: `auth.recoverPassword(flags:#, code:string, new_settings:flags.0?account.PasswordInputSettings) -> auth.Authorization`
- Официальная страница: https://core.telegram.org/method/auth.recoverPassword
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `code`: `string`
  - `new_settings`: `flags.0?account.PasswordInputSettings` - optional через flags.0

### `auth.reportMissingCode`

- Кратко: Пожаловаться / сообщить о missing код.
- ID: `-878841866` / `0xcb9deff6`
- Return type: `Bool`
- Сигнатура: `auth.reportMissingCode(phone_number:string, phone_code_hash:string, mnc:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/auth.reportMissingCode
- Параметры:
  - `phone_number`: `string`
  - `phone_code_hash`: `string`
  - `mnc`: `string`

### `auth.requestFirebaseSms`

- Кратко: Запросить Firebase SMS.
- ID: `-1908857314` / `0x8e39261e`
- Return type: `Bool`
- Сигнатура: `auth.requestFirebaseSms(flags:#, phone_number:string, phone_code_hash:string, safety_net_token:flags.0?string, play_integrity_token:flags.2?string, ios_push_secret:flags.1?string) -> Bool`
- Официальная страница: https://core.telegram.org/method/auth.requestFirebaseSms
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `phone_number`: `string`
  - `phone_code_hash`: `string`
  - `safety_net_token`: `flags.0?string` - optional через flags.0
  - `play_integrity_token`: `flags.2?string` - optional через flags.2
  - `ios_push_secret`: `flags.1?string` - optional через flags.1

### `auth.requestPasswordRecovery`

- Кратко: Запросить пароль восстановление.
- ID: `-661144474` / `0xd897bc66`
- Return type: `auth.PasswordRecovery`
- Сигнатура: `auth.requestPasswordRecovery() -> auth.PasswordRecovery`
- Официальная страница: https://core.telegram.org/method/auth.requestPasswordRecovery
- Параметры:
  - Нет параметров.

### `auth.resendCode`

- Кратко: Операция с resend код.
- ID: `-890997469` / `0xcae47523`
- Return type: `auth.SentCode`
- Сигнатура: `auth.resendCode(flags:#, phone_number:string, phone_code_hash:string, reason:flags.0?string) -> auth.SentCode`
- Официальная страница: https://core.telegram.org/method/auth.resendCode
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `phone_number`: `string`
  - `phone_code_hash`: `string`
  - `reason`: `flags.0?string` - optional через flags.0

### `auth.resetAuthorizations`

- Кратко: Сбросить авторизации/сессии.
- ID: `-1616179942` / `0x9fab0d1a`
- Return type: `Bool`
- Сигнатура: `auth.resetAuthorizations() -> Bool`
- Официальная страница: https://core.telegram.org/method/auth.resetAuthorizations
- Параметры:
  - Нет параметров.

### `auth.resetLoginEmail`

- Кратко: Сбросить логин email.
- ID: `2123760019` / `0x7e960193`
- Return type: `auth.SentCode`
- Сигнатура: `auth.resetLoginEmail(phone_number:string, phone_code_hash:string) -> auth.SentCode`
- Официальная страница: https://core.telegram.org/method/auth.resetLoginEmail
- Параметры:
  - `phone_number`: `string`
  - `phone_code_hash`: `string`

### `auth.sendCode`

- Кратко: Отправить код.
- ID: `-1502141361` / `0xa677244f`
- Return type: `auth.SentCode`
- Сигнатура: `auth.sendCode(phone_number:string, api_id:int, api_hash:string, settings:CodeSettings) -> auth.SentCode`
- Официальная страница: https://core.telegram.org/method/auth.sendCode
- Параметры:
  - `phone_number`: `string`
  - `api_id`: `int`
  - `api_hash`: `string`
  - `settings`: `CodeSettings`

### `auth.signIn`

- Кратко: Войти в данными.
- ID: `-1923962543` / `0x8d52a951`
- Return type: `auth.Authorization`
- Сигнатура: `auth.signIn(flags:#, phone_number:string, phone_code_hash:string, phone_code:flags.0?string, email_verification:flags.1?EmailVerification) -> auth.Authorization`
- Официальная страница: https://core.telegram.org/method/auth.signIn
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `phone_number`: `string`
  - `phone_code_hash`: `string`
  - `phone_code`: `flags.0?string` - optional через flags.0
  - `email_verification`: `flags.1?EmailVerification` - optional через flags.1

### `auth.signUp`

- Кратко: Зарегистрировать данными.
- ID: `-1429752041` / `0xaac7b717`
- Return type: `auth.Authorization`
- Сигнатура: `auth.signUp(flags:#, no_joined_notifications:flags.0?true, phone_number:string, phone_code_hash:string, first_name:string, last_name:string) -> auth.Authorization`
- Официальная страница: https://core.telegram.org/method/auth.signUp
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `no_joined_notifications`: `flags.0?true` - optional через flags.0
  - `phone_number`: `string`
  - `phone_code_hash`: `string`
  - `first_name`: `string`
  - `last_name`: `string`

## bots

### `bots.addPreviewMedia`

- Кратко: Операция с add превью медиа.
- ID: `397326170` / `0x17aeb75a`
- Return type: `BotPreviewMedia`
- Сигнатура: `bots.addPreviewMedia(bot:InputUser, lang_code:string, media:InputMedia) -> BotPreviewMedia`
- Официальная страница: https://core.telegram.org/method/bots.addPreviewMedia
- Параметры:
  - `bot`: `InputUser`
  - `lang_code`: `string`
  - `media`: `InputMedia`

### `bots.allowSendMessage`

- Кратко: Разрешить send сообщение.
- ID: `-248323089` / `0xf132e3ef`
- Return type: `Updates`
- Сигнатура: `bots.allowSendMessage(bot:InputUser) -> Updates`
- Официальная страница: https://core.telegram.org/method/bots.allowSendMessage
- Параметры:
  - `bot`: `InputUser`

### `bots.answerWebhookJSONQuery`

- Кратко: Операция с answer webhook json query.
- ID: `-434028723` / `0xe6213f4d`
- Return type: `Bool`
- Сигнатура: `bots.answerWebhookJSONQuery(query_id:long, data:DataJSON) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.answerWebhookJSONQuery
- Параметры:
  - `query_id`: `long`
  - `data`: `DataJSON`

### `bots.canSendMessage`

- Кратко: Проверить, может ли отправлять сообщение.
- ID: `324662502` / `0x1359f4e6`
- Return type: `Bool`
- Сигнатура: `bots.canSendMessage(bot:InputUser) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.canSendMessage
- Параметры:
  - `bot`: `InputUser`

### `bots.checkDownloadFileParams`

- Кратко: Проверить download файл params.
- ID: `1342666121` / `0x50077589`
- Return type: `Bool`
- Сигнатура: `bots.checkDownloadFileParams(bot:InputUser, file_name:string, url:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.checkDownloadFileParams
- Параметры:
  - `bot`: `InputUser`
  - `file_name`: `string`
  - `url`: `string`

### `bots.deletePreviewMedia`

- Кратко: Удалить превью медиа.
- ID: `755054003` / `0x2d0135b3`
- Return type: `Bool`
- Сигнатура: `bots.deletePreviewMedia(bot:InputUser, lang_code:string, media:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.deletePreviewMedia
- Параметры:
  - `bot`: `InputUser`
  - `lang_code`: `string`
  - `media`: `Vector`

### `bots.editPreviewMedia`

- Кратко: Изменить превью медиа.
- ID: `-2061148049` / `0x8525606f`
- Return type: `BotPreviewMedia`
- Сигнатура: `bots.editPreviewMedia(bot:InputUser, lang_code:string, media:InputMedia, new_media:InputMedia) -> BotPreviewMedia`
- Официальная страница: https://core.telegram.org/method/bots.editPreviewMedia
- Параметры:
  - `bot`: `InputUser`
  - `lang_code`: `string`
  - `media`: `InputMedia`
  - `new_media`: `InputMedia`

### `bots.getAdminedBots`

- Кратко: Получить admined ботов.
- ID: `-1334764157` / `0xb0711d83`
- Return type: `Vector`
- Сигнатура: `bots.getAdminedBots() -> Vector`
- Официальная страница: https://core.telegram.org/method/bots.getAdminedBots
- Параметры:
  - Нет параметров.

### `bots.getBotCommands`

- Кратко: Получить бота commands.
- ID: `-481554986` / `0xe34c0dd6`
- Return type: `Vector`
- Сигнатура: `bots.getBotCommands(scope:BotCommandScope, lang_code:string) -> Vector`
- Официальная страница: https://core.telegram.org/method/bots.getBotCommands
- Параметры:
  - `scope`: `BotCommandScope`
  - `lang_code`: `string`

### `bots.getBotInfo`

- Кратко: Получить бота информацию.
- ID: `-589753091` / `0xdcd914fd`
- Return type: `bots.BotInfo`
- Сигнатура: `bots.getBotInfo(flags:#, bot:flags.0?InputUser, lang_code:string) -> bots.BotInfo`
- Официальная страница: https://core.telegram.org/method/bots.getBotInfo
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `bot`: `flags.0?InputUser` - optional через flags.0
  - `lang_code`: `string`

### `bots.getBotMenuButton`

- Кратко: Получить бота меню button.
- ID: `-1671369944` / `0x9c60eb28`
- Return type: `BotMenuButton`
- Сигнатура: `bots.getBotMenuButton(user_id:InputUser) -> BotMenuButton`
- Официальная страница: https://core.telegram.org/method/bots.getBotMenuButton
- Параметры:
  - `user_id`: `InputUser`

### `bots.getBotRecommendations`

- Кратко: Получить бота recommendations.
- ID: `-1581840363` / `0xa1b70815`
- Return type: `users.Users`
- Сигнатура: `bots.getBotRecommendations(bot:InputUser) -> users.Users`
- Официальная страница: https://core.telegram.org/method/bots.getBotRecommendations
- Параметры:
  - `bot`: `InputUser`

### `bots.getPopularAppBots`

- Кратко: Получить популярные приложение ботов.
- ID: `-1034878574` / `0xc2510192`
- Return type: `bots.PopularAppBots`
- Сигнатура: `bots.getPopularAppBots(offset:string, limit:int) -> bots.PopularAppBots`
- Официальная страница: https://core.telegram.org/method/bots.getPopularAppBots
- Параметры:
  - `offset`: `string`
  - `limit`: `int`

### `bots.getPreviewInfo`

- Кратко: Получить превью информацию.
- ID: `1111143341` / `0x423ab3ad`
- Return type: `bots.PreviewInfo`
- Сигнатура: `bots.getPreviewInfo(bot:InputUser, lang_code:string) -> bots.PreviewInfo`
- Официальная страница: https://core.telegram.org/method/bots.getPreviewInfo
- Параметры:
  - `bot`: `InputUser`
  - `lang_code`: `string`

### `bots.getPreviewMedias`

- Кратко: Получить превью medias.
- ID: `-1566222003` / `0xa2a5594d`
- Return type: `Vector`
- Сигнатура: `bots.getPreviewMedias(bot:InputUser) -> Vector`
- Официальная страница: https://core.telegram.org/method/bots.getPreviewMedias
- Параметры:
  - `bot`: `InputUser`

### `bots.invokeWebViewCustomMethod`

- Кратко: Операция с invoke веб view кастомные method.
- ID: `142591463` / `0x087fc5e7`
- Return type: `DataJSON`
- Сигнатура: `bots.invokeWebViewCustomMethod(bot:InputUser, custom_method:string, params:DataJSON) -> DataJSON`
- Официальная страница: https://core.telegram.org/method/bots.invokeWebViewCustomMethod
- Параметры:
  - `bot`: `InputUser`
  - `custom_method`: `string`
  - `params`: `DataJSON`

### `bots.reorderPreviewMedias`

- Кратко: Изменить порядок превью medias.
- ID: `-1238895702` / `0xb627f3aa`
- Return type: `Bool`
- Сигнатура: `bots.reorderPreviewMedias(bot:InputUser, lang_code:string, order:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.reorderPreviewMedias
- Параметры:
  - `bot`: `InputUser`
  - `lang_code`: `string`
  - `order`: `Vector`

### `bots.reorderUsernames`

- Кратко: Изменить порядок username.
- ID: `-1760972350` / `0x9709b1c2`
- Return type: `Bool`
- Сигнатура: `bots.reorderUsernames(bot:InputUser, order:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.reorderUsernames
- Параметры:
  - `bot`: `InputUser`
  - `order`: `Vector`

### `bots.resetBotCommands`

- Кратко: Сбросить бота commands.
- ID: `1032708345` / `0x3d8de0f9`
- Return type: `Bool`
- Сигнатура: `bots.resetBotCommands(scope:BotCommandScope, lang_code:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.resetBotCommands
- Параметры:
  - `scope`: `BotCommandScope`
  - `lang_code`: `string`

### `bots.sendCustomRequest`

- Кратко: Отправить кастомные запрос.
- ID: `-1440257555` / `0xaa2769ed`
- Return type: `DataJSON`
- Сигнатура: `bots.sendCustomRequest(custom_method:string, params:DataJSON) -> DataJSON`
- Официальная страница: https://core.telegram.org/method/bots.sendCustomRequest
- Параметры:
  - `custom_method`: `string`
  - `params`: `DataJSON`

### `bots.setBotBroadcastDefaultAdminRights`

- Кратко: Установить бота эфир/трансляцию default админа rights.
- ID: `2021942497` / `0x788464e1`
- Return type: `Bool`
- Сигнатура: `bots.setBotBroadcastDefaultAdminRights(admin_rights:ChatAdminRights) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.setBotBroadcastDefaultAdminRights
- Параметры:
  - `admin_rights`: `ChatAdminRights`

### `bots.setBotCommands`

- Кратко: Установить бота commands.
- ID: `85399130` / `0x0517165a`
- Return type: `Bool`
- Сигнатура: `bots.setBotCommands(scope:BotCommandScope, lang_code:string, commands:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.setBotCommands
- Параметры:
  - `scope`: `BotCommandScope`
  - `lang_code`: `string`
  - `commands`: `Vector`

### `bots.setBotGroupDefaultAdminRights`

- Кратко: Установить бота группу default админа rights.
- ID: `-1839281686` / `0x925ec9ea`
- Return type: `Bool`
- Сигнатура: `bots.setBotGroupDefaultAdminRights(admin_rights:ChatAdminRights) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.setBotGroupDefaultAdminRights
- Параметры:
  - `admin_rights`: `ChatAdminRights`

### `bots.setBotInfo`

- Кратко: Установить бота информацию.
- ID: `282013987` / `0x10cf3123`
- Return type: `Bool`
- Сигнатура: `bots.setBotInfo(flags:#, bot:flags.2?InputUser, lang_code:string, name:flags.3?string, about:flags.0?string, description:flags.1?string) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.setBotInfo
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `bot`: `flags.2?InputUser` - optional через flags.2
  - `lang_code`: `string`
  - `name`: `flags.3?string` - optional через flags.3
  - `about`: `flags.0?string` - optional через flags.0
  - `description`: `flags.1?string` - optional через flags.1

### `bots.setBotMenuButton`

- Кратко: Установить бота меню button.
- ID: `1157944655` / `0x4504d54f`
- Return type: `Bool`
- Сигнатура: `bots.setBotMenuButton(user_id:InputUser, button:BotMenuButton) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.setBotMenuButton
- Параметры:
  - `user_id`: `InputUser`
  - `button`: `BotMenuButton`

### `bots.setCustomVerification`

- Кратко: Установить кастомные verification.
- ID: `-1953898563` / `0x8b89dfbd`
- Return type: `Bool`
- Сигнатура: `bots.setCustomVerification(flags:#, enabled:flags.1?true, bot:flags.0?InputUser, peer:InputPeer, custom_description:flags.2?string) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.setCustomVerification
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `enabled`: `flags.1?true` - optional через flags.1
  - `bot`: `flags.0?InputUser` - optional через flags.0
  - `peer`: `InputPeer`
  - `custom_description`: `flags.2?string` - optional через flags.2

### `bots.toggleUserEmojiStatusPermission`

- Кратко: Включить/выключить пользователя эмодзи статус permission.
- ID: `115237778` / `0x06de6392`
- Return type: `Bool`
- Сигнатура: `bots.toggleUserEmojiStatusPermission(bot:InputUser, enabled:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.toggleUserEmojiStatusPermission
- Параметры:
  - `bot`: `InputUser`
  - `enabled`: `Bool`

### `bots.toggleUsername`

- Кратко: Включить/выключить username.
- ID: `87861619` / `0x053ca973`
- Return type: `Bool`
- Сигнатура: `bots.toggleUsername(bot:InputUser, username:string, active:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.toggleUsername
- Параметры:
  - `bot`: `InputUser`
  - `username`: `string`
  - `active`: `Bool`

### `bots.updateStarRefProgram`

- Кратко: Обновить звезду/Stars ref program.
- ID: `2005621427` / `0x778b5ab3`
- Return type: `StarRefProgram`
- Сигнатура: `bots.updateStarRefProgram(flags:#, bot:InputUser, commission_permille:int, duration_months:flags.0?int) -> StarRefProgram`
- Официальная страница: https://core.telegram.org/method/bots.updateStarRefProgram
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `bot`: `InputUser`
  - `commission_permille`: `int`
  - `duration_months`: `flags.0?int` - optional через flags.0

### `bots.updateUserEmojiStatus`

- Кратко: Обновить пользователя эмодзи статус.
- ID: `-308334395` / `0xed9f30c5`
- Return type: `Bool`
- Сигнатура: `bots.updateUserEmojiStatus(user_id:InputUser, emoji_status:EmojiStatus) -> Bool`
- Официальная страница: https://core.telegram.org/method/bots.updateUserEmojiStatus
- Параметры:
  - `user_id`: `InputUser`
  - `emoji_status`: `EmojiStatus`

## channels

### `channels.checkSearchPostsFlood`

- Кратко: Проверить поиск posts flood.
- ID: `576090389` / `0x22567115`
- Return type: `SearchPostsFlood`
- Сигнатура: `channels.checkSearchPostsFlood(flags:#, query:flags.0?string) -> SearchPostsFlood`
- Официальная страница: https://core.telegram.org/method/channels.checkSearchPostsFlood
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `query`: `flags.0?string` - optional через flags.0

### `channels.checkUsername`

- Кратко: Проверить username.
- ID: `283557164` / `0x10e6bd2c`
- Return type: `Bool`
- Сигнатура: `channels.checkUsername(channel:InputChannel, username:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.checkUsername
- Параметры:
  - `channel`: `InputChannel`
  - `username`: `string`

### `channels.convertToGigagroup`

- Кратко: Конвертировать to гигагруппу.
- ID: `187239529` / `0x0b290c69`
- Return type: `Updates`
- Сигнатура: `channels.convertToGigagroup(channel:InputChannel) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.convertToGigagroup
- Параметры:
  - `channel`: `InputChannel`

### `channels.createChannel`

- Кратко: Создать канал.
- ID: `-1862244601` / `0x91006707`
- Return type: `Updates`
- Сигнатура: `channels.createChannel(flags:#, broadcast:flags.0?true, megagroup:flags.1?true, for_import:flags.3?true, forum:flags.5?true, title:string, about:string, geo_point:flags.2?InputGeoPoint, address:flags.2?string, ttl_period:flags.4?int) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.createChannel
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `broadcast`: `flags.0?true` - optional через flags.0
  - `megagroup`: `flags.1?true` - optional через flags.1
  - `for_import`: `flags.3?true` - optional через flags.3
  - `forum`: `flags.5?true` - optional через flags.5
  - `title`: `string`
  - `about`: `string`
  - `geo_point`: `flags.2?InputGeoPoint` - optional через flags.2
  - `address`: `flags.2?string` - optional через flags.2
  - `ttl_period`: `flags.4?int` - optional через flags.4

### `channels.createForumTopic`

- Кратко: См. официальную страницу метода createForumTopic.
- ID: `-200539612` / `0xf40c0224`
- Return type: `Updates`
- Сигнатура: `channels.createForumTopic(flags:#, channel:InputChannel, title:string, icon_color:flags.0?int, icon_emoji_id:flags.3?long, random_id:long, send_as:flags.2?InputPeer) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.createForumTopic
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `channel`: `InputChannel`
  - `title`: `string`
  - `icon_color`: `flags.0?int` - optional через flags.0
  - `icon_emoji_id`: `flags.3?long` - optional через flags.3
  - `random_id`: `long`
  - `send_as`: `flags.2?InputPeer` - optional через flags.2

### `channels.deactivateAllUsernames`

- Кратко: Операция с deactivate all username.
- ID: `170155475` / `0x0a245dd3`
- Return type: `Bool`
- Сигнатура: `channels.deactivateAllUsernames(channel:InputChannel) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.deactivateAllUsernames
- Параметры:
  - `channel`: `InputChannel`

### `channels.deleteChannel`

- Кратко: Удалить канал.
- ID: `-1072619549` / `0xc0111fe3`
- Return type: `Updates`
- Сигнатура: `channels.deleteChannel(channel:InputChannel) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.deleteChannel
- Параметры:
  - `channel`: `InputChannel`

### `channels.deleteHistory`

- Кратко: Удалить историю.
- ID: `-1683319225` / `0x9baa9647`
- Return type: `Updates`
- Сигнатура: `channels.deleteHistory(flags:#, for_everyone:flags.0?true, channel:InputChannel, max_id:int) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.deleteHistory
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `for_everyone`: `flags.0?true` - optional через flags.0
  - `channel`: `InputChannel`
  - `max_id`: `int`

### `channels.deleteMessages`

- Кратко: Удалить сообщения.
- ID: `-2067661490` / `0x84c1fd4e`
- Return type: `messages.AffectedMessages`
- Сигнатура: `channels.deleteMessages(channel:InputChannel, id:Vector) -> messages.AffectedMessages`
- Официальная страница: https://core.telegram.org/method/channels.deleteMessages
- Параметры:
  - `channel`: `InputChannel`
  - `id`: `Vector`

### `channels.deleteParticipantHistory`

- Кратко: Удалить участника историю.
- ID: `913655003` / `0x367544db`
- Return type: `messages.AffectedHistory`
- Сигнатура: `channels.deleteParticipantHistory(channel:InputChannel, participant:InputPeer) -> messages.AffectedHistory`
- Официальная страница: https://core.telegram.org/method/channels.deleteParticipantHistory
- Параметры:
  - `channel`: `InputChannel`
  - `participant`: `InputPeer`

### `channels.deleteTopicHistory`

- Кратко: См. официальную страницу метода deleteTopicHistory.
- ID: `876830509` / `0x34435f2d`
- Return type: `messages.AffectedHistory`
- Сигнатура: `channels.deleteTopicHistory(channel:InputChannel, top_msg_id:int) -> messages.AffectedHistory`
- Официальная страница: https://core.telegram.org/method/channels.deleteTopicHistory
- Параметры:
  - `channel`: `InputChannel`
  - `top_msg_id`: `int`

### `channels.editAdmin`

- Кратко: Изменить админа.
- ID: `-751007486` / `0xd33c8902`
- Return type: `Updates`
- Сигнатура: `channels.editAdmin(channel:InputChannel, user_id:InputUser, admin_rights:ChatAdminRights, rank:string) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.editAdmin
- Параметры:
  - `channel`: `InputChannel`
  - `user_id`: `InputUser`
  - `admin_rights`: `ChatAdminRights`
  - `rank`: `string`

### `channels.editBanned`

- Кратко: Изменить banned.
- ID: `-1763259007` / `0x96e6cd81`
- Return type: `Updates`
- Сигнатура: `channels.editBanned(channel:InputChannel, participant:InputPeer, banned_rights:ChatBannedRights) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.editBanned
- Параметры:
  - `channel`: `InputChannel`
  - `participant`: `InputPeer`
  - `banned_rights`: `ChatBannedRights`

### `channels.editCreator`

- Кратко: Изменить creator.
- ID: `-1892102881` / `0x8f38cd1f`
- Return type: `Updates`
- Сигнатура: `channels.editCreator(channel:InputChannel, user_id:InputUser, password:InputCheckPasswordSRP) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.editCreator
- Параметры:
  - `channel`: `InputChannel`
  - `user_id`: `InputUser`
  - `password`: `InputCheckPasswordSRP`

### `channels.editForumTopic`

- Кратко: См. официальную страницу метода editForumTopic.
- ID: `-186670715` / `0xf4dfa185`
- Return type: `Updates`
- Сигнатура: `channels.editForumTopic(flags:#, channel:InputChannel, topic_id:int, title:flags.0?string, icon_emoji_id:flags.1?long, closed:flags.2?Bool, hidden:flags.3?Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.editForumTopic
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `channel`: `InputChannel`
  - `topic_id`: `int`
  - `title`: `flags.0?string` - optional через flags.0
  - `icon_emoji_id`: `flags.1?long` - optional через flags.1
  - `closed`: `flags.2?Bool` - optional через flags.2
  - `hidden`: `flags.3?Bool` - optional через flags.3

### `channels.editLocation`

- Кратко: Изменить локацию.
- ID: `1491484525` / `0x58e63f6d`
- Return type: `Bool`
- Сигнатура: `channels.editLocation(channel:InputChannel, geo_point:InputGeoPoint, address:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.editLocation
- Параметры:
  - `channel`: `InputChannel`
  - `geo_point`: `InputGeoPoint`
  - `address`: `string`

### `channels.editPhoto`

- Кратко: Изменить фото.
- ID: `-248621111` / `0xf12e57c9`
- Return type: `Updates`
- Сигнатура: `channels.editPhoto(channel:InputChannel, photo:InputChatPhoto) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.editPhoto
- Параметры:
  - `channel`: `InputChannel`
  - `photo`: `InputChatPhoto`

### `channels.editTitle`

- Кратко: Изменить заголовок.
- ID: `1450044624` / `0x566decd0`
- Return type: `Updates`
- Сигнатура: `channels.editTitle(channel:InputChannel, title:string) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.editTitle
- Параметры:
  - `channel`: `InputChannel`
  - `title`: `string`

### `channels.exportMessageLink`

- Кратко: Экспортировать сообщение ссылку.
- ID: `-432034325` / `0xe63fadeb`
- Return type: `ExportedMessageLink`
- Сигнатура: `channels.exportMessageLink(flags:#, grouped:flags.0?true, thread:flags.1?true, channel:InputChannel, id:int) -> ExportedMessageLink`
- Официальная страница: https://core.telegram.org/method/channels.exportMessageLink
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `grouped`: `flags.0?true` - optional через flags.0
  - `thread`: `flags.1?true` - optional через flags.1
  - `channel`: `InputChannel`
  - `id`: `int`

### `channels.getAdminLog`

- Кратко: Получить админа log.
- ID: `870184064` / `0x33ddf480`
- Return type: `channels.AdminLogResults`
- Сигнатура: `channels.getAdminLog(flags:#, channel:InputChannel, q:string, events_filter:flags.0?ChannelAdminLogEventsFilter, admins:flags.1?Vector, max_id:long, min_id:long, limit:int) -> channels.AdminLogResults`
- Официальная страница: https://core.telegram.org/method/channels.getAdminLog
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `channel`: `InputChannel`
  - `q`: `string`
  - `events_filter`: `flags.0?ChannelAdminLogEventsFilter` - optional через flags.0
  - `admins`: `flags.1?Vector` - optional через flags.1
  - `max_id`: `long`
  - `min_id`: `long`
  - `limit`: `int`

### `channels.getAdminedPublicChannels`

- Кратко: Получить admined публичные каналы.
- ID: `-122669393` / `0xf8b036af`
- Return type: `messages.Chats`
- Сигнатура: `channels.getAdminedPublicChannels(flags:#, by_location:flags.0?true, check_limit:flags.1?true, for_personal:flags.2?true) -> messages.Chats`
- Официальная страница: https://core.telegram.org/method/channels.getAdminedPublicChannels
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `by_location`: `flags.0?true` - optional через flags.0
  - `check_limit`: `flags.1?true` - optional через flags.1
  - `for_personal`: `flags.2?true` - optional через flags.2

### `channels.getChannelRecommendations`

- Кратко: Получить канал recommendations.
- ID: `631707458` / `0x25a71742`
- Return type: `messages.Chats`
- Сигнатура: `channels.getChannelRecommendations(flags:#, channel:flags.0?InputChannel) -> messages.Chats`
- Официальная страница: https://core.telegram.org/method/channels.getChannelRecommendations
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `channel`: `flags.0?InputChannel` - optional через flags.0

### `channels.getChannels`

- Кратко: Получить каналы.
- ID: `176122811` / `0x0a7f6bbb`
- Return type: `messages.Chats`
- Сигнатура: `channels.getChannels(id:Vector) -> messages.Chats`
- Официальная страница: https://core.telegram.org/method/channels.getChannels
- Параметры:
  - `id`: `Vector`

### `channels.getForumTopics`

- Кратко: См. официальную страницу метода getForumTopics.
- ID: `233136337` / `0x0de560d1`
- Return type: `messages.ForumTopics`
- Сигнатура: `channels.getForumTopics(flags:#, channel:InputChannel, q:flags.0?string, offset_date:int, offset_id:int, offset_topic:int, limit:int) -> messages.ForumTopics`
- Официальная страница: https://core.telegram.org/method/channels.getForumTopics
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `channel`: `InputChannel`
  - `q`: `flags.0?string` - optional через flags.0
  - `offset_date`: `int`
  - `offset_id`: `int`
  - `offset_topic`: `int`
  - `limit`: `int`

### `channels.getForumTopicsByID`

- Кратко: См. официальную страницу метода getForumTopicsByID.
- ID: `-1333584199` / `0xb0831eb9`
- Return type: `messages.ForumTopics`
- Сигнатура: `channels.getForumTopicsByID(channel:InputChannel, topics:Vector) -> messages.ForumTopics`
- Официальная страница: https://core.telegram.org/method/channels.getForumTopicsByID
- Параметры:
  - `channel`: `InputChannel`
  - `topics`: `Vector`

### `channels.getFullChannel`

- Кратко: Получить полную информацию о канал.
- ID: `141781513` / `0x08736a09`
- Return type: `messages.ChatFull`
- Сигнатура: `channels.getFullChannel(channel:InputChannel) -> messages.ChatFull`
- Официальная страница: https://core.telegram.org/method/channels.getFullChannel
- Параметры:
  - `channel`: `InputChannel`

### `channels.getGroupsForDiscussion`

- Кратко: Получить groups for обсуждение.
- ID: `-170208392` / `0xf5dad378`
- Return type: `messages.Chats`
- Сигнатура: `channels.getGroupsForDiscussion() -> messages.Chats`
- Официальная страница: https://core.telegram.org/method/channels.getGroupsForDiscussion
- Параметры:
  - Нет параметров.

### `channels.getInactiveChannels`

- Кратко: Получить inactive каналы.
- ID: `300429806` / `0x11e831ee`
- Return type: `messages.InactiveChats`
- Сигнатура: `channels.getInactiveChannels() -> messages.InactiveChats`
- Официальная страница: https://core.telegram.org/method/channels.getInactiveChannels
- Параметры:
  - Нет параметров.

### `channels.getLeftChannels`

- Кратко: Получить left каналы.
- ID: `-2092831552` / `0x8341ecc0`
- Return type: `messages.Chats`
- Сигнатура: `channels.getLeftChannels(offset:int) -> messages.Chats`
- Официальная страница: https://core.telegram.org/method/channels.getLeftChannels
- Параметры:
  - `offset`: `int`

### `channels.getMessageAuthor`

- Кратко: Получить сообщение author.
- ID: `-320691994` / `0xece2a0e6`
- Return type: `User`
- Сигнатура: `channels.getMessageAuthor(channel:InputChannel, id:int) -> User`
- Официальная страница: https://core.telegram.org/method/channels.getMessageAuthor
- Параметры:
  - `channel`: `InputChannel`
  - `id`: `int`

### `channels.getMessages`

- Кратко: Получить сообщения.
- ID: `-1383294429` / `0xad8c9a23`
- Return type: `messages.Messages`
- Сигнатура: `channels.getMessages(channel:InputChannel, id:Vector) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/channels.getMessages
- Параметры:
  - `channel`: `InputChannel`
  - `id`: `Vector`

### `channels.getParticipant`

- Кратко: Получить участника.
- ID: `-1599378234` / `0xa0ab6cc6`
- Return type: `channels.ChannelParticipant`
- Сигнатура: `channels.getParticipant(channel:InputChannel, participant:InputPeer) -> channels.ChannelParticipant`
- Официальная страница: https://core.telegram.org/method/channels.getParticipant
- Параметры:
  - `channel`: `InputChannel`
  - `participant`: `InputPeer`

### `channels.getParticipants`

- Кратко: Получить участников.
- ID: `2010044880` / `0x77ced9d0`
- Return type: `channels.ChannelParticipants`
- Сигнатура: `channels.getParticipants(channel:InputChannel, filter:ChannelParticipantsFilter, offset:int, limit:int, hash:long) -> channels.ChannelParticipants`
- Официальная страница: https://core.telegram.org/method/channels.getParticipants
- Параметры:
  - `channel`: `InputChannel`
  - `filter`: `ChannelParticipantsFilter`
  - `offset`: `int`
  - `limit`: `int`
  - `hash`: `long`

### `channels.getSendAs`

- Кратко: Получить send as.
- ID: `-410672065` / `0xe785a43f`
- Return type: `channels.SendAsPeers`
- Сигнатура: `channels.getSendAs(flags:#, for_paid_reactions:flags.0?true, peer:InputPeer) -> channels.SendAsPeers`
- Официальная страница: https://core.telegram.org/method/channels.getSendAs
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `for_paid_reactions`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`

### `channels.inviteToChannel`

- Кратко: Пригласить to канал.
- ID: `-907854508` / `0xc9e33d54`
- Return type: `messages.InvitedUsers`
- Сигнатура: `channels.inviteToChannel(channel:InputChannel, users:Vector) -> messages.InvitedUsers`
- Официальная страница: https://core.telegram.org/method/channels.inviteToChannel
- Параметры:
  - `channel`: `InputChannel`
  - `users`: `Vector`

### `channels.joinChannel`

- Кратко: Присоединиться к канал.
- ID: `615851205` / `0x24b524c5`
- Return type: `Updates`
- Сигнатура: `channels.joinChannel(channel:InputChannel) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.joinChannel
- Параметры:
  - `channel`: `InputChannel`

### `channels.leaveChannel`

- Кратко: Покинуть канал.
- ID: `-130635115` / `0xf836aa95`
- Return type: `Updates`
- Сигнатура: `channels.leaveChannel(channel:InputChannel) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.leaveChannel
- Параметры:
  - `channel`: `InputChannel`

### `channels.readHistory`

- Кратко: Пометить как прочитанное / прочитать историю.
- ID: `-871347913` / `0xcc104937`
- Return type: `Bool`
- Сигнатура: `channels.readHistory(channel:InputChannel, max_id:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.readHistory
- Параметры:
  - `channel`: `InputChannel`
  - `max_id`: `int`

### `channels.readMessageContents`

- Кратко: Пометить как прочитанное / прочитать сообщение contents.
- ID: `-357180360` / `0xeab5dc38`
- Return type: `Bool`
- Сигнатура: `channels.readMessageContents(channel:InputChannel, id:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.readMessageContents
- Параметры:
  - `channel`: `InputChannel`
  - `id`: `Vector`

### `channels.reorderPinnedForumTopics`

- Кратко: См. официальную страницу метода reorderPinnedForumTopics.
- ID: `693150095` / `0x2950a18f`
- Return type: `Updates`
- Сигнатура: `channels.reorderPinnedForumTopics(flags:#, force:flags.0?true, channel:InputChannel, order:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.reorderPinnedForumTopics
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `force`: `flags.0?true` - optional через flags.0
  - `channel`: `InputChannel`
  - `order`: `Vector`

### `channels.reorderUsernames`

- Кратко: Изменить порядок username.
- ID: `-1268978403` / `0xb45ced1d`
- Return type: `Bool`
- Сигнатура: `channels.reorderUsernames(channel:InputChannel, order:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.reorderUsernames
- Параметры:
  - `channel`: `InputChannel`
  - `order`: `Vector`

### `channels.reportAntiSpamFalsePositive`

- Кратко: Пожаловаться / сообщить о анти спам ложное срабатывание.
- ID: `-1471109485` / `0xa850a693`
- Return type: `Bool`
- Сигнатура: `channels.reportAntiSpamFalsePositive(channel:InputChannel, msg_id:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.reportAntiSpamFalsePositive
- Параметры:
  - `channel`: `InputChannel`
  - `msg_id`: `int`

### `channels.reportSpam`

- Кратко: Пожаловаться / сообщить о спам.
- ID: `-196443371` / `0xf44a8315`
- Return type: `Bool`
- Сигнатура: `channels.reportSpam(channel:InputChannel, participant:InputPeer, id:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.reportSpam
- Параметры:
  - `channel`: `InputChannel`
  - `participant`: `InputPeer`
  - `id`: `Vector`

### `channels.restrictSponsoredMessages`

- Кратко: Операция с restrict спонсируемые сообщения.
- ID: `-1696000743` / `0x9ae91519`
- Return type: `Updates`
- Сигнатура: `channels.restrictSponsoredMessages(channel:InputChannel, restricted:Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.restrictSponsoredMessages
- Параметры:
  - `channel`: `InputChannel`
  - `restricted`: `Bool`

### `channels.searchPosts`

- Кратко: Искать posts.
- ID: `-221973939` / `0xf2c4f24d`
- Return type: `messages.Messages`
- Сигнатура: `channels.searchPosts(flags:#, hashtag:flags.0?string, query:flags.1?string, offset_rate:int, offset_peer:InputPeer, offset_id:int, limit:int, allow_paid_stars:flags.2?long) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/channels.searchPosts
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `hashtag`: `flags.0?string` - optional через flags.0
  - `query`: `flags.1?string` - optional через flags.1
  - `offset_rate`: `int`
  - `offset_peer`: `InputPeer`
  - `offset_id`: `int`
  - `limit`: `int`
  - `allow_paid_stars`: `flags.2?long` - optional через flags.2

### `channels.setBoostsToUnblockRestrictions`

- Кратко: Установить бусты to unblock restrictions.
- ID: `-1388733202` / `0xad399cee`
- Return type: `Updates`
- Сигнатура: `channels.setBoostsToUnblockRestrictions(channel:InputChannel, boosts:int) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.setBoostsToUnblockRestrictions
- Параметры:
  - `channel`: `InputChannel`
  - `boosts`: `int`

### `channels.setDiscussionGroup`

- Кратко: Установить обсуждение группу.
- ID: `1079520178` / `0x40582bb2`
- Return type: `Bool`
- Сигнатура: `channels.setDiscussionGroup(broadcast:InputChannel, group:InputChannel) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.setDiscussionGroup
- Параметры:
  - `broadcast`: `InputChannel`
  - `group`: `InputChannel`

### `channels.setEmojiStickers`

- Кратко: Установить эмодзи стикеры.
- ID: `1020866743` / `0x3cd930b7`
- Return type: `Bool`
- Сигнатура: `channels.setEmojiStickers(channel:InputChannel, stickerset:InputStickerSet) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.setEmojiStickers
- Параметры:
  - `channel`: `InputChannel`
  - `stickerset`: `InputStickerSet`

### `channels.setMainProfileTab`

- Кратко: Установить основное профиль tab.
- ID: `897842353` / `0x3583fcb1`
- Return type: `Bool`
- Сигнатура: `channels.setMainProfileTab(channel:InputChannel, tab:ProfileTab) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.setMainProfileTab
- Параметры:
  - `channel`: `InputChannel`
  - `tab`: `ProfileTab`

### `channels.setStickers`

- Кратко: Установить стикеры.
- ID: `-359881479` / `0xea8ca4f9`
- Return type: `Bool`
- Сигнатура: `channels.setStickers(channel:InputChannel, stickerset:InputStickerSet) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.setStickers
- Параметры:
  - `channel`: `InputChannel`
  - `stickerset`: `InputStickerSet`

### `channels.toggleAntiSpam`

- Кратко: Включить/выключить анти спам.
- ID: `1760814315` / `0x68f3e4eb`
- Return type: `Updates`
- Сигнатура: `channels.toggleAntiSpam(channel:InputChannel, enabled:Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.toggleAntiSpam
- Параметры:
  - `channel`: `InputChannel`
  - `enabled`: `Bool`

### `channels.toggleAutotranslation`

- Кратко: Включить/выключить autotranslation.
- ID: `377471137` / `0x167fc0a1`
- Return type: `Updates`
- Сигнатура: `channels.toggleAutotranslation(channel:InputChannel, enabled:Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.toggleAutotranslation
- Параметры:
  - `channel`: `InputChannel`
  - `enabled`: `Bool`

### `channels.toggleForum`

- Кратко: Включить/выключить форум.
- ID: `1073174324` / `0x3ff75734`
- Return type: `Updates`
- Сигнатура: `channels.toggleForum(channel:InputChannel, enabled:Bool, tabs:Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.toggleForum
- Параметры:
  - `channel`: `InputChannel`
  - `enabled`: `Bool`
  - `tabs`: `Bool`

### `channels.toggleJoinRequest`

- Кратко: Включить/выключить вход запрос.
- ID: `1277789622` / `0x4c2985b6`
- Return type: `Updates`
- Сигнатура: `channels.toggleJoinRequest(channel:InputChannel, enabled:Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.toggleJoinRequest
- Параметры:
  - `channel`: `InputChannel`
  - `enabled`: `Bool`

### `channels.toggleJoinToSend`

- Кратко: Включить/выключить вход to send.
- ID: `-456419968` / `0xe4cb9580`
- Return type: `Updates`
- Сигнатура: `channels.toggleJoinToSend(channel:InputChannel, enabled:Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.toggleJoinToSend
- Параметры:
  - `channel`: `InputChannel`
  - `enabled`: `Bool`

### `channels.toggleParticipantsHidden`

- Кратко: Включить/выключить участников hidden.
- ID: `1785624660` / `0x6a6e7854`
- Return type: `Updates`
- Сигнатура: `channels.toggleParticipantsHidden(channel:InputChannel, enabled:Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.toggleParticipantsHidden
- Параметры:
  - `channel`: `InputChannel`
  - `enabled`: `Bool`

### `channels.togglePreHistoryHidden`

- Кратко: Включить/выключить pre историю hidden.
- ID: `-356796084` / `0xeabbb94c`
- Return type: `Updates`
- Сигнатура: `channels.togglePreHistoryHidden(channel:InputChannel, enabled:Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.togglePreHistoryHidden
- Параметры:
  - `channel`: `InputChannel`
  - `enabled`: `Bool`

### `channels.toggleSignatures`

- Кратко: Включить/выключить signatures.
- ID: `1099781276` / `0x418d549c`
- Return type: `Updates`
- Сигнатура: `channels.toggleSignatures(flags:#, signatures_enabled:flags.0?true, profiles_enabled:flags.1?true, channel:InputChannel) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.toggleSignatures
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `signatures_enabled`: `flags.0?true` - optional через flags.0
  - `profiles_enabled`: `flags.1?true` - optional через flags.1
  - `channel`: `InputChannel`

### `channels.toggleSlowMode`

- Кратко: Включить/выключить медленный режим.
- ID: `-304832784` / `0xedd49ef0`
- Return type: `Updates`
- Сигнатура: `channels.toggleSlowMode(channel:InputChannel, seconds:int) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.toggleSlowMode
- Параметры:
  - `channel`: `InputChannel`
  - `seconds`: `int`

### `channels.toggleUsername`

- Кратко: Включить/выключить username.
- ID: `1358053637` / `0x50f24105`
- Return type: `Bool`
- Сигнатура: `channels.toggleUsername(channel:InputChannel, username:string, active:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.toggleUsername
- Параметры:
  - `channel`: `InputChannel`
  - `username`: `string`
  - `active`: `Bool`

### `channels.toggleViewForumAsMessages`

- Кратко: Включить/выключить view форум as сообщения.
- ID: `-1757889771` / `0x9738bb15`
- Return type: `Updates`
- Сигнатура: `channels.toggleViewForumAsMessages(channel:InputChannel, enabled:Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.toggleViewForumAsMessages
- Параметры:
  - `channel`: `InputChannel`
  - `enabled`: `Bool`

### `channels.updateColor`

- Кратко: Обновить color.
- ID: `-659933583` / `0xd8aa3671`
- Return type: `Updates`
- Сигнатура: `channels.updateColor(flags:#, for_profile:flags.1?true, channel:InputChannel, color:flags.2?int, background_emoji_id:flags.0?long) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.updateColor
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `for_profile`: `flags.1?true` - optional через flags.1
  - `channel`: `InputChannel`
  - `color`: `flags.2?int` - optional через flags.2
  - `background_emoji_id`: `flags.0?long` - optional через flags.0

### `channels.updateEmojiStatus`

- Кратко: Обновить эмодзи статус.
- ID: `-254548312` / `0xf0d3e6a8`
- Return type: `Updates`
- Сигнатура: `channels.updateEmojiStatus(channel:InputChannel, emoji_status:EmojiStatus) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.updateEmojiStatus
- Параметры:
  - `channel`: `InputChannel`
  - `emoji_status`: `EmojiStatus`

### `channels.updatePaidMessagesPrice`

- Кратко: Обновить платные сообщения price.
- ID: `1259483771` / `0x4b12327b`
- Return type: `Updates`
- Сигнатура: `channels.updatePaidMessagesPrice(flags:#, broadcast_messages_allowed:flags.0?true, channel:InputChannel, send_paid_messages_stars:long) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.updatePaidMessagesPrice
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `broadcast_messages_allowed`: `flags.0?true` - optional через flags.0
  - `channel`: `InputChannel`
  - `send_paid_messages_stars`: `long`

### `channels.updatePinnedForumTopic`

- Кратко: См. официальную страницу метода updatePinnedForumTopic.
- ID: `1814925350` / `0x6c2d9026`
- Return type: `Updates`
- Сигнатура: `channels.updatePinnedForumTopic(channel:InputChannel, topic_id:int, pinned:Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/channels.updatePinnedForumTopic
- Параметры:
  - `channel`: `InputChannel`
  - `topic_id`: `int`
  - `pinned`: `Bool`

### `channels.updateUsername`

- Кратко: Обновить username.
- ID: `890549214` / `0x3514b3de`
- Return type: `Bool`
- Сигнатура: `channels.updateUsername(channel:InputChannel, username:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/channels.updateUsername
- Параметры:
  - `channel`: `InputChannel`
  - `username`: `string`

## chatlists

### `chatlists.checkChatlistInvite`

- Кратко: Проверить папку/список чатов приглашение.
- ID: `1103171583` / `0x41c10fff`
- Return type: `chatlists.ChatlistInvite`
- Сигнатура: `chatlists.checkChatlistInvite(slug:string) -> chatlists.ChatlistInvite`
- Официальная страница: https://core.telegram.org/method/chatlists.checkChatlistInvite
- Параметры:
  - `slug`: `string`

### `chatlists.deleteExportedInvite`

- Кратко: Удалить экспортированную приглашение.
- ID: `1906072670` / `0x719c5c5e`
- Return type: `Bool`
- Сигнатура: `chatlists.deleteExportedInvite(chatlist:InputChatlist, slug:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/chatlists.deleteExportedInvite
- Параметры:
  - `chatlist`: `InputChatlist`
  - `slug`: `string`

### `chatlists.editExportedInvite`

- Кратко: Изменить экспортированные приглашение.
- ID: `1698543165` / `0x653db63d`
- Return type: `ExportedChatlistInvite`
- Сигнатура: `chatlists.editExportedInvite(flags:#, chatlist:InputChatlist, slug:string, title:flags.1?string, peers:flags.2?Vector) -> ExportedChatlistInvite`
- Официальная страница: https://core.telegram.org/method/chatlists.editExportedInvite
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `chatlist`: `InputChatlist`
  - `slug`: `string`
  - `title`: `flags.1?string` - optional через flags.1
  - `peers`: `flags.2?Vector` - optional через flags.2

### `chatlists.exportChatlistInvite`

- Кратко: Экспортировать папку/список чатов приглашение.
- ID: `-2072885362` / `0x8472478e`
- Return type: `chatlists.ExportedChatlistInvite`
- Сигнатура: `chatlists.exportChatlistInvite(chatlist:InputChatlist, title:string, peers:Vector) -> chatlists.ExportedChatlistInvite`
- Официальная страница: https://core.telegram.org/method/chatlists.exportChatlistInvite
- Параметры:
  - `chatlist`: `InputChatlist`
  - `title`: `string`
  - `peers`: `Vector`

### `chatlists.getChatlistUpdates`

- Кратко: Получить папку/список чатов updates.
- ID: `-1992190687` / `0x89419521`
- Return type: `chatlists.ChatlistUpdates`
- Сигнатура: `chatlists.getChatlistUpdates(chatlist:InputChatlist) -> chatlists.ChatlistUpdates`
- Официальная страница: https://core.telegram.org/method/chatlists.getChatlistUpdates
- Параметры:
  - `chatlist`: `InputChatlist`

### `chatlists.getExportedInvites`

- Кратко: Получить экспортированные invites.
- ID: `-838608253` / `0xce03da83`
- Return type: `chatlists.ExportedInvites`
- Сигнатура: `chatlists.getExportedInvites(chatlist:InputChatlist) -> chatlists.ExportedInvites`
- Официальная страница: https://core.telegram.org/method/chatlists.getExportedInvites
- Параметры:
  - `chatlist`: `InputChatlist`

### `chatlists.getLeaveChatlistSuggestions`

- Кратко: Получить выход папку/список чатов suggestions.
- ID: `-37955820` / `0xfdbcd714`
- Return type: `Vector`
- Сигнатура: `chatlists.getLeaveChatlistSuggestions(chatlist:InputChatlist) -> Vector`
- Официальная страница: https://core.telegram.org/method/chatlists.getLeaveChatlistSuggestions
- Параметры:
  - `chatlist`: `InputChatlist`

### `chatlists.hideChatlistUpdates`

- Кратко: Скрыть папку/список чатов updates.
- ID: `1726252795` / `0x66e486fb`
- Return type: `Bool`
- Сигнатура: `chatlists.hideChatlistUpdates(chatlist:InputChatlist) -> Bool`
- Официальная страница: https://core.telegram.org/method/chatlists.hideChatlistUpdates
- Параметры:
  - `chatlist`: `InputChatlist`

### `chatlists.joinChatlistInvite`

- Кратко: Присоединиться к папку/список чатов приглашение.
- ID: `-1498291302` / `0xa6b1e39a`
- Return type: `Updates`
- Сигнатура: `chatlists.joinChatlistInvite(slug:string, peers:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/chatlists.joinChatlistInvite
- Параметры:
  - `slug`: `string`
  - `peers`: `Vector`

### `chatlists.joinChatlistUpdates`

- Кратко: Присоединиться к папку/список чатов updates.
- ID: `-527828747` / `0xe089f8f5`
- Return type: `Updates`
- Сигнатура: `chatlists.joinChatlistUpdates(chatlist:InputChatlist, peers:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/chatlists.joinChatlistUpdates
- Параметры:
  - `chatlist`: `InputChatlist`
  - `peers`: `Vector`

### `chatlists.leaveChatlist`

- Кратко: Покинуть папку/список чатов.
- ID: `1962598714` / `0x74fae13a`
- Return type: `Updates`
- Сигнатура: `chatlists.leaveChatlist(chatlist:InputChatlist, peers:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/chatlists.leaveChatlist
- Параметры:
  - `chatlist`: `InputChatlist`
  - `peers`: `Vector`

## contacts

### `contacts.acceptContact`

- Кратко: Принять контакт.
- ID: `-130964977` / `0xf831a20f`
- Return type: `Updates`
- Сигнатура: `contacts.acceptContact(id:InputUser) -> Updates`
- Официальная страница: https://core.telegram.org/method/contacts.acceptContact
- Параметры:
  - `id`: `InputUser`

### `contacts.addContact`

- Кратко: Операция с add контакт.
- ID: `-386636848` / `0xe8f463d0`
- Return type: `Updates`
- Сигнатура: `contacts.addContact(flags:#, add_phone_privacy_exception:flags.0?true, id:InputUser, first_name:string, last_name:string, phone:string) -> Updates`
- Официальная страница: https://core.telegram.org/method/contacts.addContact
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `add_phone_privacy_exception`: `flags.0?true` - optional через flags.0
  - `id`: `InputUser`
  - `first_name`: `string`
  - `last_name`: `string`
  - `phone`: `string`

### `contacts.block`

- Кратко: Операция с блок.
- ID: `774801204` / `0x2e2e8734`
- Return type: `Bool`
- Сигнатура: `contacts.block(flags:#, my_stories_from:flags.0?true, id:InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/contacts.block
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `my_stories_from`: `flags.0?true` - optional через flags.0
  - `id`: `InputPeer`

### `contacts.blockFromReplies`

- Кратко: Операция с блок from ответы.
- ID: `698914348` / `0x29a8962c`
- Return type: `Updates`
- Сигнатура: `contacts.blockFromReplies(flags:#, delete_message:flags.0?true, delete_history:flags.1?true, report_spam:flags.2?true, msg_id:int) -> Updates`
- Официальная страница: https://core.telegram.org/method/contacts.blockFromReplies
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `delete_message`: `flags.0?true` - optional через flags.0
  - `delete_history`: `flags.1?true` - optional через flags.1
  - `report_spam`: `flags.2?true` - optional через flags.2
  - `msg_id`: `int`

### `contacts.deleteByPhones`

- Кратко: Удалить by phones.
- ID: `269745566` / `0x1013fd9e`
- Return type: `Bool`
- Сигнатура: `contacts.deleteByPhones(phones:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/contacts.deleteByPhones
- Параметры:
  - `phones`: `Vector`

### `contacts.deleteContacts`

- Кратко: Удалить контакты.
- ID: `157945344` / `0x096a0e00`
- Return type: `Updates`
- Сигнатура: `contacts.deleteContacts(id:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/contacts.deleteContacts
- Параметры:
  - `id`: `Vector`

### `contacts.editCloseFriends`

- Кратко: Изменить close friends.
- ID: `-1167653392` / `0xba6705f0`
- Return type: `Bool`
- Сигнатура: `contacts.editCloseFriends(id:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/contacts.editCloseFriends
- Параметры:
  - `id`: `Vector`

### `contacts.exportContactToken`

- Кратко: Экспортировать контакт токен.
- ID: `-127582169` / `0xf8654027`
- Return type: `ExportedContactToken`
- Сигнатура: `contacts.exportContactToken() -> ExportedContactToken`
- Официальная страница: https://core.telegram.org/method/contacts.exportContactToken
- Параметры:
  - Нет параметров.

### `contacts.getBirthdays`

- Кратко: Получить дни рождения.
- ID: `-621959068` / `0xdaeda864`
- Return type: `contacts.ContactBirthdays`
- Сигнатура: `contacts.getBirthdays() -> contacts.ContactBirthdays`
- Официальная страница: https://core.telegram.org/method/contacts.getBirthdays
- Параметры:
  - Нет параметров.

### `contacts.getBlocked`

- Кратко: Получить заблокированные.
- ID: `-1702457472` / `0x9a868f80`
- Return type: `contacts.Blocked`
- Сигнатура: `contacts.getBlocked(flags:#, my_stories_from:flags.0?true, offset:int, limit:int) -> contacts.Blocked`
- Официальная страница: https://core.telegram.org/method/contacts.getBlocked
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `my_stories_from`: `flags.0?true` - optional через flags.0
  - `offset`: `int`
  - `limit`: `int`

### `contacts.getContactIDs`

- Кратко: Получить контакт i ds.
- ID: `2061264541` / `0x7adc669d`
- Return type: `Vector`
- Сигнатура: `contacts.getContactIDs(hash:long) -> Vector`
- Официальная страница: https://core.telegram.org/method/contacts.getContactIDs
- Параметры:
  - `hash`: `long`

### `contacts.getContacts`

- Кратко: Получить контакты.
- ID: `1574346258` / `0x5dd69e12`
- Return type: `contacts.Contacts`
- Сигнатура: `contacts.getContacts(hash:long) -> contacts.Contacts`
- Официальная страница: https://core.telegram.org/method/contacts.getContacts
- Параметры:
  - `hash`: `long`

### `contacts.getLocated`

- Кратко: Получить людей рядом.
- ID: `-750207932` / `0xd348bc44`
- Return type: `Updates`
- Сигнатура: `contacts.getLocated(flags:#, background:flags.1?true, geo_point:InputGeoPoint, self_expires:flags.0?int) -> Updates`
- Официальная страница: https://core.telegram.org/method/contacts.getLocated
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `background`: `flags.1?true` - optional через flags.1
  - `geo_point`: `InputGeoPoint`
  - `self_expires`: `flags.0?int` - optional через flags.0

### `contacts.getSaved`

- Кратко: Получить сохранённые данными.
- ID: `-2098076769` / `0x82f1e39f`
- Return type: `Vector`
- Сигнатура: `contacts.getSaved() -> Vector`
- Официальная страница: https://core.telegram.org/method/contacts.getSaved
- Параметры:
  - Нет параметров.

### `contacts.getSponsoredPeers`

- Кратко: Получить спонсируемые пиры/диалоги.
- ID: `-1228356717` / `0xb6c8c393`
- Return type: `contacts.SponsoredPeers`
- Сигнатура: `contacts.getSponsoredPeers(q:string) -> contacts.SponsoredPeers`
- Официальная страница: https://core.telegram.org/method/contacts.getSponsoredPeers
- Параметры:
  - `q`: `string`

### `contacts.getStatuses`

- Кратко: Получить статусы.
- ID: `-995929106` / `0xc4a353ee`
- Return type: `Vector`
- Сигнатура: `contacts.getStatuses() -> Vector`
- Официальная страница: https://core.telegram.org/method/contacts.getStatuses
- Параметры:
  - Нет параметров.

### `contacts.getTopPeers`

- Кратко: Получить верх пиры/диалоги.
- ID: `-1758168906` / `0x973478b6`
- Return type: `contacts.TopPeers`
- Сигнатура: `contacts.getTopPeers(flags:#, correspondents:flags.0?true, bots_pm:flags.1?true, bots_inline:flags.2?true, phone_calls:flags.3?true, forward_users:flags.4?true, forward_chats:flags.5?true, groups:flags.10?true, channels:flags.15?true, bots_app:flags.16?true, offset:int, limit:int, hash:long) -> contacts.TopPeers`
- Официальная страница: https://core.telegram.org/method/contacts.getTopPeers
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `correspondents`: `flags.0?true` - optional через flags.0
  - `bots_pm`: `flags.1?true` - optional через flags.1
  - `bots_inline`: `flags.2?true` - optional через flags.2
  - `phone_calls`: `flags.3?true` - optional через flags.3
  - `forward_users`: `flags.4?true` - optional через flags.4
  - `forward_chats`: `flags.5?true` - optional через flags.5
  - `groups`: `flags.10?true` - optional через flags.10
  - `channels`: `flags.15?true` - optional через flags.15
  - `bots_app`: `flags.16?true` - optional через flags.16
  - `offset`: `int`
  - `limit`: `int`
  - `hash`: `long`

### `contacts.importContactToken`

- Кратко: Импортировать контакт токен.
- ID: `318789512` / `0x13005788`
- Return type: `User`
- Сигнатура: `contacts.importContactToken(token:string) -> User`
- Официальная страница: https://core.telegram.org/method/contacts.importContactToken
- Параметры:
  - `token`: `string`

### `contacts.importContacts`

- Кратко: Импортировать контакты.
- ID: `746589157` / `0x2c800be5`
- Return type: `contacts.ImportedContacts`
- Сигнатура: `contacts.importContacts(contacts:Vector) -> contacts.ImportedContacts`
- Официальная страница: https://core.telegram.org/method/contacts.importContacts
- Параметры:
  - `contacts`: `Vector`

### `contacts.resetSaved`

- Кратко: Сбросить сохранённое.
- ID: `-2020263951` / `0x879537f1`
- Return type: `Bool`
- Сигнатура: `contacts.resetSaved() -> Bool`
- Официальная страница: https://core.telegram.org/method/contacts.resetSaved
- Параметры:
  - Нет параметров.

### `contacts.resetTopPeerRating`

- Кратко: Сбросить верх peer/диалог rating.
- ID: `451113900` / `0x1ae373ac`
- Return type: `Bool`
- Сигнатура: `contacts.resetTopPeerRating(category:TopPeerCategory, peer:InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/contacts.resetTopPeerRating
- Параметры:
  - `category`: `TopPeerCategory`
  - `peer`: `InputPeer`

### `contacts.resolvePhone`

- Кратко: Разрешить / получить по ссылке телефон.
- ID: `-1963375804` / `0x8af94344`
- Return type: `contacts.ResolvedPeer`
- Сигнатура: `contacts.resolvePhone(phone:string) -> contacts.ResolvedPeer`
- Официальная страница: https://core.telegram.org/method/contacts.resolvePhone
- Параметры:
  - `phone`: `string`

### `contacts.resolveUsername`

- Кратко: Разрешить / получить по ссылке username.
- ID: `1918565308` / `0x725afbbc`
- Return type: `contacts.ResolvedPeer`
- Сигнатура: `contacts.resolveUsername(flags:#, username:string, referer:flags.0?string) -> contacts.ResolvedPeer`
- Официальная страница: https://core.telegram.org/method/contacts.resolveUsername
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `username`: `string`
  - `referer`: `flags.0?string` - optional через flags.0

### `contacts.search`

- Кратко: Искать данными.
- ID: `301470424` / `0x11f812d8`
- Return type: `contacts.Found`
- Сигнатура: `contacts.search(q:string, limit:int) -> contacts.Found`
- Официальная страница: https://core.telegram.org/method/contacts.search
- Параметры:
  - `q`: `string`
  - `limit`: `int`

### `contacts.setBlocked`

- Кратко: Установить заблокированные.
- ID: `-1798939530` / `0x94c65c76`
- Return type: `Bool`
- Сигнатура: `contacts.setBlocked(flags:#, my_stories_from:flags.0?true, id:Vector, limit:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/contacts.setBlocked
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `my_stories_from`: `flags.0?true` - optional через flags.0
  - `id`: `Vector`
  - `limit`: `int`

### `contacts.toggleTopPeers`

- Кратко: Включить/выключить верх пиры/диалоги.
- ID: `-2062238246` / `0x8514bdda`
- Return type: `Bool`
- Сигнатура: `contacts.toggleTopPeers(enabled:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/contacts.toggleTopPeers
- Параметры:
  - `enabled`: `Bool`

### `contacts.unblock`

- Кратко: Операция с unblock.
- ID: `-1252994264` / `0xb550d328`
- Return type: `Bool`
- Сигнатура: `contacts.unblock(flags:#, my_stories_from:flags.0?true, id:InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/contacts.unblock
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `my_stories_from`: `flags.0?true` - optional через flags.0
  - `id`: `InputPeer`

## core

### `initConnection`

- Кратко: См. официальную страницу метода initConnection.
- ID: `-1043505495` / `0xc1cd5ea9`
- Return type: `X`
- Сигнатура: `initConnection(flags:#, api_id:int, device_model:string, system_version:string, app_version:string, system_lang_code:string, lang_pack:string, lang_code:string, proxy:flags.0?InputClientProxy, params:flags.1?JSONValue, query:!X) -> X`
- Официальная страница: https://core.telegram.org/method/initConnection
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `api_id`: `int`
  - `device_model`: `string`
  - `system_version`: `string`
  - `app_version`: `string`
  - `system_lang_code`: `string`
  - `lang_pack`: `string`
  - `lang_code`: `string`
  - `proxy`: `flags.0?InputClientProxy` - optional через flags.0
  - `params`: `flags.1?JSONValue` - optional через flags.1
  - `query`: `!X`

### `invokeAfterMsg`

- Кратко: См. официальную страницу метода invokeAfterMsg.
- ID: `-878758099` / `0xcb9f372d`
- Return type: `X`
- Сигнатура: `invokeAfterMsg(msg_id:long, query:!X) -> X`
- Официальная страница: https://core.telegram.org/method/invokeAfterMsg
- Параметры:
  - `msg_id`: `long`
  - `query`: `!X`

### `invokeAfterMsgs`

- Кратко: См. официальную страницу метода invokeAfterMsgs.
- ID: `1036301552` / `0x3dc4b4f0`
- Return type: `X`
- Сигнатура: `invokeAfterMsgs(msg_ids:Vector, query:!X) -> X`
- Официальная страница: https://core.telegram.org/method/invokeAfterMsgs
- Параметры:
  - `msg_ids`: `Vector`
  - `query`: `!X`

### `invokeWithApnsSecret`

- Кратко: См. официальную страницу метода invokeWithApnsSecret.
- ID: `229528824` / `0x0dae54f8`
- Return type: `X`
- Сигнатура: `invokeWithApnsSecret(nonce:string, secret:string, query:!X) -> X`
- Официальная страница: https://core.telegram.org/method/invokeWithApnsSecret
- Параметры:
  - `nonce`: `string`
  - `secret`: `string`
  - `query`: `!X`

### `invokeWithBusinessConnection`

- Кратко: См. официальную страницу метода invokeWithBusinessConnection.
- ID: `-584540274` / `0xdd289f8e`
- Return type: `X`
- Сигнатура: `invokeWithBusinessConnection(connection_id:string, query:!X) -> X`
- Официальная страница: https://core.telegram.org/method/invokeWithBusinessConnection
- Параметры:
  - `connection_id`: `string`
  - `query`: `!X`

### `invokeWithGooglePlayIntegrity`

- Кратко: См. официальную страницу метода invokeWithGooglePlayIntegrity.
- ID: `502868356` / `0x1df92984`
- Return type: `X`
- Сигнатура: `invokeWithGooglePlayIntegrity(nonce:string, token:string, query:!X) -> X`
- Официальная страница: https://core.telegram.org/method/invokeWithGooglePlayIntegrity
- Параметры:
  - `nonce`: `string`
  - `token`: `string`
  - `query`: `!X`

### `invokeWithLayer`

- Кратко: См. официальную страницу метода invokeWithLayer.
- ID: `-627372787` / `0xda9b0d0d`
- Return type: `X`
- Сигнатура: `invokeWithLayer(layer:int, query:!X) -> X`
- Официальная страница: https://core.telegram.org/method/invokeWithLayer
- Параметры:
  - `layer`: `int`
  - `query`: `!X`

### `invokeWithMessagesRange`

- Кратко: См. официальную страницу метода invokeWithMessagesRange.
- ID: `911373810` / `0x365275f2`
- Return type: `X`
- Сигнатура: `invokeWithMessagesRange(range:MessageRange, query:!X) -> X`
- Официальная страница: https://core.telegram.org/method/invokeWithMessagesRange
- Параметры:
  - `range`: `MessageRange`
  - `query`: `!X`

### `invokeWithReCaptcha`

- Кратко: См. официальную страницу метода invokeWithReCaptcha.
- ID: `-1380249708` / `0xadbb0f94`
- Return type: `X`
- Сигнатура: `invokeWithReCaptcha(token:string, query:!X) -> X`
- Официальная страница: https://core.telegram.org/method/invokeWithReCaptcha
- Параметры:
  - `token`: `string`
  - `query`: `!X`

### `invokeWithTakeout`

- Кратко: См. официальную страницу метода invokeWithTakeout.
- ID: `-1398145746` / `0xaca9fd2e`
- Return type: `X`
- Сигнатура: `invokeWithTakeout(takeout_id:long, query:!X) -> X`
- Официальная страница: https://core.telegram.org/method/invokeWithTakeout
- Параметры:
  - `takeout_id`: `long`
  - `query`: `!X`

### `invokeWithoutUpdates`

- Кратко: См. официальную страницу метода invokeWithoutUpdates.
- ID: `-1080796745` / `0xbf9459b7`
- Return type: `X`
- Сигнатура: `invokeWithoutUpdates(query:!X) -> X`
- Официальная страница: https://core.telegram.org/method/invokeWithoutUpdates
- Параметры:
  - `query`: `!X`

## folders

### `folders.editPeerFolders`

- Кратко: Изменить peer/диалог папки.
- ID: `1749536939` / `0x6847d0ab`
- Return type: `Updates`
- Сигнатура: `folders.editPeerFolders(folder_peers:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/folders.editPeerFolders
- Параметры:
  - `folder_peers`: `Vector`

## fragment

### `fragment.getCollectibleInfo`

- Кратко: Получить коллекционный объект информацию.
- ID: `-1105295942` / `0xbe1e85ba`
- Return type: `fragment.CollectibleInfo`
- Сигнатура: `fragment.getCollectibleInfo(collectible:InputCollectible) -> fragment.CollectibleInfo`
- Официальная страница: https://core.telegram.org/method/fragment.getCollectibleInfo
- Параметры:
  - `collectible`: `InputCollectible`

## help

### `help.acceptTermsOfService`

- Кратко: Принять условия сервиса.
- ID: `-294455398` / `0xee72f79a`
- Return type: `Bool`
- Сигнатура: `help.acceptTermsOfService(id:DataJSON) -> Bool`
- Официальная страница: https://core.telegram.org/method/help.acceptTermsOfService
- Параметры:
  - `id`: `DataJSON`

### `help.dismissSuggestion`

- Кратко: Операция с dismiss подсказку.
- ID: `-183649631` / `0xf50dbaa1`
- Return type: `Bool`
- Сигнатура: `help.dismissSuggestion(peer:InputPeer, suggestion:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/help.dismissSuggestion
- Параметры:
  - `peer`: `InputPeer`
  - `suggestion`: `string`

### `help.editUserInfo`

- Кратко: Изменить пользователя информацию.
- ID: `1723407216` / `0x66b91b70`
- Return type: `help.UserInfo`
- Сигнатура: `help.editUserInfo(user_id:InputUser, message:string, entities:Vector) -> help.UserInfo`
- Официальная страница: https://core.telegram.org/method/help.editUserInfo
- Параметры:
  - `user_id`: `InputUser`
  - `message`: `string`
  - `entities`: `Vector`

### `help.getAppConfig`

- Кратко: Получить приложение конфигурацию.
- ID: `1642330196` / `0x61e3f854`
- Return type: `help.AppConfig`
- Сигнатура: `help.getAppConfig(hash:int) -> help.AppConfig`
- Официальная страница: https://core.telegram.org/method/help.getAppConfig
- Параметры:
  - `hash`: `int`

### `help.getAppUpdate`

- Кратко: Получить приложение обновление.
- ID: `1378703997` / `0x522d5a7d`
- Return type: `help.AppUpdate`
- Сигнатура: `help.getAppUpdate(source:string) -> help.AppUpdate`
- Официальная страница: https://core.telegram.org/method/help.getAppUpdate
- Параметры:
  - `source`: `string`

### `help.getCdnConfig`

- Кратко: Получить cdn конфигурацию.
- ID: `1375900482` / `0x52029342`
- Return type: `CdnConfig`
- Сигнатура: `help.getCdnConfig() -> CdnConfig`
- Официальная страница: https://core.telegram.org/method/help.getCdnConfig
- Параметры:
  - Нет параметров.

### `help.getConfig`

- Кратко: Получить конфигурацию.
- ID: `-990308245` / `0xc4f9186b`
- Return type: `Config`
- Сигнатура: `help.getConfig() -> Config`
- Официальная страница: https://core.telegram.org/method/help.getConfig
- Параметры:
  - Нет параметров.

### `help.getCountriesList`

- Кратко: Получить страны список.
- ID: `1935116200` / `0x735787a8`
- Return type: `help.CountriesList`
- Сигнатура: `help.getCountriesList(lang_code:string, hash:int) -> help.CountriesList`
- Официальная страница: https://core.telegram.org/method/help.getCountriesList
- Параметры:
  - `lang_code`: `string`
  - `hash`: `int`

### `help.getDeepLinkInfo`

- Кратко: Получить deep ссылку информацию.
- ID: `1072547679` / `0x3fedc75f`
- Return type: `help.DeepLinkInfo`
- Сигнатура: `help.getDeepLinkInfo(path:string) -> help.DeepLinkInfo`
- Официальная страница: https://core.telegram.org/method/help.getDeepLinkInfo
- Параметры:
  - `path`: `string`

### `help.getInviteText`

- Кратко: Получить приглашение текст.
- ID: `1295590211` / `0x4d392343`
- Return type: `help.InviteText`
- Сигнатура: `help.getInviteText() -> help.InviteText`
- Официальная страница: https://core.telegram.org/method/help.getInviteText
- Параметры:
  - Нет параметров.

### `help.getNearestDc`

- Кратко: Получить ближайший дата-центр.
- ID: `531836966` / `0x1fb33026`
- Return type: `NearestDc`
- Сигнатура: `help.getNearestDc() -> NearestDc`
- Официальная страница: https://core.telegram.org/method/help.getNearestDc
- Параметры:
  - Нет параметров.

### `help.getPassportConfig`

- Кратко: Получить passport конфигурацию.
- ID: `-966677240` / `0xc661ad08`
- Return type: `help.PassportConfig`
- Сигнатура: `help.getPassportConfig(hash:int) -> help.PassportConfig`
- Официальная страница: https://core.telegram.org/method/help.getPassportConfig
- Параметры:
  - `hash`: `int`

### `help.getPeerColors`

- Кратко: Получить peer/диалог colors.
- ID: `-629083089` / `0xda80f42f`
- Return type: `help.PeerColors`
- Сигнатура: `help.getPeerColors(hash:int) -> help.PeerColors`
- Официальная страница: https://core.telegram.org/method/help.getPeerColors
- Параметры:
  - `hash`: `int`

### `help.getPeerProfileColors`

- Кратко: Получить peer/диалог профиль colors.
- ID: `-1412453891` / `0xabcfa9fd`
- Return type: `help.PeerColors`
- Сигнатура: `help.getPeerProfileColors(hash:int) -> help.PeerColors`
- Официальная страница: https://core.telegram.org/method/help.getPeerProfileColors
- Параметры:
  - `hash`: `int`

### `help.getPremiumPromo`

- Кратко: Получить Premium промо.
- ID: `-1206152236` / `0xb81b93d4`
- Return type: `help.PremiumPromo`
- Сигнатура: `help.getPremiumPromo() -> help.PremiumPromo`
- Официальная страница: https://core.telegram.org/method/help.getPremiumPromo
- Параметры:
  - Нет параметров.

### `help.getPromoData`

- Кратко: Получить промо данные.
- ID: `-1063816159` / `0xc0977421`
- Return type: `help.PromoData`
- Сигнатура: `help.getPromoData() -> help.PromoData`
- Официальная страница: https://core.telegram.org/method/help.getPromoData
- Параметры:
  - Нет параметров.

### `help.getRecentMeUrls`

- Кратко: Получить недавние me urls.
- ID: `1036054804` / `0x3dc0f114`
- Return type: `help.RecentMeUrls`
- Сигнатура: `help.getRecentMeUrls(referer:string) -> help.RecentMeUrls`
- Официальная страница: https://core.telegram.org/method/help.getRecentMeUrls
- Параметры:
  - `referer`: `string`

### `help.getSupport`

- Кратко: Получить поддержку.
- ID: `-1663104819` / `0x9cdf08cd`
- Return type: `help.Support`
- Сигнатура: `help.getSupport() -> help.Support`
- Официальная страница: https://core.telegram.org/method/help.getSupport
- Параметры:
  - Нет параметров.

### `help.getSupportName`

- Кратко: Получить поддержку имя.
- ID: `-748624084` / `0xd360e72c`
- Return type: `help.SupportName`
- Сигнатура: `help.getSupportName() -> help.SupportName`
- Официальная страница: https://core.telegram.org/method/help.getSupportName
- Параметры:
  - Нет параметров.

### `help.getTermsOfServiceUpdate`

- Кратко: Получить условия сервиса обновление.
- ID: `749019089` / `0x2ca51fd1`
- Return type: `help.TermsOfServiceUpdate`
- Сигнатура: `help.getTermsOfServiceUpdate() -> help.TermsOfServiceUpdate`
- Официальная страница: https://core.telegram.org/method/help.getTermsOfServiceUpdate
- Параметры:
  - Нет параметров.

### `help.getTimezonesList`

- Кратко: Получить timezones список.
- ID: `1236468288` / `0x49b30240`
- Return type: `help.TimezonesList`
- Сигнатура: `help.getTimezonesList(hash:int) -> help.TimezonesList`
- Официальная страница: https://core.telegram.org/method/help.getTimezonesList
- Параметры:
  - `hash`: `int`

### `help.getUserInfo`

- Кратко: Получить пользователя информацию.
- ID: `59377875` / `0x038a08d3`
- Return type: `help.UserInfo`
- Сигнатура: `help.getUserInfo(user_id:InputUser) -> help.UserInfo`
- Официальная страница: https://core.telegram.org/method/help.getUserInfo
- Параметры:
  - `user_id`: `InputUser`

### `help.hidePromoData`

- Кратко: Скрыть промо данные.
- ID: `505748629` / `0x1e251c95`
- Return type: `Bool`
- Сигнатура: `help.hidePromoData(peer:InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/help.hidePromoData
- Параметры:
  - `peer`: `InputPeer`

### `help.saveAppLog`

- Кратко: Сохранить приложение log.
- ID: `1862465352` / `0x6f02f748`
- Return type: `Bool`
- Сигнатура: `help.saveAppLog(events:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/help.saveAppLog
- Параметры:
  - `events`: `Vector`

### `help.setBotUpdatesStatus`

- Кратко: Установить бота updates статус.
- ID: `-333262899` / `0xec22cfcd`
- Return type: `Bool`
- Сигнатура: `help.setBotUpdatesStatus(pending_updates_count:int, message:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/help.setBotUpdatesStatus
- Параметры:
  - `pending_updates_count`: `int`
  - `message`: `string`

## langpack

### `langpack.getDifference`

- Кратко: Получить разницу.
- ID: `-845657435` / `0xcd984aa5`
- Return type: `LangPackDifference`
- Сигнатура: `langpack.getDifference(lang_pack:string, lang_code:string, from_version:int) -> LangPackDifference`
- Официальная страница: https://core.telegram.org/method/langpack.getDifference
- Параметры:
  - `lang_pack`: `string`
  - `lang_code`: `string`
  - `from_version`: `int`

### `langpack.getLangPack`

- Кратко: Получить lang pack.
- ID: `-219008246` / `0xf2f2330a`
- Return type: `LangPackDifference`
- Сигнатура: `langpack.getLangPack(lang_pack:string, lang_code:string) -> LangPackDifference`
- Официальная страница: https://core.telegram.org/method/langpack.getLangPack
- Параметры:
  - `lang_pack`: `string`
  - `lang_code`: `string`

### `langpack.getLanguage`

- Кратко: Получить язык.
- ID: `1784243458` / `0x6a596502`
- Return type: `LangPackLanguage`
- Сигнатура: `langpack.getLanguage(lang_pack:string, lang_code:string) -> LangPackLanguage`
- Официальная страница: https://core.telegram.org/method/langpack.getLanguage
- Параметры:
  - `lang_pack`: `string`
  - `lang_code`: `string`

### `langpack.getLanguages`

- Кратко: Получить languages.
- ID: `1120311183` / `0x42c6978f`
- Return type: `Vector`
- Сигнатура: `langpack.getLanguages(lang_pack:string) -> Vector`
- Официальная страница: https://core.telegram.org/method/langpack.getLanguages
- Параметры:
  - `lang_pack`: `string`

### `langpack.getStrings`

- Кратко: Получить строки.
- ID: `-269862909` / `0xefea3803`
- Return type: `Vector`
- Сигнатура: `langpack.getStrings(lang_pack:string, lang_code:string, keys:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/langpack.getStrings
- Параметры:
  - `lang_pack`: `string`
  - `lang_code`: `string`
  - `keys`: `Vector`

## messages

### `messages.acceptEncryption`

- Кратко: Принять encryption.
- ID: `1035731989` / `0x3dbc0415`
- Return type: `EncryptedChat`
- Сигнатура: `messages.acceptEncryption(peer:InputEncryptedChat, g_b:bytes, key_fingerprint:long) -> EncryptedChat`
- Официальная страница: https://core.telegram.org/method/messages.acceptEncryption
- Параметры:
  - `peer`: `InputEncryptedChat`
  - `g_b`: `bytes`
  - `key_fingerprint`: `long`

### `messages.acceptUrlAuth`

- Кратко: Принять URL авторизации.
- ID: `-1322487515` / `0xb12c7125`
- Return type: `UrlAuthResult`
- Сигнатура: `messages.acceptUrlAuth(flags:#, write_allowed:flags.0?true, peer:flags.1?InputPeer, msg_id:flags.1?int, button_id:flags.1?int, url:flags.2?string) -> UrlAuthResult`
- Официальная страница: https://core.telegram.org/method/messages.acceptUrlAuth
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `write_allowed`: `flags.0?true` - optional через flags.0
  - `peer`: `flags.1?InputPeer` - optional через flags.1
  - `msg_id`: `flags.1?int` - optional через flags.1
  - `button_id`: `flags.1?int` - optional через flags.1
  - `url`: `flags.2?string` - optional через flags.2

### `messages.addChatUser`

- Кратко: Операция с add чат пользователя.
- ID: `-876162809` / `0xcbc6d107`
- Return type: `messages.InvitedUsers`
- Сигнатура: `messages.addChatUser(chat_id:long, user_id:InputUser, fwd_limit:int) -> messages.InvitedUsers`
- Официальная страница: https://core.telegram.org/method/messages.addChatUser
- Параметры:
  - `chat_id`: `long`
  - `user_id`: `InputUser`
  - `fwd_limit`: `int`

### `messages.appendTodoList`

- Кратко: Операция с append todo список.
- ID: `564531287` / `0x21a61057`
- Return type: `Updates`
- Сигнатура: `messages.appendTodoList(peer:InputPeer, msg_id:int, list:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.appendTodoList
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `list`: `Vector`

### `messages.checkChatInvite`

- Кратко: Проверить чат приглашение.
- ID: `1051570619` / `0x3eadb1bb`
- Return type: `ChatInvite`
- Сигнатура: `messages.checkChatInvite(hash:string) -> ChatInvite`
- Официальная страница: https://core.telegram.org/method/messages.checkChatInvite
- Параметры:
  - `hash`: `string`

### `messages.checkHistoryImport`

- Кратко: Проверить историю import.
- ID: `1140726259` / `0x43fe19f3`
- Return type: `messages.HistoryImportParsed`
- Сигнатура: `messages.checkHistoryImport(import_head:string) -> messages.HistoryImportParsed`
- Официальная страница: https://core.telegram.org/method/messages.checkHistoryImport
- Параметры:
  - `import_head`: `string`

### `messages.checkHistoryImportPeer`

- Кратко: Проверить историю import peer/диалог.
- ID: `1573261059` / `0x5dc60f03`
- Return type: `messages.CheckedHistoryImportPeer`
- Сигнатура: `messages.checkHistoryImportPeer(peer:InputPeer) -> messages.CheckedHistoryImportPeer`
- Официальная страница: https://core.telegram.org/method/messages.checkHistoryImportPeer
- Параметры:
  - `peer`: `InputPeer`

### `messages.checkQuickReplyShortcut`

- Кратко: Проверить быстрый ответ shortcut.
- ID: `-237962285` / `0xf1d0fbd3`
- Return type: `Bool`
- Сигнатура: `messages.checkQuickReplyShortcut(shortcut:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.checkQuickReplyShortcut
- Параметры:
  - `shortcut`: `string`

### `messages.clearAllDrafts`

- Кратко: Операция с clear all drafts.
- ID: `2119757468` / `0x7e58ee9c`
- Return type: `Bool`
- Сигнатура: `messages.clearAllDrafts() -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.clearAllDrafts
- Параметры:
  - Нет параметров.

### `messages.clearRecentReactions`

- Кратко: Операция с clear недавние реакции.
- ID: `-1644236876` / `0x9dfeefb4`
- Return type: `Bool`
- Сигнатура: `messages.clearRecentReactions() -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.clearRecentReactions
- Параметры:
  - Нет параметров.

### `messages.clearRecentStickers`

- Кратко: Операция с clear недавние стикеры.
- ID: `-1986437075` / `0x8999602d`
- Return type: `Bool`
- Сигнатура: `messages.clearRecentStickers(flags:#, attached:flags.0?true) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.clearRecentStickers
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `attached`: `flags.0?true` - optional через flags.0

### `messages.clickSponsoredMessage`

- Кратко: Операция с click спонсируемые сообщение.
- ID: `-2110454402` / `0x8235057e`
- Return type: `Bool`
- Сигнатура: `messages.clickSponsoredMessage(flags:#, media:flags.0?true, fullscreen:flags.1?true, random_id:bytes) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.clickSponsoredMessage
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `media`: `flags.0?true` - optional через flags.0
  - `fullscreen`: `flags.1?true` - optional через flags.1
  - `random_id`: `bytes`

### `messages.createChat`

- Кратко: Создать чат.
- ID: `-1831936556` / `0x92ceddd4`
- Return type: `messages.InvitedUsers`
- Сигнатура: `messages.createChat(flags:#, users:Vector, title:string, ttl_period:flags.0?int) -> messages.InvitedUsers`
- Официальная страница: https://core.telegram.org/method/messages.createChat
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `users`: `Vector`
  - `title`: `string`
  - `ttl_period`: `flags.0?int` - optional через flags.0

### `messages.deleteChat`

- Кратко: Удалить чат.
- ID: `1540419152` / `0x5bd0ee50`
- Return type: `Bool`
- Сигнатура: `messages.deleteChat(chat_id:long) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.deleteChat
- Параметры:
  - `chat_id`: `long`

### `messages.deleteChatUser`

- Кратко: Удалить чат пользователя.
- ID: `-1575461717` / `0xa2185cab`
- Return type: `Updates`
- Сигнатура: `messages.deleteChatUser(flags:#, revoke_history:flags.0?true, chat_id:long, user_id:InputUser) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.deleteChatUser
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `revoke_history`: `flags.0?true` - optional через flags.0
  - `chat_id`: `long`
  - `user_id`: `InputUser`

### `messages.deleteExportedChatInvite`

- Кратко: Удалить экспортированную чат приглашение.
- ID: `-731601877` / `0xd464a42b`
- Return type: `Bool`
- Сигнатура: `messages.deleteExportedChatInvite(peer:InputPeer, link:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.deleteExportedChatInvite
- Параметры:
  - `peer`: `InputPeer`
  - `link`: `string`

### `messages.deleteFactCheck`

- Кратко: Удалить fact check.
- ID: `-774204404` / `0xd1da940c`
- Return type: `Updates`
- Сигнатура: `messages.deleteFactCheck(peer:InputPeer, msg_id:int) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.deleteFactCheck
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`

### `messages.deleteHistory`

- Кратко: Удалить историю.
- ID: `-1332768214` / `0xb08f922a`
- Return type: `messages.AffectedHistory`
- Сигнатура: `messages.deleteHistory(flags:#, just_clear:flags.0?true, revoke:flags.1?true, peer:InputPeer, max_id:int, min_date:flags.2?int, max_date:flags.3?int) -> messages.AffectedHistory`
- Официальная страница: https://core.telegram.org/method/messages.deleteHistory
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `just_clear`: `flags.0?true` - optional через flags.0
  - `revoke`: `flags.1?true` - optional через flags.1
  - `peer`: `InputPeer`
  - `max_id`: `int`
  - `min_date`: `flags.2?int` - optional через flags.2
  - `max_date`: `flags.3?int` - optional через flags.3

### `messages.deleteMessages`

- Кратко: Удалить сообщения.
- ID: `-443640366` / `0xe58e95d2`
- Return type: `messages.AffectedMessages`
- Сигнатура: `messages.deleteMessages(flags:#, revoke:flags.0?true, id:Vector) -> messages.AffectedMessages`
- Официальная страница: https://core.telegram.org/method/messages.deleteMessages
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `revoke`: `flags.0?true` - optional через flags.0
  - `id`: `Vector`

### `messages.deletePhoneCallHistory`

- Кратко: Удалить телефон звонок историю.
- ID: `-104078327` / `0xf9cbe409`
- Return type: `messages.AffectedFoundMessages`
- Сигнатура: `messages.deletePhoneCallHistory(flags:#, revoke:flags.0?true) -> messages.AffectedFoundMessages`
- Официальная страница: https://core.telegram.org/method/messages.deletePhoneCallHistory
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `revoke`: `flags.0?true` - optional через flags.0

### `messages.deleteQuickReplyMessages`

- Кратко: Удалить быстрый ответ сообщения.
- ID: `-519706352` / `0xe105e910`
- Return type: `Updates`
- Сигнатура: `messages.deleteQuickReplyMessages(shortcut_id:int, id:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.deleteQuickReplyMessages
- Параметры:
  - `shortcut_id`: `int`
  - `id`: `Vector`

### `messages.deleteQuickReplyShortcut`

- Кратко: Удалить быстрый ответ shortcut.
- ID: `1019234112` / `0x3cc04740`
- Return type: `Bool`
- Сигнатура: `messages.deleteQuickReplyShortcut(shortcut_id:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.deleteQuickReplyShortcut
- Параметры:
  - `shortcut_id`: `int`

### `messages.deleteRevokedExportedChatInvites`

- Кратко: Удалить отозванные экспортированные чат invites.
- ID: `1452833749` / `0x56987bd5`
- Return type: `Bool`
- Сигнатура: `messages.deleteRevokedExportedChatInvites(peer:InputPeer, admin_id:InputUser) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.deleteRevokedExportedChatInvites
- Параметры:
  - `peer`: `InputPeer`
  - `admin_id`: `InputUser`

### `messages.deleteSavedHistory`

- Кратко: Удалить сохранённое историю.
- ID: `1304758367` / `0x4dc5085f`
- Return type: `messages.AffectedHistory`
- Сигнатура: `messages.deleteSavedHistory(flags:#, parent_peer:flags.0?InputPeer, peer:InputPeer, max_id:int, min_date:flags.2?int, max_date:flags.3?int) -> messages.AffectedHistory`
- Официальная страница: https://core.telegram.org/method/messages.deleteSavedHistory
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `parent_peer`: `flags.0?InputPeer` - optional через flags.0
  - `peer`: `InputPeer`
  - `max_id`: `int`
  - `min_date`: `flags.2?int` - optional через flags.2
  - `max_date`: `flags.3?int` - optional через flags.3

### `messages.deleteScheduledMessages`

- Кратко: Удалить запланированные сообщения.
- ID: `1504586518` / `0x59ae2b16`
- Return type: `Updates`
- Сигнатура: `messages.deleteScheduledMessages(peer:InputPeer, id:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.deleteScheduledMessages
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`

### `messages.discardEncryption`

- Кратко: Операция с discard encryption.
- ID: `-208425312` / `0xf393aea0`
- Return type: `Bool`
- Сигнатура: `messages.discardEncryption(flags:#, delete_history:flags.0?true, chat_id:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.discardEncryption
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `delete_history`: `flags.0?true` - optional через flags.0
  - `chat_id`: `int`

### `messages.editChatAbout`

- Кратко: Изменить чат about.
- ID: `-554301545` / `0xdef60797`
- Return type: `Bool`
- Сигнатура: `messages.editChatAbout(peer:InputPeer, about:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.editChatAbout
- Параметры:
  - `peer`: `InputPeer`
  - `about`: `string`

### `messages.editChatAdmin`

- Кратко: Изменить чат админа.
- ID: `-1470377534` / `0xa85bd1c2`
- Return type: `Bool`
- Сигнатура: `messages.editChatAdmin(chat_id:long, user_id:InputUser, is_admin:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.editChatAdmin
- Параметры:
  - `chat_id`: `long`
  - `user_id`: `InputUser`
  - `is_admin`: `Bool`

### `messages.editChatDefaultBannedRights`

- Кратко: Изменить чат default banned rights.
- ID: `-1517917375` / `0xa5866b41`
- Return type: `Updates`
- Сигнатура: `messages.editChatDefaultBannedRights(peer:InputPeer, banned_rights:ChatBannedRights) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.editChatDefaultBannedRights
- Параметры:
  - `peer`: `InputPeer`
  - `banned_rights`: `ChatBannedRights`

### `messages.editChatPhoto`

- Кратко: Изменить чат фото.
- ID: `903730804` / `0x35ddd674`
- Return type: `Updates`
- Сигнатура: `messages.editChatPhoto(chat_id:long, photo:InputChatPhoto) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.editChatPhoto
- Параметры:
  - `chat_id`: `long`
  - `photo`: `InputChatPhoto`

### `messages.editChatTitle`

- Кратко: Изменить чат заголовок.
- ID: `1937260541` / `0x73783ffd`
- Return type: `Updates`
- Сигнатура: `messages.editChatTitle(chat_id:long, title:string) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.editChatTitle
- Параметры:
  - `chat_id`: `long`
  - `title`: `string`

### `messages.editExportedChatInvite`

- Кратко: Изменить экспортированные чат приглашение.
- ID: `-1110823051` / `0xbdca2f75`
- Return type: `messages.ExportedChatInvite`
- Сигнатура: `messages.editExportedChatInvite(flags:#, revoked:flags.2?true, peer:InputPeer, link:string, expire_date:flags.0?int, usage_limit:flags.1?int, request_needed:flags.3?Bool, title:flags.4?string) -> messages.ExportedChatInvite`
- Официальная страница: https://core.telegram.org/method/messages.editExportedChatInvite
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `revoked`: `flags.2?true` - optional через flags.2
  - `peer`: `InputPeer`
  - `link`: `string`
  - `expire_date`: `flags.0?int` - optional через flags.0
  - `usage_limit`: `flags.1?int` - optional через flags.1
  - `request_needed`: `flags.3?Bool` - optional через flags.3
  - `title`: `flags.4?string` - optional через flags.4

### `messages.editFactCheck`

- Кратко: Изменить fact check.
- ID: `92925557` / `0x0589ee75`
- Return type: `Updates`
- Сигнатура: `messages.editFactCheck(peer:InputPeer, msg_id:int, text:TextWithEntities) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.editFactCheck
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `text`: `TextWithEntities`

### `messages.editInlineBotMessage`

- Кратко: Изменить inline бота сообщение.
- ID: `-2091549254` / `0x83557dba`
- Return type: `Bool`
- Сигнатура: `messages.editInlineBotMessage(flags:#, no_webpage:flags.1?true, invert_media:flags.16?true, id:InputBotInlineMessageID, message:flags.11?string, media:flags.14?InputMedia, reply_markup:flags.2?ReplyMarkup, entities:flags.3?Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.editInlineBotMessage
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `no_webpage`: `flags.1?true` - optional через flags.1
  - `invert_media`: `flags.16?true` - optional через flags.16
  - `id`: `InputBotInlineMessageID`
  - `message`: `flags.11?string` - optional через flags.11
  - `media`: `flags.14?InputMedia` - optional через flags.14
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2
  - `entities`: `flags.3?Vector` - optional через flags.3

### `messages.editMessage`

- Кратко: Изменить сообщение.
- ID: `-539934715` / `0xdfd14005`
- Return type: `Updates`
- Сигнатура: `messages.editMessage(flags:#, no_webpage:flags.1?true, invert_media:flags.16?true, peer:InputPeer, id:int, message:flags.11?string, media:flags.14?InputMedia, reply_markup:flags.2?ReplyMarkup, entities:flags.3?Vector, schedule_date:flags.15?int, quick_reply_shortcut_id:flags.17?int) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.editMessage
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `no_webpage`: `flags.1?true` - optional через flags.1
  - `invert_media`: `flags.16?true` - optional через flags.16
  - `peer`: `InputPeer`
  - `id`: `int`
  - `message`: `flags.11?string` - optional через flags.11
  - `media`: `flags.14?InputMedia` - optional через flags.14
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2
  - `entities`: `flags.3?Vector` - optional через flags.3
  - `schedule_date`: `flags.15?int` - optional через flags.15
  - `quick_reply_shortcut_id`: `flags.17?int` - optional через flags.17

### `messages.editQuickReplyShortcut`

- Кратко: Изменить быстрый ответ shortcut.
- ID: `1543519471` / `0x5c003cef`
- Return type: `Bool`
- Сигнатура: `messages.editQuickReplyShortcut(shortcut_id:int, shortcut:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.editQuickReplyShortcut
- Параметры:
  - `shortcut_id`: `int`
  - `shortcut`: `string`

### `messages.exportChatInvite`

- Кратко: Экспортировать чат приглашение.
- ID: `-1537876336` / `0xa455de90`
- Return type: `ExportedChatInvite`
- Сигнатура: `messages.exportChatInvite(flags:#, legacy_revoke_permanent:flags.2?true, request_needed:flags.3?true, peer:InputPeer, expire_date:flags.0?int, usage_limit:flags.1?int, title:flags.4?string, subscription_pricing:flags.5?StarsSubscriptionPricing) -> ExportedChatInvite`
- Официальная страница: https://core.telegram.org/method/messages.exportChatInvite
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `legacy_revoke_permanent`: `flags.2?true` - optional через flags.2
  - `request_needed`: `flags.3?true` - optional через flags.3
  - `peer`: `InputPeer`
  - `expire_date`: `flags.0?int` - optional через flags.0
  - `usage_limit`: `flags.1?int` - optional через flags.1
  - `title`: `flags.4?string` - optional через flags.4
  - `subscription_pricing`: `flags.5?StarsSubscriptionPricing` - optional через flags.5

### `messages.faveSticker`

- Кратко: Операция с fave стикер.
- ID: `-1174420133` / `0xb9ffc55b`
- Return type: `Bool`
- Сигнатура: `messages.faveSticker(id:InputDocument, unfave:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.faveSticker
- Параметры:
  - `id`: `InputDocument`
  - `unfave`: `Bool`

### `messages.forwardMessages`

- Кратко: Переслать сообщения.
- ID: `-1752618806` / `0x978928ca`
- Return type: `Updates`
- Сигнатура: `messages.forwardMessages(flags:#, silent:flags.5?true, background:flags.6?true, with_my_score:flags.8?true, drop_author:flags.11?true, drop_media_captions:flags.12?true, noforwards:flags.14?true, allow_paid_floodskip:flags.19?true, from_peer:InputPeer, id:Vector, random_id:Vector, to_peer:InputPeer, top_msg_id:flags.9?int, reply_to:flags.22?InputReplyTo, schedule_date:flags.10?int, send_as:flags.13?InputPeer, quick_reply_shortcut:flags.17?InputQuickReplyShortcut, video_timestamp:flags.20?int, allow_paid_stars:flags.21?long, suggested_post:flags.23?SuggestedPost) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.forwardMessages
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `silent`: `flags.5?true` - optional через flags.5
  - `background`: `flags.6?true` - optional через flags.6
  - `with_my_score`: `flags.8?true` - optional через flags.8
  - `drop_author`: `flags.11?true` - optional через flags.11
  - `drop_media_captions`: `flags.12?true` - optional через flags.12
  - `noforwards`: `flags.14?true` - optional через flags.14
  - `allow_paid_floodskip`: `flags.19?true` - optional через flags.19
  - `from_peer`: `InputPeer`
  - `id`: `Vector`
  - `random_id`: `Vector`
  - `to_peer`: `InputPeer`
  - `top_msg_id`: `flags.9?int` - optional через flags.9
  - `reply_to`: `flags.22?InputReplyTo` - optional через flags.22
  - `schedule_date`: `flags.10?int` - optional через flags.10
  - `send_as`: `flags.13?InputPeer` - optional через flags.13
  - `quick_reply_shortcut`: `flags.17?InputQuickReplyShortcut` - optional через flags.17
  - `video_timestamp`: `flags.20?int` - optional через flags.20
  - `allow_paid_stars`: `flags.21?long` - optional через flags.21
  - `suggested_post`: `flags.23?SuggestedPost` - optional через flags.23

### `messages.getAdminsWithInvites`

- Кратко: Получить админов с invites.
- ID: `958457583` / `0x3920e6ef`
- Return type: `messages.ChatAdminsWithInvites`
- Сигнатура: `messages.getAdminsWithInvites(peer:InputPeer) -> messages.ChatAdminsWithInvites`
- Официальная страница: https://core.telegram.org/method/messages.getAdminsWithInvites
- Параметры:
  - `peer`: `InputPeer`

### `messages.getAllDrafts`

- Кратко: Получить все drafts.
- ID: `1782549861` / `0x6a3f8d65`
- Return type: `Updates`
- Сигнатура: `messages.getAllDrafts() -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.getAllDrafts
- Параметры:
  - Нет параметров.

### `messages.getAllStickers`

- Кратко: Получить все стикеры.
- ID: `-1197432408` / `0xb8a0a1a8`
- Return type: `messages.AllStickers`
- Сигнатура: `messages.getAllStickers(hash:long) -> messages.AllStickers`
- Официальная страница: https://core.telegram.org/method/messages.getAllStickers
- Параметры:
  - `hash`: `long`

### `messages.getArchivedStickers`

- Кратко: Получить архивные стикеры.
- ID: `1475442322` / `0x57f17692`
- Return type: `messages.ArchivedStickers`
- Сигнатура: `messages.getArchivedStickers(flags:#, masks:flags.0?true, emojis:flags.1?true, offset_id:long, limit:int) -> messages.ArchivedStickers`
- Официальная страница: https://core.telegram.org/method/messages.getArchivedStickers
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `masks`: `flags.0?true` - optional через flags.0
  - `emojis`: `flags.1?true` - optional через flags.1
  - `offset_id`: `long`
  - `limit`: `int`

### `messages.getAttachMenuBot`

- Кратко: Получить прикрепление меню бота.
- ID: `1998676370` / `0x77216192`
- Return type: `AttachMenuBotsBot`
- Сигнатура: `messages.getAttachMenuBot(bot:InputUser) -> AttachMenuBotsBot`
- Официальная страница: https://core.telegram.org/method/messages.getAttachMenuBot
- Параметры:
  - `bot`: `InputUser`

### `messages.getAttachMenuBots`

- Кратко: Получить прикрепление меню ботов.
- ID: `385663691` / `0x16fcc2cb`
- Return type: `AttachMenuBots`
- Сигнатура: `messages.getAttachMenuBots(hash:long) -> AttachMenuBots`
- Официальная страница: https://core.telegram.org/method/messages.getAttachMenuBots
- Параметры:
  - `hash`: `long`

### `messages.getAttachedStickers`

- Кратко: Получить прикреплённые стикеры.
- ID: `-866424884` / `0xcc5b67cc`
- Return type: `Vector`
- Сигнатура: `messages.getAttachedStickers(media:InputStickeredMedia) -> Vector`
- Официальная страница: https://core.telegram.org/method/messages.getAttachedStickers
- Параметры:
  - `media`: `InputStickeredMedia`

### `messages.getAvailableEffects`

- Кратко: Получить available effects.
- ID: `-559805895` / `0xdea20a39`
- Return type: `messages.AvailableEffects`
- Сигнатура: `messages.getAvailableEffects(hash:int) -> messages.AvailableEffects`
- Официальная страница: https://core.telegram.org/method/messages.getAvailableEffects
- Параметры:
  - `hash`: `int`

### `messages.getAvailableReactions`

- Кратко: Получить available реакции.
- ID: `417243308` / `0x18dea0ac`
- Return type: `messages.AvailableReactions`
- Сигнатура: `messages.getAvailableReactions(hash:int) -> messages.AvailableReactions`
- Официальная страница: https://core.telegram.org/method/messages.getAvailableReactions
- Параметры:
  - `hash`: `int`

### `messages.getBotApp`

- Кратко: Получить бота приложение.
- ID: `889046467` / `0x34fdc5c3`
- Return type: `messages.BotApp`
- Сигнатура: `messages.getBotApp(app:InputBotApp, hash:long) -> messages.BotApp`
- Официальная страница: https://core.telegram.org/method/messages.getBotApp
- Параметры:
  - `app`: `InputBotApp`
  - `hash`: `long`

### `messages.getBotCallbackAnswer`

- Кратко: Получить бота callback answer.
- ID: `-1824339449` / `0x9342ca07`
- Return type: `messages.BotCallbackAnswer`
- Сигнатура: `messages.getBotCallbackAnswer(flags:#, game:flags.1?true, peer:InputPeer, msg_id:int, data:flags.0?bytes, password:flags.2?InputCheckPasswordSRP) -> messages.BotCallbackAnswer`
- Официальная страница: https://core.telegram.org/method/messages.getBotCallbackAnswer
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `game`: `flags.1?true` - optional через flags.1
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `data`: `flags.0?bytes` - optional через flags.0
  - `password`: `flags.2?InputCheckPasswordSRP` - optional через flags.2

### `messages.getChatInviteImporters`

- Кратко: Получить чат приглашение импортёров.
- ID: `-553329330` / `0xdf04dd4e`
- Return type: `messages.ChatInviteImporters`
- Сигнатура: `messages.getChatInviteImporters(flags:#, requested:flags.0?true, subscription_expired:flags.3?true, peer:InputPeer, link:flags.1?string, q:flags.2?string, offset_date:int, offset_user:InputUser, limit:int) -> messages.ChatInviteImporters`
- Официальная страница: https://core.telegram.org/method/messages.getChatInviteImporters
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `requested`: `flags.0?true` - optional через flags.0
  - `subscription_expired`: `flags.3?true` - optional через flags.3
  - `peer`: `InputPeer`
  - `link`: `flags.1?string` - optional через flags.1
  - `q`: `flags.2?string` - optional через flags.2
  - `offset_date`: `int`
  - `offset_user`: `InputUser`
  - `limit`: `int`

### `messages.getChats`

- Кратко: Получить чаты.
- ID: `1240027791` / `0x49e9528f`
- Return type: `messages.Chats`
- Сигнатура: `messages.getChats(id:Vector) -> messages.Chats`
- Официальная страница: https://core.telegram.org/method/messages.getChats
- Параметры:
  - `id`: `Vector`

### `messages.getCommonChats`

- Кратко: Получить общие чаты.
- ID: `-468934396` / `0xe40ca104`
- Return type: `messages.Chats`
- Сигнатура: `messages.getCommonChats(user_id:InputUser, max_id:long, limit:int) -> messages.Chats`
- Официальная страница: https://core.telegram.org/method/messages.getCommonChats
- Параметры:
  - `user_id`: `InputUser`
  - `max_id`: `long`
  - `limit`: `int`

### `messages.getCustomEmojiDocuments`

- Кратко: Получить кастомные эмодзи documents.
- ID: `-643100844` / `0xd9ab0f54`
- Return type: `Vector`
- Сигнатура: `messages.getCustomEmojiDocuments(document_id:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/messages.getCustomEmojiDocuments
- Параметры:
  - `document_id`: `Vector`

### `messages.getDefaultHistoryTTL`

- Кратко: Получить default историю TTL/срок жизни.
- ID: `1703637384` / `0x658b7188`
- Return type: `DefaultHistoryTTL`
- Сигнатура: `messages.getDefaultHistoryTTL() -> DefaultHistoryTTL`
- Официальная страница: https://core.telegram.org/method/messages.getDefaultHistoryTTL
- Параметры:
  - Нет параметров.

### `messages.getDefaultTagReactions`

- Кратко: Получить default tag реакции.
- ID: `-1107741656` / `0xbdf93428`
- Return type: `messages.Reactions`
- Сигнатура: `messages.getDefaultTagReactions(hash:long) -> messages.Reactions`
- Официальная страница: https://core.telegram.org/method/messages.getDefaultTagReactions
- Параметры:
  - `hash`: `long`

### `messages.getDhConfig`

- Кратко: Получить dh конфигурацию.
- ID: `651135312` / `0x26cf8950`
- Return type: `messages.DhConfig`
- Сигнатура: `messages.getDhConfig(version:int, random_length:int) -> messages.DhConfig`
- Официальная страница: https://core.telegram.org/method/messages.getDhConfig
- Параметры:
  - `version`: `int`
  - `random_length`: `int`

### `messages.getDialogFilters`

- Кратко: Получить диалог filters.
- ID: `-271283063` / `0xefd48c89`
- Return type: `messages.DialogFilters`
- Сигнатура: `messages.getDialogFilters() -> messages.DialogFilters`
- Официальная страница: https://core.telegram.org/method/messages.getDialogFilters
- Параметры:
  - Нет параметров.

### `messages.getDialogUnreadMarks`

- Кратко: Получить диалог unread marks.
- ID: `555754018` / `0x21202222`
- Return type: `Vector`
- Сигнатура: `messages.getDialogUnreadMarks(flags:#, parent_peer:flags.0?InputPeer) -> Vector`
- Официальная страница: https://core.telegram.org/method/messages.getDialogUnreadMarks
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `parent_peer`: `flags.0?InputPeer` - optional через flags.0

### `messages.getDialogs`

- Кратко: Получить диалоги.
- ID: `-1594569905` / `0xa0f4cb4f`
- Return type: `messages.Dialogs`
- Сигнатура: `messages.getDialogs(flags:#, exclude_pinned:flags.0?true, folder_id:flags.1?int, offset_date:int, offset_id:int, offset_peer:InputPeer, limit:int, hash:long) -> messages.Dialogs`
- Официальная страница: https://core.telegram.org/method/messages.getDialogs
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `exclude_pinned`: `flags.0?true` - optional через flags.0
  - `folder_id`: `flags.1?int` - optional через flags.1
  - `offset_date`: `int`
  - `offset_id`: `int`
  - `offset_peer`: `InputPeer`
  - `limit`: `int`
  - `hash`: `long`

### `messages.getDiscussionMessage`

- Кратко: Получить обсуждение сообщение.
- ID: `1147761405` / `0x446972fd`
- Return type: `messages.DiscussionMessage`
- Сигнатура: `messages.getDiscussionMessage(peer:InputPeer, msg_id:int) -> messages.DiscussionMessage`
- Официальная страница: https://core.telegram.org/method/messages.getDiscussionMessage
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`

### `messages.getDocumentByHash`

- Кратко: Получить document by hash.
- ID: `-1309538785` / `0xb1f2061f`
- Return type: `Document`
- Сигнатура: `messages.getDocumentByHash(sha256:bytes, size:long, mime_type:string) -> Document`
- Официальная страница: https://core.telegram.org/method/messages.getDocumentByHash
- Параметры:
  - `sha256`: `bytes`
  - `size`: `long`
  - `mime_type`: `string`

### `messages.getEmojiGroups`

- Кратко: Получить эмодзи groups.
- ID: `1955122779` / `0x7488ce5b`
- Return type: `messages.EmojiGroups`
- Сигнатура: `messages.getEmojiGroups(hash:int) -> messages.EmojiGroups`
- Официальная страница: https://core.telegram.org/method/messages.getEmojiGroups
- Параметры:
  - `hash`: `int`

### `messages.getEmojiKeywords`

- Кратко: Получить эмодзи keywords.
- ID: `899735650` / `0x35a0e062`
- Return type: `EmojiKeywordsDifference`
- Сигнатура: `messages.getEmojiKeywords(lang_code:string) -> EmojiKeywordsDifference`
- Официальная страница: https://core.telegram.org/method/messages.getEmojiKeywords
- Параметры:
  - `lang_code`: `string`

### `messages.getEmojiKeywordsDifference`

- Кратко: Получить эмодзи keywords разницу.
- ID: `352892591` / `0x1508b6af`
- Return type: `EmojiKeywordsDifference`
- Сигнатура: `messages.getEmojiKeywordsDifference(lang_code:string, from_version:int) -> EmojiKeywordsDifference`
- Официальная страница: https://core.telegram.org/method/messages.getEmojiKeywordsDifference
- Параметры:
  - `lang_code`: `string`
  - `from_version`: `int`

### `messages.getEmojiKeywordsLanguages`

- Кратко: Получить эмодзи keywords languages.
- ID: `1318675378` / `0x4e9963b2`
- Return type: `Vector`
- Сигнатура: `messages.getEmojiKeywordsLanguages(lang_codes:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/messages.getEmojiKeywordsLanguages
- Параметры:
  - `lang_codes`: `Vector`

### `messages.getEmojiProfilePhotoGroups`

- Кратко: Получить эмодзи профиль фото groups.
- ID: `564480243` / `0x21a548f3`
- Return type: `messages.EmojiGroups`
- Сигнатура: `messages.getEmojiProfilePhotoGroups(hash:int) -> messages.EmojiGroups`
- Официальная страница: https://core.telegram.org/method/messages.getEmojiProfilePhotoGroups
- Параметры:
  - `hash`: `int`

### `messages.getEmojiStatusGroups`

- Кратко: Получить эмодзи статус groups.
- ID: `785209037` / `0x2ecd56cd`
- Return type: `messages.EmojiGroups`
- Сигнатура: `messages.getEmojiStatusGroups(hash:int) -> messages.EmojiGroups`
- Официальная страница: https://core.telegram.org/method/messages.getEmojiStatusGroups
- Параметры:
  - `hash`: `int`

### `messages.getEmojiStickerGroups`

- Кратко: Получить эмодзи стикер groups.
- ID: `500711669` / `0x1dd840f5`
- Return type: `messages.EmojiGroups`
- Сигнатура: `messages.getEmojiStickerGroups(hash:int) -> messages.EmojiGroups`
- Официальная страница: https://core.telegram.org/method/messages.getEmojiStickerGroups
- Параметры:
  - `hash`: `int`

### `messages.getEmojiStickers`

- Кратко: Получить эмодзи стикеры.
- ID: `-67329649` / `0xfbfca18f`
- Return type: `messages.AllStickers`
- Сигнатура: `messages.getEmojiStickers(hash:long) -> messages.AllStickers`
- Официальная страница: https://core.telegram.org/method/messages.getEmojiStickers
- Параметры:
  - `hash`: `long`

### `messages.getEmojiURL`

- Кратко: Получить эмодзи url.
- ID: `-709817306` / `0xd5b10c26`
- Return type: `EmojiURL`
- Сигнатура: `messages.getEmojiURL(lang_code:string) -> EmojiURL`
- Официальная страница: https://core.telegram.org/method/messages.getEmojiURL
- Параметры:
  - `lang_code`: `string`

### `messages.getExportedChatInvite`

- Кратко: Получить экспортированные чат приглашение.
- ID: `1937010524` / `0x73746f5c`
- Return type: `messages.ExportedChatInvite`
- Сигнатура: `messages.getExportedChatInvite(peer:InputPeer, link:string) -> messages.ExportedChatInvite`
- Официальная страница: https://core.telegram.org/method/messages.getExportedChatInvite
- Параметры:
  - `peer`: `InputPeer`
  - `link`: `string`

### `messages.getExportedChatInvites`

- Кратко: Получить экспортированные чат invites.
- ID: `-1565154314` / `0xa2b5a3f6`
- Return type: `messages.ExportedChatInvites`
- Сигнатура: `messages.getExportedChatInvites(flags:#, revoked:flags.3?true, peer:InputPeer, admin_id:InputUser, offset_date:flags.2?int, offset_link:flags.2?string, limit:int) -> messages.ExportedChatInvites`
- Официальная страница: https://core.telegram.org/method/messages.getExportedChatInvites
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `revoked`: `flags.3?true` - optional через flags.3
  - `peer`: `InputPeer`
  - `admin_id`: `InputUser`
  - `offset_date`: `flags.2?int` - optional через flags.2
  - `offset_link`: `flags.2?string` - optional через flags.2
  - `limit`: `int`

### `messages.getExtendedMedia`

- Кратко: Получить расширенные медиа.
- ID: `-2064119788` / `0x84f80814`
- Return type: `Updates`
- Сигнатура: `messages.getExtendedMedia(peer:InputPeer, id:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.getExtendedMedia
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`

### `messages.getFactCheck`

- Кратко: Получить fact check.
- ID: `-1177696786` / `0xb9cdc5ee`
- Return type: `Vector`
- Сигнатура: `messages.getFactCheck(peer:InputPeer, msg_id:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/messages.getFactCheck
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `Vector`

### `messages.getFavedStickers`

- Кратко: Получить faved стикеры.
- ID: `82946729` / `0x04f1aaa9`
- Return type: `messages.FavedStickers`
- Сигнатура: `messages.getFavedStickers(hash:long) -> messages.FavedStickers`
- Официальная страница: https://core.telegram.org/method/messages.getFavedStickers
- Параметры:
  - `hash`: `long`

### `messages.getFeaturedEmojiStickers`

- Кратко: Получить рекомендуемые эмодзи стикеры.
- ID: `248473398` / `0x0ecf6736`
- Return type: `messages.FeaturedStickers`
- Сигнатура: `messages.getFeaturedEmojiStickers(hash:long) -> messages.FeaturedStickers`
- Официальная страница: https://core.telegram.org/method/messages.getFeaturedEmojiStickers
- Параметры:
  - `hash`: `long`

### `messages.getFeaturedStickers`

- Кратко: Получить рекомендуемые стикеры.
- ID: `1685588756` / `0x64780b14`
- Return type: `messages.FeaturedStickers`
- Сигнатура: `messages.getFeaturedStickers(hash:long) -> messages.FeaturedStickers`
- Официальная страница: https://core.telegram.org/method/messages.getFeaturedStickers
- Параметры:
  - `hash`: `long`

### `messages.getFullChat`

- Кратко: Получить полную информацию о чат.
- ID: `-1364194508` / `0xaeb00b34`
- Return type: `messages.ChatFull`
- Сигнатура: `messages.getFullChat(chat_id:long) -> messages.ChatFull`
- Официальная страница: https://core.telegram.org/method/messages.getFullChat
- Параметры:
  - `chat_id`: `long`

### `messages.getGameHighScores`

- Кратко: Получить game high scores.
- ID: `-400399203` / `0xe822649d`
- Return type: `messages.HighScores`
- Сигнатура: `messages.getGameHighScores(peer:InputPeer, id:int, user_id:InputUser) -> messages.HighScores`
- Официальная страница: https://core.telegram.org/method/messages.getGameHighScores
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `int`
  - `user_id`: `InputUser`

### `messages.getHistory`

- Кратко: Получить историю.
- ID: `1143203525` / `0x4423e6c5`
- Return type: `messages.Messages`
- Сигнатура: `messages.getHistory(peer:InputPeer, offset_id:int, offset_date:int, add_offset:int, limit:int, max_id:int, min_id:int, hash:long) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.getHistory
- Параметры:
  - `peer`: `InputPeer`
  - `offset_id`: `int`
  - `offset_date`: `int`
  - `add_offset`: `int`
  - `limit`: `int`
  - `max_id`: `int`
  - `min_id`: `int`
  - `hash`: `long`

### `messages.getInlineBotResults`

- Кратко: Получить inline бота results.
- ID: `1364105629` / `0x514e999d`
- Return type: `messages.BotResults`
- Сигнатура: `messages.getInlineBotResults(flags:#, bot:InputUser, peer:InputPeer, geo_point:flags.0?InputGeoPoint, query:string, offset:string) -> messages.BotResults`
- Официальная страница: https://core.telegram.org/method/messages.getInlineBotResults
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `bot`: `InputUser`
  - `peer`: `InputPeer`
  - `geo_point`: `flags.0?InputGeoPoint` - optional через flags.0
  - `query`: `string`
  - `offset`: `string`

### `messages.getInlineGameHighScores`

- Кратко: Получить inline game high scores.
- ID: `258170395` / `0x0f635e1b`
- Return type: `messages.HighScores`
- Сигнатура: `messages.getInlineGameHighScores(id:InputBotInlineMessageID, user_id:InputUser) -> messages.HighScores`
- Официальная страница: https://core.telegram.org/method/messages.getInlineGameHighScores
- Параметры:
  - `id`: `InputBotInlineMessageID`
  - `user_id`: `InputUser`

### `messages.getMaskStickers`

- Кратко: Получить маску стикеры.
- ID: `1678738104` / `0x640f82b8`
- Return type: `messages.AllStickers`
- Сигнатура: `messages.getMaskStickers(hash:long) -> messages.AllStickers`
- Официальная страница: https://core.telegram.org/method/messages.getMaskStickers
- Параметры:
  - `hash`: `long`

### `messages.getMessageEditData`

- Кратко: Получить сообщение edit данные.
- ID: `-39416522` / `0xfda68d36`
- Return type: `messages.MessageEditData`
- Сигнатура: `messages.getMessageEditData(peer:InputPeer, id:int) -> messages.MessageEditData`
- Официальная страница: https://core.telegram.org/method/messages.getMessageEditData
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `int`

### `messages.getMessageReactionsList`

- Кратко: Получить сообщение реакции список.
- ID: `1176190792` / `0x461b3f48`
- Return type: `messages.MessageReactionsList`
- Сигнатура: `messages.getMessageReactionsList(flags:#, peer:InputPeer, id:int, reaction:flags.0?Reaction, offset:flags.1?string, limit:int) -> messages.MessageReactionsList`
- Официальная страница: https://core.telegram.org/method/messages.getMessageReactionsList
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `id`: `int`
  - `reaction`: `flags.0?Reaction` - optional через flags.0
  - `offset`: `flags.1?string` - optional через flags.1
  - `limit`: `int`

### `messages.getMessageReadParticipants`

- Кратко: Получить сообщение прочтение участников.
- ID: `834782287` / `0x31c1c44f`
- Return type: `Vector`
- Сигнатура: `messages.getMessageReadParticipants(peer:InputPeer, msg_id:int) -> Vector`
- Официальная страница: https://core.telegram.org/method/messages.getMessageReadParticipants
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`

### `messages.getMessages`

- Кратко: Получить сообщения.
- ID: `1673946374` / `0x63c66506`
- Return type: `messages.Messages`
- Сигнатура: `messages.getMessages(id:Vector) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.getMessages
- Параметры:
  - `id`: `Vector`

### `messages.getMessagesReactions`

- Кратко: Получить сообщения реакции.
- ID: `-1950707482` / `0x8bba90e6`
- Return type: `Updates`
- Сигнатура: `messages.getMessagesReactions(peer:InputPeer, id:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.getMessagesReactions
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`

### `messages.getMessagesViews`

- Кратко: Получить сообщения просмотры.
- ID: `1468322785` / `0x5784d3e1`
- Return type: `messages.MessageViews`
- Сигнатура: `messages.getMessagesViews(peer:InputPeer, id:Vector, increment:Bool) -> messages.MessageViews`
- Официальная страница: https://core.telegram.org/method/messages.getMessagesViews
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`
  - `increment`: `Bool`

### `messages.getMyStickers`

- Кратко: Получить my стикеры.
- ID: `-793386500` / `0xd0b5e1fc`
- Return type: `messages.MyStickers`
- Сигнатура: `messages.getMyStickers(offset_id:long, limit:int) -> messages.MyStickers`
- Официальная страница: https://core.telegram.org/method/messages.getMyStickers
- Параметры:
  - `offset_id`: `long`
  - `limit`: `int`

### `messages.getOldFeaturedStickers`

- Кратко: Получить old рекомендуемые стикеры.
- ID: `2127598753` / `0x7ed094a1`
- Return type: `messages.FeaturedStickers`
- Сигнатура: `messages.getOldFeaturedStickers(offset:int, limit:int, hash:long) -> messages.FeaturedStickers`
- Официальная страница: https://core.telegram.org/method/messages.getOldFeaturedStickers
- Параметры:
  - `offset`: `int`
  - `limit`: `int`
  - `hash`: `long`

### `messages.getOnlines`

- Кратко: Получить онлайн-статусы.
- ID: `1848369232` / `0x6e2be050`
- Return type: `ChatOnlines`
- Сигнатура: `messages.getOnlines(peer:InputPeer) -> ChatOnlines`
- Официальная страница: https://core.telegram.org/method/messages.getOnlines
- Параметры:
  - `peer`: `InputPeer`

### `messages.getOutboxReadDate`

- Кратко: Получить outbox прочтение date.
- ID: `-1941176739` / `0x8c4bfe5d`
- Return type: `OutboxReadDate`
- Сигнатура: `messages.getOutboxReadDate(peer:InputPeer, msg_id:int) -> OutboxReadDate`
- Официальная страница: https://core.telegram.org/method/messages.getOutboxReadDate
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`

### `messages.getPaidReactionPrivacy`

- Кратко: Получить платные реакцию приватность.
- ID: `1193563562` / `0x472455aa`
- Return type: `Updates`
- Сигнатура: `messages.getPaidReactionPrivacy() -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.getPaidReactionPrivacy
- Параметры:
  - Нет параметров.

### `messages.getPeerDialogs`

- Кратко: Получить peer/диалог диалоги.
- ID: `-462373635` / `0xe470bcfd`
- Return type: `messages.PeerDialogs`
- Сигнатура: `messages.getPeerDialogs(peers:Vector) -> messages.PeerDialogs`
- Официальная страница: https://core.telegram.org/method/messages.getPeerDialogs
- Параметры:
  - `peers`: `Vector`

### `messages.getPeerSettings`

- Кратко: Получить peer/диалог настройки.
- ID: `-270948702` / `0xefd9a6a2`
- Return type: `messages.PeerSettings`
- Сигнатура: `messages.getPeerSettings(peer:InputPeer) -> messages.PeerSettings`
- Официальная страница: https://core.telegram.org/method/messages.getPeerSettings
- Параметры:
  - `peer`: `InputPeer`

### `messages.getPinnedDialogs`

- Кратко: Получить закреплённое диалоги.
- ID: `-692498958` / `0xd6b94df2`
- Return type: `messages.PeerDialogs`
- Сигнатура: `messages.getPinnedDialogs(folder_id:int) -> messages.PeerDialogs`
- Официальная страница: https://core.telegram.org/method/messages.getPinnedDialogs
- Параметры:
  - `folder_id`: `int`

### `messages.getPinnedSavedDialogs`

- Кратко: Получить закреплённое сохранённое диалоги.
- ID: `-700607264` / `0xd63d94e0`
- Return type: `messages.SavedDialogs`
- Сигнатура: `messages.getPinnedSavedDialogs() -> messages.SavedDialogs`
- Официальная страница: https://core.telegram.org/method/messages.getPinnedSavedDialogs
- Параметры:
  - Нет параметров.

### `messages.getPollResults`

- Кратко: Получить poll results.
- ID: `1941660731` / `0x73bb643b`
- Return type: `Updates`
- Сигнатура: `messages.getPollResults(peer:InputPeer, msg_id:int) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.getPollResults
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`

### `messages.getPollVotes`

- Кратко: Получить poll votes.
- ID: `-1200736242` / `0xb86e380e`
- Return type: `messages.VotesList`
- Сигнатура: `messages.getPollVotes(flags:#, peer:InputPeer, id:int, option:flags.0?bytes, offset:flags.1?string, limit:int) -> messages.VotesList`
- Официальная страница: https://core.telegram.org/method/messages.getPollVotes
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `id`: `int`
  - `option`: `flags.0?bytes` - optional через flags.0
  - `offset`: `flags.1?string` - optional через flags.1
  - `limit`: `int`

### `messages.getPreparedInlineMessage`

- Кратко: Получить подготовленные inline сообщение.
- ID: `-2055291464` / `0x857ebdb8`
- Return type: `messages.PreparedInlineMessage`
- Сигнатура: `messages.getPreparedInlineMessage(bot:InputUser, id:string) -> messages.PreparedInlineMessage`
- Официальная страница: https://core.telegram.org/method/messages.getPreparedInlineMessage
- Параметры:
  - `bot`: `InputUser`
  - `id`: `string`

### `messages.getQuickReplies`

- Кратко: Получить быстрый ответы.
- ID: `-729550168` / `0xd483f2a8`
- Return type: `messages.QuickReplies`
- Сигнатура: `messages.getQuickReplies(hash:long) -> messages.QuickReplies`
- Официальная страница: https://core.telegram.org/method/messages.getQuickReplies
- Параметры:
  - `hash`: `long`

### `messages.getQuickReplyMessages`

- Кратко: Получить быстрый ответ сообщения.
- ID: `-1801153085` / `0x94a495c3`
- Return type: `messages.Messages`
- Сигнатура: `messages.getQuickReplyMessages(flags:#, shortcut_id:int, id:flags.0?Vector, hash:long) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.getQuickReplyMessages
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `shortcut_id`: `int`
  - `id`: `flags.0?Vector` - optional через flags.0
  - `hash`: `long`

### `messages.getRecentLocations`

- Кратко: Получить недавние locations.
- ID: `1881817312` / `0x702a40e0`
- Return type: `messages.Messages`
- Сигнатура: `messages.getRecentLocations(peer:InputPeer, limit:int, hash:long) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.getRecentLocations
- Параметры:
  - `peer`: `InputPeer`
  - `limit`: `int`
  - `hash`: `long`

### `messages.getRecentReactions`

- Кратко: Получить недавние реакции.
- ID: `960896434` / `0x39461db2`
- Return type: `messages.Reactions`
- Сигнатура: `messages.getRecentReactions(limit:int, hash:long) -> messages.Reactions`
- Официальная страница: https://core.telegram.org/method/messages.getRecentReactions
- Параметры:
  - `limit`: `int`
  - `hash`: `long`

### `messages.getRecentStickers`

- Кратко: Получить недавние стикеры.
- ID: `-1649852357` / `0x9da9403b`
- Return type: `messages.RecentStickers`
- Сигнатура: `messages.getRecentStickers(flags:#, attached:flags.0?true, hash:long) -> messages.RecentStickers`
- Официальная страница: https://core.telegram.org/method/messages.getRecentStickers
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `attached`: `flags.0?true` - optional через flags.0
  - `hash`: `long`

### `messages.getReplies`

- Кратко: Получить ответы.
- ID: `584962828` / `0x22ddd30c`
- Return type: `messages.Messages`
- Сигнатура: `messages.getReplies(peer:InputPeer, msg_id:int, offset_id:int, offset_date:int, add_offset:int, limit:int, max_id:int, min_id:int, hash:long) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.getReplies
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `offset_id`: `int`
  - `offset_date`: `int`
  - `add_offset`: `int`
  - `limit`: `int`
  - `max_id`: `int`
  - `min_id`: `int`
  - `hash`: `long`

### `messages.getSavedDialogs`

- Кратко: Получить сохранённые диалоги.
- ID: `512883865` / `0x1e91fc99`
- Return type: `messages.SavedDialogs`
- Сигнатура: `messages.getSavedDialogs(flags:#, exclude_pinned:flags.0?true, parent_peer:flags.1?InputPeer, offset_date:int, offset_id:int, offset_peer:InputPeer, limit:int, hash:long) -> messages.SavedDialogs`
- Официальная страница: https://core.telegram.org/method/messages.getSavedDialogs
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `exclude_pinned`: `flags.0?true` - optional через flags.0
  - `parent_peer`: `flags.1?InputPeer` - optional через flags.1
  - `offset_date`: `int`
  - `offset_id`: `int`
  - `offset_peer`: `InputPeer`
  - `limit`: `int`
  - `hash`: `long`

### `messages.getSavedDialogsByID`

- Кратко: Получить сохранённые диалоги by id.
- ID: `1869585558` / `0x6f6f9c96`
- Return type: `messages.SavedDialogs`
- Сигнатура: `messages.getSavedDialogsByID(flags:#, parent_peer:flags.1?InputPeer, ids:Vector) -> messages.SavedDialogs`
- Официальная страница: https://core.telegram.org/method/messages.getSavedDialogsByID
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `parent_peer`: `flags.1?InputPeer` - optional через flags.1
  - `ids`: `Vector`

### `messages.getSavedGifs`

- Кратко: Получить сохранённые GIF.
- ID: `1559270965` / `0x5cf09635`
- Return type: `messages.SavedGifs`
- Сигнатура: `messages.getSavedGifs(hash:long) -> messages.SavedGifs`
- Официальная страница: https://core.telegram.org/method/messages.getSavedGifs
- Параметры:
  - `hash`: `long`

### `messages.getSavedHistory`

- Кратко: Получить сохранённые историю.
- ID: `-1718964215` / `0x998ab009`
- Return type: `messages.Messages`
- Сигнатура: `messages.getSavedHistory(flags:#, parent_peer:flags.0?InputPeer, peer:InputPeer, offset_id:int, offset_date:int, add_offset:int, limit:int, max_id:int, min_id:int, hash:long) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.getSavedHistory
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `parent_peer`: `flags.0?InputPeer` - optional через flags.0
  - `peer`: `InputPeer`
  - `offset_id`: `int`
  - `offset_date`: `int`
  - `add_offset`: `int`
  - `limit`: `int`
  - `max_id`: `int`
  - `min_id`: `int`
  - `hash`: `long`

### `messages.getSavedReactionTags`

- Кратко: Получить сохранённые реакцию tags.
- ID: `909631579` / `0x3637e05b`
- Return type: `messages.SavedReactionTags`
- Сигнатура: `messages.getSavedReactionTags(flags:#, peer:flags.0?InputPeer, hash:long) -> messages.SavedReactionTags`
- Официальная страница: https://core.telegram.org/method/messages.getSavedReactionTags
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `flags.0?InputPeer` - optional через flags.0
  - `hash`: `long`

### `messages.getScheduledHistory`

- Кратко: Получить запланированные историю.
- ID: `-183077365` / `0xf516760b`
- Return type: `messages.Messages`
- Сигнатура: `messages.getScheduledHistory(peer:InputPeer, hash:long) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.getScheduledHistory
- Параметры:
  - `peer`: `InputPeer`
  - `hash`: `long`

### `messages.getScheduledMessages`

- Кратко: Получить запланированные сообщения.
- ID: `-1111817116` / `0xbdbb0464`
- Return type: `messages.Messages`
- Сигнатура: `messages.getScheduledMessages(peer:InputPeer, id:Vector) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.getScheduledMessages
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`

### `messages.getSearchCounters`

- Кратко: Получить поиск counters.
- ID: `465367808` / `0x1bbcf300`
- Return type: `Vector`
- Сигнатура: `messages.getSearchCounters(flags:#, peer:InputPeer, saved_peer_id:flags.2?InputPeer, top_msg_id:flags.0?int, filters:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/messages.getSearchCounters
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `saved_peer_id`: `flags.2?InputPeer` - optional через flags.2
  - `top_msg_id`: `flags.0?int` - optional через flags.0
  - `filters`: `Vector`

### `messages.getSearchResultsCalendar`

- Кратко: Получить поиск results calendar.
- ID: `1789130429` / `0x6aa3f6bd`
- Return type: `messages.SearchResultsCalendar`
- Сигнатура: `messages.getSearchResultsCalendar(flags:#, peer:InputPeer, saved_peer_id:flags.2?InputPeer, filter:MessagesFilter, offset_id:int, offset_date:int) -> messages.SearchResultsCalendar`
- Официальная страница: https://core.telegram.org/method/messages.getSearchResultsCalendar
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `saved_peer_id`: `flags.2?InputPeer` - optional через flags.2
  - `filter`: `MessagesFilter`
  - `offset_id`: `int`
  - `offset_date`: `int`

### `messages.getSearchResultsPositions`

- Кратко: Получить поиск results positions.
- ID: `-1669386480` / `0x9c7f2f10`
- Return type: `messages.SearchResultsPositions`
- Сигнатура: `messages.getSearchResultsPositions(flags:#, peer:InputPeer, saved_peer_id:flags.2?InputPeer, filter:MessagesFilter, offset_id:int, limit:int) -> messages.SearchResultsPositions`
- Официальная страница: https://core.telegram.org/method/messages.getSearchResultsPositions
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `saved_peer_id`: `flags.2?InputPeer` - optional через flags.2
  - `filter`: `MessagesFilter`
  - `offset_id`: `int`
  - `limit`: `int`

### `messages.getSplitRanges`

- Кратко: Получить split ranges.
- ID: `486505992` / `0x1cff7e08`
- Return type: `Vector`
- Сигнатура: `messages.getSplitRanges() -> Vector`
- Официальная страница: https://core.telegram.org/method/messages.getSplitRanges
- Параметры:
  - Нет параметров.

### `messages.getSponsoredMessages`

- Кратко: Получить спонсируемые сообщения.
- ID: `1030547536` / `0x3d6ce850`
- Return type: `messages.SponsoredMessages`
- Сигнатура: `messages.getSponsoredMessages(flags:#, peer:InputPeer, msg_id:flags.0?int) -> messages.SponsoredMessages`
- Официальная страница: https://core.telegram.org/method/messages.getSponsoredMessages
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `msg_id`: `flags.0?int` - optional через flags.0

### `messages.getStickerSet`

- Кратко: Получить стикер set.
- ID: `-928977804` / `0xc8a0ec74`
- Return type: `messages.StickerSet`
- Сигнатура: `messages.getStickerSet(stickerset:InputStickerSet, hash:int) -> messages.StickerSet`
- Официальная страница: https://core.telegram.org/method/messages.getStickerSet
- Параметры:
  - `stickerset`: `InputStickerSet`
  - `hash`: `int`

### `messages.getStickers`

- Кратко: Получить стикеры.
- ID: `-710552671` / `0xd5a5d3a1`
- Return type: `messages.Stickers`
- Сигнатура: `messages.getStickers(emoticon:string, hash:long) -> messages.Stickers`
- Официальная страница: https://core.telegram.org/method/messages.getStickers
- Параметры:
  - `emoticon`: `string`
  - `hash`: `long`

### `messages.getSuggestedDialogFilters`

- Кратко: Получить предложенные диалог filters.
- ID: `-1566780372` / `0xa29cd42c`
- Return type: `Vector`
- Сигнатура: `messages.getSuggestedDialogFilters() -> Vector`
- Официальная страница: https://core.telegram.org/method/messages.getSuggestedDialogFilters
- Параметры:
  - Нет параметров.

### `messages.getTopReactions`

- Кратко: Получить верх реакции.
- ID: `-1149164102` / `0xbb8125ba`
- Return type: `messages.Reactions`
- Сигнатура: `messages.getTopReactions(limit:int, hash:long) -> messages.Reactions`
- Официальная страница: https://core.telegram.org/method/messages.getTopReactions
- Параметры:
  - `limit`: `int`
  - `hash`: `long`

### `messages.getUnreadMentions`

- Кратко: Получить unread mentions.
- ID: `-251140208` / `0xf107e790`
- Return type: `messages.Messages`
- Сигнатура: `messages.getUnreadMentions(flags:#, peer:InputPeer, top_msg_id:flags.0?int, offset_id:int, add_offset:int, limit:int, max_id:int, min_id:int) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.getUnreadMentions
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `top_msg_id`: `flags.0?int` - optional через flags.0
  - `offset_id`: `int`
  - `add_offset`: `int`
  - `limit`: `int`
  - `max_id`: `int`
  - `min_id`: `int`

### `messages.getUnreadReactions`

- Кратко: Получить unread реакции.
- ID: `-1115713364` / `0xbd7f90ac`
- Return type: `messages.Messages`
- Сигнатура: `messages.getUnreadReactions(flags:#, peer:InputPeer, top_msg_id:flags.0?int, saved_peer_id:flags.1?InputPeer, offset_id:int, add_offset:int, limit:int, max_id:int, min_id:int) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.getUnreadReactions
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `top_msg_id`: `flags.0?int` - optional через flags.0
  - `saved_peer_id`: `flags.1?InputPeer` - optional через flags.1
  - `offset_id`: `int`
  - `add_offset`: `int`
  - `limit`: `int`
  - `max_id`: `int`
  - `min_id`: `int`

### `messages.getWebPage`

- Кратко: Получить веб page.
- ID: `-1919511901` / `0x8d9692a3`
- Return type: `messages.WebPage`
- Сигнатура: `messages.getWebPage(url:string, hash:int) -> messages.WebPage`
- Официальная страница: https://core.telegram.org/method/messages.getWebPage
- Параметры:
  - `url`: `string`
  - `hash`: `int`

### `messages.getWebPagePreview`

- Кратко: Получить веб page превью.
- ID: `1460498287` / `0x570d6f6f`
- Return type: `messages.WebPagePreview`
- Сигнатура: `messages.getWebPagePreview(flags:#, message:string, entities:flags.3?Vector) -> messages.WebPagePreview`
- Официальная страница: https://core.telegram.org/method/messages.getWebPagePreview
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `message`: `string`
  - `entities`: `flags.3?Vector` - optional через flags.3

### `messages.hideAllChatJoinRequests`

- Кратко: Скрыть all чат вход запросы.
- ID: `-528091926` / `0xe085f4ea`
- Return type: `Updates`
- Сигнатура: `messages.hideAllChatJoinRequests(flags:#, approved:flags.0?true, peer:InputPeer, link:flags.1?string) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.hideAllChatJoinRequests
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `approved`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`
  - `link`: `flags.1?string` - optional через flags.1

### `messages.hideChatJoinRequest`

- Кратко: Скрыть чат вход запрос.
- ID: `2145904661` / `0x7fe7e815`
- Return type: `Updates`
- Сигнатура: `messages.hideChatJoinRequest(flags:#, approved:flags.0?true, peer:InputPeer, user_id:InputUser) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.hideChatJoinRequest
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `approved`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`
  - `user_id`: `InputUser`

### `messages.hidePeerSettingsBar`

- Кратко: Скрыть peer/диалог настройки bar.
- ID: `1336717624` / `0x4facb138`
- Return type: `Bool`
- Сигнатура: `messages.hidePeerSettingsBar(peer:InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.hidePeerSettingsBar
- Параметры:
  - `peer`: `InputPeer`

### `messages.importChatInvite`

- Кратко: Импортировать чат приглашение.
- ID: `1817183516` / `0x6c50051c`
- Return type: `Updates`
- Сигнатура: `messages.importChatInvite(hash:string) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.importChatInvite
- Параметры:
  - `hash`: `string`

### `messages.initHistoryImport`

- Кратко: Операция с init историю import.
- ID: `873008187` / `0x34090c3b`
- Return type: `messages.HistoryImport`
- Сигнатура: `messages.initHistoryImport(peer:InputPeer, file:InputFile, media_count:int) -> messages.HistoryImport`
- Официальная страница: https://core.telegram.org/method/messages.initHistoryImport
- Параметры:
  - `peer`: `InputPeer`
  - `file`: `InputFile`
  - `media_count`: `int`

### `messages.installStickerSet`

- Кратко: Установить стикер set.
- ID: `-946871200` / `0xc78fe460`
- Return type: `messages.StickerSetInstallResult`
- Сигнатура: `messages.installStickerSet(stickerset:InputStickerSet, archived:Bool) -> messages.StickerSetInstallResult`
- Официальная страница: https://core.telegram.org/method/messages.installStickerSet
- Параметры:
  - `stickerset`: `InputStickerSet`
  - `archived`: `Bool`

### `messages.markDialogUnread`

- Кратко: Операция с mark диалог unread.
- ID: `-1940912392` / `0x8c5006f8`
- Return type: `Bool`
- Сигнатура: `messages.markDialogUnread(flags:#, unread:flags.0?true, parent_peer:flags.1?InputPeer, peer:InputDialogPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.markDialogUnread
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `unread`: `flags.0?true` - optional через flags.0
  - `parent_peer`: `flags.1?InputPeer` - optional через flags.1
  - `peer`: `InputDialogPeer`

### `messages.migrateChat`

- Кратко: Мигрировать чат.
- ID: `-1568189671` / `0xa2875319`
- Return type: `Updates`
- Сигнатура: `messages.migrateChat(chat_id:long) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.migrateChat
- Параметры:
  - `chat_id`: `long`

### `messages.prolongWebView`

- Кратко: Операция с prolong веб view.
- ID: `-1328014717` / `0xb0d81a83`
- Return type: `Bool`
- Сигнатура: `messages.prolongWebView(flags:#, silent:flags.5?true, peer:InputPeer, bot:InputUser, query_id:long, reply_to:flags.0?InputReplyTo, send_as:flags.13?InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.prolongWebView
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `silent`: `flags.5?true` - optional через flags.5
  - `peer`: `InputPeer`
  - `bot`: `InputUser`
  - `query_id`: `long`
  - `reply_to`: `flags.0?InputReplyTo` - optional через flags.0
  - `send_as`: `flags.13?InputPeer` - optional через flags.13

### `messages.rateTranscribedAudio`

- Кратко: Операция с rate расшифрованное аудио.
- ID: `2132608815` / `0x7f1d072f`
- Return type: `Bool`
- Сигнатура: `messages.rateTranscribedAudio(peer:InputPeer, msg_id:int, transcription_id:long, good:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.rateTranscribedAudio
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `transcription_id`: `long`
  - `good`: `Bool`

### `messages.readDiscussion`

- Кратко: Пометить как прочитанное / прочитать обсуждение.
- ID: `-147740172` / `0xf731a9f4`
- Return type: `Bool`
- Сигнатура: `messages.readDiscussion(peer:InputPeer, msg_id:int, read_max_id:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.readDiscussion
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `read_max_id`: `int`

### `messages.readEncryptedHistory`

- Кратко: Пометить как прочитанное / прочитать encrypted историю.
- ID: `2135648522` / `0x7f4b690a`
- Return type: `Bool`
- Сигнатура: `messages.readEncryptedHistory(peer:InputEncryptedChat, max_date:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.readEncryptedHistory
- Параметры:
  - `peer`: `InputEncryptedChat`
  - `max_date`: `int`

### `messages.readFeaturedStickers`

- Кратко: Пометить как прочитанное / прочитать рекомендуемые стикеры.
- ID: `1527873830` / `0x5b118126`
- Return type: `Bool`
- Сигнатура: `messages.readFeaturedStickers(id:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.readFeaturedStickers
- Параметры:
  - `id`: `Vector`

### `messages.readHistory`

- Кратко: Пометить как прочитанное / прочитать историю.
- ID: `238054714` / `0x0e306d3a`
- Return type: `messages.AffectedMessages`
- Сигнатура: `messages.readHistory(peer:InputPeer, max_id:int) -> messages.AffectedMessages`
- Официальная страница: https://core.telegram.org/method/messages.readHistory
- Параметры:
  - `peer`: `InputPeer`
  - `max_id`: `int`

### `messages.readMentions`

- Кратко: Пометить как прочитанное / прочитать mentions.
- ID: `921026381` / `0x36e5bf4d`
- Return type: `messages.AffectedHistory`
- Сигнатура: `messages.readMentions(flags:#, peer:InputPeer, top_msg_id:flags.0?int) -> messages.AffectedHistory`
- Официальная страница: https://core.telegram.org/method/messages.readMentions
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `top_msg_id`: `flags.0?int` - optional через flags.0

### `messages.readMessageContents`

- Кратко: Пометить как прочитанное / прочитать сообщение contents.
- ID: `916930423` / `0x36a73f77`
- Return type: `messages.AffectedMessages`
- Сигнатура: `messages.readMessageContents(id:Vector) -> messages.AffectedMessages`
- Официальная страница: https://core.telegram.org/method/messages.readMessageContents
- Параметры:
  - `id`: `Vector`

### `messages.readReactions`

- Кратко: Пометить как прочитанное / прочитать реакции.
- ID: `-1631301741` / `0x9ec44f93`
- Return type: `messages.AffectedHistory`
- Сигнатура: `messages.readReactions(flags:#, peer:InputPeer, top_msg_id:flags.0?int, saved_peer_id:flags.1?InputPeer) -> messages.AffectedHistory`
- Официальная страница: https://core.telegram.org/method/messages.readReactions
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `top_msg_id`: `flags.0?int` - optional через flags.0
  - `saved_peer_id`: `flags.1?InputPeer` - optional через flags.1

### `messages.readSavedHistory`

- Кратко: Пометить как прочитанное / прочитать сохранённое историю.
- ID: `-1169540261` / `0xba4a3b5b`
- Return type: `Bool`
- Сигнатура: `messages.readSavedHistory(parent_peer:InputPeer, peer:InputPeer, max_id:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.readSavedHistory
- Параметры:
  - `parent_peer`: `InputPeer`
  - `peer`: `InputPeer`
  - `max_id`: `int`

### `messages.receivedMessages`

- Кратко: Операция с received сообщения.
- ID: `94983360` / `0x05a954c0`
- Return type: `Vector`
- Сигнатура: `messages.receivedMessages(max_id:int) -> Vector`
- Официальная страница: https://core.telegram.org/method/messages.receivedMessages
- Параметры:
  - `max_id`: `int`

### `messages.receivedQueue`

- Кратко: Операция с received queue.
- ID: `1436924774` / `0x55a5bb66`
- Return type: `Vector`
- Сигнатура: `messages.receivedQueue(max_qts:int) -> Vector`
- Официальная страница: https://core.telegram.org/method/messages.receivedQueue
- Параметры:
  - `max_qts`: `int`

### `messages.reorderPinnedDialogs`

- Кратко: Изменить порядок закреплённое диалоги.
- ID: `991616823` / `0x3b1adf37`
- Return type: `Bool`
- Сигнатура: `messages.reorderPinnedDialogs(flags:#, force:flags.0?true, folder_id:int, order:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.reorderPinnedDialogs
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `force`: `flags.0?true` - optional через flags.0
  - `folder_id`: `int`
  - `order`: `Vector`

### `messages.reorderPinnedSavedDialogs`

- Кратко: Изменить порядок закреплённое сохранённое диалоги.
- ID: `-1955502713` / `0x8b716587`
- Return type: `Bool`
- Сигнатура: `messages.reorderPinnedSavedDialogs(flags:#, force:flags.0?true, order:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.reorderPinnedSavedDialogs
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `force`: `flags.0?true` - optional через flags.0
  - `order`: `Vector`

### `messages.reorderQuickReplies`

- Кратко: Изменить порядок быстрый ответы.
- ID: `1613961479` / `0x60331907`
- Return type: `Bool`
- Сигнатура: `messages.reorderQuickReplies(order:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.reorderQuickReplies
- Параметры:
  - `order`: `Vector`

### `messages.reorderStickerSets`

- Кратко: Изменить порядок стикер sets.
- ID: `2016638777` / `0x78337739`
- Return type: `Bool`
- Сигнатура: `messages.reorderStickerSets(flags:#, masks:flags.0?true, emojis:flags.1?true, order:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.reorderStickerSets
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `masks`: `flags.0?true` - optional через flags.0
  - `emojis`: `flags.1?true` - optional через flags.1
  - `order`: `Vector`

### `messages.report`

- Кратко: Пожаловаться / сообщить о данными.
- ID: `-59199589` / `0xfc78af9b`
- Return type: `ReportResult`
- Сигнатура: `messages.report(peer:InputPeer, id:Vector, option:bytes, message:string) -> ReportResult`
- Официальная страница: https://core.telegram.org/method/messages.report
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`
  - `option`: `bytes`
  - `message`: `string`

### `messages.reportEncryptedSpam`

- Кратко: Пожаловаться / сообщить о encrypted спам.
- ID: `1259113487` / `0x4b0c8c0f`
- Return type: `Bool`
- Сигнатура: `messages.reportEncryptedSpam(peer:InputEncryptedChat) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.reportEncryptedSpam
- Параметры:
  - `peer`: `InputEncryptedChat`

### `messages.reportMessagesDelivery`

- Кратко: Пожаловаться / сообщить о сообщения delivery.
- ID: `1517122453` / `0x5a6d7395`
- Return type: `Bool`
- Сигнатура: `messages.reportMessagesDelivery(flags:#, push:flags.0?true, peer:InputPeer, id:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.reportMessagesDelivery
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `push`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`
  - `id`: `Vector`

### `messages.reportReaction`

- Кратко: Пожаловаться / сообщить о реакцию.
- ID: `1063567478` / `0x3f64c076`
- Return type: `Bool`
- Сигнатура: `messages.reportReaction(peer:InputPeer, id:int, reaction_peer:InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.reportReaction
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `int`
  - `reaction_peer`: `InputPeer`

### `messages.reportSpam`

- Кратко: Пожаловаться / сообщить о спам.
- ID: `-820669733` / `0xcf1592db`
- Return type: `Bool`
- Сигнатура: `messages.reportSpam(peer:InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.reportSpam
- Параметры:
  - `peer`: `InputPeer`

### `messages.reportSponsoredMessage`

- Кратко: Пожаловаться / сообщить о спонсируемые сообщение.
- ID: `315355332` / `0x12cbf0c4`
- Return type: `channels.SponsoredMessageReportResult`
- Сигнатура: `messages.reportSponsoredMessage(random_id:bytes, option:bytes) -> channels.SponsoredMessageReportResult`
- Официальная страница: https://core.telegram.org/method/messages.reportSponsoredMessage
- Параметры:
  - `random_id`: `bytes`
  - `option`: `bytes`

### `messages.requestAppWebView`

- Кратко: Запросить приложение веб view.
- ID: `1398901710` / `0x53618bce`
- Return type: `WebViewResult`
- Сигнатура: `messages.requestAppWebView(flags:#, write_allowed:flags.0?true, compact:flags.7?true, fullscreen:flags.8?true, peer:InputPeer, app:InputBotApp, start_param:flags.1?string, theme_params:flags.2?DataJSON, platform:string) -> WebViewResult`
- Официальная страница: https://core.telegram.org/method/messages.requestAppWebView
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `write_allowed`: `flags.0?true` - optional через flags.0
  - `compact`: `flags.7?true` - optional через flags.7
  - `fullscreen`: `flags.8?true` - optional через flags.8
  - `peer`: `InputPeer`
  - `app`: `InputBotApp`
  - `start_param`: `flags.1?string` - optional через flags.1
  - `theme_params`: `flags.2?DataJSON` - optional через flags.2
  - `platform`: `string`

### `messages.requestEncryption`

- Кратко: Запросить encryption.
- ID: `-162681021` / `0xf64daf43`
- Return type: `EncryptedChat`
- Сигнатура: `messages.requestEncryption(user_id:InputUser, random_id:int, g_a:bytes) -> EncryptedChat`
- Официальная страница: https://core.telegram.org/method/messages.requestEncryption
- Параметры:
  - `user_id`: `InputUser`
  - `random_id`: `int`
  - `g_a`: `bytes`

### `messages.requestMainWebView`

- Кратко: Запросить основное веб view.
- ID: `-908059013` / `0xc9e01e7b`
- Return type: `WebViewResult`
- Сигнатура: `messages.requestMainWebView(flags:#, compact:flags.7?true, fullscreen:flags.8?true, peer:InputPeer, bot:InputUser, start_param:flags.1?string, theme_params:flags.0?DataJSON, platform:string) -> WebViewResult`
- Официальная страница: https://core.telegram.org/method/messages.requestMainWebView
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `compact`: `flags.7?true` - optional через flags.7
  - `fullscreen`: `flags.8?true` - optional через flags.8
  - `peer`: `InputPeer`
  - `bot`: `InputUser`
  - `start_param`: `flags.1?string` - optional через flags.1
  - `theme_params`: `flags.0?DataJSON` - optional через flags.0
  - `platform`: `string`

### `messages.requestSimpleWebView`

- Кратко: Запросить simple веб view.
- ID: `1094336115` / `0x413a3e73`
- Return type: `WebViewResult`
- Сигнатура: `messages.requestSimpleWebView(flags:#, from_switch_webview:flags.1?true, from_side_menu:flags.2?true, compact:flags.7?true, fullscreen:flags.8?true, bot:InputUser, url:flags.3?string, start_param:flags.4?string, theme_params:flags.0?DataJSON, platform:string) -> WebViewResult`
- Официальная страница: https://core.telegram.org/method/messages.requestSimpleWebView
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `from_switch_webview`: `flags.1?true` - optional через flags.1
  - `from_side_menu`: `flags.2?true` - optional через flags.2
  - `compact`: `flags.7?true` - optional через flags.7
  - `fullscreen`: `flags.8?true` - optional через flags.8
  - `bot`: `InputUser`
  - `url`: `flags.3?string` - optional через flags.3
  - `start_param`: `flags.4?string` - optional через flags.4
  - `theme_params`: `flags.0?DataJSON` - optional через flags.0
  - `platform`: `string`

### `messages.requestUrlAuth`

- Кратко: Запросить URL авторизации.
- ID: `428848198` / `0x198fb446`
- Return type: `UrlAuthResult`
- Сигнатура: `messages.requestUrlAuth(flags:#, peer:flags.1?InputPeer, msg_id:flags.1?int, button_id:flags.1?int, url:flags.2?string) -> UrlAuthResult`
- Официальная страница: https://core.telegram.org/method/messages.requestUrlAuth
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `flags.1?InputPeer` - optional через flags.1
  - `msg_id`: `flags.1?int` - optional через flags.1
  - `button_id`: `flags.1?int` - optional через flags.1
  - `url`: `flags.2?string` - optional через flags.2

### `messages.requestWebView`

- Кратко: Запросить веб view.
- ID: `647873217` / `0x269dc2c1`
- Return type: `WebViewResult`
- Сигнатура: `messages.requestWebView(flags:#, from_bot_menu:flags.4?true, silent:flags.5?true, compact:flags.7?true, fullscreen:flags.8?true, peer:InputPeer, bot:InputUser, url:flags.1?string, start_param:flags.3?string, theme_params:flags.2?DataJSON, platform:string, reply_to:flags.0?InputReplyTo, send_as:flags.13?InputPeer) -> WebViewResult`
- Официальная страница: https://core.telegram.org/method/messages.requestWebView
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `from_bot_menu`: `flags.4?true` - optional через flags.4
  - `silent`: `flags.5?true` - optional через flags.5
  - `compact`: `flags.7?true` - optional через flags.7
  - `fullscreen`: `flags.8?true` - optional через flags.8
  - `peer`: `InputPeer`
  - `bot`: `InputUser`
  - `url`: `flags.1?string` - optional через flags.1
  - `start_param`: `flags.3?string` - optional через flags.3
  - `theme_params`: `flags.2?DataJSON` - optional через flags.2
  - `platform`: `string`
  - `reply_to`: `flags.0?InputReplyTo` - optional через flags.0
  - `send_as`: `flags.13?InputPeer` - optional через flags.13

### `messages.saveDefaultSendAs`

- Кратко: Сохранить default send as.
- ID: `-855777386` / `0xccfddf96`
- Return type: `Bool`
- Сигнатура: `messages.saveDefaultSendAs(peer:InputPeer, send_as:InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.saveDefaultSendAs
- Параметры:
  - `peer`: `InputPeer`
  - `send_as`: `InputPeer`

### `messages.saveDraft`

- Кратко: Сохранить черновик.
- ID: `1420701838` / `0x54ae308e`
- Return type: `Bool`
- Сигнатура: `messages.saveDraft(flags:#, no_webpage:flags.1?true, invert_media:flags.6?true, reply_to:flags.4?InputReplyTo, peer:InputPeer, message:string, entities:flags.3?Vector, media:flags.5?InputMedia, effect:flags.7?long, suggested_post:flags.8?SuggestedPost) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.saveDraft
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `no_webpage`: `flags.1?true` - optional через flags.1
  - `invert_media`: `flags.6?true` - optional через flags.6
  - `reply_to`: `flags.4?InputReplyTo` - optional через flags.4
  - `peer`: `InputPeer`
  - `message`: `string`
  - `entities`: `flags.3?Vector` - optional через flags.3
  - `media`: `flags.5?InputMedia` - optional через flags.5
  - `effect`: `flags.7?long` - optional через flags.7
  - `suggested_post`: `flags.8?SuggestedPost` - optional через flags.8

### `messages.saveGif`

- Кратко: Сохранить GIF.
- ID: `846868683` / `0x327a30cb`
- Return type: `Bool`
- Сигнатура: `messages.saveGif(id:InputDocument, unsave:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.saveGif
- Параметры:
  - `id`: `InputDocument`
  - `unsave`: `Bool`

### `messages.savePreparedInlineMessage`

- Кратко: Сохранить подготовленные inline сообщение.
- ID: `-232816849` / `0xf21f7f2f`
- Return type: `messages.BotPreparedInlineMessage`
- Сигнатура: `messages.savePreparedInlineMessage(flags:#, result:InputBotInlineResult, user_id:InputUser, peer_types:flags.0?Vector) -> messages.BotPreparedInlineMessage`
- Официальная страница: https://core.telegram.org/method/messages.savePreparedInlineMessage
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `result`: `InputBotInlineResult`
  - `user_id`: `InputUser`
  - `peer_types`: `flags.0?Vector` - optional через flags.0

### `messages.saveRecentSticker`

- Кратко: Сохранить недавние стикер.
- ID: `958863608` / `0x392718f8`
- Return type: `Bool`
- Сигнатура: `messages.saveRecentSticker(flags:#, attached:flags.0?true, id:InputDocument, unsave:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.saveRecentSticker
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `attached`: `flags.0?true` - optional через flags.0
  - `id`: `InputDocument`
  - `unsave`: `Bool`

### `messages.search`

- Кратко: Искать данными.
- ID: `703497338` / `0x29ee847a`
- Return type: `messages.Messages`
- Сигнатура: `messages.search(flags:#, peer:InputPeer, q:string, from_id:flags.0?InputPeer, saved_peer_id:flags.2?InputPeer, saved_reaction:flags.3?Vector, top_msg_id:flags.1?int, filter:MessagesFilter, min_date:int, max_date:int, offset_id:int, add_offset:int, limit:int, max_id:int, min_id:int, hash:long) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.search
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `q`: `string`
  - `from_id`: `flags.0?InputPeer` - optional через flags.0
  - `saved_peer_id`: `flags.2?InputPeer` - optional через flags.2
  - `saved_reaction`: `flags.3?Vector` - optional через flags.3
  - `top_msg_id`: `flags.1?int` - optional через flags.1
  - `filter`: `MessagesFilter`
  - `min_date`: `int`
  - `max_date`: `int`
  - `offset_id`: `int`
  - `add_offset`: `int`
  - `limit`: `int`
  - `max_id`: `int`
  - `min_id`: `int`
  - `hash`: `long`

### `messages.searchCustomEmoji`

- Кратко: Искать кастомные эмодзи.
- ID: `739360983` / `0x2c11c0d7`
- Return type: `EmojiList`
- Сигнатура: `messages.searchCustomEmoji(emoticon:string, hash:long) -> EmojiList`
- Официальная страница: https://core.telegram.org/method/messages.searchCustomEmoji
- Параметры:
  - `emoticon`: `string`
  - `hash`: `long`

### `messages.searchEmojiStickerSets`

- Кратко: Искать эмодзи стикер sets.
- ID: `-1833678516` / `0x92b4494c`
- Return type: `messages.FoundStickerSets`
- Сигнатура: `messages.searchEmojiStickerSets(flags:#, exclude_featured:flags.0?true, q:string, hash:long) -> messages.FoundStickerSets`
- Официальная страница: https://core.telegram.org/method/messages.searchEmojiStickerSets
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `exclude_featured`: `flags.0?true` - optional через flags.0
  - `q`: `string`
  - `hash`: `long`

### `messages.searchGlobal`

- Кратко: Искать глобальные.
- ID: `1271290010` / `0x4bc6589a`
- Return type: `messages.Messages`
- Сигнатура: `messages.searchGlobal(flags:#, broadcasts_only:flags.1?true, groups_only:flags.2?true, users_only:flags.3?true, folder_id:flags.0?int, q:string, filter:MessagesFilter, min_date:int, max_date:int, offset_rate:int, offset_peer:InputPeer, offset_id:int, limit:int) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.searchGlobal
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `broadcasts_only`: `flags.1?true` - optional через flags.1
  - `groups_only`: `flags.2?true` - optional через flags.2
  - `users_only`: `flags.3?true` - optional через flags.3
  - `folder_id`: `flags.0?int` - optional через flags.0
  - `q`: `string`
  - `filter`: `MessagesFilter`
  - `min_date`: `int`
  - `max_date`: `int`
  - `offset_rate`: `int`
  - `offset_peer`: `InputPeer`
  - `offset_id`: `int`
  - `limit`: `int`

### `messages.searchSentMedia`

- Кратко: Искать sent медиа.
- ID: `276705696` / `0x107e31a0`
- Return type: `messages.Messages`
- Сигнатура: `messages.searchSentMedia(q:string, filter:MessagesFilter, limit:int) -> messages.Messages`
- Официальная страница: https://core.telegram.org/method/messages.searchSentMedia
- Параметры:
  - `q`: `string`
  - `filter`: `MessagesFilter`
  - `limit`: `int`

### `messages.searchStickerSets`

- Кратко: Искать стикер sets.
- ID: `896555914` / `0x35705b8a`
- Return type: `messages.FoundStickerSets`
- Сигнатура: `messages.searchStickerSets(flags:#, exclude_featured:flags.0?true, q:string, hash:long) -> messages.FoundStickerSets`
- Официальная страница: https://core.telegram.org/method/messages.searchStickerSets
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `exclude_featured`: `flags.0?true` - optional через flags.0
  - `q`: `string`
  - `hash`: `long`

### `messages.searchStickers`

- Кратко: Искать стикеры.
- ID: `699516522` / `0x29b1c66a`
- Return type: `messages.FoundStickers`
- Сигнатура: `messages.searchStickers(flags:#, emojis:flags.0?true, q:string, emoticon:string, lang_code:Vector, offset:int, limit:int, hash:long) -> messages.FoundStickers`
- Официальная страница: https://core.telegram.org/method/messages.searchStickers
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `emojis`: `flags.0?true` - optional через flags.0
  - `q`: `string`
  - `emoticon`: `string`
  - `lang_code`: `Vector`
  - `offset`: `int`
  - `limit`: `int`
  - `hash`: `long`

### `messages.sendBotRequestedPeer`

- Кратко: Отправить бота requested peer/диалог.
- ID: `-1850552224` / `0x91b2d060`
- Return type: `Updates`
- Сигнатура: `messages.sendBotRequestedPeer(peer:InputPeer, msg_id:int, button_id:int, requested_peers:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.sendBotRequestedPeer
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `button_id`: `int`
  - `requested_peers`: `Vector`

### `messages.sendEncrypted`

- Кратко: Отправить encrypted.
- ID: `1157265941` / `0x44fa7a15`
- Return type: `messages.SentEncryptedMessage`
- Сигнатура: `messages.sendEncrypted(flags:#, silent:flags.0?true, peer:InputEncryptedChat, random_id:long, data:bytes) -> messages.SentEncryptedMessage`
- Официальная страница: https://core.telegram.org/method/messages.sendEncrypted
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `silent`: `flags.0?true` - optional через flags.0
  - `peer`: `InputEncryptedChat`
  - `random_id`: `long`
  - `data`: `bytes`

### `messages.sendEncryptedFile`

- Кратко: Отправить encrypted файл.
- ID: `1431914525` / `0x5559481d`
- Return type: `messages.SentEncryptedMessage`
- Сигнатура: `messages.sendEncryptedFile(flags:#, silent:flags.0?true, peer:InputEncryptedChat, random_id:long, data:bytes, file:InputEncryptedFile) -> messages.SentEncryptedMessage`
- Официальная страница: https://core.telegram.org/method/messages.sendEncryptedFile
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `silent`: `flags.0?true` - optional через flags.0
  - `peer`: `InputEncryptedChat`
  - `random_id`: `long`
  - `data`: `bytes`
  - `file`: `InputEncryptedFile`

### `messages.sendEncryptedService`

- Кратко: Отправить encrypted сервиса.
- ID: `852769188` / `0x32d439a4`
- Return type: `messages.SentEncryptedMessage`
- Сигнатура: `messages.sendEncryptedService(peer:InputEncryptedChat, random_id:long, data:bytes) -> messages.SentEncryptedMessage`
- Официальная страница: https://core.telegram.org/method/messages.sendEncryptedService
- Параметры:
  - `peer`: `InputEncryptedChat`
  - `random_id`: `long`
  - `data`: `bytes`

### `messages.sendInlineBotResult`

- Кратко: Отправить inline бота result.
- ID: `-1060145594` / `0xc0cf7646`
- Return type: `Updates`
- Сигнатура: `messages.sendInlineBotResult(flags:#, silent:flags.5?true, background:flags.6?true, clear_draft:flags.7?true, hide_via:flags.11?true, peer:InputPeer, reply_to:flags.0?InputReplyTo, random_id:long, query_id:long, id:string, schedule_date:flags.10?int, send_as:flags.13?InputPeer, quick_reply_shortcut:flags.17?InputQuickReplyShortcut, allow_paid_stars:flags.21?long) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.sendInlineBotResult
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `silent`: `flags.5?true` - optional через flags.5
  - `background`: `flags.6?true` - optional через flags.6
  - `clear_draft`: `flags.7?true` - optional через flags.7
  - `hide_via`: `flags.11?true` - optional через flags.11
  - `peer`: `InputPeer`
  - `reply_to`: `flags.0?InputReplyTo` - optional через flags.0
  - `random_id`: `long`
  - `query_id`: `long`
  - `id`: `string`
  - `schedule_date`: `flags.10?int` - optional через flags.10
  - `send_as`: `flags.13?InputPeer` - optional через flags.13
  - `quick_reply_shortcut`: `flags.17?InputQuickReplyShortcut` - optional через flags.17
  - `allow_paid_stars`: `flags.21?long` - optional через flags.21

### `messages.sendMedia`

- Кратко: Отправить медиа.
- ID: `-1403659839` / `0xac55d9c1`
- Return type: `Updates`
- Сигнатура: `messages.sendMedia(flags:#, silent:flags.5?true, background:flags.6?true, clear_draft:flags.7?true, noforwards:flags.14?true, update_stickersets_order:flags.15?true, invert_media:flags.16?true, allow_paid_floodskip:flags.19?true, peer:InputPeer, reply_to:flags.0?InputReplyTo, media:InputMedia, message:string, random_id:long, reply_markup:flags.2?ReplyMarkup, entities:flags.3?Vector, schedule_date:flags.10?int, send_as:flags.13?InputPeer, quick_reply_shortcut:flags.17?InputQuickReplyShortcut, effect:flags.18?long, allow_paid_stars:flags.21?long, suggested_post:flags.22?SuggestedPost) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.sendMedia
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `silent`: `flags.5?true` - optional через flags.5
  - `background`: `flags.6?true` - optional через flags.6
  - `clear_draft`: `flags.7?true` - optional через flags.7
  - `noforwards`: `flags.14?true` - optional через flags.14
  - `update_stickersets_order`: `flags.15?true` - optional через flags.15
  - `invert_media`: `flags.16?true` - optional через flags.16
  - `allow_paid_floodskip`: `flags.19?true` - optional через flags.19
  - `peer`: `InputPeer`
  - `reply_to`: `flags.0?InputReplyTo` - optional через flags.0
  - `media`: `InputMedia`
  - `message`: `string`
  - `random_id`: `long`
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2
  - `entities`: `flags.3?Vector` - optional через flags.3
  - `schedule_date`: `flags.10?int` - optional через flags.10
  - `send_as`: `flags.13?InputPeer` - optional через flags.13
  - `quick_reply_shortcut`: `flags.17?InputQuickReplyShortcut` - optional через flags.17
  - `effect`: `flags.18?long` - optional через flags.18
  - `allow_paid_stars`: `flags.21?long` - optional через flags.21
  - `suggested_post`: `flags.22?SuggestedPost` - optional через flags.22

### `messages.sendMessage`

- Кратко: Отправить сообщение.
- ID: `-33170278` / `0xfe05dc9a`
- Return type: `Updates`
- Сигнатура: `messages.sendMessage(flags:#, no_webpage:flags.1?true, silent:flags.5?true, background:flags.6?true, clear_draft:flags.7?true, noforwards:flags.14?true, update_stickersets_order:flags.15?true, invert_media:flags.16?true, allow_paid_floodskip:flags.19?true, peer:InputPeer, reply_to:flags.0?InputReplyTo, message:string, random_id:long, reply_markup:flags.2?ReplyMarkup, entities:flags.3?Vector, schedule_date:flags.10?int, send_as:flags.13?InputPeer, quick_reply_shortcut:flags.17?InputQuickReplyShortcut, effect:flags.18?long, allow_paid_stars:flags.21?long, suggested_post:flags.22?SuggestedPost) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.sendMessage
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `no_webpage`: `flags.1?true` - optional через flags.1
  - `silent`: `flags.5?true` - optional через flags.5
  - `background`: `flags.6?true` - optional через flags.6
  - `clear_draft`: `flags.7?true` - optional через flags.7
  - `noforwards`: `flags.14?true` - optional через flags.14
  - `update_stickersets_order`: `flags.15?true` - optional через flags.15
  - `invert_media`: `flags.16?true` - optional через flags.16
  - `allow_paid_floodskip`: `flags.19?true` - optional через flags.19
  - `peer`: `InputPeer`
  - `reply_to`: `flags.0?InputReplyTo` - optional через flags.0
  - `message`: `string`
  - `random_id`: `long`
  - `reply_markup`: `flags.2?ReplyMarkup` - optional через flags.2
  - `entities`: `flags.3?Vector` - optional через flags.3
  - `schedule_date`: `flags.10?int` - optional через flags.10
  - `send_as`: `flags.13?InputPeer` - optional через flags.13
  - `quick_reply_shortcut`: `flags.17?InputQuickReplyShortcut` - optional через flags.17
  - `effect`: `flags.18?long` - optional через flags.18
  - `allow_paid_stars`: `flags.21?long` - optional через flags.21
  - `suggested_post`: `flags.22?SuggestedPost` - optional через flags.22

### `messages.sendMultiMedia`

- Кратко: Отправить multi медиа.
- ID: `469278068` / `0x1bf89d74`
- Return type: `Updates`
- Сигнатура: `messages.sendMultiMedia(flags:#, silent:flags.5?true, background:flags.6?true, clear_draft:flags.7?true, noforwards:flags.14?true, update_stickersets_order:flags.15?true, invert_media:flags.16?true, allow_paid_floodskip:flags.19?true, peer:InputPeer, reply_to:flags.0?InputReplyTo, multi_media:Vector, schedule_date:flags.10?int, send_as:flags.13?InputPeer, quick_reply_shortcut:flags.17?InputQuickReplyShortcut, effect:flags.18?long, allow_paid_stars:flags.21?long) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.sendMultiMedia
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `silent`: `flags.5?true` - optional через flags.5
  - `background`: `flags.6?true` - optional через flags.6
  - `clear_draft`: `flags.7?true` - optional через flags.7
  - `noforwards`: `flags.14?true` - optional через flags.14
  - `update_stickersets_order`: `flags.15?true` - optional через flags.15
  - `invert_media`: `flags.16?true` - optional через flags.16
  - `allow_paid_floodskip`: `flags.19?true` - optional через flags.19
  - `peer`: `InputPeer`
  - `reply_to`: `flags.0?InputReplyTo` - optional через flags.0
  - `multi_media`: `Vector`
  - `schedule_date`: `flags.10?int` - optional через flags.10
  - `send_as`: `flags.13?InputPeer` - optional через flags.13
  - `quick_reply_shortcut`: `flags.17?InputQuickReplyShortcut` - optional через flags.17
  - `effect`: `flags.18?long` - optional через flags.18
  - `allow_paid_stars`: `flags.21?long` - optional через flags.21

### `messages.sendPaidReaction`

- Кратко: Отправить платные реакцию.
- ID: `1488702288` / `0x58bbcb50`
- Return type: `Updates`
- Сигнатура: `messages.sendPaidReaction(flags:#, peer:InputPeer, msg_id:int, count:int, random_id:long, private:flags.0?PaidReactionPrivacy) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.sendPaidReaction
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `count`: `int`
  - `random_id`: `long`
  - `private`: `flags.0?PaidReactionPrivacy` - optional через flags.0

### `messages.sendQuickReplyMessages`

- Кратко: Отправить быстрый ответ сообщения.
- ID: `1819610593` / `0x6c750de1`
- Return type: `Updates`
- Сигнатура: `messages.sendQuickReplyMessages(peer:InputPeer, shortcut_id:int, id:Vector, random_id:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.sendQuickReplyMessages
- Параметры:
  - `peer`: `InputPeer`
  - `shortcut_id`: `int`
  - `id`: `Vector`
  - `random_id`: `Vector`

### `messages.sendReaction`

- Кратко: Отправить реакцию.
- ID: `-754091820` / `0xd30d78d4`
- Return type: `Updates`
- Сигнатура: `messages.sendReaction(flags:#, big:flags.1?true, add_to_recent:flags.2?true, peer:InputPeer, msg_id:int, reaction:flags.0?Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.sendReaction
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `big`: `flags.1?true` - optional через flags.1
  - `add_to_recent`: `flags.2?true` - optional через flags.2
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `reaction`: `flags.0?Vector` - optional через flags.0

### `messages.sendScheduledMessages`

- Кратко: Отправить запланированные сообщения.
- ID: `-1120369398` / `0xbd38850a`
- Return type: `Updates`
- Сигнатура: `messages.sendScheduledMessages(peer:InputPeer, id:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.sendScheduledMessages
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`

### `messages.sendScreenshotNotification`

- Кратко: Отправить screenshot notification.
- ID: `-1589618665` / `0xa1405817`
- Return type: `Updates`
- Сигнатура: `messages.sendScreenshotNotification(peer:InputPeer, reply_to:InputReplyTo, random_id:long) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.sendScreenshotNotification
- Параметры:
  - `peer`: `InputPeer`
  - `reply_to`: `InputReplyTo`
  - `random_id`: `long`

### `messages.sendVote`

- Кратко: Отправить vote.
- ID: `283795844` / `0x10ea6184`
- Return type: `Updates`
- Сигнатура: `messages.sendVote(peer:InputPeer, msg_id:int, options:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.sendVote
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `options`: `Vector`

### `messages.sendWebViewData`

- Кратко: Отправить веб view данные.
- ID: `-603831608` / `0xdc0242c8`
- Return type: `Updates`
- Сигнатура: `messages.sendWebViewData(bot:InputUser, random_id:long, button_text:string, data:string) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.sendWebViewData
- Параметры:
  - `bot`: `InputUser`
  - `random_id`: `long`
  - `button_text`: `string`
  - `data`: `string`

### `messages.sendWebViewResultMessage`

- Кратко: Отправить веб view result сообщение.
- ID: `172168437` / `0x0a4314f5`
- Return type: `WebViewMessageSent`
- Сигнатура: `messages.sendWebViewResultMessage(bot_query_id:string, result:InputBotInlineResult) -> WebViewMessageSent`
- Официальная страница: https://core.telegram.org/method/messages.sendWebViewResultMessage
- Параметры:
  - `bot_query_id`: `string`
  - `result`: `InputBotInlineResult`

### `messages.setBotCallbackAnswer`

- Кратко: Установить бота callback answer.
- ID: `-712043766` / `0xd58f130a`
- Return type: `Bool`
- Сигнатура: `messages.setBotCallbackAnswer(flags:#, alert:flags.1?true, query_id:long, message:flags.0?string, url:flags.2?string, cache_time:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.setBotCallbackAnswer
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `alert`: `flags.1?true` - optional через flags.1
  - `query_id`: `long`
  - `message`: `flags.0?string` - optional через flags.0
  - `url`: `flags.2?string` - optional через flags.2
  - `cache_time`: `int`

### `messages.setBotPrecheckoutResults`

- Кратко: Установить бота precheckout results.
- ID: `163765653` / `0x09c2dd95`
- Return type: `Bool`
- Сигнатура: `messages.setBotPrecheckoutResults(flags:#, success:flags.1?true, query_id:long, error:flags.0?string) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.setBotPrecheckoutResults
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `success`: `flags.1?true` - optional через flags.1
  - `query_id`: `long`
  - `error`: `flags.0?string` - optional через flags.0

### `messages.setBotShippingResults`

- Кратко: Установить бота shipping results.
- ID: `-436833542` / `0xe5f672fa`
- Return type: `Bool`
- Сигнатура: `messages.setBotShippingResults(flags:#, query_id:long, error:flags.0?string, shipping_options:flags.1?Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.setBotShippingResults
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `query_id`: `long`
  - `error`: `flags.0?string` - optional через flags.0
  - `shipping_options`: `flags.1?Vector` - optional через flags.1

### `messages.setChatAvailableReactions`

- Кратко: Установить чат available реакции.
- ID: `-2041895551` / `0x864b2581`
- Return type: `Updates`
- Сигнатура: `messages.setChatAvailableReactions(flags:#, peer:InputPeer, available_reactions:ChatReactions, reactions_limit:flags.0?int, paid_enabled:flags.1?Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.setChatAvailableReactions
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `available_reactions`: `ChatReactions`
  - `reactions_limit`: `flags.0?int` - optional через flags.0
  - `paid_enabled`: `flags.1?Bool` - optional через flags.1

### `messages.setChatTheme`

- Кратко: Установить чат тему.
- ID: `135398089` / `0x081202c9`
- Return type: `Updates`
- Сигнатура: `messages.setChatTheme(peer:InputPeer, theme:InputChatTheme) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.setChatTheme
- Параметры:
  - `peer`: `InputPeer`
  - `theme`: `InputChatTheme`

### `messages.setChatWallPaper`

- Кратко: Установить чат wall paper.
- ID: `-1879389471` / `0x8ffacae1`
- Return type: `Updates`
- Сигнатура: `messages.setChatWallPaper(flags:#, for_both:flags.3?true, revert:flags.4?true, peer:InputPeer, wallpaper:flags.0?InputWallPaper, settings:flags.2?WallPaperSettings, id:flags.1?int) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.setChatWallPaper
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `for_both`: `flags.3?true` - optional через flags.3
  - `revert`: `flags.4?true` - optional через flags.4
  - `peer`: `InputPeer`
  - `wallpaper`: `flags.0?InputWallPaper` - optional через flags.0
  - `settings`: `flags.2?WallPaperSettings` - optional через flags.2
  - `id`: `flags.1?int` - optional через flags.1

### `messages.setDefaultHistoryTTL`

- Кратко: Установить default историю TTL/срок жизни.
- ID: `-1632299963` / `0x9eb51445`
- Return type: `Bool`
- Сигнатура: `messages.setDefaultHistoryTTL(period:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.setDefaultHistoryTTL
- Параметры:
  - `period`: `int`

### `messages.setDefaultReaction`

- Кратко: Установить default реакцию.
- ID: `1330094102` / `0x4f47a016`
- Return type: `Bool`
- Сигнатура: `messages.setDefaultReaction(reaction:Reaction) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.setDefaultReaction
- Параметры:
  - `reaction`: `Reaction`

### `messages.setEncryptedTyping`

- Кратко: Установить encrypted статус набора.
- ID: `2031374829` / `0x791451ed`
- Return type: `Bool`
- Сигнатура: `messages.setEncryptedTyping(peer:InputEncryptedChat, typing:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.setEncryptedTyping
- Параметры:
  - `peer`: `InputEncryptedChat`
  - `typing`: `Bool`

### `messages.setGameScore`

- Кратко: Установить game score.
- ID: `-1896289088` / `0x8ef8ecc0`
- Return type: `Updates`
- Сигнатура: `messages.setGameScore(flags:#, edit_message:flags.0?true, force:flags.1?true, peer:InputPeer, id:int, user_id:InputUser, score:int) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.setGameScore
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `edit_message`: `flags.0?true` - optional через flags.0
  - `force`: `flags.1?true` - optional через flags.1
  - `peer`: `InputPeer`
  - `id`: `int`
  - `user_id`: `InputUser`
  - `score`: `int`

### `messages.setHistoryTTL`

- Кратко: Установить историю TTL/срок жизни.
- ID: `-1207017500` / `0xb80e5fe4`
- Return type: `Updates`
- Сигнатура: `messages.setHistoryTTL(peer:InputPeer, period:int) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.setHistoryTTL
- Параметры:
  - `peer`: `InputPeer`
  - `period`: `int`

### `messages.setInlineBotResults`

- Кратко: Установить inline бота results.
- ID: `-1156406247` / `0xbb12a419`
- Return type: `Bool`
- Сигнатура: `messages.setInlineBotResults(flags:#, gallery:flags.0?true, private:flags.1?true, query_id:long, results:Vector, cache_time:int, next_offset:flags.2?string, switch_pm:flags.3?InlineBotSwitchPM, switch_webview:flags.4?InlineBotWebView) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.setInlineBotResults
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `gallery`: `flags.0?true` - optional через flags.0
  - `private`: `flags.1?true` - optional через flags.1
  - `query_id`: `long`
  - `results`: `Vector`
  - `cache_time`: `int`
  - `next_offset`: `flags.2?string` - optional через flags.2
  - `switch_pm`: `flags.3?InlineBotSwitchPM` - optional через flags.3
  - `switch_webview`: `flags.4?InlineBotWebView` - optional через flags.4

### `messages.setInlineGameScore`

- Кратко: Установить inline game score.
- ID: `363700068` / `0x15ad9f64`
- Return type: `Bool`
- Сигнатура: `messages.setInlineGameScore(flags:#, edit_message:flags.0?true, force:flags.1?true, id:InputBotInlineMessageID, user_id:InputUser, score:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.setInlineGameScore
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `edit_message`: `flags.0?true` - optional через flags.0
  - `force`: `flags.1?true` - optional через flags.1
  - `id`: `InputBotInlineMessageID`
  - `user_id`: `InputUser`
  - `score`: `int`

### `messages.setTyping`

- Кратко: Установить статус набора.
- ID: `1486110434` / `0x58943ee2`
- Return type: `Bool`
- Сигнатура: `messages.setTyping(flags:#, peer:InputPeer, top_msg_id:flags.0?int, action:SendMessageAction) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.setTyping
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `top_msg_id`: `flags.0?int` - optional через flags.0
  - `action`: `SendMessageAction`

### `messages.startBot`

- Кратко: Операция с запуск бота.
- ID: `-421563528` / `0xe6df7378`
- Return type: `Updates`
- Сигнатура: `messages.startBot(bot:InputUser, peer:InputPeer, random_id:long, start_param:string) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.startBot
- Параметры:
  - `bot`: `InputUser`
  - `peer`: `InputPeer`
  - `random_id`: `long`
  - `start_param`: `string`

### `messages.startHistoryImport`

- Кратко: Операция с запуск историю import.
- ID: `-1271008444` / `0xb43df344`
- Return type: `Bool`
- Сигнатура: `messages.startHistoryImport(peer:InputPeer, import_id:long) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.startHistoryImport
- Параметры:
  - `peer`: `InputPeer`
  - `import_id`: `long`

### `messages.toggleBotInAttachMenu`

- Кратко: Включить/выключить бота in прикрепление меню.
- ID: `1777704297` / `0x69f59d69`
- Return type: `Bool`
- Сигнатура: `messages.toggleBotInAttachMenu(flags:#, write_allowed:flags.0?true, bot:InputUser, enabled:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.toggleBotInAttachMenu
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `write_allowed`: `flags.0?true` - optional через flags.0
  - `bot`: `InputUser`
  - `enabled`: `Bool`

### `messages.toggleDialogFilterTags`

- Кратко: Включить/выключить диалог filter tags.
- ID: `-47326647` / `0xfd2dda49`
- Return type: `Bool`
- Сигнатура: `messages.toggleDialogFilterTags(enabled:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.toggleDialogFilterTags
- Параметры:
  - `enabled`: `Bool`

### `messages.toggleDialogPin`

- Кратко: Включить/выключить диалог pin.
- ID: `-1489903017` / `0xa731e257`
- Return type: `Bool`
- Сигнатура: `messages.toggleDialogPin(flags:#, pinned:flags.0?true, peer:InputDialogPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.toggleDialogPin
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `pinned`: `flags.0?true` - optional через flags.0
  - `peer`: `InputDialogPeer`

### `messages.toggleNoForwards`

- Кратко: Включить/выключить no forwards.
- ID: `-1323389022` / `0xb11eafa2`
- Return type: `Updates`
- Сигнатура: `messages.toggleNoForwards(peer:InputPeer, enabled:Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.toggleNoForwards
- Параметры:
  - `peer`: `InputPeer`
  - `enabled`: `Bool`

### `messages.togglePaidReactionPrivacy`

- Кратко: Включить/выключить платные реакцию приватность.
- ID: `1129874869` / `0x435885b5`
- Return type: `Bool`
- Сигнатура: `messages.togglePaidReactionPrivacy(peer:InputPeer, msg_id:int, private:PaidReactionPrivacy) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.togglePaidReactionPrivacy
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `private`: `PaidReactionPrivacy`

### `messages.togglePeerTranslations`

- Кратко: Включить/выключить peer/диалог переводы.
- ID: `-461589127` / `0xe47cb579`
- Return type: `Bool`
- Сигнатура: `messages.togglePeerTranslations(flags:#, disabled:flags.0?true, peer:InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.togglePeerTranslations
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `disabled`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`

### `messages.toggleSavedDialogPin`

- Кратко: Включить/выключить сохранённое диалог pin.
- ID: `-1400783906` / `0xac81bbde`
- Return type: `Bool`
- Сигнатура: `messages.toggleSavedDialogPin(flags:#, pinned:flags.0?true, peer:InputDialogPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.toggleSavedDialogPin
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `pinned`: `flags.0?true` - optional через flags.0
  - `peer`: `InputDialogPeer`

### `messages.toggleStickerSets`

- Кратко: Включить/выключить стикер sets.
- ID: `-1257951254` / `0xb5052fea`
- Return type: `Bool`
- Сигнатура: `messages.toggleStickerSets(flags:#, uninstall:flags.0?true, archive:flags.1?true, unarchive:flags.2?true, stickersets:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.toggleStickerSets
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `uninstall`: `flags.0?true` - optional через flags.0
  - `archive`: `flags.1?true` - optional через flags.1
  - `unarchive`: `flags.2?true` - optional через flags.2
  - `stickersets`: `Vector`

### `messages.toggleSuggestedPostApproval`

- Кратко: Включить/выключить предложенные post approval.
- ID: `-2130229924` / `0x8107455c`
- Return type: `Updates`
- Сигнатура: `messages.toggleSuggestedPostApproval(flags:#, reject:flags.1?true, peer:InputPeer, msg_id:int, schedule_date:flags.0?int, reject_comment:flags.2?string) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.toggleSuggestedPostApproval
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `reject`: `flags.1?true` - optional через flags.1
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `schedule_date`: `flags.0?int` - optional через flags.0
  - `reject_comment`: `flags.2?string` - optional через flags.2

### `messages.toggleTodoCompleted`

- Кратко: Включить/выключить todo completed.
- ID: `-740282076` / `0xd3e03124`
- Return type: `Updates`
- Сигнатура: `messages.toggleTodoCompleted(peer:InputPeer, msg_id:int, completed:Vector, incompleted:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.toggleTodoCompleted
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`
  - `completed`: `Vector`
  - `incompleted`: `Vector`

### `messages.transcribeAudio`

- Кратко: Операция с transcribe аудио.
- ID: `647928393` / `0x269e9a49`
- Return type: `messages.TranscribedAudio`
- Сигнатура: `messages.transcribeAudio(peer:InputPeer, msg_id:int) -> messages.TranscribedAudio`
- Официальная страница: https://core.telegram.org/method/messages.transcribeAudio
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`

### `messages.translateText`

- Кратко: Операция с translate текст.
- ID: `1662529584` / `0x63183030`
- Return type: `messages.TranslatedText`
- Сигнатура: `messages.translateText(flags:#, peer:flags.0?InputPeer, id:flags.0?Vector, text:flags.1?Vector, to_lang:string) -> messages.TranslatedText`
- Официальная страница: https://core.telegram.org/method/messages.translateText
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `flags.0?InputPeer` - optional через flags.0
  - `id`: `flags.0?Vector` - optional через flags.0
  - `text`: `flags.1?Vector` - optional через flags.1
  - `to_lang`: `string`

### `messages.uninstallStickerSet`

- Кратко: Удалить стикер set.
- ID: `-110209570` / `0xf96e55de`
- Return type: `Bool`
- Сигнатура: `messages.uninstallStickerSet(stickerset:InputStickerSet) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.uninstallStickerSet
- Параметры:
  - `stickerset`: `InputStickerSet`

### `messages.unpinAllMessages`

- Кратко: Операция с unpin all сообщения.
- ID: `103667527` / `0x062dd747`
- Return type: `messages.AffectedHistory`
- Сигнатура: `messages.unpinAllMessages(flags:#, peer:InputPeer, top_msg_id:flags.0?int, saved_peer_id:flags.1?InputPeer) -> messages.AffectedHistory`
- Официальная страница: https://core.telegram.org/method/messages.unpinAllMessages
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `top_msg_id`: `flags.0?int` - optional через flags.0
  - `saved_peer_id`: `flags.1?InputPeer` - optional через flags.1

### `messages.updateDialogFilter`

- Кратко: Обновить диалог filter.
- ID: `450142282` / `0x1ad4a04a`
- Return type: `Bool`
- Сигнатура: `messages.updateDialogFilter(flags:#, id:int, filter:flags.0?DialogFilter) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.updateDialogFilter
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `id`: `int`
  - `filter`: `flags.0?DialogFilter` - optional через flags.0

### `messages.updateDialogFiltersOrder`

- Кратко: Обновить диалог filters order.
- ID: `-983318044` / `0xc563c1e4`
- Return type: `Bool`
- Сигнатура: `messages.updateDialogFiltersOrder(order:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.updateDialogFiltersOrder
- Параметры:
  - `order`: `Vector`

### `messages.updatePinnedMessage`

- Кратко: Обновить закреплённое сообщение.
- ID: `-760547348` / `0xd2aaf7ec`
- Return type: `Updates`
- Сигнатура: `messages.updatePinnedMessage(flags:#, silent:flags.0?true, unpin:flags.1?true, pm_oneside:flags.2?true, peer:InputPeer, id:int) -> Updates`
- Официальная страница: https://core.telegram.org/method/messages.updatePinnedMessage
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `silent`: `flags.0?true` - optional через flags.0
  - `unpin`: `flags.1?true` - optional через flags.1
  - `pm_oneside`: `flags.2?true` - optional через flags.2
  - `peer`: `InputPeer`
  - `id`: `int`

### `messages.updateSavedReactionTag`

- Кратко: Обновить сохранённое реакцию tag.
- ID: `1613331948` / `0x60297dec`
- Return type: `Bool`
- Сигнатура: `messages.updateSavedReactionTag(flags:#, reaction:Reaction, title:flags.0?string) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.updateSavedReactionTag
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `reaction`: `Reaction`
  - `title`: `flags.0?string` - optional через flags.0

### `messages.uploadEncryptedFile`

- Кратко: Загрузить encrypted файл.
- ID: `1347929239` / `0x5057c497`
- Return type: `EncryptedFile`
- Сигнатура: `messages.uploadEncryptedFile(peer:InputEncryptedChat, file:InputEncryptedFile) -> EncryptedFile`
- Официальная страница: https://core.telegram.org/method/messages.uploadEncryptedFile
- Параметры:
  - `peer`: `InputEncryptedChat`
  - `file`: `InputEncryptedFile`

### `messages.uploadImportedMedia`

- Кратко: Загрузить импортированные медиа.
- ID: `713433234` / `0x2a862092`
- Return type: `MessageMedia`
- Сигнатура: `messages.uploadImportedMedia(peer:InputPeer, import_id:long, file_name:string, media:InputMedia) -> MessageMedia`
- Официальная страница: https://core.telegram.org/method/messages.uploadImportedMedia
- Параметры:
  - `peer`: `InputPeer`
  - `import_id`: `long`
  - `file_name`: `string`
  - `media`: `InputMedia`

### `messages.uploadMedia`

- Кратко: Загрузить медиа.
- ID: `345405816` / `0x14967978`
- Return type: `MessageMedia`
- Сигнатура: `messages.uploadMedia(flags:#, business_connection_id:flags.0?string, peer:InputPeer, media:InputMedia) -> MessageMedia`
- Официальная страница: https://core.telegram.org/method/messages.uploadMedia
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `business_connection_id`: `flags.0?string` - optional через flags.0
  - `peer`: `InputPeer`
  - `media`: `InputMedia`

### `messages.viewSponsoredMessage`

- Кратко: Операция с view спонсируемые сообщение.
- ID: `647902787` / `0x269e3643`
- Return type: `Bool`
- Сигнатура: `messages.viewSponsoredMessage(random_id:bytes) -> Bool`
- Официальная страница: https://core.telegram.org/method/messages.viewSponsoredMessage
- Параметры:
  - `random_id`: `bytes`

## payments

### `payments.applyGiftCode`

- Кратко: Применить подарок код.
- ID: `-152934316` / `0xf6e26854`
- Return type: `Updates`
- Сигнатура: `payments.applyGiftCode(slug:string) -> Updates`
- Официальная страница: https://core.telegram.org/method/payments.applyGiftCode
- Параметры:
  - `slug`: `string`

### `payments.assignAppStoreTransaction`

- Кратко: Привязать / сообщить о приложение store transaction.
- ID: `-2131921795` / `0x80ed747d`
- Return type: `Updates`
- Сигнатура: `payments.assignAppStoreTransaction(receipt:bytes, purpose:InputStorePaymentPurpose) -> Updates`
- Официальная страница: https://core.telegram.org/method/payments.assignAppStoreTransaction
- Параметры:
  - `receipt`: `bytes`
  - `purpose`: `InputStorePaymentPurpose`

### `payments.assignPlayMarketTransaction`

- Кратко: Привязать / сообщить о play market transaction.
- ID: `-537046829` / `0xdffd50d3`
- Return type: `Updates`
- Сигнатура: `payments.assignPlayMarketTransaction(receipt:DataJSON, purpose:InputStorePaymentPurpose) -> Updates`
- Официальная страница: https://core.telegram.org/method/payments.assignPlayMarketTransaction
- Параметры:
  - `receipt`: `DataJSON`
  - `purpose`: `InputStorePaymentPurpose`

### `payments.botCancelStarsSubscription`

- Кратко: Операция с бота cancel Stars подписку.
- ID: `1845102114` / `0x6dfa0622`
- Return type: `Bool`
- Сигнатура: `payments.botCancelStarsSubscription(flags:#, restore:flags.0?true, user_id:InputUser, charge_id:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/payments.botCancelStarsSubscription
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `restore`: `flags.0?true` - optional через flags.0
  - `user_id`: `InputUser`
  - `charge_id`: `string`

### `payments.canPurchaseStore`

- Кратко: Проверить возможность покупки store.
- ID: `1339842215` / `0x4fdc5ea7`
- Return type: `Bool`
- Сигнатура: `payments.canPurchaseStore(purpose:InputStorePaymentPurpose) -> Bool`
- Официальная страница: https://core.telegram.org/method/payments.canPurchaseStore
- Параметры:
  - `purpose`: `InputStorePaymentPurpose`

### `payments.changeStarsSubscription`

- Кратко: Операция с change Stars подписку.
- ID: `-948500360` / `0xc7770878`
- Return type: `Bool`
- Сигнатура: `payments.changeStarsSubscription(flags:#, peer:InputPeer, subscription_id:string, canceled:flags.0?Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/payments.changeStarsSubscription
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `subscription_id`: `string`
  - `canceled`: `flags.0?Bool` - optional через flags.0

### `payments.checkCanSendGift`

- Кратко: Проверить can send подарок.
- ID: `-1060835895` / `0xc0c4edc9`
- Return type: `payments.CheckCanSendGiftResult`
- Сигнатура: `payments.checkCanSendGift(gift_id:long) -> payments.CheckCanSendGiftResult`
- Официальная страница: https://core.telegram.org/method/payments.checkCanSendGift
- Параметры:
  - `gift_id`: `long`

### `payments.checkGiftCode`

- Кратко: Проверить подарок код.
- ID: `-1907247935` / `0x8e51b4c1`
- Return type: `payments.CheckedGiftCode`
- Сигнатура: `payments.checkGiftCode(slug:string) -> payments.CheckedGiftCode`
- Официальная страница: https://core.telegram.org/method/payments.checkGiftCode
- Параметры:
  - `slug`: `string`

### `payments.clearSavedInfo`

- Кратко: Операция с clear сохранённое информацию.
- ID: `-667062079` / `0xd83d70c1`
- Return type: `Bool`
- Сигнатура: `payments.clearSavedInfo(flags:#, credentials:flags.0?true, info:flags.1?true) -> Bool`
- Официальная страница: https://core.telegram.org/method/payments.clearSavedInfo
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `credentials`: `flags.0?true` - optional через flags.0
  - `info`: `flags.1?true` - optional через flags.1

### `payments.connectStarRefBot`

- Кратко: Операция с connect звезду/Stars ref бота.
- ID: `2127901834` / `0x7ed5348a`
- Return type: `payments.ConnectedStarRefBots`
- Сигнатура: `payments.connectStarRefBot(peer:InputPeer, bot:InputUser) -> payments.ConnectedStarRefBots`
- Официальная страница: https://core.telegram.org/method/payments.connectStarRefBot
- Параметры:
  - `peer`: `InputPeer`
  - `bot`: `InputUser`

### `payments.convertStarGift`

- Кратко: Конвертировать звезду/Stars подарок.
- ID: `1958676331` / `0x74bf076b`
- Return type: `Bool`
- Сигнатура: `payments.convertStarGift(stargift:InputSavedStarGift) -> Bool`
- Официальная страница: https://core.telegram.org/method/payments.convertStarGift
- Параметры:
  - `stargift`: `InputSavedStarGift`

### `payments.createStarGiftCollection`

- Кратко: Создать звезду/Stars подарок collection.
- ID: `524947079` / `0x1f4a0e87`
- Return type: `StarGiftCollection`
- Сигнатура: `payments.createStarGiftCollection(peer:InputPeer, title:string, stargift:Vector) -> StarGiftCollection`
- Официальная страница: https://core.telegram.org/method/payments.createStarGiftCollection
- Параметры:
  - `peer`: `InputPeer`
  - `title`: `string`
  - `stargift`: `Vector`

### `payments.deleteStarGiftCollection`

- Кратко: Удалить звезду/Stars подарок collection.
- ID: `-1386854168` / `0xad5648e8`
- Return type: `Bool`
- Сигнатура: `payments.deleteStarGiftCollection(peer:InputPeer, collection_id:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/payments.deleteStarGiftCollection
- Параметры:
  - `peer`: `InputPeer`
  - `collection_id`: `int`

### `payments.editConnectedStarRefBot`

- Кратко: Изменить подключённого звезду/Stars ref бота.
- ID: `-453204829` / `0xe4fca4a3`
- Return type: `payments.ConnectedStarRefBots`
- Сигнатура: `payments.editConnectedStarRefBot(flags:#, revoked:flags.0?true, peer:InputPeer, link:string) -> payments.ConnectedStarRefBots`
- Официальная страница: https://core.telegram.org/method/payments.editConnectedStarRefBot
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `revoked`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`
  - `link`: `string`

### `payments.exportInvoice`

- Кратко: Экспортировать инвойс.
- ID: `261206117` / `0x0f91b065`
- Return type: `payments.ExportedInvoice`
- Сигнатура: `payments.exportInvoice(invoice_media:InputMedia) -> payments.ExportedInvoice`
- Официальная страница: https://core.telegram.org/method/payments.exportInvoice
- Параметры:
  - `invoice_media`: `InputMedia`

### `payments.fulfillStarsSubscription`

- Кратко: Операция с fulfill Stars подписку.
- ID: `-866391117` / `0xcc5bebb3`
- Return type: `Bool`
- Сигнатура: `payments.fulfillStarsSubscription(peer:InputPeer, subscription_id:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/payments.fulfillStarsSubscription
- Параметры:
  - `peer`: `InputPeer`
  - `subscription_id`: `string`

### `payments.getBankCardData`

- Кратко: Получить bank card данные.
- ID: `779736953` / `0x2e79d779`
- Return type: `payments.BankCardData`
- Сигнатура: `payments.getBankCardData(number:string) -> payments.BankCardData`
- Официальная страница: https://core.telegram.org/method/payments.getBankCardData
- Параметры:
  - `number`: `string`

### `payments.getConnectedStarRefBot`

- Кратко: Получить подключённого звезду/Stars ref бота.
- ID: `-1210476304` / `0xb7d998f0`
- Return type: `payments.ConnectedStarRefBots`
- Сигнатура: `payments.getConnectedStarRefBot(peer:InputPeer, bot:InputUser) -> payments.ConnectedStarRefBots`
- Официальная страница: https://core.telegram.org/method/payments.getConnectedStarRefBot
- Параметры:
  - `peer`: `InputPeer`
  - `bot`: `InputUser`

### `payments.getConnectedStarRefBots`

- Кратко: Получить подключённого звезду/Stars ref ботов.
- ID: `1483318611` / `0x5869a553`
- Return type: `payments.ConnectedStarRefBots`
- Сигнатура: `payments.getConnectedStarRefBots(flags:#, peer:InputPeer, offset_date:flags.2?int, offset_link:flags.2?string, limit:int) -> payments.ConnectedStarRefBots`
- Официальная страница: https://core.telegram.org/method/payments.getConnectedStarRefBots
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `offset_date`: `flags.2?int` - optional через flags.2
  - `offset_link`: `flags.2?string` - optional через flags.2
  - `limit`: `int`

### `payments.getGiveawayInfo`

- Кратко: Получить розыгрыш информацию.
- ID: `-198994907` / `0xf4239425`
- Return type: `payments.GiveawayInfo`
- Сигнатура: `payments.getGiveawayInfo(peer:InputPeer, msg_id:int) -> payments.GiveawayInfo`
- Официальная страница: https://core.telegram.org/method/payments.getGiveawayInfo
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`

### `payments.getPaymentForm`

- Кратко: Получить платёж form.
- ID: `924093883` / `0x37148dbb`
- Return type: `payments.PaymentForm`
- Сигнатура: `payments.getPaymentForm(flags:#, invoice:InputInvoice, theme_params:flags.0?DataJSON) -> payments.PaymentForm`
- Официальная страница: https://core.telegram.org/method/payments.getPaymentForm
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `invoice`: `InputInvoice`
  - `theme_params`: `flags.0?DataJSON` - optional через flags.0

### `payments.getPaymentReceipt`

- Кратко: Получить платёж квитанцию.
- ID: `611897804` / `0x2478d1cc`
- Return type: `payments.PaymentReceipt`
- Сигнатура: `payments.getPaymentReceipt(peer:InputPeer, msg_id:int) -> payments.PaymentReceipt`
- Официальная страница: https://core.telegram.org/method/payments.getPaymentReceipt
- Параметры:
  - `peer`: `InputPeer`
  - `msg_id`: `int`

### `payments.getPremiumGiftCodeOptions`

- Кратко: Получить Premium подарок код options.
- ID: `660060756` / `0x2757ba54`
- Return type: `Vector`
- Сигнатура: `payments.getPremiumGiftCodeOptions(flags:#, boost_peer:flags.0?InputPeer) -> Vector`
- Официальная страница: https://core.telegram.org/method/payments.getPremiumGiftCodeOptions
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `boost_peer`: `flags.0?InputPeer` - optional через flags.0

### `payments.getResaleStarGifts`

- Кратко: Получить resale звезду/Stars подарки.
- ID: `2053087798` / `0x7a5fa236`
- Return type: `payments.ResaleStarGifts`
- Сигнатура: `payments.getResaleStarGifts(flags:#, sort_by_price:flags.1?true, sort_by_num:flags.2?true, attributes_hash:flags.0?long, gift_id:long, attributes:flags.3?Vector, offset:string, limit:int) -> payments.ResaleStarGifts`
- Официальная страница: https://core.telegram.org/method/payments.getResaleStarGifts
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `sort_by_price`: `flags.1?true` - optional через flags.1
  - `sort_by_num`: `flags.2?true` - optional через flags.2
  - `attributes_hash`: `flags.0?long` - optional через flags.0
  - `gift_id`: `long`
  - `attributes`: `flags.3?Vector` - optional через flags.3
  - `offset`: `string`
  - `limit`: `int`

### `payments.getSavedInfo`

- Кратко: Получить сохранённые информацию.
- ID: `578650699` / `0x227d824b`
- Return type: `payments.SavedInfo`
- Сигнатура: `payments.getSavedInfo() -> payments.SavedInfo`
- Официальная страница: https://core.telegram.org/method/payments.getSavedInfo
- Параметры:
  - Нет параметров.

### `payments.getSavedStarGift`

- Кратко: Получить сохранённые звезду/Stars подарок.
- ID: `-1269456634` / `0xb455a106`
- Return type: `payments.SavedStarGifts`
- Сигнатура: `payments.getSavedStarGift(stargift:Vector) -> payments.SavedStarGifts`
- Официальная страница: https://core.telegram.org/method/payments.getSavedStarGift
- Параметры:
  - `stargift`: `Vector`

### `payments.getSavedStarGifts`

- Кратко: Получить сохранённые звезду/Stars подарки.
- ID: `-1558583959` / `0xa319e569`
- Return type: `payments.SavedStarGifts`
- Сигнатура: `payments.getSavedStarGifts(flags:#, exclude_unsaved:flags.0?true, exclude_saved:flags.1?true, exclude_unlimited:flags.2?true, exclude_unique:flags.4?true, sort_by_value:flags.5?true, exclude_upgradable:flags.7?true, exclude_unupgradable:flags.8?true, peer:InputPeer, collection_id:flags.6?int, offset:string, limit:int) -> payments.SavedStarGifts`
- Официальная страница: https://core.telegram.org/method/payments.getSavedStarGifts
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `exclude_unsaved`: `flags.0?true` - optional через flags.0
  - `exclude_saved`: `flags.1?true` - optional через flags.1
  - `exclude_unlimited`: `flags.2?true` - optional через flags.2
  - `exclude_unique`: `flags.4?true` - optional через flags.4
  - `sort_by_value`: `flags.5?true` - optional через flags.5
  - `exclude_upgradable`: `flags.7?true` - optional через flags.7
  - `exclude_unupgradable`: `flags.8?true` - optional через flags.8
  - `peer`: `InputPeer`
  - `collection_id`: `flags.6?int` - optional через flags.6
  - `offset`: `string`
  - `limit`: `int`

### `payments.getStarGiftCollections`

- Кратко: Получить звезду/Stars подарок collections.
- ID: `-1743023651` / `0x981b91dd`
- Return type: `payments.StarGiftCollections`
- Сигнатура: `payments.getStarGiftCollections(peer:InputPeer, hash:long) -> payments.StarGiftCollections`
- Официальная страница: https://core.telegram.org/method/payments.getStarGiftCollections
- Параметры:
  - `peer`: `InputPeer`
  - `hash`: `long`

### `payments.getStarGiftUpgradePreview`

- Кратко: Получить звезду/Stars подарок upgrade превью.
- ID: `-1667580751` / `0x9c9abcb1`
- Return type: `payments.StarGiftUpgradePreview`
- Сигнатура: `payments.getStarGiftUpgradePreview(gift_id:long) -> payments.StarGiftUpgradePreview`
- Официальная страница: https://core.telegram.org/method/payments.getStarGiftUpgradePreview
- Параметры:
  - `gift_id`: `long`

### `payments.getStarGiftWithdrawalUrl`

- Кратко: Получить звезду/Stars подарок withdrawal URL.
- ID: `-798059608` / `0xd06e93a8`
- Return type: `payments.StarGiftWithdrawalUrl`
- Сигнатура: `payments.getStarGiftWithdrawalUrl(stargift:InputSavedStarGift, password:InputCheckPasswordSRP) -> payments.StarGiftWithdrawalUrl`
- Официальная страница: https://core.telegram.org/method/payments.getStarGiftWithdrawalUrl
- Параметры:
  - `stargift`: `InputSavedStarGift`
  - `password`: `InputCheckPasswordSRP`

### `payments.getStarGifts`

- Кратко: Получить звезду/Stars подарки.
- ID: `-1000983152` / `0xc4563590`
- Return type: `payments.StarGifts`
- Сигнатура: `payments.getStarGifts(hash:int) -> payments.StarGifts`
- Официальная страница: https://core.telegram.org/method/payments.getStarGifts
- Параметры:
  - `hash`: `int`

### `payments.getStarsGiftOptions`

- Кратко: Получить Stars подарок options.
- ID: `-741774392` / `0xd3c96bc8`
- Return type: `Vector`
- Сигнатура: `payments.getStarsGiftOptions(flags:#, user_id:flags.0?InputUser) -> Vector`
- Официальная страница: https://core.telegram.org/method/payments.getStarsGiftOptions
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `user_id`: `flags.0?InputUser` - optional через flags.0

### `payments.getStarsGiveawayOptions`

- Кратко: Получить Stars розыгрыш options.
- ID: `-1122042562` / `0xbd1efd3e`
- Return type: `Vector`
- Сигнатура: `payments.getStarsGiveawayOptions() -> Vector`
- Официальная страница: https://core.telegram.org/method/payments.getStarsGiveawayOptions
- Параметры:
  - Нет параметров.

### `payments.getStarsRevenueAdsAccountUrl`

- Кратко: Получить Stars доход ads account URL.
- ID: `-774377531` / `0xd1d7efc5`
- Return type: `payments.StarsRevenueAdsAccountUrl`
- Сигнатура: `payments.getStarsRevenueAdsAccountUrl(peer:InputPeer) -> payments.StarsRevenueAdsAccountUrl`
- Официальная страница: https://core.telegram.org/method/payments.getStarsRevenueAdsAccountUrl
- Параметры:
  - `peer`: `InputPeer`

### `payments.getStarsRevenueStats`

- Кратко: Получить Stars доход статистику.
- ID: `-652215594` / `0xd91ffad6`
- Return type: `payments.StarsRevenueStats`
- Сигнатура: `payments.getStarsRevenueStats(flags:#, dark:flags.0?true, ton:flags.1?true, peer:InputPeer) -> payments.StarsRevenueStats`
- Официальная страница: https://core.telegram.org/method/payments.getStarsRevenueStats
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `dark`: `flags.0?true` - optional через flags.0
  - `ton`: `flags.1?true` - optional через flags.1
  - `peer`: `InputPeer`

### `payments.getStarsRevenueWithdrawalUrl`

- Кратко: Получить Stars доход withdrawal URL.
- ID: `607378578` / `0x2433dc92`
- Return type: `payments.StarsRevenueWithdrawalUrl`
- Сигнатура: `payments.getStarsRevenueWithdrawalUrl(flags:#, ton:flags.0?true, peer:InputPeer, amount:flags.1?long, password:InputCheckPasswordSRP) -> payments.StarsRevenueWithdrawalUrl`
- Официальная страница: https://core.telegram.org/method/payments.getStarsRevenueWithdrawalUrl
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `ton`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`
  - `amount`: `flags.1?long` - optional через flags.1
  - `password`: `InputCheckPasswordSRP`

### `payments.getStarsStatus`

- Кратко: Получить Stars статус.
- ID: `1319744447` / `0x4ea9b3bf`
- Return type: `payments.StarsStatus`
- Сигнатура: `payments.getStarsStatus(flags:#, ton:flags.0?true, peer:InputPeer) -> payments.StarsStatus`
- Официальная страница: https://core.telegram.org/method/payments.getStarsStatus
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `ton`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`

### `payments.getStarsSubscriptions`

- Кратко: Получить Stars subscriptions.
- ID: `52761285` / `0x032512c5`
- Return type: `payments.StarsStatus`
- Сигнатура: `payments.getStarsSubscriptions(flags:#, missing_balance:flags.0?true, peer:InputPeer, offset:string) -> payments.StarsStatus`
- Официальная страница: https://core.telegram.org/method/payments.getStarsSubscriptions
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `missing_balance`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`
  - `offset`: `string`

### `payments.getStarsTopupOptions`

- Кратко: Получить Stars topup options.
- ID: `-1072773165` / `0xc00ec7d3`
- Return type: `Vector`
- Сигнатура: `payments.getStarsTopupOptions() -> Vector`
- Официальная страница: https://core.telegram.org/method/payments.getStarsTopupOptions
- Параметры:
  - Нет параметров.

### `payments.getStarsTransactions`

- Кратко: Получить Stars transactions.
- ID: `1775912279` / `0x69da4557`
- Return type: `payments.StarsStatus`
- Сигнатура: `payments.getStarsTransactions(flags:#, inbound:flags.0?true, outbound:flags.1?true, ascending:flags.2?true, ton:flags.4?true, subscription_id:flags.3?string, peer:InputPeer, offset:string, limit:int) -> payments.StarsStatus`
- Официальная страница: https://core.telegram.org/method/payments.getStarsTransactions
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `inbound`: `flags.0?true` - optional через flags.0
  - `outbound`: `flags.1?true` - optional через flags.1
  - `ascending`: `flags.2?true` - optional через flags.2
  - `ton`: `flags.4?true` - optional через flags.4
  - `subscription_id`: `flags.3?string` - optional через flags.3
  - `peer`: `InputPeer`
  - `offset`: `string`
  - `limit`: `int`

### `payments.getStarsTransactionsByID`

- Кратко: Получить Stars transactions by id.
- ID: `768218808` / `0x2dca16b8`
- Return type: `payments.StarsStatus`
- Сигнатура: `payments.getStarsTransactionsByID(flags:#, ton:flags.0?true, peer:InputPeer, id:Vector) -> payments.StarsStatus`
- Официальная страница: https://core.telegram.org/method/payments.getStarsTransactionsByID
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `ton`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`
  - `id`: `Vector`

### `payments.getSuggestedStarRefBots`

- Кратко: Получить предложенные звезду/Stars ref ботов.
- ID: `225134839` / `0x0d6b48f7`
- Return type: `payments.SuggestedStarRefBots`
- Сигнатура: `payments.getSuggestedStarRefBots(flags:#, order_by_revenue:flags.0?true, order_by_date:flags.1?true, peer:InputPeer, offset:string, limit:int) -> payments.SuggestedStarRefBots`
- Официальная страница: https://core.telegram.org/method/payments.getSuggestedStarRefBots
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `order_by_revenue`: `flags.0?true` - optional через flags.0
  - `order_by_date`: `flags.1?true` - optional через flags.1
  - `peer`: `InputPeer`
  - `offset`: `string`
  - `limit`: `int`

### `payments.getUniqueStarGift`

- Кратко: Получить unique звезду/Stars подарок.
- ID: `-1583919758` / `0xa1974d72`
- Return type: `payments.UniqueStarGift`
- Сигнатура: `payments.getUniqueStarGift(slug:string) -> payments.UniqueStarGift`
- Официальная страница: https://core.telegram.org/method/payments.getUniqueStarGift
- Параметры:
  - `slug`: `string`

### `payments.getUniqueStarGiftValueInfo`

- Кратко: Получить unique звезду/Stars подарок value информацию.
- ID: `1130737515` / `0x4365af6b`
- Return type: `payments.UniqueStarGiftValueInfo`
- Сигнатура: `payments.getUniqueStarGiftValueInfo(slug:string) -> payments.UniqueStarGiftValueInfo`
- Официальная страница: https://core.telegram.org/method/payments.getUniqueStarGiftValueInfo
- Параметры:
  - `slug`: `string`

### `payments.launchPrepaidGiveaway`

- Кратко: Запустить prepaid розыгрыш.
- ID: `1609928480` / `0x5ff58f20`
- Return type: `Updates`
- Сигнатура: `payments.launchPrepaidGiveaway(peer:InputPeer, giveaway_id:long, purpose:InputStorePaymentPurpose) -> Updates`
- Официальная страница: https://core.telegram.org/method/payments.launchPrepaidGiveaway
- Параметры:
  - `peer`: `InputPeer`
  - `giveaway_id`: `long`
  - `purpose`: `InputStorePaymentPurpose`

### `payments.refundStarsCharge`

- Кратко: Операция с refund Stars charge.
- ID: `632196938` / `0x25ae8f4a`
- Return type: `Updates`
- Сигнатура: `payments.refundStarsCharge(user_id:InputUser, charge_id:string) -> Updates`
- Официальная страница: https://core.telegram.org/method/payments.refundStarsCharge
- Параметры:
  - `user_id`: `InputUser`
  - `charge_id`: `string`

### `payments.reorderStarGiftCollections`

- Кратко: Изменить порядок звезду/Stars подарок collections.
- ID: `-1020594996` / `0xc32af4cc`
- Return type: `Bool`
- Сигнатура: `payments.reorderStarGiftCollections(peer:InputPeer, order:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/payments.reorderStarGiftCollections
- Параметры:
  - `peer`: `InputPeer`
  - `order`: `Vector`

### `payments.saveStarGift`

- Кратко: Сохранить звезду/Stars подарок.
- ID: `707422588` / `0x2a2a697c`
- Return type: `Bool`
- Сигнатура: `payments.saveStarGift(flags:#, unsave:flags.0?true, stargift:InputSavedStarGift) -> Bool`
- Официальная страница: https://core.telegram.org/method/payments.saveStarGift
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `unsave`: `flags.0?true` - optional через flags.0
  - `stargift`: `InputSavedStarGift`

### `payments.sendPaymentForm`

- Кратко: Отправить платёж form.
- ID: `755192367` / `0x2d03522f`
- Return type: `payments.PaymentResult`
- Сигнатура: `payments.sendPaymentForm(flags:#, form_id:long, invoice:InputInvoice, requested_info_id:flags.0?string, shipping_option_id:flags.1?string, credentials:InputPaymentCredentials, tip_amount:flags.2?long) -> payments.PaymentResult`
- Официальная страница: https://core.telegram.org/method/payments.sendPaymentForm
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `form_id`: `long`
  - `invoice`: `InputInvoice`
  - `requested_info_id`: `flags.0?string` - optional через flags.0
  - `shipping_option_id`: `flags.1?string` - optional через flags.1
  - `credentials`: `InputPaymentCredentials`
  - `tip_amount`: `flags.2?long` - optional через flags.2

### `payments.sendStarsForm`

- Кратко: Отправить Stars form.
- ID: `2040056084` / `0x7998c914`
- Return type: `payments.PaymentResult`
- Сигнатура: `payments.sendStarsForm(form_id:long, invoice:InputInvoice) -> payments.PaymentResult`
- Официальная страница: https://core.telegram.org/method/payments.sendStarsForm
- Параметры:
  - `form_id`: `long`
  - `invoice`: `InputInvoice`

### `payments.toggleChatStarGiftNotifications`

- Кратко: Включить/выключить чат звезду/Stars подарок notifications.
- ID: `1626009505` / `0x60eaefa1`
- Return type: `Bool`
- Сигнатура: `payments.toggleChatStarGiftNotifications(flags:#, enabled:flags.0?true, peer:InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/payments.toggleChatStarGiftNotifications
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `enabled`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`

### `payments.toggleStarGiftsPinnedToTop`

- Кратко: Включить/выключить звезду/Stars подарки закреплённое to верх.
- ID: `353626032` / `0x1513e7b0`
- Return type: `Bool`
- Сигнатура: `payments.toggleStarGiftsPinnedToTop(peer:InputPeer, stargift:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/payments.toggleStarGiftsPinnedToTop
- Параметры:
  - `peer`: `InputPeer`
  - `stargift`: `Vector`

### `payments.transferStarGift`

- Кратко: Операция с transfer звезду/Stars подарок.
- ID: `2132285290` / `0x7f18176a`
- Return type: `Updates`
- Сигнатура: `payments.transferStarGift(stargift:InputSavedStarGift, to_id:InputPeer) -> Updates`
- Официальная страница: https://core.telegram.org/method/payments.transferStarGift
- Параметры:
  - `stargift`: `InputSavedStarGift`
  - `to_id`: `InputPeer`

### `payments.updateStarGiftCollection`

- Кратко: Обновить звезду/Stars подарок collection.
- ID: `1339932391` / `0x4fddbee7`
- Return type: `StarGiftCollection`
- Сигнатура: `payments.updateStarGiftCollection(flags:#, peer:InputPeer, collection_id:int, title:flags.0?string, delete_stargift:flags.1?Vector, add_stargift:flags.2?Vector, order:flags.3?Vector) -> StarGiftCollection`
- Официальная страница: https://core.telegram.org/method/payments.updateStarGiftCollection
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `collection_id`: `int`
  - `title`: `flags.0?string` - optional через flags.0
  - `delete_stargift`: `flags.1?Vector` - optional через flags.1
  - `add_stargift`: `flags.2?Vector` - optional через flags.2
  - `order`: `flags.3?Vector` - optional через flags.3

### `payments.updateStarGiftPrice`

- Кратко: Обновить звезду/Stars подарок price.
- ID: `-306287413` / `0xedbe6ccb`
- Return type: `Updates`
- Сигнатура: `payments.updateStarGiftPrice(stargift:InputSavedStarGift, resell_amount:StarsAmount) -> Updates`
- Официальная страница: https://core.telegram.org/method/payments.updateStarGiftPrice
- Параметры:
  - `stargift`: `InputSavedStarGift`
  - `resell_amount`: `StarsAmount`

### `payments.upgradeStarGift`

- Кратко: Операция с upgrade звезду/Stars подарок.
- ID: `-1361648395` / `0xaed6e4f5`
- Return type: `Updates`
- Сигнатура: `payments.upgradeStarGift(flags:#, keep_original_details:flags.0?true, stargift:InputSavedStarGift) -> Updates`
- Официальная страница: https://core.telegram.org/method/payments.upgradeStarGift
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `keep_original_details`: `flags.0?true` - optional через flags.0
  - `stargift`: `InputSavedStarGift`

### `payments.validateRequestedInfo`

- Кратко: Операция с validate requested информацию.
- ID: `-1228345045` / `0xb6c8f12b`
- Return type: `payments.ValidatedRequestedInfo`
- Сигнатура: `payments.validateRequestedInfo(flags:#, save:flags.0?true, invoice:InputInvoice, info:PaymentRequestedInfo) -> payments.ValidatedRequestedInfo`
- Официальная страница: https://core.telegram.org/method/payments.validateRequestedInfo
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `save`: `flags.0?true` - optional через flags.0
  - `invoice`: `InputInvoice`
  - `info`: `PaymentRequestedInfo`

## phone

### `phone.acceptCall`

- Кратко: Принять звонок.
- ID: `1003664544` / `0x3bd2b4a0`
- Return type: `phone.PhoneCall`
- Сигнатура: `phone.acceptCall(peer:InputPhoneCall, g_b:bytes, protocol:PhoneCallProtocol) -> phone.PhoneCall`
- Официальная страница: https://core.telegram.org/method/phone.acceptCall
- Параметры:
  - `peer`: `InputPhoneCall`
  - `g_b`: `bytes`
  - `protocol`: `PhoneCallProtocol`

### `phone.checkGroupCall`

- Кратко: Проверить группу звонок.
- ID: `-1248003721` / `0xb59cf977`
- Return type: `Vector`
- Сигнатура: `phone.checkGroupCall(call:InputGroupCall, sources:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/phone.checkGroupCall
- Параметры:
  - `call`: `InputGroupCall`
  - `sources`: `Vector`

### `phone.confirmCall`

- Кратко: Подтвердить звонок.
- ID: `788404002` / `0x2efe1722`
- Return type: `phone.PhoneCall`
- Сигнатура: `phone.confirmCall(peer:InputPhoneCall, g_a:bytes, key_fingerprint:long, protocol:PhoneCallProtocol) -> phone.PhoneCall`
- Официальная страница: https://core.telegram.org/method/phone.confirmCall
- Параметры:
  - `peer`: `InputPhoneCall`
  - `g_a`: `bytes`
  - `key_fingerprint`: `long`
  - `protocol`: `PhoneCallProtocol`

### `phone.createConferenceCall`

- Кратко: Создать конференц звонок.
- ID: `2097431739` / `0x7d0444bb`
- Return type: `Updates`
- Сигнатура: `phone.createConferenceCall(flags:#, muted:flags.0?true, video_stopped:flags.2?true, join:flags.3?true, random_id:int, public_key:flags.3?int256, block:flags.3?bytes, params:flags.3?DataJSON) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.createConferenceCall
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `muted`: `flags.0?true` - optional через flags.0
  - `video_stopped`: `flags.2?true` - optional через flags.2
  - `join`: `flags.3?true` - optional через flags.3
  - `random_id`: `int`
  - `public_key`: `flags.3?int256` - optional через flags.3
  - `block`: `flags.3?bytes` - optional через flags.3
  - `params`: `flags.3?DataJSON` - optional через flags.3

### `phone.createGroupCall`

- Кратко: Создать группу звонок.
- ID: `1221445336` / `0x48cdc6d8`
- Return type: `Updates`
- Сигнатура: `phone.createGroupCall(flags:#, rtmp_stream:flags.2?true, peer:InputPeer, random_id:int, title:flags.0?string, schedule_date:flags.1?int) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.createGroupCall
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `rtmp_stream`: `flags.2?true` - optional через flags.2
  - `peer`: `InputPeer`
  - `random_id`: `int`
  - `title`: `flags.0?string` - optional через flags.0
  - `schedule_date`: `flags.1?int` - optional через flags.1

### `phone.declineConferenceCallInvite`

- Кратко: Отклонить конференц звонок приглашение.
- ID: `1011325297` / `0x3c479971`
- Return type: `Updates`
- Сигнатура: `phone.declineConferenceCallInvite(msg_id:int) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.declineConferenceCallInvite
- Параметры:
  - `msg_id`: `int`

### `phone.deleteConferenceCallParticipants`

- Кратко: Удалить конференц звонок участников.
- ID: `-1935276763` / `0x8ca60525`
- Return type: `Updates`
- Сигнатура: `phone.deleteConferenceCallParticipants(flags:#, only_left:flags.0?true, kick:flags.1?true, call:InputGroupCall, ids:Vector, block:bytes) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.deleteConferenceCallParticipants
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `only_left`: `flags.0?true` - optional через flags.0
  - `kick`: `flags.1?true` - optional через flags.1
  - `call`: `InputGroupCall`
  - `ids`: `Vector`
  - `block`: `bytes`

### `phone.discardCall`

- Кратко: Операция с discard звонок.
- ID: `-1295269440` / `0xb2cbc1c0`
- Return type: `Updates`
- Сигнатура: `phone.discardCall(flags:#, video:flags.0?true, peer:InputPhoneCall, duration:int, reason:PhoneCallDiscardReason, connection_id:long) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.discardCall
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `video`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPhoneCall`
  - `duration`: `int`
  - `reason`: `PhoneCallDiscardReason`
  - `connection_id`: `long`

### `phone.discardGroupCall`

- Кратко: Операция с discard группу звонок.
- ID: `2054648117` / `0x7a777135`
- Return type: `Updates`
- Сигнатура: `phone.discardGroupCall(call:InputGroupCall) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.discardGroupCall
- Параметры:
  - `call`: `InputGroupCall`

### `phone.editGroupCallParticipant`

- Кратко: Изменить группу звонок участника.
- ID: `-1524155713` / `0xa5273abf`
- Return type: `Updates`
- Сигнатура: `phone.editGroupCallParticipant(flags:#, call:InputGroupCall, participant:InputPeer, muted:flags.0?Bool, volume:flags.1?int, raise_hand:flags.2?Bool, video_stopped:flags.3?Bool, video_paused:flags.4?Bool, presentation_paused:flags.5?Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.editGroupCallParticipant
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `call`: `InputGroupCall`
  - `participant`: `InputPeer`
  - `muted`: `flags.0?Bool` - optional через flags.0
  - `volume`: `flags.1?int` - optional через flags.1
  - `raise_hand`: `flags.2?Bool` - optional через flags.2
  - `video_stopped`: `flags.3?Bool` - optional через flags.3
  - `video_paused`: `flags.4?Bool` - optional через flags.4
  - `presentation_paused`: `flags.5?Bool` - optional через flags.5

### `phone.editGroupCallTitle`

- Кратко: Изменить группу звонок заголовок.
- ID: `480685066` / `0x1ca6ac0a`
- Return type: `Updates`
- Сигнатура: `phone.editGroupCallTitle(call:InputGroupCall, title:string) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.editGroupCallTitle
- Параметры:
  - `call`: `InputGroupCall`
  - `title`: `string`

### `phone.exportGroupCallInvite`

- Кратко: Экспортировать группу звонок приглашение.
- ID: `-425040769` / `0xe6aa647f`
- Return type: `phone.ExportedGroupCallInvite`
- Сигнатура: `phone.exportGroupCallInvite(flags:#, can_self_unmute:flags.0?true, call:InputGroupCall) -> phone.ExportedGroupCallInvite`
- Официальная страница: https://core.telegram.org/method/phone.exportGroupCallInvite
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `can_self_unmute`: `flags.0?true` - optional через flags.0
  - `call`: `InputGroupCall`

### `phone.getCallConfig`

- Кратко: Получить звонок конфигурацию.
- ID: `1430593449` / `0x55451fa9`
- Return type: `DataJSON`
- Сигнатура: `phone.getCallConfig() -> DataJSON`
- Официальная страница: https://core.telegram.org/method/phone.getCallConfig
- Параметры:
  - Нет параметров.

### `phone.getGroupCall`

- Кратко: Получить группу звонок.
- ID: `68699611` / `0x041845db`
- Return type: `phone.GroupCall`
- Сигнатура: `phone.getGroupCall(call:InputGroupCall, limit:int) -> phone.GroupCall`
- Официальная страница: https://core.telegram.org/method/phone.getGroupCall
- Параметры:
  - `call`: `InputGroupCall`
  - `limit`: `int`

### `phone.getGroupCallChainBlocks`

- Кратко: Получить группу звонок chain blocks.
- ID: `-291534682` / `0xee9f88a6`
- Return type: `Updates`
- Сигнатура: `phone.getGroupCallChainBlocks(call:InputGroupCall, sub_chain_id:int, offset:int, limit:int) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.getGroupCallChainBlocks
- Параметры:
  - `call`: `InputGroupCall`
  - `sub_chain_id`: `int`
  - `offset`: `int`
  - `limit`: `int`

### `phone.getGroupCallJoinAs`

- Кратко: Получить группу звонок вход as.
- ID: `-277077702` / `0xef7c213a`
- Return type: `phone.JoinAsPeers`
- Сигнатура: `phone.getGroupCallJoinAs(peer:InputPeer) -> phone.JoinAsPeers`
- Официальная страница: https://core.telegram.org/method/phone.getGroupCallJoinAs
- Параметры:
  - `peer`: `InputPeer`

### `phone.getGroupCallStreamChannels`

- Кратко: Получить группу звонок stream каналы.
- ID: `447879488` / `0x1ab21940`
- Return type: `phone.GroupCallStreamChannels`
- Сигнатура: `phone.getGroupCallStreamChannels(call:InputGroupCall) -> phone.GroupCallStreamChannels`
- Официальная страница: https://core.telegram.org/method/phone.getGroupCallStreamChannels
- Параметры:
  - `call`: `InputGroupCall`

### `phone.getGroupCallStreamRtmpUrl`

- Кратко: Получить группу звонок stream rtmp URL.
- ID: `-558650433` / `0xdeb3abbf`
- Return type: `phone.GroupCallStreamRtmpUrl`
- Сигнатура: `phone.getGroupCallStreamRtmpUrl(peer:InputPeer, revoke:Bool) -> phone.GroupCallStreamRtmpUrl`
- Официальная страница: https://core.telegram.org/method/phone.getGroupCallStreamRtmpUrl
- Параметры:
  - `peer`: `InputPeer`
  - `revoke`: `Bool`

### `phone.getGroupParticipants`

- Кратко: Получить группу участников.
- ID: `-984033109` / `0xc558d8ab`
- Return type: `phone.GroupParticipants`
- Сигнатура: `phone.getGroupParticipants(call:InputGroupCall, ids:Vector, sources:Vector, offset:string, limit:int) -> phone.GroupParticipants`
- Официальная страница: https://core.telegram.org/method/phone.getGroupParticipants
- Параметры:
  - `call`: `InputGroupCall`
  - `ids`: `Vector`
  - `sources`: `Vector`
  - `offset`: `string`
  - `limit`: `int`

### `phone.inviteConferenceCallParticipant`

- Кратко: Пригласить конференц звонок участника.
- ID: `-1124981115` / `0xbcf22685`
- Return type: `Updates`
- Сигнатура: `phone.inviteConferenceCallParticipant(flags:#, video:flags.0?true, call:InputGroupCall, user_id:InputUser) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.inviteConferenceCallParticipant
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `video`: `flags.0?true` - optional через flags.0
  - `call`: `InputGroupCall`
  - `user_id`: `InputUser`

### `phone.inviteToGroupCall`

- Кратко: Пригласить to группу звонок.
- ID: `2067345760` / `0x7b393160`
- Return type: `Updates`
- Сигнатура: `phone.inviteToGroupCall(call:InputGroupCall, users:Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.inviteToGroupCall
- Параметры:
  - `call`: `InputGroupCall`
  - `users`: `Vector`

### `phone.joinGroupCall`

- Кратко: Присоединиться к группу звонок.
- ID: `-1883951017` / `0x8fb53057`
- Return type: `Updates`
- Сигнатура: `phone.joinGroupCall(flags:#, muted:flags.0?true, video_stopped:flags.2?true, call:InputGroupCall, join_as:InputPeer, invite_hash:flags.1?string, public_key:flags.3?int256, block:flags.3?bytes, params:DataJSON) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.joinGroupCall
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `muted`: `flags.0?true` - optional через flags.0
  - `video_stopped`: `flags.2?true` - optional через flags.2
  - `call`: `InputGroupCall`
  - `join_as`: `InputPeer`
  - `invite_hash`: `flags.1?string` - optional через flags.1
  - `public_key`: `flags.3?int256` - optional через flags.3
  - `block`: `flags.3?bytes` - optional через flags.3
  - `params`: `DataJSON`

### `phone.joinGroupCallPresentation`

- Кратко: Присоединиться к группу звонок presentation.
- ID: `-873829436` / `0xcbea6bc4`
- Return type: `Updates`
- Сигнатура: `phone.joinGroupCallPresentation(call:InputGroupCall, params:DataJSON) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.joinGroupCallPresentation
- Параметры:
  - `call`: `InputGroupCall`
  - `params`: `DataJSON`

### `phone.leaveGroupCall`

- Кратко: Покинуть группу звонок.
- ID: `1342404601` / `0x500377f9`
- Return type: `Updates`
- Сигнатура: `phone.leaveGroupCall(call:InputGroupCall, source:int) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.leaveGroupCall
- Параметры:
  - `call`: `InputGroupCall`
  - `source`: `int`

### `phone.leaveGroupCallPresentation`

- Кратко: Покинуть группу звонок presentation.
- ID: `475058500` / `0x1c50d144`
- Return type: `Updates`
- Сигнатура: `phone.leaveGroupCallPresentation(call:InputGroupCall) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.leaveGroupCallPresentation
- Параметры:
  - `call`: `InputGroupCall`

### `phone.receivedCall`

- Кратко: Операция с received звонок.
- ID: `399855457` / `0x17d54f61`
- Return type: `Bool`
- Сигнатура: `phone.receivedCall(peer:InputPhoneCall) -> Bool`
- Официальная страница: https://core.telegram.org/method/phone.receivedCall
- Параметры:
  - `peer`: `InputPhoneCall`

### `phone.requestCall`

- Кратко: Запросить звонок.
- ID: `1124046573` / `0x42ff96ed`
- Return type: `phone.PhoneCall`
- Сигнатура: `phone.requestCall(flags:#, video:flags.0?true, user_id:InputUser, random_id:int, g_a_hash:bytes, protocol:PhoneCallProtocol) -> phone.PhoneCall`
- Официальная страница: https://core.telegram.org/method/phone.requestCall
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `video`: `flags.0?true` - optional через flags.0
  - `user_id`: `InputUser`
  - `random_id`: `int`
  - `g_a_hash`: `bytes`
  - `protocol`: `PhoneCallProtocol`

### `phone.saveCallDebug`

- Кратко: Сохранить звонок debug.
- ID: `662363518` / `0x277add7e`
- Return type: `Bool`
- Сигнатура: `phone.saveCallDebug(peer:InputPhoneCall, debug:DataJSON) -> Bool`
- Официальная страница: https://core.telegram.org/method/phone.saveCallDebug
- Параметры:
  - `peer`: `InputPhoneCall`
  - `debug`: `DataJSON`

### `phone.saveCallLog`

- Кратко: Сохранить звонок log.
- ID: `1092913030` / `0x41248786`
- Return type: `Bool`
- Сигнатура: `phone.saveCallLog(peer:InputPhoneCall, file:InputFile) -> Bool`
- Официальная страница: https://core.telegram.org/method/phone.saveCallLog
- Параметры:
  - `peer`: `InputPhoneCall`
  - `file`: `InputFile`

### `phone.saveDefaultGroupCallJoinAs`

- Кратко: Сохранить default группу звонок вход as.
- ID: `1465786252` / `0x575e1f8c`
- Return type: `Bool`
- Сигнатура: `phone.saveDefaultGroupCallJoinAs(peer:InputPeer, join_as:InputPeer) -> Bool`
- Официальная страница: https://core.telegram.org/method/phone.saveDefaultGroupCallJoinAs
- Параметры:
  - `peer`: `InputPeer`
  - `join_as`: `InputPeer`

### `phone.sendConferenceCallBroadcast`

- Кратко: Отправить конференц звонок эфир/трансляцию.
- ID: `-965732096` / `0xc6701900`
- Return type: `Updates`
- Сигнатура: `phone.sendConferenceCallBroadcast(call:InputGroupCall, block:bytes) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.sendConferenceCallBroadcast
- Параметры:
  - `call`: `InputGroupCall`
  - `block`: `bytes`

### `phone.sendSignalingData`

- Кратко: Отправить signaling данные.
- ID: `-8744061` / `0xff7a9383`
- Return type: `Bool`
- Сигнатура: `phone.sendSignalingData(peer:InputPhoneCall, data:bytes) -> Bool`
- Официальная страница: https://core.telegram.org/method/phone.sendSignalingData
- Параметры:
  - `peer`: `InputPhoneCall`
  - `data`: `bytes`

### `phone.setCallRating`

- Кратко: Установить звонок rating.
- ID: `1508562471` / `0x59ead627`
- Return type: `Updates`
- Сигнатура: `phone.setCallRating(flags:#, user_initiative:flags.0?true, peer:InputPhoneCall, rating:int, comment:string) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.setCallRating
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `user_initiative`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPhoneCall`
  - `rating`: `int`
  - `comment`: `string`

### `phone.startScheduledGroupCall`

- Кратко: Операция с запуск запланированные группу звонок.
- ID: `1451287362` / `0x5680e342`
- Return type: `Updates`
- Сигнатура: `phone.startScheduledGroupCall(call:InputGroupCall) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.startScheduledGroupCall
- Параметры:
  - `call`: `InputGroupCall`

### `phone.toggleGroupCallRecord`

- Кратко: Включить/выключить группу звонок запись.
- ID: `-248985848` / `0xf128c708`
- Return type: `Updates`
- Сигнатура: `phone.toggleGroupCallRecord(flags:#, start:flags.0?true, video:flags.2?true, call:InputGroupCall, title:flags.1?string, video_portrait:flags.2?Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.toggleGroupCallRecord
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `start`: `flags.0?true` - optional через flags.0
  - `video`: `flags.2?true` - optional через flags.2
  - `call`: `InputGroupCall`
  - `title`: `flags.1?string` - optional через flags.1
  - `video_portrait`: `flags.2?Bool` - optional через flags.2

### `phone.toggleGroupCallSettings`

- Кратко: Включить/выключить группу звонок настройки.
- ID: `1958458429` / `0x74bbb43d`
- Return type: `Updates`
- Сигнатура: `phone.toggleGroupCallSettings(flags:#, reset_invite_hash:flags.1?true, call:InputGroupCall, join_muted:flags.0?Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.toggleGroupCallSettings
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `reset_invite_hash`: `flags.1?true` - optional через flags.1
  - `call`: `InputGroupCall`
  - `join_muted`: `flags.0?Bool` - optional через flags.0

### `phone.toggleGroupCallStartSubscription`

- Кратко: Включить/выключить группу звонок запуск подписку.
- ID: `563885286` / `0x219c34e6`
- Return type: `Updates`
- Сигнатура: `phone.toggleGroupCallStartSubscription(call:InputGroupCall, subscribed:Bool) -> Updates`
- Официальная страница: https://core.telegram.org/method/phone.toggleGroupCallStartSubscription
- Параметры:
  - `call`: `InputGroupCall`
  - `subscribed`: `Bool`

## photos

### `photos.deletePhotos`

- Кратко: Удалить фото.
- ID: `-2016444625` / `0x87cf7f2f`
- Return type: `Vector`
- Сигнатура: `photos.deletePhotos(id:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/photos.deletePhotos
- Параметры:
  - `id`: `Vector`

### `photos.getUserPhotos`

- Кратко: Получить пользователя фото.
- ID: `-1848823128` / `0x91cd32a8`
- Return type: `photos.Photos`
- Сигнатура: `photos.getUserPhotos(user_id:InputUser, offset:int, max_id:long, limit:int) -> photos.Photos`
- Официальная страница: https://core.telegram.org/method/photos.getUserPhotos
- Параметры:
  - `user_id`: `InputUser`
  - `offset`: `int`
  - `max_id`: `long`
  - `limit`: `int`

### `photos.updateProfilePhoto`

- Кратко: Обновить профиль фото.
- ID: `166207545` / `0x09e82039`
- Return type: `photos.Photo`
- Сигнатура: `photos.updateProfilePhoto(flags:#, fallback:flags.0?true, bot:flags.1?InputUser, id:InputPhoto) -> photos.Photo`
- Официальная страница: https://core.telegram.org/method/photos.updateProfilePhoto
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `fallback`: `flags.0?true` - optional через flags.0
  - `bot`: `flags.1?InputUser` - optional через flags.1
  - `id`: `InputPhoto`

### `photos.uploadContactProfilePhoto`

- Кратко: Загрузить контакт профиль фото.
- ID: `-515093903` / `0xe14c4a71`
- Return type: `photos.Photo`
- Сигнатура: `photos.uploadContactProfilePhoto(flags:#, suggest:flags.3?true, save:flags.4?true, user_id:InputUser, file:flags.0?InputFile, video:flags.1?InputFile, video_start_ts:flags.2?double, video_emoji_markup:flags.5?VideoSize) -> photos.Photo`
- Официальная страница: https://core.telegram.org/method/photos.uploadContactProfilePhoto
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `suggest`: `flags.3?true` - optional через flags.3
  - `save`: `flags.4?true` - optional через flags.4
  - `user_id`: `InputUser`
  - `file`: `flags.0?InputFile` - optional через flags.0
  - `video`: `flags.1?InputFile` - optional через flags.1
  - `video_start_ts`: `flags.2?double` - optional через flags.2
  - `video_emoji_markup`: `flags.5?VideoSize` - optional через flags.5

### `photos.uploadProfilePhoto`

- Кратко: Загрузить профиль фото.
- ID: `59286453` / `0x0388a3b5`
- Return type: `photos.Photo`
- Сигнатура: `photos.uploadProfilePhoto(flags:#, fallback:flags.3?true, bot:flags.5?InputUser, file:flags.0?InputFile, video:flags.1?InputFile, video_start_ts:flags.2?double, video_emoji_markup:flags.4?VideoSize) -> photos.Photo`
- Официальная страница: https://core.telegram.org/method/photos.uploadProfilePhoto
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `fallback`: `flags.3?true` - optional через flags.3
  - `bot`: `flags.5?InputUser` - optional через flags.5
  - `file`: `flags.0?InputFile` - optional через flags.0
  - `video`: `flags.1?InputFile` - optional через flags.1
  - `video_start_ts`: `flags.2?double` - optional через flags.2
  - `video_emoji_markup`: `flags.4?VideoSize` - optional через flags.4

## premium

### `premium.applyBoost`

- Кратко: Применить буст.
- ID: `1803396934` / `0x6b7da746`
- Return type: `premium.MyBoosts`
- Сигнатура: `premium.applyBoost(flags:#, slots:flags.0?Vector, peer:InputPeer) -> premium.MyBoosts`
- Официальная страница: https://core.telegram.org/method/premium.applyBoost
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `slots`: `flags.0?Vector` - optional через flags.0
  - `peer`: `InputPeer`

### `premium.getBoostsList`

- Кратко: Получить бусты список.
- ID: `1626764896` / `0x60f67660`
- Return type: `premium.BoostsList`
- Сигнатура: `premium.getBoostsList(flags:#, gifts:flags.0?true, peer:InputPeer, offset:string, limit:int) -> premium.BoostsList`
- Официальная страница: https://core.telegram.org/method/premium.getBoostsList
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `gifts`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`
  - `offset`: `string`
  - `limit`: `int`

### `premium.getBoostsStatus`

- Кратко: Получить бусты статус.
- ID: `70197089` / `0x042f1f61`
- Return type: `premium.BoostsStatus`
- Сигнатура: `premium.getBoostsStatus(peer:InputPeer) -> premium.BoostsStatus`
- Официальная страница: https://core.telegram.org/method/premium.getBoostsStatus
- Параметры:
  - `peer`: `InputPeer`

### `premium.getMyBoosts`

- Кратко: Получить my бусты.
- ID: `199719754` / `0x0be77b4a`
- Return type: `premium.MyBoosts`
- Сигнатура: `premium.getMyBoosts() -> premium.MyBoosts`
- Официальная страница: https://core.telegram.org/method/premium.getMyBoosts
- Параметры:
  - Нет параметров.

### `premium.getUserBoosts`

- Кратко: Получить пользователя бусты.
- ID: `965037343` / `0x39854d1f`
- Return type: `premium.BoostsList`
- Сигнатура: `premium.getUserBoosts(peer:InputPeer, user_id:InputUser) -> premium.BoostsList`
- Официальная страница: https://core.telegram.org/method/premium.getUserBoosts
- Параметры:
  - `peer`: `InputPeer`
  - `user_id`: `InputUser`

## smsjobs

### `smsjobs.finishJob`

- Кратко: Завершить job.
- ID: `1327415076` / `0x4f1ebf24`
- Return type: `Bool`
- Сигнатура: `smsjobs.finishJob(flags:#, job_id:string, error:flags.0?string) -> Bool`
- Официальная страница: https://core.telegram.org/method/smsjobs.finishJob
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `job_id`: `string`
  - `error`: `flags.0?string` - optional через flags.0

### `smsjobs.getSmsJob`

- Кратко: Получить SMS job.
- ID: `2005766191` / `0x778d902f`
- Return type: `SmsJob`
- Сигнатура: `smsjobs.getSmsJob(job_id:string) -> SmsJob`
- Официальная страница: https://core.telegram.org/method/smsjobs.getSmsJob
- Параметры:
  - `job_id`: `string`

### `smsjobs.getStatus`

- Кратко: Получить статус.
- ID: `279353576` / `0x10a698e8`
- Return type: `smsjobs.Status`
- Сигнатура: `smsjobs.getStatus() -> smsjobs.Status`
- Официальная страница: https://core.telegram.org/method/smsjobs.getStatus
- Параметры:
  - Нет параметров.

### `smsjobs.isEligibleToJoin`

- Кратко: Операция с is eligible to вход.
- ID: `249313744` / `0x0edc39d0`
- Return type: `smsjobs.EligibilityToJoin`
- Сигнатура: `smsjobs.isEligibleToJoin() -> smsjobs.EligibilityToJoin`
- Официальная страница: https://core.telegram.org/method/smsjobs.isEligibleToJoin
- Параметры:
  - Нет параметров.

### `smsjobs.join`

- Кратко: Присоединиться к данными.
- ID: `-1488007635` / `0xa74ece2d`
- Return type: `Bool`
- Сигнатура: `smsjobs.join() -> Bool`
- Официальная страница: https://core.telegram.org/method/smsjobs.join
- Параметры:
  - Нет параметров.

### `smsjobs.leave`

- Кратко: Покинуть данными.
- ID: `-1734824589` / `0x9898ad73`
- Return type: `Bool`
- Сигнатура: `smsjobs.leave() -> Bool`
- Официальная страница: https://core.telegram.org/method/smsjobs.leave
- Параметры:
  - Нет параметров.

### `smsjobs.updateSettings`

- Кратко: Обновить настройки.
- ID: `155164863` / `0x093fa0bf`
- Return type: `Bool`
- Сигнатура: `smsjobs.updateSettings(flags:#, allow_international:flags.0?true) -> Bool`
- Официальная страница: https://core.telegram.org/method/smsjobs.updateSettings
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `allow_international`: `flags.0?true` - optional через flags.0

## stats

### `stats.getBroadcastStats`

- Кратко: Получить эфир/трансляцию статистику.
- ID: `-1421720550` / `0xab42441a`
- Return type: `stats.BroadcastStats`
- Сигнатура: `stats.getBroadcastStats(flags:#, dark:flags.0?true, channel:InputChannel) -> stats.BroadcastStats`
- Официальная страница: https://core.telegram.org/method/stats.getBroadcastStats
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `dark`: `flags.0?true` - optional через flags.0
  - `channel`: `InputChannel`

### `stats.getMegagroupStats`

- Кратко: Получить megagroup статистику.
- ID: `-589330937` / `0xdcdf8607`
- Return type: `stats.MegagroupStats`
- Сигнатура: `stats.getMegagroupStats(flags:#, dark:flags.0?true, channel:InputChannel) -> stats.MegagroupStats`
- Официальная страница: https://core.telegram.org/method/stats.getMegagroupStats
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `dark`: `flags.0?true` - optional через flags.0
  - `channel`: `InputChannel`

### `stats.getMessagePublicForwards`

- Кратко: Получить сообщение публичные forwards.
- ID: `1595212100` / `0x5f150144`
- Return type: `stats.PublicForwards`
- Сигнатура: `stats.getMessagePublicForwards(channel:InputChannel, msg_id:int, offset:string, limit:int) -> stats.PublicForwards`
- Официальная страница: https://core.telegram.org/method/stats.getMessagePublicForwards
- Параметры:
  - `channel`: `InputChannel`
  - `msg_id`: `int`
  - `offset`: `string`
  - `limit`: `int`

### `stats.getMessageStats`

- Кратко: Получить сообщение статистику.
- ID: `-1226791947` / `0xb6e0a3f5`
- Return type: `stats.MessageStats`
- Сигнатура: `stats.getMessageStats(flags:#, dark:flags.0?true, channel:InputChannel, msg_id:int) -> stats.MessageStats`
- Официальная страница: https://core.telegram.org/method/stats.getMessageStats
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `dark`: `flags.0?true` - optional через flags.0
  - `channel`: `InputChannel`
  - `msg_id`: `int`

### `stats.getStoryPublicForwards`

- Кратко: Получить историю публичные forwards.
- ID: `-1505526026` / `0xa6437ef6`
- Return type: `stats.PublicForwards`
- Сигнатура: `stats.getStoryPublicForwards(peer:InputPeer, id:int, offset:string, limit:int) -> stats.PublicForwards`
- Официальная страница: https://core.telegram.org/method/stats.getStoryPublicForwards
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `int`
  - `offset`: `string`
  - `limit`: `int`

### `stats.getStoryStats`

- Кратко: Получить историю статистику.
- ID: `927985472` / `0x374fef40`
- Return type: `stats.StoryStats`
- Сигнатура: `stats.getStoryStats(flags:#, dark:flags.0?true, peer:InputPeer, id:int) -> stats.StoryStats`
- Официальная страница: https://core.telegram.org/method/stats.getStoryStats
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `dark`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`
  - `id`: `int`

### `stats.loadAsyncGraph`

- Кратко: Операция с load async graph.
- ID: `1646092192` / `0x621d5fa0`
- Return type: `StatsGraph`
- Сигнатура: `stats.loadAsyncGraph(flags:#, token:string, x:flags.0?long) -> StatsGraph`
- Официальная страница: https://core.telegram.org/method/stats.loadAsyncGraph
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `token`: `string`
  - `x`: `flags.0?long` - optional через flags.0

## stickers

### `stickers.addStickerToSet`

- Кратко: Операция с add стикер to set.
- ID: `-2041315650` / `0x8653febe`
- Return type: `messages.StickerSet`
- Сигнатура: `stickers.addStickerToSet(stickerset:InputStickerSet, sticker:InputStickerSetItem) -> messages.StickerSet`
- Официальная страница: https://core.telegram.org/method/stickers.addStickerToSet
- Параметры:
  - `stickerset`: `InputStickerSet`
  - `sticker`: `InputStickerSetItem`

### `stickers.changeSticker`

- Кратко: Операция с change стикер.
- ID: `-179077444` / `0xf5537ebc`
- Return type: `messages.StickerSet`
- Сигнатура: `stickers.changeSticker(flags:#, sticker:InputDocument, emoji:flags.0?string, mask_coords:flags.1?MaskCoords, keywords:flags.2?string) -> messages.StickerSet`
- Официальная страница: https://core.telegram.org/method/stickers.changeSticker
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `sticker`: `InputDocument`
  - `emoji`: `flags.0?string` - optional через flags.0
  - `mask_coords`: `flags.1?MaskCoords` - optional через flags.1
  - `keywords`: `flags.2?string` - optional через flags.2

### `stickers.changeStickerPosition`

- Кратко: Операция с change стикер position.
- ID: `-4795190` / `0xffb6d4ca`
- Return type: `messages.StickerSet`
- Сигнатура: `stickers.changeStickerPosition(sticker:InputDocument, position:int) -> messages.StickerSet`
- Официальная страница: https://core.telegram.org/method/stickers.changeStickerPosition
- Параметры:
  - `sticker`: `InputDocument`
  - `position`: `int`

### `stickers.checkShortName`

- Кратко: Проверить short имя.
- ID: `676017721` / `0x284b3639`
- Return type: `Bool`
- Сигнатура: `stickers.checkShortName(short_name:string) -> Bool`
- Официальная страница: https://core.telegram.org/method/stickers.checkShortName
- Параметры:
  - `short_name`: `string`

### `stickers.createStickerSet`

- Кратко: Создать стикер set.
- ID: `-1876841625` / `0x9021ab67`
- Return type: `messages.StickerSet`
- Сигнатура: `stickers.createStickerSet(flags:#, masks:flags.0?true, emojis:flags.5?true, text_color:flags.6?true, user_id:InputUser, title:string, short_name:string, thumb:flags.2?InputDocument, stickers:Vector, software:flags.3?string) -> messages.StickerSet`
- Официальная страница: https://core.telegram.org/method/stickers.createStickerSet
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `masks`: `flags.0?true` - optional через flags.0
  - `emojis`: `flags.5?true` - optional через flags.5
  - `text_color`: `flags.6?true` - optional через flags.6
  - `user_id`: `InputUser`
  - `title`: `string`
  - `short_name`: `string`
  - `thumb`: `flags.2?InputDocument` - optional через flags.2
  - `stickers`: `Vector`
  - `software`: `flags.3?string` - optional через flags.3

### `stickers.deleteStickerSet`

- Кратко: Удалить стикер set.
- ID: `-2022685804` / `0x87704394`
- Return type: `Bool`
- Сигнатура: `stickers.deleteStickerSet(stickerset:InputStickerSet) -> Bool`
- Официальная страница: https://core.telegram.org/method/stickers.deleteStickerSet
- Параметры:
  - `stickerset`: `InputStickerSet`

### `stickers.removeStickerFromSet`

- Кратко: Операция с remove стикер from set.
- ID: `-143257775` / `0xf7760f51`
- Return type: `messages.StickerSet`
- Сигнатура: `stickers.removeStickerFromSet(sticker:InputDocument) -> messages.StickerSet`
- Официальная страница: https://core.telegram.org/method/stickers.removeStickerFromSet
- Параметры:
  - `sticker`: `InputDocument`

### `stickers.renameStickerSet`

- Кратко: Операция с rename стикер set.
- ID: `306912256` / `0x124b1c00`
- Return type: `messages.StickerSet`
- Сигнатура: `stickers.renameStickerSet(stickerset:InputStickerSet, title:string) -> messages.StickerSet`
- Официальная страница: https://core.telegram.org/method/stickers.renameStickerSet
- Параметры:
  - `stickerset`: `InputStickerSet`
  - `title`: `string`

### `stickers.replaceSticker`

- Кратко: Операция с replace стикер.
- ID: `1184253338` / `0x4696459a`
- Return type: `messages.StickerSet`
- Сигнатура: `stickers.replaceSticker(sticker:InputDocument, new_sticker:InputStickerSetItem) -> messages.StickerSet`
- Официальная страница: https://core.telegram.org/method/stickers.replaceSticker
- Параметры:
  - `sticker`: `InputDocument`
  - `new_sticker`: `InputStickerSetItem`

### `stickers.setStickerSetThumb`

- Кратко: Установить стикер set thumb.
- ID: `-1486204014` / `0xa76a5392`
- Return type: `messages.StickerSet`
- Сигнатура: `stickers.setStickerSetThumb(flags:#, stickerset:InputStickerSet, thumb:flags.0?InputDocument, thumb_document_id:flags.1?long) -> messages.StickerSet`
- Официальная страница: https://core.telegram.org/method/stickers.setStickerSetThumb
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `stickerset`: `InputStickerSet`
  - `thumb`: `flags.0?InputDocument` - optional через flags.0
  - `thumb_document_id`: `flags.1?long` - optional через flags.1

### `stickers.suggestShortName`

- Кратко: Операция с suggest short имя.
- ID: `1303364867` / `0x4dafc503`
- Return type: `stickers.SuggestedShortName`
- Сигнатура: `stickers.suggestShortName(title:string) -> stickers.SuggestedShortName`
- Официальная страница: https://core.telegram.org/method/stickers.suggestShortName
- Параметры:
  - `title`: `string`

## stories

### `stories.activateStealthMode`

- Кратко: Операция с activate stealth режим.
- ID: `1471926630` / `0x57bbd166`
- Return type: `Updates`
- Сигнатура: `stories.activateStealthMode(flags:#, past:flags.0?true, future:flags.1?true) -> Updates`
- Официальная страница: https://core.telegram.org/method/stories.activateStealthMode
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `past`: `flags.0?true` - optional через flags.0
  - `future`: `flags.1?true` - optional через flags.1

### `stories.canSendStory`

- Кратко: Проверить, может ли отправлять историю.
- ID: `820732912` / `0x30eb63f0`
- Return type: `stories.CanSendStoryCount`
- Сигнатура: `stories.canSendStory(peer:InputPeer) -> stories.CanSendStoryCount`
- Официальная страница: https://core.telegram.org/method/stories.canSendStory
- Параметры:
  - `peer`: `InputPeer`

### `stories.createAlbum`

- Кратко: Создать album.
- ID: `-1553754395` / `0xa36396e5`
- Return type: `StoryAlbum`
- Сигнатура: `stories.createAlbum(peer:InputPeer, title:string, stories:Vector) -> StoryAlbum`
- Официальная страница: https://core.telegram.org/method/stories.createAlbum
- Параметры:
  - `peer`: `InputPeer`
  - `title`: `string`
  - `stories`: `Vector`

### `stories.deleteAlbum`

- Кратко: Удалить album.
- ID: `-1925949744` / `0x8d3456d0`
- Return type: `Bool`
- Сигнатура: `stories.deleteAlbum(peer:InputPeer, album_id:int) -> Bool`
- Официальная страница: https://core.telegram.org/method/stories.deleteAlbum
- Параметры:
  - `peer`: `InputPeer`
  - `album_id`: `int`

### `stories.deleteStories`

- Кратко: Удалить истории.
- ID: `-1369842849` / `0xae59db5f`
- Return type: `Vector`
- Сигнатура: `stories.deleteStories(peer:InputPeer, id:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/stories.deleteStories
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`

### `stories.editStory`

- Кратко: Изменить историю.
- ID: `-1249658298` / `0xb583ba46`
- Return type: `Updates`
- Сигнатура: `stories.editStory(flags:#, peer:InputPeer, id:int, media:flags.0?InputMedia, media_areas:flags.3?Vector, caption:flags.1?string, entities:flags.1?Vector, privacy_rules:flags.2?Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/stories.editStory
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `id`: `int`
  - `media`: `flags.0?InputMedia` - optional через flags.0
  - `media_areas`: `flags.3?Vector` - optional через flags.3
  - `caption`: `flags.1?string` - optional через flags.1
  - `entities`: `flags.1?Vector` - optional через flags.1
  - `privacy_rules`: `flags.2?Vector` - optional через flags.2

### `stories.exportStoryLink`

- Кратко: Экспортировать историю ссылку.
- ID: `2072899360` / `0x7b8def20`
- Return type: `ExportedStoryLink`
- Сигнатура: `stories.exportStoryLink(peer:InputPeer, id:int) -> ExportedStoryLink`
- Официальная страница: https://core.telegram.org/method/stories.exportStoryLink
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `int`

### `stories.getAlbumStories`

- Кратко: Получить album истории.
- ID: `-1400869535` / `0xac806d61`
- Return type: `stories.Stories`
- Сигнатура: `stories.getAlbumStories(peer:InputPeer, album_id:int, offset:int, limit:int) -> stories.Stories`
- Официальная страница: https://core.telegram.org/method/stories.getAlbumStories
- Параметры:
  - `peer`: `InputPeer`
  - `album_id`: `int`
  - `offset`: `int`
  - `limit`: `int`

### `stories.getAlbums`

- Кратко: Получить albums.
- ID: `632548039` / `0x25b3eac7`
- Return type: `stories.Albums`
- Сигнатура: `stories.getAlbums(peer:InputPeer, hash:long) -> stories.Albums`
- Официальная страница: https://core.telegram.org/method/stories.getAlbums
- Параметры:
  - `peer`: `InputPeer`
  - `hash`: `long`

### `stories.getAllReadPeerStories`

- Кратко: Получить все прочтение peer/диалог истории.
- ID: `-1688541191` / `0x9b5ae7f9`
- Return type: `Updates`
- Сигнатура: `stories.getAllReadPeerStories() -> Updates`
- Официальная страница: https://core.telegram.org/method/stories.getAllReadPeerStories
- Параметры:
  - Нет параметров.

### `stories.getAllStories`

- Кратко: Получить все истории.
- ID: `-290400731` / `0xeeb0d625`
- Return type: `stories.AllStories`
- Сигнатура: `stories.getAllStories(flags:#, next:flags.1?true, hidden:flags.2?true, state:flags.0?string) -> stories.AllStories`
- Официальная страница: https://core.telegram.org/method/stories.getAllStories
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `next`: `flags.1?true` - optional через flags.1
  - `hidden`: `flags.2?true` - optional через flags.2
  - `state`: `flags.0?string` - optional через flags.0

### `stories.getChatsToSend`

- Кратко: Получить чаты to send.
- ID: `-1519744160` / `0xa56a8b60`
- Return type: `messages.Chats`
- Сигнатура: `stories.getChatsToSend() -> messages.Chats`
- Официальная страница: https://core.telegram.org/method/stories.getChatsToSend
- Параметры:
  - Нет параметров.

### `stories.getPeerMaxIDs`

- Кратко: Получить peer/диалог max i ds.
- ID: `1398375363` / `0x535983c3`
- Return type: `Vector`
- Сигнатура: `stories.getPeerMaxIDs(id:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/stories.getPeerMaxIDs
- Параметры:
  - `id`: `Vector`

### `stories.getPeerStories`

- Кратко: Получить peer/диалог истории.
- ID: `743103056` / `0x2c4ada50`
- Return type: `stories.PeerStories`
- Сигнатура: `stories.getPeerStories(peer:InputPeer) -> stories.PeerStories`
- Официальная страница: https://core.telegram.org/method/stories.getPeerStories
- Параметры:
  - `peer`: `InputPeer`

### `stories.getPinnedStories`

- Кратко: Получить закреплённое истории.
- ID: `1478600156` / `0x5821a5dc`
- Return type: `stories.Stories`
- Сигнатура: `stories.getPinnedStories(peer:InputPeer, offset_id:int, limit:int) -> stories.Stories`
- Официальная страница: https://core.telegram.org/method/stories.getPinnedStories
- Параметры:
  - `peer`: `InputPeer`
  - `offset_id`: `int`
  - `limit`: `int`

### `stories.getStoriesArchive`

- Кратко: Получить истории архив.
- ID: `-1271586794` / `0xb4352016`
- Return type: `stories.Stories`
- Сигнатура: `stories.getStoriesArchive(peer:InputPeer, offset_id:int, limit:int) -> stories.Stories`
- Официальная страница: https://core.telegram.org/method/stories.getStoriesArchive
- Параметры:
  - `peer`: `InputPeer`
  - `offset_id`: `int`
  - `limit`: `int`

### `stories.getStoriesByID`

- Кратко: Получить истории by id.
- ID: `1467271796` / `0x5774ca74`
- Return type: `stories.Stories`
- Сигнатура: `stories.getStoriesByID(peer:InputPeer, id:Vector) -> stories.Stories`
- Официальная страница: https://core.telegram.org/method/stories.getStoriesByID
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`

### `stories.getStoriesViews`

- Кратко: Получить истории просмотры.
- ID: `685862088` / `0x28e16cc8`
- Return type: `stories.StoryViews`
- Сигнатура: `stories.getStoriesViews(peer:InputPeer, id:Vector) -> stories.StoryViews`
- Официальная страница: https://core.telegram.org/method/stories.getStoriesViews
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`

### `stories.getStoryReactionsList`

- Кратко: Получить историю реакции список.
- ID: `-1179482081` / `0xb9b2881f`
- Return type: `stories.StoryReactionsList`
- Сигнатура: `stories.getStoryReactionsList(flags:#, forwards_first:flags.2?true, peer:InputPeer, id:int, reaction:flags.0?Reaction, offset:flags.1?string, limit:int) -> stories.StoryReactionsList`
- Официальная страница: https://core.telegram.org/method/stories.getStoryReactionsList
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `forwards_first`: `flags.2?true` - optional через flags.2
  - `peer`: `InputPeer`
  - `id`: `int`
  - `reaction`: `flags.0?Reaction` - optional через flags.0
  - `offset`: `flags.1?string` - optional через flags.1
  - `limit`: `int`

### `stories.getStoryViewsList`

- Кратко: Получить историю просмотры список.
- ID: `2127707223` / `0x7ed23c57`
- Return type: `stories.StoryViewsList`
- Сигнатура: `stories.getStoryViewsList(flags:#, just_contacts:flags.0?true, reactions_first:flags.2?true, forwards_first:flags.3?true, peer:InputPeer, q:flags.1?string, id:int, offset:string, limit:int) -> stories.StoryViewsList`
- Официальная страница: https://core.telegram.org/method/stories.getStoryViewsList
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `just_contacts`: `flags.0?true` - optional через flags.0
  - `reactions_first`: `flags.2?true` - optional через flags.2
  - `forwards_first`: `flags.3?true` - optional через flags.3
  - `peer`: `InputPeer`
  - `q`: `flags.1?string` - optional через flags.1
  - `id`: `int`
  - `offset`: `string`
  - `limit`: `int`

### `stories.incrementStoryViews`

- Кратко: Операция с increment историю просмотры.
- ID: `-1308456197` / `0xb2028afb`
- Return type: `Bool`
- Сигнатура: `stories.incrementStoryViews(peer:InputPeer, id:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/stories.incrementStoryViews
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`

### `stories.readStories`

- Кратко: Пометить как прочитанное / прочитать истории.
- ID: `-1521034552` / `0xa556dac8`
- Return type: `Vector`
- Сигнатура: `stories.readStories(peer:InputPeer, max_id:int) -> Vector`
- Официальная страница: https://core.telegram.org/method/stories.readStories
- Параметры:
  - `peer`: `InputPeer`
  - `max_id`: `int`

### `stories.reorderAlbums`

- Кратко: Изменить порядок albums.
- ID: `-2060059687` / `0x8535fbd9`
- Return type: `Bool`
- Сигнатура: `stories.reorderAlbums(peer:InputPeer, order:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/stories.reorderAlbums
- Параметры:
  - `peer`: `InputPeer`
  - `order`: `Vector`

### `stories.report`

- Кратко: Пожаловаться / сообщить о данными.
- ID: `433646405` / `0x19d8eb45`
- Return type: `ReportResult`
- Сигнатура: `stories.report(peer:InputPeer, id:Vector, option:bytes, message:string) -> ReportResult`
- Официальная страница: https://core.telegram.org/method/stories.report
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`
  - `option`: `bytes`
  - `message`: `string`

### `stories.searchPosts`

- Кратко: Искать posts.
- ID: `-780072697` / `0xd1810907`
- Return type: `stories.FoundStories`
- Сигнатура: `stories.searchPosts(flags:#, hashtag:flags.0?string, area:flags.1?MediaArea, peer:flags.2?InputPeer, offset:string, limit:int) -> stories.FoundStories`
- Официальная страница: https://core.telegram.org/method/stories.searchPosts
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `hashtag`: `flags.0?string` - optional через flags.0
  - `area`: `flags.1?MediaArea` - optional через flags.1
  - `peer`: `flags.2?InputPeer` - optional через flags.2
  - `offset`: `string`
  - `limit`: `int`

### `stories.sendReaction`

- Кратко: Отправить реакцию.
- ID: `2144810674` / `0x7fd736b2`
- Return type: `Updates`
- Сигнатура: `stories.sendReaction(flags:#, add_to_recent:flags.0?true, peer:InputPeer, story_id:int, reaction:Reaction) -> Updates`
- Официальная страница: https://core.telegram.org/method/stories.sendReaction
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `add_to_recent`: `flags.0?true` - optional через flags.0
  - `peer`: `InputPeer`
  - `story_id`: `int`
  - `reaction`: `Reaction`

### `stories.sendStory`

- Кратко: Отправить историю.
- ID: `1937752812` / `0x737fc2ec`
- Return type: `Updates`
- Сигнатура: `stories.sendStory(flags:#, pinned:flags.2?true, noforwards:flags.4?true, fwd_modified:flags.7?true, peer:InputPeer, media:InputMedia, media_areas:flags.5?Vector, caption:flags.0?string, entities:flags.1?Vector, privacy_rules:Vector, random_id:long, period:flags.3?int, fwd_from_id:flags.6?InputPeer, fwd_from_story:flags.6?int, albums:flags.8?Vector) -> Updates`
- Официальная страница: https://core.telegram.org/method/stories.sendStory
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `pinned`: `flags.2?true` - optional через flags.2
  - `noforwards`: `flags.4?true` - optional через flags.4
  - `fwd_modified`: `flags.7?true` - optional через flags.7
  - `peer`: `InputPeer`
  - `media`: `InputMedia`
  - `media_areas`: `flags.5?Vector` - optional через flags.5
  - `caption`: `flags.0?string` - optional через flags.0
  - `entities`: `flags.1?Vector` - optional через flags.1
  - `privacy_rules`: `Vector`
  - `random_id`: `long`
  - `period`: `flags.3?int` - optional через flags.3
  - `fwd_from_id`: `flags.6?InputPeer` - optional через flags.6
  - `fwd_from_story`: `flags.6?int` - optional через flags.6
  - `albums`: `flags.8?Vector` - optional через flags.8

### `stories.toggleAllStoriesHidden`

- Кратко: Включить/выключить all истории hidden.
- ID: `2082822084` / `0x7c2557c4`
- Return type: `Bool`
- Сигнатура: `stories.toggleAllStoriesHidden(hidden:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/stories.toggleAllStoriesHidden
- Параметры:
  - `hidden`: `Bool`

### `stories.togglePeerStoriesHidden`

- Кратко: Включить/выключить peer/диалог истории hidden.
- ID: `-1123805756` / `0xbd0415c4`
- Return type: `Bool`
- Сигнатура: `stories.togglePeerStoriesHidden(peer:InputPeer, hidden:Bool) -> Bool`
- Официальная страница: https://core.telegram.org/method/stories.togglePeerStoriesHidden
- Параметры:
  - `peer`: `InputPeer`
  - `hidden`: `Bool`

### `stories.togglePinned`

- Кратко: Включить/выключить закреплённое.
- ID: `-1703566865` / `0x9a75a1ef`
- Return type: `Vector`
- Сигнатура: `stories.togglePinned(peer:InputPeer, id:Vector, pinned:Bool) -> Vector`
- Официальная страница: https://core.telegram.org/method/stories.togglePinned
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`
  - `pinned`: `Bool`

### `stories.togglePinnedToTop`

- Кратко: Включить/выключить закреплённое to верх.
- ID: `187268763` / `0x0b297e9b`
- Return type: `Bool`
- Сигнатура: `stories.togglePinnedToTop(peer:InputPeer, id:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/stories.togglePinnedToTop
- Параметры:
  - `peer`: `InputPeer`
  - `id`: `Vector`

### `stories.updateAlbum`

- Кратко: Обновить album.
- ID: `1582455222` / `0x5e5259b6`
- Return type: `StoryAlbum`
- Сигнатура: `stories.updateAlbum(flags:#, peer:InputPeer, album_id:int, title:flags.0?string, delete_stories:flags.1?Vector, add_stories:flags.2?Vector, order:flags.3?Vector) -> StoryAlbum`
- Официальная страница: https://core.telegram.org/method/stories.updateAlbum
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `peer`: `InputPeer`
  - `album_id`: `int`
  - `title`: `flags.0?string` - optional через flags.0
  - `delete_stories`: `flags.1?Vector` - optional через flags.1
  - `add_stories`: `flags.2?Vector` - optional через flags.2
  - `order`: `flags.3?Vector` - optional через flags.3

## updates

### `updates.getChannelDifference`

- Кратко: Получить канал разницу.
- ID: `51854712` / `0x03173d78`
- Return type: `updates.ChannelDifference`
- Сигнатура: `updates.getChannelDifference(flags:#, force:flags.0?true, channel:InputChannel, filter:ChannelMessagesFilter, pts:int, limit:int) -> updates.ChannelDifference`
- Официальная страница: https://core.telegram.org/method/updates.getChannelDifference
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `force`: `flags.0?true` - optional через flags.0
  - `channel`: `InputChannel`
  - `filter`: `ChannelMessagesFilter`
  - `pts`: `int`
  - `limit`: `int`

### `updates.getDifference`

- Кратко: Получить разницу.
- ID: `432207715` / `0x19c2f763`
- Return type: `updates.Difference`
- Сигнатура: `updates.getDifference(flags:#, pts:int, pts_limit:flags.1?int, pts_total_limit:flags.0?int, date:int, qts:int, qts_limit:flags.2?int) -> updates.Difference`
- Официальная страница: https://core.telegram.org/method/updates.getDifference
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `pts`: `int`
  - `pts_limit`: `flags.1?int` - optional через flags.1
  - `pts_total_limit`: `flags.0?int` - optional через flags.0
  - `date`: `int`
  - `qts`: `int`
  - `qts_limit`: `flags.2?int` - optional через flags.2

### `updates.getState`

- Кратко: Получить state.
- ID: `-304838614` / `0xedd4882a`
- Return type: `updates.State`
- Сигнатура: `updates.getState() -> updates.State`
- Официальная страница: https://core.telegram.org/method/updates.getState
- Параметры:
  - Нет параметров.

## upload

### `upload.getCdnFile`

- Кратко: Получить cdn файл.
- ID: `962554330` / `0x395f69da`
- Return type: `upload.CdnFile`
- Сигнатура: `upload.getCdnFile(file_token:bytes, offset:long, limit:int) -> upload.CdnFile`
- Официальная страница: https://core.telegram.org/method/upload.getCdnFile
- Параметры:
  - `file_token`: `bytes`
  - `offset`: `long`
  - `limit`: `int`

### `upload.getCdnFileHashes`

- Кратко: Получить cdn файл hashes.
- ID: `-1847836879` / `0x91dc3f31`
- Return type: `Vector`
- Сигнатура: `upload.getCdnFileHashes(file_token:bytes, offset:long) -> Vector`
- Официальная страница: https://core.telegram.org/method/upload.getCdnFileHashes
- Параметры:
  - `file_token`: `bytes`
  - `offset`: `long`

### `upload.getFile`

- Кратко: Получить файл.
- ID: `-1101843010` / `0xbe5335be`
- Return type: `upload.File`
- Сигнатура: `upload.getFile(flags:#, precise:flags.0?true, cdn_supported:flags.1?true, location:InputFileLocation, offset:long, limit:int) -> upload.File`
- Официальная страница: https://core.telegram.org/method/upload.getFile
- Параметры:
  - `flags`: `#` - служебное поле flags
  - `precise`: `flags.0?true` - optional через flags.0
  - `cdn_supported`: `flags.1?true` - optional через flags.1
  - `location`: `InputFileLocation`
  - `offset`: `long`
  - `limit`: `int`

### `upload.getFileHashes`

- Кратко: Получить файл hashes.
- ID: `-1856595926` / `0x9156982a`
- Return type: `Vector`
- Сигнатура: `upload.getFileHashes(location:InputFileLocation, offset:long) -> Vector`
- Официальная страница: https://core.telegram.org/method/upload.getFileHashes
- Параметры:
  - `location`: `InputFileLocation`
  - `offset`: `long`

### `upload.getWebFile`

- Кратко: Получить веб файл.
- ID: `619086221` / `0x24e6818d`
- Return type: `upload.WebFile`
- Сигнатура: `upload.getWebFile(location:InputWebFileLocation, offset:int, limit:int) -> upload.WebFile`
- Официальная страница: https://core.telegram.org/method/upload.getWebFile
- Параметры:
  - `location`: `InputWebFileLocation`
  - `offset`: `int`
  - `limit`: `int`

### `upload.reuploadCdnFile`

- Кратко: Операция с reupload cdn файл.
- ID: `-1691921240` / `0x9b2754a8`
- Return type: `Vector`
- Сигнатура: `upload.reuploadCdnFile(file_token:bytes, request_token:bytes) -> Vector`
- Официальная страница: https://core.telegram.org/method/upload.reuploadCdnFile
- Параметры:
  - `file_token`: `bytes`
  - `request_token`: `bytes`

### `upload.saveBigFilePart`

- Кратко: Сохранить big файл part.
- ID: `-562337987` / `0xde7b673d`
- Return type: `Bool`
- Сигнатура: `upload.saveBigFilePart(file_id:long, file_part:int, file_total_parts:int, bytes:bytes) -> Bool`
- Официальная страница: https://core.telegram.org/method/upload.saveBigFilePart
- Параметры:
  - `file_id`: `long`
  - `file_part`: `int`
  - `file_total_parts`: `int`
  - `bytes`: `bytes`

### `upload.saveFilePart`

- Кратко: Сохранить файл part.
- ID: `-1291540959` / `0xb304a621`
- Return type: `Bool`
- Сигнатура: `upload.saveFilePart(file_id:long, file_part:int, bytes:bytes) -> Bool`
- Официальная страница: https://core.telegram.org/method/upload.saveFilePart
- Параметры:
  - `file_id`: `long`
  - `file_part`: `int`
  - `bytes`: `bytes`

## users

### `users.getFullUser`

- Кратко: Получить полную информацию о пользователя.
- ID: `-1240508136` / `0xb60f5918`
- Return type: `users.UserFull`
- Сигнатура: `users.getFullUser(id:InputUser) -> users.UserFull`
- Официальная страница: https://core.telegram.org/method/users.getFullUser
- Параметры:
  - `id`: `InputUser`

### `users.getRequirementsToContact`

- Кратко: Получить требования to контакт.
- ID: `-660962397` / `0xd89a83a3`
- Return type: `Vector`
- Сигнатура: `users.getRequirementsToContact(id:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/users.getRequirementsToContact
- Параметры:
  - `id`: `Vector`

### `users.getSavedMusic`

- Кратко: Получить сохранённые музыку.
- ID: `2022539235` / `0x788d7fe3`
- Return type: `users.SavedMusic`
- Сигнатура: `users.getSavedMusic(id:InputUser, offset:int, limit:int, hash:long) -> users.SavedMusic`
- Официальная страница: https://core.telegram.org/method/users.getSavedMusic
- Параметры:
  - `id`: `InputUser`
  - `offset`: `int`
  - `limit`: `int`
  - `hash`: `long`

### `users.getSavedMusicByID`

- Кратко: Получить сохранённые музыку by id.
- ID: `1970513129` / `0x7573a4e9`
- Return type: `users.SavedMusic`
- Сигнатура: `users.getSavedMusicByID(id:InputUser, documents:Vector) -> users.SavedMusic`
- Официальная страница: https://core.telegram.org/method/users.getSavedMusicByID
- Параметры:
  - `id`: `InputUser`
  - `documents`: `Vector`

### `users.getUsers`

- Кратко: Получить пользователей.
- ID: `227648840` / `0x0d91a548`
- Return type: `Vector`
- Сигнатура: `users.getUsers(id:Vector) -> Vector`
- Официальная страница: https://core.telegram.org/method/users.getUsers
- Параметры:
  - `id`: `Vector`

### `users.setSecureValueErrors`

- Кратко: Установить secure value errors.
- ID: `-1865902923` / `0x90c894b5`
- Return type: `Bool`
- Сигнатура: `users.setSecureValueErrors(id:InputUser, errors:Vector) -> Bool`
- Официальная страница: https://core.telegram.org/method/users.setSecureValueErrors
- Параметры:
  - `id`: `InputUser`
  - `errors`: `Vector`
