微信目录结构

├── 3rd
│   ├── CrashReporter
│   │   ├── google
│   │   │   └── protobuf-c
│   │   │       └── protobuf-c.c
│   │   └── source
│   │       └── PLCrashLogWriter.m
│   └── wtlogin
│       ├── Comm
│       │   └── Wl_Reachability.m
│       ├── KeyWrapper
│       │   └── SafeSingleItemWrapper.m
│       ├── MemManager
│       │   ├── MemAppidSigManager.m
│       │   ├── MemSigManager.m
│       │   └── MemUserAppidSig.m
│       ├── PlatformInfo
│       │   └── WtloginPlatformInfo.m
│       ├── WTLoginApi.m
│       └── WloginProtocol
│           ├── Tlv
│           │   ├── WloginTlv.m
│           │   ├── WloginTlv_0x100.m
│           │   ├── WloginTlv_0x107.m
│           │   ├── WloginTlv_0x116.m
│           │   ├── WloginTlv_0x118.m
│           │   ├── WloginTlv_0x11a.m
│           │   ├── WloginTlv_0x11b.m
│           │   ├── WloginTlv_0x129.m
│           │   ├── WloginTlv_0x132.m
│           │   ├── WloginTlv_0x141.m
│           │   ├── WloginTlv_0x142.m
│           │   ├── WloginTlv_0x147.m
│           │   ├── WloginTlv_0x148.m
│           │   ├── WloginTlv_0x153.m
│           │   ├── WloginTlv_0x166.m
│           │   ├── WloginTlv_0x18.m
│           │   ├── WloginTlv_0x2.m
│           │   └── WloginTlv_0xa.m
│           ├── WloginPkgHead.m
│           └── WloginProtocol.m
├── DTCoreTextWrapper
│   └── DTCoreText
│       ├── HTML\ Parsing
│       │   ├── DTCoreTextFunctions.m
│       │   ├── DTHTMLAttributedStringBuilder.m
│       │   ├── DTHTMLElement
│       │   │   └── DTHTMLElement.m
│       │   └── DTTextAttachment
│       │       └── DTTextAttachment.m
│       ├── Layouting
│       │   └── DTCoreTextGlyphRun.m
│       └── UI
│           ├── DTAttributedTextCell.m
│           └── DTLazyImageView.m
├── MMApp
│   ├── AppUtil.mm
│   ├── BackgroundTask.mm
│   ├── FunctionSwitchUtil.mm
│   ├── MicroMessengerAppDelegate.mm
│   ├── SettingUtil.mm
│   └── UiUtil.mm
├── MMCommon
│   └── MMCommonAdapter.mm
├── MMControl
│   ├── ActionSheet
│   │   ├── MMActionSheet.mm
│   │   ├── MMIconActionSheet.mm
│   │   └── WCActionSheet.mm
│   ├── AutoLayout
│   │   └── UIView+AutoLayout.mm
│   ├── BlurEffect
│   │   └── UIView+BlurEffect.mm
│   ├── ControlUtil.mm
│   ├── CoolAnimation
│   │   └── UIView+Genie.mm
│   ├── FlowComponent
│   │   └── Control
│   │       └── WCBaseControlLogic.mm
│   ├── HeadImage
│   │   ├── MMBrandHeadImageView.mm
│   │   └── MMHeadImageView.mm
│   ├── ImageLoader
│   │   ├── MMBatchImageLoader.mm
│   │   ├── MMCDNImageView.mm
│   │   ├── MMImageLoader.mm
│   │   └── MMImageLoadingTask.mm
│   ├── MMImagePicker
│   │   ├── MMAlbumDataProvider.mm
│   │   ├── MMAsset.mm
│   │   ├── MMAssetForALAssetLibrary.mm
│   │   ├── MMAssetForPHAssetFramework.mm
│   │   ├── MMAssetMgr.mm
│   │   ├── MMAssetPickerController.mm
│   │   ├── MMAssetView.mm
│   │   ├── MMImagePickerManager.mm
│   │   ├── MMImagePreviewBrowserController.mm
│   │   ├── MMImageUtil.mm
│   │   ├── MMVideoCompressHelper.mm
│   │   └── MMVideoPreviewBrowserController.mm
│   ├── MMTableView
│   │   └── MMTableViewCellInfo.mm
│   ├── MMUIWindow
│   │   ├── MMToastViewController.mm
│   │   ├── MMWindowController.mm
│   │   └── MMWindowMgr.mm
│   ├── MMVoiceSearchBar
│   │   └── MMVoiceSearchBar.mm
│   ├── MediaPlayer
│   │   └── MMMPMoviePlayerController.mm
│   ├── RichText
│   │   ├── CTRichTextView.mm
│   │   ├── Parsers
│   │   │   ├── BoldTextParser.mm
│   │   │   ├── ImageParser.mm
│   │   │   ├── LinkAnchorParser.mm
│   │   │   ├── LinkTextParser.mm
│   │   │   ├── PhoneNumberParser.mm
│   │   │   ├── TextParser.mm
│   │   │   ├── WCCustomImgParser.mm
│   │   │   └── WCCustomLinkParser.mm
│   │   ├── PatternGenerator
│   │   │   └── StylePatternGenerator.mm
│   │   └── RichTextView.mm
│   ├── ScrollView
│   │   └── SequencePageScrollView.mm
│   ├── VideoControl
│   │   └── MMMoviePlayerController.mm
│   └── common
│       ├── AsyncImageView.mm
│       ├── MMGrowTextView.mm
│       ├── MMImageScrollViewHelper.mm
│       ├── MMListViewController.mm
│       ├── MMLoadingView.mm
│       ├── MMMultiMenuTableViewCell.mm
│       ├── MMPhoneNumberHandler.mm
│       ├── MMPickerView.mm
│       ├── MMProgressViewEx.mm
│       ├── MMRegionPickerViewController.mm
│       ├── MMTabBarBaseViewController.mm
│       ├── MMTableView.mm
│       ├── MMTextView.mm
│       ├── MMUIControlEvent.m
│       ├── MMUITextView.mm
│       ├── MMUIViewController.mm
│       ├── MMUIWindow.mm
│       └── MMURLHandler.mm
├── MMFoundation
│   ├── AccountStorage
│   │   ├── AccountStorageMgr.mm
│   │   ├── Setting.mm
│   │   ├── SettingExt.mm
│   │   └── UpdateInfo.mm
│   ├── AudioService
│   │   ├── AudioControl
│   │   │   ├── RemoteControlCheck.mm
│   │   │   └── SysCallCheck.mm
│   │   ├── AudioDevice
│   │   │   ├── AUAudioDevice.mm
│   │   │   └── PCMAudioFile.mm
│   │   ├── AudioFile.mm
│   │   ├── AudioHelper.mm
│   │   ├── AudioPlayer
│   │   │   ├── AMRAudioPlayer.mm
│   │   │   ├── AQAudioPlayer.mm
│   │   │   ├── BaseAudioPlayer.mm
│   │   │   ├── SPXAudioPlayer.mm
│   │   │   └── SilkAudioPlayer.mm
│   │   ├── AudioRecorder
│   │   │   ├── AMRAudioRecorder.mm
│   │   │   ├── AQAudioRecorder.mm
│   │   │   ├── BaseAudioRecorder.mm
│   │   │   ├── SPXAudioRecorder.mm
│   │   │   └── SilkAudioRecorder.mm
│   │   ├── MMAudioSession.mm
│   │   └── MusicPlayer
│   │       ├── MMAudioDataPipe.m
│   │       ├── MMAudioStreamPlayer.m
│   │       ├── MMMusicPlayer.mm
│   │       └── MMMusicPlayerMgr.mm
│   ├── BaseEvent
│   │   ├── BaseEvent.mm
│   │   ├── MultiEvent.mm
│   │   └── ProtobufEvent.mm
│   ├── BaseProtocol
│   │   ├── CdnChannel.mm
│   │   ├── ProtobufPrtlChannel.mm
│   │   ├── StructCommon.mm
│   │   └── UrlChannel.mm
│   ├── CdnCom
│   │   └── CdnComMgr.mm
│   ├── CleanService
│   │   ├── CleanCacheService.mm
│   │   └── DeletePathService.mm
│   ├── ConfigMgr
│   │   ├── MMConfigMgr+Extend.mm
│   │   └── MMConfigMgr.mm
│   ├── EventService
│   │   ├── EventService+CreateEvent.mm
│   │   └── EventService.mm
│   ├── International
│   │   ├── MMLanguageMgr.mm
│   │   ├── MMLanguagePackageDownloadMgr.mm
│   │   ├── MMRegionCodeMgr.mm
│   │   └── MMRegionPackageDownloadMgr.mm
│   ├── Location
│   │   ├── LocationRetriever.mm
│   │   ├── MMLocationDB+WCDB.mm
│   │   └── MMLocationMgr.mm
│   ├── MMDB
│   │   ├── MMDB.mm
│   │   └── WCDB
│   │       ├── OpLogDB.mm
│   │       └── WCDB.mm
│   ├── MMEvent
│   │   ├── Event
│   │   │   ├── LocalOpEvent
│   │   │   │   └── ChatStatusEvent.mm
│   │   │   └── NetworkEvent
│   │   │       ├── AuthEvent.mm
│   │   │       ├── BindQQEvent.mm
│   │   │       ├── CheckQQEvent.mm
│   │   │       ├── GetImgEvent
│   │   │       │   └── GetImgEvent.mm
│   │   │       ├── SearchContactEvent.mm
│   │   │       └── SendMesEvent
│   │   │           ├── ImplSendEvent.mm
│   │   │           └── SendMesEvent.mm
│   │   ├── NewReg
│   │   │   └── NewRegPrtl.mm
│   │   ├── NewSync
│   │   │   ├── GetBottleContactEvent.mm
│   │   │   ├── GetQQEvent.mm
│   │   │   ├── GetSxEvent.mm
│   │   │   ├── ImplSpecialSyncEvent.mm
│   │   │   ├── MsgHelper.mm
│   │   │   ├── NewInitEvent.mm
│   │   │   ├── NewInitPrtl.mm
│   │   │   ├── NewSyncEvent.mm
│   │   │   ├── NewSyncHandler.mm
│   │   │   ├── NewSyncPrtl.mm
│   │   │   ├── SpecialSyncPrtl.mm
│   │   │   ├── SyncBaseEvent.mm
│   │   │   └── SyncBasePrtl.mm
│   │   └── Protocol
│   │       ├── AuthPrtl.mm
│   │       ├── BindQQPrtl.mm
│   │       ├── CheckQQPrtl.mm
│   │       ├── GetImgPrtl.mm
│   │       ├── GetVerifyImgPrtl.mm
│   │       ├── LBSFindPrtl.mm
│   │       ├── NewInviteFriendPrtl.mm
│   │       ├── SearchContactPrtl.mm
│   │       ├── SendCardPrtl.mm
│   │       ├── SendMesPrtl.mm
│   │       ├── SwitchPushMailPrtl.mm
│   │       └── VerifyEmailPrtl.mm
│   ├── MMFastImageCache
│   │   ├── FICExtension
│   │   │   └── MMFICTimelinePreviewImg.mm
│   │   ├── MMFICImageTable.mm
│   │   ├── MMFICImageTableChunk.m
│   │   ├── MMFICImageTableEntry.m
│   │   ├── MMFICImageTableMetadata.mm
│   │   └── MMFICUtilities.mm
│   ├── MMNetWork
│   │   ├── AsyncSocket.m
│   │   ├── CmdID.mm
│   │   ├── IDCHostMgr.mm
│   │   ├── MMHeader.mm
│   │   ├── RsaCert
│   │   │   └── RsaCertMgr.mm
│   │   └── SvrError
│   │       └── SvrErrorMgr.mm
│   ├── MMOSS
│   │   ├── ABtest
│   │   │   ├── ABtestMgr.mm
│   │   │   └── ABtestPoint.mm
│   │   ├── BlockMonitor
│   │   │   ├── MMCheckDumpViewController.mm
│   │   │   ├── MMDumpReportTask.mm
│   │   │   ├── MMDumpReporterMgr.mm
│   │   │   ├── MMMonitorConfigMgr.mm
│   │   │   ├── MMMonitorMgr+CallStack.m
│   │   │   └── MMMonitorMgr.mm
│   │   ├── ClickStream
│   │   │   └── ClickStreamMgr.mm
│   │   ├── Console
│   │   │   ├── MMLogViewController.mm
│   │   │   ├── MMShowLogViewController.mm
│   │   │   └── iConsoleWindow.mm
│   │   ├── DatabaseRecover
│   │   │   ├── MMDBRConfig.mm
│   │   │   ├── MMDBRDetector.mm
│   │   │   ├── MMDBRRepairer.mm
│   │   │   ├── MMDBRReporter.mm
│   │   │   ├── MMDBRecoverViewController.mm
│   │   │   ├── MMDatabaseRecoverMgr+Util.mm
│   │   │   └── MMDatabaseRecoverMgr.mm
│   │   ├── DiskUsage
│   │   │   ├── ClearData
│   │   │   │   ├── ClearDataMgr.mm
│   │   │   │   └── ScanAppSpaceSizeService.mm
│   │   │   └── DiskUsageScan
│   │   │       ├── MMDiskBizUsageHandler.mm
│   │   │       ├── MMDiskUsageConfigHandler.mm
│   │   │       ├── MMDiskUsageMgr.mm
│   │   │       ├── MMDiskUsageReporter.mm
│   │   │       ├── MMDiskUsageScaner.mm
│   │   │       └── MMDiskUsageUtil.mm
│   │   ├── FlowStat
│   │   │   ├── FlowStat.mm
│   │   │   └── FlowStatDB.mm
│   │   ├── LogReport
│   │   │   └── LogReportMgr.mm
│   │   ├── PerformenceDataReport
│   │   │   └── MMPerformanceDataReportMgr.mm
│   │   ├── PowerMonitor
│   │   │   └── MMPowerMgr+Memory.m
│   │   └── StatReport
│   │       └── StatReportMgr.mm
│   ├── MMSvrKit
│   │   └── CommNew
│   │       ├── mergekeyforcli.mm
│   │       └── sk_mmmicromsgstruct_iphone.cpp
│   ├── MainControll.mm
│   ├── NetworkStatus
│   │   └── NetworkStatusMgr.mm
│   ├── NewSyncService
│   │   ├── NewSyncPlugin
│   │   │   └── NewSyncPluginMgr.mm
│   │   ├── NewSyncService.mm
│   │   ├── OplogDataLogic.mm
│   │   └── OplogEventHandler.mm
│   ├── PackageDownload
│   │   ├── MMPackageDownloadMgr.mm
│   │   └── MMPackageListDownloadEventHandler.mm
│   ├── Plugin
│   │   └── PluginUtil.mm
│   ├── Sight
│   │   ├── Components
│   │   │   ├── MMQRCodeScanner.mm
│   │   │   ├── MMQRStrokeView.mm
│   │   │   ├── MMovieCompressor.mm
│   │   │   └── MMovieDecoder.mm
│   │   ├── SightCameraCapture.mm
│   │   ├── SightMovieWriterF2.mm
│   │   ├── SightPreviewViewF2.mm
│   │   └── SightUtils.mm
│   ├── Tokenizer
│   │   ├── OneOrBinaryTokenizer.mm
│   │   ├── TokenizerRegister.mm
│   │   └── TokenizerUtil.mm
│   ├── Util
│   │   ├── DownloadFile.mm
│   │   ├── JailBreakHelper.mm
│   │   ├── MMKeychain.mm
│   │   ├── MMKeychainManager.mm
│   │   ├── ResourceMonitor.mm
│   │   └── Utility.mm
│   └── WTLogin
│       └── WTLoginMgr.mm
├── MMMain
│   ├── Audio
│   │   └── Model
│   │       ├── AudioReceiver.mm
│   │       └── AudioSender.mm
│   ├── BakChat
│   │   ├── Controller
│   │   │   ├── BakChatListViewController.mm
│   │   │   └── BakChatUploadSelecteSessionViewController.mm
│   │   └── Model
│   │       ├── BakChatAESDecrypt.mm
│   │       ├── BakChatBaseMethodHelper.mm
│   │       ├── BakChatRecoverFileHelper.mm
│   │       ├── BakChatRecoverMgr.mm
│   │       ├── BakChatRecoverNetworkHelper.mm
│   │       ├── BakChatUploadBreakPointStruct.mm
│   │       ├── BakChatUploadMgr.mm
│   │       └── BakChatUploadNetworkHelper.mm
│   ├── CameraScan
│   │   ├── Common
│   │   │   ├── Controller
│   │   │   │   ├── BaseScanLogicController.mm
│   │   │   │   ├── CameraConfig.mm
│   │   │   │   ├── CameraScanViewController.mm
│   │   │   │   ├── MotionDetector.mm
│   │   │   │   └── UploadDetectLogic.mm
│   │   │   └── View
│   │   │       └── CameraScannerView.mm
│   │   ├── OCRTrans
│   │   │   ├── Controller
│   │   │   │   └── OCRTransLogicController.mm
│   │   │   └── Model
│   │   │       └── OCRTransMgr.mm
│   │   ├── ProductDetail
│   │   │   └── Model
│   │   │       └── ScanStatMgr.mm
│   │   ├── QRCode
│   │   │   ├── Controller
│   │   │   │   ├── QRCodeViewController.mm
│   │   │   │   └── VcardViewController.mm
│   │   │   └── Model
│   │   │       ├── GetA8KeyLogic.mm
│   │   │       ├── MMQRCodeMgr.mm
│   │   │       └── MMVcardItem.mm
│   │   ├── ScanBarCode
│   │   │   └── Model
│   │   │       └── ScanBarcodeMgr.mm
│   │   ├── ScanBook
│   │   │   ├── Controller
│   │   │   │   └── ScanBookLogicController.mm
│   │   │   ├── Model
│   │   │   │   ├── ScanBookMgr.mm
│   │   │   │   └── ScanBookStorage.mm
│   │   │   └── View
│   │   │       └── BookScanner.mm
│   │   ├── ScanQRCode
│   │   │   ├── Controller
│   │   │   │   └── ScanQRCodeLogicController.mm
│   │   │   └── View
│   │   │       └── NewQRCodeScanner.mm
│   │   ├── ScanStreetView
│   │   │   ├── Controller
│   │   │   │   └── ScanStreetViewLogicController.mm
│   │   │   └── Model
│   │   │       ├── ScanStreetViewMgr.mm
│   │   │       └── StreetViewResult.mm
│   │   └── ScanTV
│   │       ├── Controller
│   │       │   └── ScanTVLogicController.mm
│   │       └── Model
│   │           └── ScanTVHelper.mm
│   ├── ClearData
│   │   └── Controller
│   │       └── MsgResourceBrowseViewController.mm
│   ├── Contacts
│   │   ├── Controller
│   │   │   ├── BrandContactsViewController.mm
│   │   │   ├── ContactNoWeixinViewController.mm
│   │   │   ├── ContactsViewController.mm
│   │   │   ├── MultiSelectContactsViewController.mm
│   │   │   ├── SelectContactsViewController.mm
│   │   │   ├── ShareFriendOnChatLogicController.mm
│   │   │   └── ShareMyFriendLogicController.mm
│   │   ├── Profile
│   │   │   ├── Controller
│   │   │   │   ├── ContactInfoViewController.mm
│   │   │   │   ├── MMSayHelloViewController.mm
│   │   │   │   ├── QQContactInfoViewController.mm
│   │   │   │   └── SocialInfomationViewController.mm
│   │   │   ├── Model
│   │   │   │   ├── Protocol
│   │   │   │   │   └── VerifyContactPrtl.mm
│   │   │   │   └── UpdateProfileMgr.mm
│   │   │   └── View
│   │   │       ├── AlbumContactInfoAssist.mm
│   │   │       ├── BaseContactInfoAssist.mm
│   │   │       ├── VoiceVoipContactInfoAssist.mm
│   │   │       ├── VoipContactInfoAssist.mm
│   │   │       └── WeixinContactInfoAssist.mm
│   │   ├── Remark
│   │   │   └── Model
│   │   │       └── ContactRemarkLogic.mm
│   │   └── Tag
│   │       └── Model
│   │           └── ContactTagMgr.mm
│   ├── CrashReport
│   │   └── Model
│   │       ├── MMCrashReportConnection.mm
│   │       └── MMCrashReportHandler.mm
│   ├── Emoticon
│   │   ├── EmoticonBoard
│   │   │   ├── Model
│   │   │   │   ├── EmoticonAddFromServerLogicObject.mm
│   │   │   │   ├── EmoticonAddToServerLogicObject.mm
│   │   │   │   ├── EmoticonBackUpMgr.mm
│   │   │   │   ├── EmoticonBackupLogicObject.mm
│   │   │   │   ├── EmoticonBackupMd5ListCgi.mm
│   │   │   │   ├── EmoticonBackupOperateMgr.mm
│   │   │   │   ├── EmoticonDeleteFromServerLogicObject.mm
│   │   │   │   ├── EmoticonDownloadCgi.mm
│   │   │   │   ├── EmoticonDownloadMd5ListCgi.mm
│   │   │   │   ├── EmoticonOperateCgi.mm
│   │   │   │   ├── EmoticonRecoverLogicObject.mm
│   │   │   │   ├── EmoticonServerNotifyTaskGenerator.mm
│   │   │   │   └── EmoticonUploadCgi.mm
│   │   │   └── View
│   │   │       ├── EmoticonBoardView.mm
│   │   │       ├── EmoticonPickViewController.mm
│   │   │       ├── MMEmoticonView.mm
│   │   │       └── QQEmojiDataHelper.mm
│   │   ├── EmoticonManage
│   │   │   └── Controller
│   │   │       ├── EmoticonCustomManageViewController.mm
│   │   │       └── PurchasedEmoticonViewController.mm
│   │   └── EmoticonStore
│   │       ├── Controller
│   │       │   ├── EmoticonStoreDetailViewController.mm
│   │       │   ├── EmoticonStoreViewController.mm
│   │       │   └── EmoticonTusijiDetailViewController.mm
│   │       └── View
│   │           └── EmoticonStoreCell.mm
│   ├── Expose
│   │   ├── Controller
│   │   │   ├── MMExposeViewController.mm
│   │   │   └── MMNotInterestViewController.mm
│   │   └── Model
│   │       └── MMExposeConfigMgr.mm
│   ├── Favorites
│   │   ├── FavDetail
│   │   │   ├── Controller
│   │   │   │   ├── DetailViewController
│   │   │   │   │   ├── FavFileDetailViewController.mm
│   │   │   │   │   ├── FavFullScreenImageView.mm
│   │   │   │   │   ├── FavLocationDetailViewController.mm
│   │   │   │   │   ├── FavRecordDetailViewController.mm
│   │   │   │   │   └── FavVideoDetailViewController.mm
│   │   │   │   └── FavAudioRecorder.mm
│   │   │   └── View
│   │   │       ├── FavAudioPlayerController.mm
│   │   │       └── FavImageFullScreenViewContainer.mm
│   │   ├── FavList
│   │   │   ├── Controller
│   │   │   │   ├── MMFavoritesDataController.mm
│   │   │   │   └── MyFavoritesViewController.mm
│   │   │   └── View
│   │   │       └── NodeView
│   │   │           ├── MyFavoritesGoodsCellView.mm
│   │   │           ├── MyFavoritesMallProductCellView.mm
│   │   │           └── MyFavoritesTVCellView.mm
│   │   ├── FavPost
│   │   │   └── View
│   │   │       └── FavPostVoiceView.mm
│   │   ├── Model
│   │   │   ├── FavoritesAsyncUpload
│   │   │   │   ├── FavoritesAsyncUploadMgr.mm
│   │   │   │   └── FavoritesAsyncUploader.mm
│   │   │   ├── FavoritesBatchDel
│   │   │   │   └── FavoritesBatchDelMgr.mm
│   │   │   ├── FavoritesBatchGet
│   │   │   │   └── FavoritesBatchGetMgr.mm
│   │   │   ├── FavoritesDB
│   │   │   │   ├── FavoritesCDNInfoDB.mm
│   │   │   │   ├── FavoritesDownloadCDNInfoDB.mm
│   │   │   │   ├── FavoritesItemDB.mm
│   │   │   │   ├── FavoritesSearchDB.mm
│   │   │   │   ├── FavoritesTagDB.mm
│   │   │   │   └── MyFavoritesDB.mm
│   │   │   ├── FavoritesDownload
│   │   │   │   ├── FavoritesDownloadMgr.mm
│   │   │   │   └── FavoritesDownloader.mm
│   │   │   ├── FavoritesMgr.mm
│   │   │   ├── FavoritesRecordUtil.mm
│   │   │   ├── FavoritesSync
│   │   │   │   └── FavoritesSyncMgr.mm
│   │   │   ├── FavoritesUpload
│   │   │   │   ├── FavoritesUploadMgr.mm
│   │   │   │   └── FavoritesUploader.mm
│   │   │   └── FavoritesUtil.mm
│   │   └── Util
│   │       └── FavAddItemHelper.mm
│   ├── FindFriend
│   │   ├── Controller
│   │   │   ├── AddFriendEntryViewController.mm
│   │   │   ├── AddFriendListViewController.mm
│   │   │   └── FindFriendEntryViewController.mm
│   │   ├── Model
│   │   │   └── FriendAsistSessionMgr.mm
│   │   ├── RadarSearch
│   │   │   ├── Controller
│   │   │   │   └── RadarCreateRoomViewController.mm
│   │   │   ├── Model
│   │   │   │   └── RadarSearchMgr.mm
│   │   │   └── View
│   │   │       └── RadarSearchView.mm
│   │   └── SearchFriend
│   │       ├── Controller
│   │       │   └── SearchContactListViewController.mm
│   │       └── Model
│   │           └── SearchContactDataProvider.mm
│   ├── FloatBottle
│   │   ├── Controller
│   │   │   ├── BottleProfileEditViewController.mm
│   │   │   ├── BottleProfileViewController.mm
│   │   │   ├── BottleSessionViewController.mm
│   │   │   └── SandyBeachViewController.mm
│   │   ├── Model
│   │   │   ├── BottleContactDB.mm
│   │   │   ├── BottleContactExtendCode.mm
│   │   │   ├── BottleContactMgr.mm
│   │   │   ├── BottleDB.mm
│   │   │   ├── BottleExtendCode.mm
│   │   │   ├── BottleMgr.mm
│   │   │   └── Protocol
│   │   │       ├── FishBottlePrtl.mm
│   │   │       ├── GetBottleCountPrtl.mm
│   │   │       ├── OpenBottlePrtl.mm
│   │   │       └── ThrowBottlePrtl.mm
│   │   └── View
│   │       ├── ControlView
│   │       │   └── BottleAnimation.mm
│   │       ├── LogicView
│   │       │   └── BaseBottleView.mm
│   │       └── utils
│   │           └── NSDateExtendPLP.mm
│   ├── ForwardMessage
│   │   └── Controller
│   │       └── ForwardMsgUtil.mm
│   ├── FullTextSearch
│   │   ├── Controller
│   │   │   └── FTSVoiceSearchBarController.mm
│   │   ├── Model
│   │   │   ├── FTSFacade.mm
│   │   │   ├── LocalSearch
│   │   │   │   ├── AsyncTaskQueueEngine.mm
│   │   │   │   ├── Contact
│   │   │   │   │   └── FTSContactMgr.mm
│   │   │   │   ├── FTSDB.mm
│   │   │   │   ├── Favorites
│   │   │   │   │   ├── FTSFavDB.mm
│   │   │   │   │   ├── FTSFavMgr.mm
│   │   │   │   │   └── FTSFavUtil.mm
│   │   │   │   ├── LocalSearch.mm
│   │   │   │   ├── Memory
│   │   │   │   │   └── FTSMemorySearchMgr.mm
│   │   │   │   └── Message
│   │   │   │       ├── FTSMessageDB.mm
│   │   │   │       └── FTSMessageMgr.mm
│   │   │   └── OnlineSearch
│   │   │       ├── FTSOnlineData.mm
│   │   │       └── FTSOnlineSearchMgr.mm
│   │   └── View
│   │       └── TableCell
│   │           └── FTSTimelineCell.mm
│   ├── Group
│   │   ├── Controller
│   │   │   ├── ChatRoomBindCardUpgradeViewController.mm
│   │   │   ├── ChatRoomInfoViewController.mm
│   │   │   ├── ChatroomMemberRemoveViewController.mm
│   │   │   ├── GroupSelectContactsViewController.mm
│   │   │   ├── MemberListViewController.mm
│   │   │   └── RoomContactSelectViewController.mm
│   │   ├── Model
│   │   │   └── ContactsCreateChatRoomLogic.mm
│   │   └── View
│   │       └── ChatRoomMemberGridView.mm
│   ├── ImageBrowser
│   │   ├── Controller
│   │   │   ├── EmoticonMsgBrowseViewController.mm
│   │   │   ├── MsgImageBrowseViewController.mm
│   │   │   ├── MsgImgFullScreenViewController.mm
│   │   │   ├── MultiPickImageMsgViewController.mm
│   │   │   └── PhotoViewController.mm
│   │   └── View
│   │       └── MsgFastBrowseView.mm
│   ├── Mail
│   │   ├── NativeMail
│   │   │   ├── Controller
│   │   │   │   ├── MMReadMailViewController.mm
│   │   │   │   ├── MailAttachDetailViewController.mm
│   │   │   │   ├── WriteMailViewController.mm
│   │   │   │   └── ZipViewController.mm
│   │   │   ├── Model
│   │   │   │   ├── MMHttpCacheMgr.mm
│   │   │   │   ├── MMHttpConnection.mm
│   │   │   │   ├── MessageWrap+PushMail.mm
│   │   │   │   ├── QQMailHttpRespHandler.mm
│   │   │   │   ├── QQMailMgr+MailCache.mm
│   │   │   │   └── QQMailMgr.mm
│   │   │   └── View
│   │   │       ├── MMMailContactSelectViewController.mm
│   │   │       ├── MailAttachmentControlView.mm
│   │   │       └── MailContentView.mm
│   │   └── WebMail
│   │       ├── Controller
│   │       │   └── WebMailViewController.mm
│   │       └── Model
│   │           ├── ComposeSendHelper.mm
│   │           ├── NewQQMailMgr.mm
│   │           ├── NewQQMailQueueHelper.mm
│   │           ├── UploadAttachmentDataHelper.mm
│   │           └── UploadConversationFileHelper.mm
│   ├── MainFrame
│   │   ├── Header
│   │   │   ├── Controller
│   │   │   │   ├── MFMassSendBannerLogic.mm
│   │   │   │   ├── MFPushBannerLogic.mm
│   │   │   │   ├── MFPushSystemMsgLogic.mm
│   │   │   │   └── MainFrameHeaderLogic.mm
│   │   │   ├── Model
│   │   │   │   ├── BannerToast
│   │   │   │   │   └── BannerToastMgr.mm
│   │   │   │   └── PushSystemMsg
│   │   │   │       ├── Protocol
│   │   │   │       │   └── GetPushSystemImagePrtl.mm
│   │   │   │       └── PushSystemMsgMgr.mm
│   │   │   └── View
│   │   │       ├── MFWebMMBtn.mm
│   │   │       └── PushSystemMsgView.mm
│   │   ├── List
│   │   │   └── Controller
│   │   │       ├── LogicController
│   │   │       │   ├── MainFrameCellData.mm
│   │   │       │   ├── MainFrameCellDataManager.mm
│   │   │       │   └── MainFrameLogicController.mm
│   │   │       └── ViewController
│   │   │           ├── NewMainFrameViewController.mm
│   │   │           └── SetHeaderImageViewController.mm
│   │   └── RightTopMenu
│   │       └── Model
│   │           └── RightTopMenuData.mm
│   ├── MainUI
│   │   ├── Common
│   │   │   ├── MMTabBarController.mm
│   │   │   └── UINavigationControllerExtend.mm
│   │   ├── Controller
│   │   │   └── AppViewControllerManager.mm
│   │   ├── Theme
│   │   │   ├── ResPackage
│   │   │   │   └── MMResPackageMgr.mm
│   │   │   └── Theme
│   │   │       ├── MMColor.mm
│   │   │       ├── MMDrawScript.mm
│   │   │       ├── MMTheme.mm
│   │   │       └── MMThemeManager.mm
│   │   └── View
│   │       ├── SvrErrorTipViewController.mm
│   │       └── SvrErrorTipWindow.mm
│   ├── MassSend
│   │   ├── Controller
│   │   │   └── MMMassSendWriteMessageViewController.mm
│   │   └── Model
│   │       ├── MassSendMgr.mm
│   │       └── MessageWrap+MassSend.mm
│   ├── Message
│   │   ├── Controller
│   │   │   ├── Controllers
│   │   │   │   ├── AutoplayController.mm
│   │   │   │   ├── GameController.mm
│   │   │   │   ├── ImageController.mm
│   │   │   │   ├── PlayingController.mm
│   │   │   │   ├── RecordController.mm
│   │   │   │   ├── TypingController.mm
│   │   │   │   └── UrlController.mm
│   │   │   ├── MMMsgLogicManager.mm
│   │   │   ├── MsgLogicController
│   │   │   │   ├── BaseMsgContentLogicController.mm
│   │   │   │   ├── FloatBottleContentLogicController.mm
│   │   │   │   ├── QQMsgContentLogicController.mm
│   │   │   │   └── RoomContentLogicController.mm
│   │   │   ├── MsgRecordDetail
│   │   │   │   └── MsgRecordFileDetailViewController.mm
│   │   │   └── MsgViewController
│   │   │       ├── BaseMsgContentViewController.mm
│   │   │       ├── MsgSearchHelper.mm
│   │   │       └── VolumeCheckHelper.mm
│   │   ├── Model
│   │   │   ├── EasterEgg
│   │   │   │   └── MMEasterEggMgr.mm
│   │   │   ├── LocationThumb
│   │   │   │   └── LocationThumbMgr.mm
│   │   │   ├── MessageExt
│   │   │   │   ├── ImageAutoDownloadMgr.mm
│   │   │   │   └── MessageWrap+SysNewXml_ForBiz.mm
│   │   │   └── TranslateMsg
│   │   │       └── TranslateMsgMgr.mm
│   │   └── View
│   │       ├── MessageNodeView
│   │       │   ├── AppMessageNodeView
│   │       │   │   ├── AppDefaultMessageNodeView.mm
│   │       │   │   ├── AppEmoticonMessageNodeView.mm
│   │       │   │   ├── AppEmoticonSharedMessageNodeView.mm
│   │       │   │   ├── AppFileMessageNodeView.mm
│   │       │   │   ├── AppHardWareLikeNotifyMessageNode.mm
│   │       │   │   ├── AppHardWareRankMessageNode.mm
│   │       │   │   ├── AppMessageBlockButton.mm
│   │       │   │   ├── AppProductMessageNodeView.mm
│   │       │   │   ├── AppRecordMessageNodeView.mm
│   │       │   │   ├── AppShakeMessageNodeView.mm
│   │       │   │   ├── AppTVMessageNodeView.mm
│   │       │   │   ├── AppUrlMessageNodeView.mm
│   │       │   │   ├── AppWCCardMessageNodeView.mm
│   │       │   │   ├── AppWCProductMessageNodeView.mm
│   │       │   │   └── WCPayMsgNodeView
│   │       │   │       ├── WCPayC2CFestivalMsgNodeView.mm
│   │       │   │       ├── WCPayC2CMessageNodeView.mm
│   │       │   │       ├── WCPayMessageBaseNodeView.mm
│   │       │   │       ├── WCPayTransferAcceptedMessageNodeView.mm
│   │       │   │       ├── WCPayTransferMessageNodeView.mm
│   │       │   │       └── WCPayTransferRejectedMessageNodeView.mm
│   │       │   ├── AttributedReaderMessageNodeaView.mm
│   │       │   ├── BaseMessageNodeView.mm
│   │       │   ├── EmoticonMessageNodeView.mm
│   │       │   ├── GameMessageNodeView.mm
│   │       │   ├── HeadImgReaderMessageNodeaView.mm
│   │       │   ├── ReaderNewMessageNodeView.mm
│   │       │   ├── ShortVideoMessageNodeView.mm
│   │       │   ├── TextMessageNodeView.mm
│   │       │   ├── VideoMessageNodeView.mm
│   │       │   ├── VoiceMessageNodeView.mm
│   │       │   ├── VoiceReminderConfirmNodeView.mm
│   │       │   └── VoiceReminderRemindNodeView.mm
│   │       └── ToolView
│   │           ├── MMInputToolView.mm
│   │           ├── MMLandscapeInputToolView.mm
│   │           ├── RecordView.mm
│   │           └── SelectAttachmentView.mm
│   ├── POI
│   │   ├── Controller
│   │   │   ├── WCTimelinePOICategoryViewController.mm
│   │   │   ├── WCTimelinePOICreateViewController.mm
│   │   │   └── WCTimelinePOIPickerViewController.mm
│   │   └── Model
│   │       ├── CreatePOIMgr.mm
│   │       └── LBSLifeMgr.mm
│   ├── PeopleNearBy
│   │   ├── Controller
│   │   │   ├── LbsRoom
│   │   │   │   └── LbsRoomInfoViewController.mm
│   │   │   ├── PeopleNearByListViewController.mm
│   │   │   ├── SeePeopleNearByLogicController.mm
│   │   │   └── SeePeopleNearbyViewController.mm
│   │   └── Model
│   │       ├── LbsContactInfoList.mm
│   │       └── LbsRoom
│   │           └── LbsRoomSessionMgr.mm
│   ├── QQMsg
│   │   └── Controller
│   │       └── QQOfflineMsgViewController.mm
│   ├── RecoverData
│   │   ├── Controller
│   │   │   └── RecoverDataViewController.mm
│   │   └── Model
│   │       ├── RecoverDataManager.mm
│   │       └── RecoverDataWorker.mm
│   ├── Setting
│   │   ├── ChatBackground
│   │   │   ├── Controller
│   │   │   │   └── ChatBackgroundEntranceViewController.mm
│   │   │   └── Model
│   │   │       └── ChatBackgroundMgr.mm
│   │   ├── Controller
│   │   │   ├── FeedBackViewController.mm
│   │   │   ├── KFViewController.mm
│   │   │   ├── MoreViewController.mm
│   │   │   ├── NewSettingFontSizeViewController.mm
│   │   │   ├── NewSettingViewController.mm
│   │   │   ├── PushNoDisturbViewController.mm
│   │   │   ├── SettingAboutMMViewController.mm
│   │   │   ├── SettingAutoDownloadSightViewController.mm
│   │   │   ├── SettingModifyEmailViewController.mm
│   │   │   ├── SettingNotificationViewController.mm
│   │   │   └── SettingPrivateConfigViewController.mm
│   │   ├── Model
│   │   │   └── DelaySwitchSettingMgr.mm
│   │   └── MyAccountSetting
│   │       ├── Controller
│   │       │   ├── AccountBaseViewController.mm
│   │       │   ├── BigChatRoomInviteViewController.mm
│   │       │   ├── SetDeviceSafeViewController.mm
│   │       │   ├── SettingModifyAliasViewController.mm
│   │       │   ├── SettingMyAccountExtInfoViewController.mm
│   │       │   ├── SettingMyAccountInfoViewController.mm
│   │       │   └── SettingMyProfileViewController.mm
│   │       └── Model
│   │           └── PasswordLogic.mm
│   ├── Shake
│   │   ├── Controller
│   │   │   ├── Logic
│   │   │   │   ├── ShakeBeaconLogicController.mm
│   │   │   │   ├── ShakeCardLogicController.mm
│   │   │   │   ├── ShakeChecker.mm
│   │   │   │   ├── ShakePeopleLogicController.mm
│   │   │   │   └── ShakeRangingBeaconsMgr.mm
│   │   │   └── ViewController
│   │   │       ├── ShakeMsgListViewController.mm
│   │   │       └── ShakeViewController.mm
│   │   ├── Model
│   │   │   ├── Notification
│   │   │   │   └── ShakeMsgNotifyMgr.mm
│   │   │   ├── ShakeBgImgDownloadMgr.mm
│   │   │   ├── ShakeSearch
│   │   │   │   ├── BeaconSearchMgr.mm
│   │   │   │   ├── MusicSearchMgr.mm
│   │   │   │   ├── ShakeCardMgr.mm
│   │   │   │   ├── TvSearchMgr.mm
│   │   │   │   ├── UploadAFPMgr.mm
│   │   │   │   ├── UploadMusicFPMgr.mm
│   │   │   │   └── UploadTvFPMgr.mm
│   │   │   └── Storage
│   │   │       └── ShakeTvStorage.mm
│   │   └── View
│   │       └── Widget
│   │           └── ShakeSingleView.mm
│   ├── ShareExtension
│   │   └── Model
│   │       └── SEVideoManager.mm
│   ├── ShareLocation
│   │   ├── Controller
│   │   │   ├── MMPickLocationViewController.mm
│   │   │   └── MMViewLocationViewController.mm
│   │   ├── Model
│   │   │   ├── GetPOIListMgr.mm
│   │   │   ├── MMAddressAnnotation.mm
│   │   │   ├── MapDirectionsMgr.mm
│   │   │   ├── TrackPresentMgr.mm
│   │   │   └── TrackRoomMgr.mm
│   │   └── View
│   │       ├── HorizontalTableView.mm
│   │       ├── MKMapView+ZoomLevel.mm
│   │       ├── MMLocationPinView.mm
│   │       └── TrackRoomView.mm
│   ├── Sight
│   │   ├── Controller
│   │   │   ├── MainFrameSightViewController.mm
│   │   │   ├── SightMomentEditViewController.mm
│   │   │   └── SightMomentGroupSelectViewController.mm
│   │   ├── Model
│   │   │   ├── MMAVPlayerMgr.mm
│   │   │   ├── MassSendSight
│   │   │   │   ├── MassSendShortVideoLogic.mm
│   │   │   │   └── UploadShortVideoToCdn.mm
│   │   │   ├── SightCaptureLogicWithoutGL.mm
│   │   │   ├── SightDraftMgr.mm
│   │   │   └── SightFacade.mm
│   │   ├── NewYear
│   │   │   ├── NewYearSightCacheLogic.mm
│   │   │   └── SightTVSliderView.mm
│   │   └── View
│   │       ├── ShortVideoToolbar.mm
│   │       ├── SightDistributeTableView.mm
│   │       ├── SightMainframeIconView.mm
│   │       └── SightPlayerView.mm
│   ├── SyncPhoneContact
│   │   └── Controller
│   │       └── SyncPhoneContactsViewController.mm
│   ├── UniversalSession
│   │   └── Model
│   │       └── MMBaseSessionStorage.mm
│   ├── VoiceExtend
│   │   ├── VoiceInput
│   │   │   ├── Model
│   │   │   │   ├── UploadInputVoiceMgr.mm
│   │   │   │   └── VoiceInputMgr.mm
│   │   │   └── View
│   │   │       └── VoiceInputView.mm
│   │   ├── VoicePrint
│   │   │   ├── Controller
│   │   │   │   ├── CreateVoicePrintLogicController.mm
│   │   │   │   ├── NewFeatureSelectionViewController.mm
│   │   │   │   ├── VerifyVoicePrintLogicController.mm
│   │   │   │   └── VoicePrintLogicControllerFactory.mm
│   │   │   ├── Model
│   │   │   │   ├── UploadVoicePrintMgr.mm
│   │   │   │   ├── VPGetResourceCgi.mm
│   │   │   │   ├── VPGetTicketCgi.mm
│   │   │   │   ├── VPSwitchOpCgi.mm
│   │   │   │   └── VoicePrintMgr.mm
│   │   │   └── View
│   │   │       ├── NewBaseVoicePrintViewController.mm
│   │   │       ├── NewCreateVoicePrintViewController.mm
│   │   │       └── NewVerifyVoicePrintViewController.mm
│   │   ├── VoiceReminder
│   │   │   └── Model
│   │   │       └── VoiceReminderMgr.mm
│   │   ├── VoiceSearch
│   │   │   ├── Controller
│   │   │   │   ├── VoiceSearchContactsViewController.mm
│   │   │   │   └── VoiceSearchMutilLevelViewController.mm
│   │   │   └── Model
│   │   │       ├── UploadSearchVoiceMgr.mm
│   │   │       └── VoiceSearchMgr.mm
│   │   └── VoiceTrans
│   │       └── Model
│   │           └── VoiceTransHelper.mm
│   ├── Voip
│   │   ├── Controller
│   │   │   └── VoipUIManager.mm
│   │   ├── Model
│   │   │   ├── Adapter
│   │   │   │   └── VOIPChannelAdapter.mm
│   │   │   ├── VOIPHelper.mm
│   │   │   ├── VOIPMessageMgr.mm
│   │   │   ├── VOIPPushMgr.mm
│   │   │   ├── VOIPReportData.mm
│   │   │   ├── VOIPSyncMgr.mm
│   │   │   ├── Video
│   │   │   │   ├── AVVideoDevice.mm
│   │   │   │   ├── VOIPVideoRender.mm
│   │   │   │   └── VoipOpenglesContext.mm
│   │   │   ├── VoIPMgr
│   │   │   │   ├── DeviceModelConfigMgr.mm
│   │   │   │   ├── VOIPMgr-Comm.mm
│   │   │   │   ├── VOIPMgr-Connect.mm
│   │   │   │   ├── VOIPMgr-Dial.mm
│   │   │   │   ├── VOIPMgr-Session.mm
│   │   │   │   ├── VOIPMgr-Talk.mm
│   │   │   │   └── VOIPMgr.mm
│   │   │   ├── VoIPModeSwitchMgr
│   │   │   │   ├── VOIPModeSwitchMgr.mm
│   │   │   │   └── VOIPModeSwitchStateMachine.mm
│   │   │   └── VoipMinimizeReportObject.mm
│   │   └── View
│   │       ├── VideoVoipCallerView.mm
│   │       ├── VideoVoipReceiverView.mm
│   │       ├── VideoVoipTalkingView.mm
│   │       └── VideoVoipView.mm
│   ├── WCAccount
│   │   ├── 3rdAccount
│   │   │   ├── Facebook
│   │   │   │   └── Model
│   │   │   │       ├── FacebookAuth.mm
│   │   │   │       ├── MMFBTokenCachingStrategy.mm
│   │   │   │       └── MMFacebookMgr.mm
│   │   │   ├── Google
│   │   │   │   ├── Controller
│   │   │   │   │   ├── BindOrUnbindGoogleAccountViewController.mm
│   │   │   │   │   ├── GTMOAuth2ViewControllerTouch.m
│   │   │   │   │   └── GoogleContactsViewController.mm
│   │   │   │   └── Model
│   │   │   │       ├── GoogleContactAPIFetchImpl.mm
│   │   │   │       ├── GoogleContactMgr.mm
│   │   │   │       └── ListGoogleContactsFromWXServerImpl.mm
│   │   │   └── Twitter
│   │   │       └── Model
│   │   │           └── MMTwitterAuth.mm
│   │   ├── Login&Reg
│   │   │   ├── Controller
│   │   │   │   ├── WCAccountLoginByQRCodeViewController.mm
│   │   │   │   └── WCAccountRegisterViewController.mm
│   │   │   └── Model
│   │   │       ├── LoginLogic.mm
│   │   │       ├── OneClickLogin
│   │   │       │   ├── BluetoothLoginLogic.mm
│   │   │       │   ├── PushLoginURLCGI.mm
│   │   │       │   └── SendActiveCGI.mm
│   │   │       ├── QRCodeLogin
│   │   │       │   ├── CheckQRCodeLoginCGI.mm
│   │   │       │   ├── GetQRCodeLoginCGI.mm
│   │   │       │   └── QRCodeLoginLogic.mm
│   │   │       ├── WCAccountBaseControlLogic.mm
│   │   │       ├── WCAccountCommon.mm
│   │   │       ├── WCAccountControlMgr.mm
│   │   │       ├── WCAccountEmailRegControlLogic.mm
│   │   │       ├── WCAccountFindFriendControlLogic.mm
│   │   │       ├── WCAccountLogic.mm
│   │   │       ├── WCAccountQRCodeLoginControlLogic.mm
│   │   │       ├── WCAccountRegisterControlLogic.mm
│   │   │       └── WCFindFriendLogic.mm
│   │   ├── Mobile
│   │   │   ├── Controller
│   │   │   │   ├── BindPhoneInfoViewController.mm
│   │   │   │   ├── VerifyCodeByVoiceViewController.mm
│   │   │   │   └── VerifyPhoneViewController.mm
│   │   │   └── Model
│   │   │       ├── AddressBookFriendMgr.mm
│   │   │       ├── MMAddressBookMgr.mm
│   │   │       ├── NetworkEvent
│   │   │       │   └── UploadMContactEvent.mm
│   │   │       └── Protocol
│   │   │           ├── ResetPasswordByMobilePrtl.mm
│   │   │           └── UploadMContactPrtl.mm
│   │   ├── MultiOnline
│   │   │   ├── Controller
│   │   │   │   └── OneClickLogin
│   │   │   │       ├── ExtraDeviceLoginViewController.mm
│   │   │   │       ├── OnlineDeviceInfoViewController.mm
│   │   │   │       └── WCAccountOneClickLoginViewController.mm
│   │   │   └── Model
│   │   │       ├── MacLogin
│   │   │       │   ├── ExtraDeviceLoginMgr.mm
│   │   │       │   └── PushLoginURLMgr.mm
│   │   │       └── OnlineClient
│   │   │           ├── HeartBeatMgr.mm
│   │   │           └── OnlineClientMgr.mm
│   │   ├── PreEnter
│   │   │   └── Model
│   │   │       ├── AppCommentMgr.mm
│   │   │       ├── PreEnterWechatLogic+CheckShowRating.mm
│   │   │       └── PreEnterWechatLogic.mm
│   │   └── QQAccount
│   │       ├── Controller
│   │       │   ├── ListQQFriendGroupViewController.mm
│   │       │   ├── ListQQFriendViewController.mm
│   │       │   ├── SettingBindQQVerifyViewController.mm
│   │       │   ├── SettingBindQQViewController.mm
│   │       │   └── SettingModifyQQViewController.mm
│   │       └── Model
│   │           └── QQAccountMgr.mm
│   ├── WXTalk
│   │   ├── Controller
│   │   │   └── WXTalkUIManager.mm
│   │   ├── Model
│   │   │   ├── WXTalkDNSController.mm
│   │   │   ├── WXTalkMgr-Session.mm
│   │   │   ├── WXTalkMgr-Talk.mm
│   │   │   ├── WXTalkMgr.mm
│   │   │   ├── WXTalkPresentMgr.mm
│   │   │   └── WXTalkStatusReportHelper.mm
│   │   └── View
│   │       └── WXTalkHeadListView.mm
│   └── WcSns
│       ├── Model
│       │   ├── WCAdvertise
│       │   │   ├── WCAdvertiseCommentUploadMgr.mm
│       │   │   ├── WCAdvertiseDataHelper.mm
│       │   │   ├── WCAdvertiseLogicMgr.mm
│       │   │   └── WCAdvertiseStatMgr.mm
│       │   ├── WCDB
│       │   │   └── MyWCDB.mm
│       │   ├── WCFacade.mm
│       │   ├── classifyTimeline
│       │   │   └── WCClassifyTimelineDataProvider_Sns.mm
│       │   ├── comment
│       │   │   ├── WCCommentUploadMgr.mm
│       │   │   ├── WCNotificationCenterMgr.mm
│       │   │   └── WCSyncEventHandler.mm
│       │   ├── common
│       │   │   ├── WCCommon.mm
│       │   │   └── WCUtil.mm
│       │   ├── download
│       │   │   ├── WCDownloadEventHandler.mm
│       │   │   └── WCDownloadMgr.mm
│       │   ├── group
│       │   │   └── WCGroupMgr.mm
│       │   ├── homepage
│       │   │   └── WCHomepageDataProvider_Sns.mm
│       │   ├── localLogic
│       │   │   └── WCLLUpload.mm
│       │   ├── misc
│       │   │   ├── WCBGImgLogic.mm
│       │   │   ├── WCImageCache.mm
│       │   │   ├── WCInputTextCacheMgr.mm
│       │   │   └── WCOpLog.mm
│       │   ├── timeline
│       │   │   ├── WCTimelineDataProvider_Sns.mm
│       │   │   └── WCTimelineMgr.mm
│       │   └── upload
│       │       ├── WCDataUploader.mm
│       │       ├── WCMediaUploader.mm
│       │       ├── WCTaskUploader.mm
│       │       ├── WCUploadCommon.mm
│       │       └── WCUploadMgr.mm
│       └── UI
│           ├── WCComment
│           │   ├── WCCommentDetailViewControllerFB.mm
│           │   ├── WCCommentListViewController.mm
│           │   ├── WCCommentStrangerViewController.mm
│           │   ├── WCCommentView.mm
│           │   └── WCCommentViewFB.mm
│           ├── WCCommit
│           │   ├── WCCommitSelectorController.mm
│           │   ├── WCCommitViewController.mm
│           │   ├── WCForwardViewController.mm
│           │   └── WCNewCommitViewController.mm
│           ├── WCGroup
│           │   ├── WCClassifyMembersViewController.mm
│           │   ├── WCEditMemberPannel.mm
│           │   ├── WCGroupMemberViewController.mm
│           │   ├── WCGroupTagViewController.mm
│           │   ├── WCSelectGroupCell.mm
│           │   ├── WCSetPermissionsViewController.mm
│           │   └── WCSetStrangerPermissionsViewController.mm
│           ├── WCList
│           │   ├── CellView
│           │   │   └── WCListPhotoCellView.mm
│           │   ├── WCListHeaderView.mm
│           │   ├── WCListView.mm
│           │   └── WCListViewController.mm
│           ├── WCSetting
│           │   └── WCCustomizeViewController.mm
│           ├── WCTimeLine
│           │   ├── WCClassifyTimeLineViewController.mm
│           │   ├── WCContentItemViewTemplateNewSight.mm
│           │   ├── WCContentItemViewTemplateSight.mm
│           │   ├── WCTimeLineCellMediaContentView.mm
│           │   ├── WCTimeLineCellView.mm
│           │   ├── WCTimeLineCommentCellView.mm
│           │   └── WCTimeLineViewController.mm
│           └── comm
│               ├── PageScrollView.mm
│               ├── WCHeaderGridView.mm
│               ├── WCImageFullScreenView.mm
│               ├── WCImageFullScreenViewContainer.mm
│               ├── WCImageView.mm
│               ├── WCMultiImageScannerController.mm
│               ├── WCPhotoMutipleImageViewController.mm
│               ├── WCPuzzleImageView.mm
│               ├── WCSightView.mm
│               └── WCUIUtil.mm
├── PublicComponentV2
│   ├── AccessoryC2Objc.mm
│   ├── C2Objc_Logic.mm
│   ├── ios_weixin_support
│   │   ├── KVCommReport
│   │   │   └── KVCommReportLogic.mm
│   │   ├── NetCmdEvent.mm
│   │   ├── NetCmdSendOnlyEvent.mm
│   │   └── mmpack.mm
│   ├── kvcomm_C2Objc_Logic.mm
│   └── platform_logic.mm
├── WC3rdApp
│   ├── Mode
│   │   ├── AppCommunicate
│   │   │   └── WeChatApiUtil.m
│   │   ├── AppFramework
│   │   │   ├── NewAuthHandler.mm
│   │   │   ├── OnGotAppMsgHandler.mm
│   │   │   ├── OpenRankListHandler.mm
│   │   │   ├── SMSAddCardHandler.mm
│   │   │   ├── SendAppMsgHandler.mm
│   │   │   ├── SendAppMsgToFavoritesHandler.mm
│   │   │   ├── SendAppMsgToWCHandler.mm
│   │   │   ├── SendFileMsgHandler.mm
│   │   │   └── WechatConnectHandler.mm
│   │   └── AppMgr
│   │       ├── AppCatchCrashMgr.mm
│   │       ├── AppDataMgr.mm
│   │       ├── OpenApiMgr.mm
│   │       ├── OpenApiMgrHelper.mm
│   │       ├── RecommendAppsLogicImpl.mm
│   │       └── ServiceAppsLogicImpl.mm
│   └── ViewController
│       ├── 3rdApp
│       │   ├── AppDetailViewController.mm
│       │   ├── AppEmotionPreviewViewController.mm
│       │   └── ServiceAppListViewController.mm
│       ├── JumpToBizWebview
│       │   └── JumpToBizWebviewLogicHelper.mm
│       ├── OpenProfile
│       │   └── OpenProfileLogicHelper.mm
│       └── ShareAuth
│           └── WCShareAuthViewController.mm
├── WCBiz
│   ├── Common
│   │   ├── Control
│   │   │   └── WCBizControlLogic.mm
│   │   └── View
│   │       └── UIControl
│   │           ├── WCBizFullImageView.mm
│   │           └── WCBizMultiImageBrowseViewContainer.mm
│   ├── PayU
│   │   ├── PayUControl
│   │   │   ├── OpenWalletControl
│   │   │   │   └── WCPayOpenWalletLogic.mm
│   │   │   ├── PayUCardControl
│   │   │   │   └── PayUBalanceControl
│   │   │   │       └── WCPayPayUBalanceSaveMoneyControlLogic.mm
│   │   │   ├── PayUOnlinePayControl
│   │   │   │   └── WCPayPayUPayMoneyLogic.mm
│   │   │   └── PayUTransferControl
│   │   │       └── WCPayPayUTransferMoneyControlLogic.mm
│   │   └── View
│   │       ├── UIControl
│   │       │   ├── WCPayPayUCVVCtrlItem.mm
│   │       │   ├── WCPayPayUCardDetailView.mm
│   │       │   ├── WCPayPayUPasswordCtrlItem.mm
│   │       │   └── WCPayPayUSecureCtrlItem.mm
│   │       └── ViewController
│   │           ├── TransferViewController
│   │           │   └── WCPayPayUFacingReceiveQRCodeViewController.mm
│   │           └── WCPayUBizMainViewController.mm
│   ├── Utility
│   │   └── WCBizUtil.mm
│   ├── WCAdress
│   │   ├── Control
│   │   │   ├── WCAddressControlLogic.mm
│   │   │   └── WCAddressEntranceControlLogic.mm
│   │   ├── Model
│   │   │   └── WCAddressLogicMgr.mm
│   │   └── View
│   │       └── ViewController
│   │           └── WCAddressListViewController.mm
│   ├── WCBizCommon
│   │   └── Controller
│   │       ├── WCProductActionLogicController.mm
│   │       └── WCProductSKULogicController.mm
│   ├── WCBizMain
│   │   └── View
│   │       └── WCBizMainViewController.mm
│   ├── WCBusinessJump
│   │   ├── Model
│   │   │   ├── WCBusinessJumpMgr.mm
│   │   │   └── WCTempChatMgr.mm
│   │   └── ViewController
│   │       └── WCBusinessJumpViewController.mm
│   ├── WCCardPkg
│   │   ├── Control
│   │   │   ├── WCCardDetailViewController.mm
│   │   │   └── WCCardPackageAnimatViewController.mm
│   │   ├── Model
│   │   │   ├── WCCardBulkImport
│   │   │   │   └── WCCardBulkImportMgr.mm
│   │   │   ├── WCCardMsgCenter
│   │   │   │   └── WCCardMsgCenterMgr.mm
│   │   │   ├── WCCardPkgBatchDel
│   │   │   │   └── WCCardPkgBatchDelMgr.mm
│   │   │   ├── WCCardPkgBatchGet
│   │   │   │   └── WCCardPkgBatchGetMgr.mm
│   │   │   ├── WCCardPkgBatchGetCardItemByTpInfo
│   │   │   │   └── WCCardPkgBatchGetCardItemByTpInfoMgr.mm
│   │   │   ├── WCCardPkgDataBase
│   │   │   │   ├── WCCardPkgDB+WCDB.mm
│   │   │   │   ├── WCCardPkgDB+WCDBCardInfoTable.mm
│   │   │   │   └── WCCardPkgDB+WCDBMsgCenterTable.mm
│   │   │   ├── WCCardPkgMgr.mm
│   │   │   ├── WCCardPkgSync
│   │   │   │   └── WCCardPkgSyncMgr.mm
│   │   │   └── WCCardPkgUtil.mm
│   │   └── View
│   │       ├── WCCardCollectionView.mm
│   │       ├── WCCardCollectionViewCell.mm
│   │       ├── WCCardHeaderView.mm
│   │       └── WCCardPackageTableView.mm
│   ├── WCInnerJump
│   │   └── JDStore
│   │       └── WCJdBussinessMgr.mm
│   ├── WCMall
│   │   ├── Control
│   │   │   └── WCMallFunctionActivityPayControlLogic.mm
│   │   ├── Model
│   │   │   └── WCMallLogicMgr.mm
│   │   └── View
│   │       └── UIControl
│   │           ├── WCMallProductsPickerItem.mm
│   │           └── WCMallTelephoneTextFieldItem.mm
│   ├── WCPay
│   │   ├── Control
│   │   │   ├── AbroadWalletControl
│   │   │   │   └── WCPayHtml5WalletLogic.mm
│   │   │   ├── BaseControl
│   │   │   │   └── WCPayControlLogic.mm
│   │   │   ├── C2CMessageControl
│   │   │   │   ├── WCPayRetrySendC2CMessageLogic.mm
│   │   │   │   └── WCPaySendC2CMessageJSApiLogicControl.mm
│   │   │   ├── OfflinePayControl
│   │   │   │   └── WCPayOfflinePayMainLogic.mm
│   │   │   ├── OnlinePayControl
│   │   │   │   ├── WCPayPayMoneyFromWAPPayLogic.mm
│   │   │   │   └── WCPayPayMoneyLogic.mm
│   │   │   ├── OrderControl
│   │   │   │   └── WCPayOrderHistoryLogic.mm
│   │   │   ├── PatternLockControl
│   │   │   │   ├── MMPatternLockLogic.mm
│   │   │   │   ├── MMPatternLockPwdMgr.mm
│   │   │   │   └── MMPatternLockViewController.mm
│   │   │   └── WCPayControlMgr.mm
│   │   ├── Model
│   │   │   ├── DB
│   │   │   │   └── WCPayMsgDB.mm
│   │   │   ├── Manager
│   │   │   │   ├── WCPayLogicMgr+AboutOrder.mm
│   │   │   │   ├── WCPayLogicMgr+AddCard.mm
│   │   │   │   ├── WCPayLogicMgr+CardControl.mm
│   │   │   │   ├── WCPayLogicMgr+CreditPay.mm
│   │   │   │   ├── WCPayLogicMgr+MsgCenter.mm
│   │   │   │   ├── WCPayLogicMgr+OfflinePay.mm
│   │   │   │   ├── WCPayLogicMgr+PayAuth.mm
│   │   │   │   ├── WCPayLogicMgr+PayMoney.mm
│   │   │   │   ├── WCPayLogicMgr+ResetPwd.mm
│   │   │   │   ├── WCPayLogicMgr+TransferMoney.mm
│   │   │   │   ├── WCPayLogicMgr+WCPayMockLogicMrg.mm
│   │   │   │   ├── WCPayLogicMgr.mm
│   │   │   │   └── WCPayWordingHelpMgr.mm
│   │   │   ├── Network
│   │   │   │   └── WCPayNetworkHelper.mm
│   │   │   └── iAP
│   │   │       └── iAPMgr.mm
│   │   └── View
│   │       ├── UIControl
│   │       │   ├── WCPayCardDetailView.mm
│   │       │   ├── WCPayOfflinePayCodeView.mm
│   │       │   ├── WCPayPickerView.mm
│   │       │   ├── WCPayTenpayPasswordCtrlItem.mm
│   │       │   └── WCPayTenpaySecureCtrlItem.mm
│   │       └── ViewController
│   │           ├── MultipleUseViewController
│   │           │   ├── WCPayCardNumberConfirmViewController.mm
│   │           │   ├── WCPayCardNumberScanViewController.mm
│   │           │   └── WCPayFillCardNumberViewController.mm
│   │           └── PrivateViewController
│   │               ├── BalanceViewController
│   │               │   ├── WCPayBalanceDetailViewController.mm
│   │               │   └── WCPayFetchViewController.mm
│   │               ├── OfflinePayViewController
│   │               │   ├── WCPayOfflinePaySettingViewController.mm
│   │               │   └── WCPayOfflinePayViewController.mm
│   │               ├── OrderViewController
│   │               │   ├── WCPayNewOrderDetailViewController.mm
│   │               │   ├── WCPayNewOrderHistoryViewController.mm
│   │               │   ├── WCPayOrderAndProductDetailHistoryInfoViewController.mm
│   │               │   └── WCPayOrderHistoryViewController.mm
│   │               └── TransferViewController
│   │                   ├── WCPayFacingReceiveQRCodeViewController.mm
│   │                   ├── WCPayTransferSelectChatRoomContactViewController.mm
│   │                   ├── WCPayTransferSelectContactsViewController.mm
│   │                   └── WCPayTransferSelectSessionViewController.mm
│   ├── WCProduct
│   │   ├── Controller
│   │   │   ├── WCProductBuyDetailViewController.mm
│   │   │   ├── WCProductDetailViewController.mm
│   │   │   └── WCProductSKUViewController.mm
│   │   └── Model
│   │       └── WCProductMgr.mm
│   ├── WCPublicWifi
│   │   └── Model
│   │       ├── APAccess.mm
│   │       ├── APAuth.mm
│   │       ├── APCheck.mm
│   │       ├── PublicWifiCache.mm
│   │       ├── PublicWifiDB.mm
│   │       ├── PublicWifiGetA8KeyLogic.mm
│   │       ├── PublicWifiHelper.mm
│   │       └── PublicWifiManager.mm
│   └── WCRedEnvelopes
│       ├── Control
│       │   ├── EnterpriseRedEnvelopesControl
│       │   │   ├── WCRedEnvEnterpriseReceiveControlLogic.mm
│       │   │   └── WCRedEnvelopesEnterpriseControlLogic.mm
│       │   ├── WCRedEnvelopesControlLogic.mm
│       │   ├── WCRedEnvelopesControlMgr.mm
│       │   ├── WCRedEnvelopesReceiveControlLogic.mm
│       │   └── WCRedEnvelopesSendControlLogic.mm
│       ├── Model
│       │   └── WCRedEnvelopesLogicMgr.mm
│       └── View
│           ├── UIControl
│           │   ├── WCAtomicRedEnvReceiveHomeView.mm
│           │   ├── WCAtomicRedEnvReceiveWelcomeView.mm
│           │   ├── WCFestivalRedEnvReceiveHomeView.mm
│           │   ├── WCFestivalRedEnvShareView.mm
│           │   ├── WCRedEnvelopesCommentInputToolView.mm
│           │   └── WCRedEnvelopesReceiveHomeView.mm
│           └── ViewController
│               ├── WCRedEnvelopesMakeRedEnvelopesViewController.mm
│               ├── WCRedEnvelopesMultiSelectContactsViewController.mm
│               ├── WCRedEnvelopesRedEnvelopesHistoryListViewController.mm
│               └── WCRedEnvelopesSessionSelectViewController.mm
├── WCBrand
│   ├── DeviceBrand
│   │   ├── 3rd
│   │   │   └── BlueTooth
│   │   │       ├── BlueBLEAdapter.mm
│   │   │       ├── BlueDevicePool.mm
│   │   │       ├── BlueEAAdapter.mm
│   │   │       ├── BlueIDPool.mm
│   │   │       └── BlueManager.mm
│   │   ├── Model
│   │   │   ├── WCDeviceAccount
│   │   │   │   └── WCDeviceAccountDB
│   │   │   │       └── WCDeviceAccountWCDB.mm
│   │   │   ├── WCDeviceAirKiss
│   │   │   │   └── WCDeviceAirKissMgr.mm
│   │   │   ├── WCDeviceBrandLogicHelper
│   │   │   │   ├── WCDeviceAuthLogic.mm
│   │   │   │   ├── WCDeviceM7Logic.mm
│   │   │   │   ├── WCDeviceSendDataToManufacturSvrLogic.mm
│   │   │   │   └── WCDeviceWifiStateLogic.mm
│   │   │   ├── WCDeviceBrandMgr.mm
│   │   │   ├── WCDeviceComm.mm
│   │   │   ├── WCDeviceDebug
│   │   │   │   ├── WCDeviceDebugMgr.mm
│   │   │   │   └── WCDeviceDebugViewController.mm
│   │   │   ├── WCDeviceJSApi
│   │   │   │   └── WCDeviceJSApiMgr.mm
│   │   │   └── WCDeviceNetwork
│   │   │       └── WCDeviceNetworkLogicMgr.mm
│   │   └── View
│   │       └── AirKissViewController.mm
│   ├── EnterpriseBrand
│   │   └── EnterpriseBrandSession
│   │       ├── Controller
│   │       │   └── EnterpriseBrandSessionListViewController.mm
│   │       └── Model
│   │           ├── MMEnterpriseBrandSessionMgr.mm
│   │           └── MMEnterpriseSubSessionCacher.mm
│   ├── KFBrand
│   │   └── Model
│   │       ├── KFContactCacher.mm
│   │       └── KFContactMgr.mm
│   ├── NormalBrand
│   │   ├── BrandCertification
│   │   │   └── CertInfoMgr.mm
│   │   ├── BrandConversation
│   │   │   ├── Controller
│   │   │   │   └── BrandCustomStyleUILogicController.mm
│   │   │   ├── Model
│   │   │   │   ├── BrandDeviceConnectLogicController.mm
│   │   │   │   ├── BrandServiceContinueLocationReportLogic.mm
│   │   │   │   └── BrandServiceEnterConversationLogic.mm
│   │   │   └── View
│   │   │       ├── CustomMenuButton.mm
│   │   │       └── MMHorizontalTableView.mm
│   │   ├── BrandIAPMgr
│   │   │   └── BrandIAPMgr.mm
│   │   ├── BrandMessage
│   │   │   └── TemplateMsgRecvMgr.mm
│   │   ├── BrandProfile
│   │   │   └── Controller
│   │   │       └── BrandUserContactInfoAssist.mm
│   │   ├── BrandServiceSearch
│   │   │   └── Model
│   │   │       ├── BSSDetailPageLogicController.mm
│   │   │       ├── BSSHomePageLogicController.mm
│   │   │       └── BrandServiceSearchCommonUtil.mm
│   │   └── BrandSession
│   │       ├── Controller
│   │       │   └── BrandSessionViewController.mm
│   │       └── Model
│   │           └── BrandSessionMgr.mm
│   └── RankSns
│       └── Model
│           ├── DeviceRankProfileMgr.mm
│           ├── DeviceRankSettingMgr.mm
│           ├── DeviceRankSnsMgr.mm
│           └── DeviceRankUsersMgr.mm
├── WCGame
│   └── GameCenterV2
│       ├── Controller
│       │   ├── Detail
│       │   │   └── GameCenterDetailViewController.mm
│       │   ├── GameCenterHomeViewController.mm
│       │   └── Library
│       │       ├── GameLibraryViewController.mm
│       │       └── GameMoreViewController.mm
│       └── Model
│           ├── Detail
│           │   └── GameCenterDetailLogicController.mm
│           ├── GameCenterManager.mm
│           ├── GameCenterUtil.mm
│           ├── Library
│           │   └── GameLibrarayLogicController.mm
│           ├── MsgCenter
│           │   └── GameMsgDB
│           │       └── GameMsgDB+WCDB.mm
│           ├── Notification
│           │   └── GameNotifyMsgMgr.mm
│           ├── Search
│           │   └── GameSearchManager.mm
│           └── Statistics
│               └── GameStatMgr.mm
├── WCNewYear
│   ├── Controller
│   │   ├── NewYearShakeViewController.mm
│   │   └── NewYearShowListViewController.mm
│   └── Model
│       ├── NewYearCtrlMgr.mm
│       ├── NewYearResourceDownloadMgr.mm
│       ├── NewYearResourceMgr.mm
│       ├── NewYearShakeEvent.mm
│       ├── NewYearShakeMgr.mm
│       ├── NewYearUploadFamilyPhotoMgr.mm
│       └── NewYearUtil.mm
├── WCWeb
│   ├── JSAPI
│   │   └── Model
│   │       ├── MMJSApiVerifyMgr.mm
│   │       ├── WebviewJSEventHandler_getBrandIAPPayRequest.mm
│   │       ├── WebviewJSEventHandler_getInstallState.mm
│   │       ├── WebviewJSEventHandler_saveImage.mm
│   │       ├── WebviewJSEventHandler_sendAppMessage.mm
│   │       ├── WebviewJSEventHandler_shareQQ.mm
│   │       ├── WebviewJSEventHandler_shareQZone.mm
│   │       └── WebviewJSEventHandler_shareWeibo.mm
│   ├── JSAuth
│   │   └── Model
│   │       └── WebviewAskAuthorizationLogic.mm
│   └── WebView
│       ├── Controller
│       │   ├── MMWebViewController+MenuAction.mm
│       │   └── MMWebViewController.mm
│       └── Model
│           ├── MMWebViewHistory.mm
│           ├── ResourceManager
│           │   ├── WebResourceCDNDownloadHelper.mm
│           │   ├── WebResourceCDNUploadHelper.mm
│           │   ├── WebResourceUploadHelper.mm
│           │   ├── WebviewRecorderManager.mm
│           │   ├── WebviewResourceDownloadHelper.mm
│           │   └── WebviewResourceManager.mm
│           ├── WebViewA8KeyLogicImpl.mm
│           └── WebViewJSLogicImpl.mm
├── WeChatKernel
│   ├── Contact
│   │   ├── AutoSetRemarkMgr.mm
│   │   ├── CContact+BrandContact.mm
│   │   ├── ChatRoomData.mm
│   │   ├── Contact.mm
│   │   ├── ContactMgr.mm
│   │   ├── ContactOPLog.mm
│   │   ├── ContactProfileMgr.mm
│   │   ├── ContactStorage
│   │   │   ├── ContactDB.mm
│   │   │   ├── ContactExtendCode.mm
│   │   │   ├── QQContactDB.mm
│   │   │   └── QQContactMMDB.mm
│   │   ├── GetContactEventHandler.mm
│   │   ├── MMBizMenuInfo.mm
│   │   ├── QQContactMgr.mm
│   │   └── StrangerContactMgr.mm
│   ├── Group
│   │   ├── GetChatRoomMemberDetailEventHandler.mm
│   │   ├── GroupDB.mm
│   │   ├── GroupMgr.mm
│   │   └── GroupOpLog.mm
│   ├── HeadImage
│   │   ├── MMHDHeadImgDownloader.mm
│   │   ├── MMHeadImageCacher.mm
│   │   ├── MMHeadImageDownloader.mm
│   │   ├── MMHeadImageMgr+Utility.mm
│   │   ├── MMHeadImageMgr.mm
│   │   └── UploadHDHeadImg.mm
│   ├── Message
│   │   ├── Audio
│   │   │   ├── DownloadVoiceMgr.mm
│   │   │   ├── MMNewUploadVoiceMgr.mm
│   │   │   ├── MessageWrap+Voice.mm
│   │   │   ├── NetworkEvent
│   │   │   │   ├── DownloadVoiceEvent.mm
│   │   │   │   └── UploadVoiceEvent.mm
│   │   │   ├── Protocol
│   │   │   │   ├── DownloadVoicePrtl.mm
│   │   │   │   └── UploadVoicePrtl.mm
│   │   │   └── VoiceExtendCode.mm
│   │   ├── DraftController.mm
│   │   ├── Emoticon
│   │   │   ├── EmoticonManage
│   │   │   │   ├── EmoticonMgr.mm
│   │   │   │   ├── EmoticonPackageDB.mm
│   │   │   │   ├── EmoticonPackageMgr.mm
│   │   │   │   └── EmoticonSortSetting.mm
│   │   │   ├── EmoticonMessage
│   │   │   │   ├── EmojiDB.mm
│   │   │   │   ├── EmoticonDB.mm
│   │   │   │   ├── EmoticonDownloadMgr.mm
│   │   │   │   ├── EmoticonUploadMgr.mm
│   │   │   │   └── MessageWrap+Emoticon.mm
│   │   │   └── EmoticonStore
│   │   │       ├── EmoticonDescMgr.mm
│   │   │       ├── EmoticonPackageStateMgr.mm
│   │   │       ├── EmoticonRecommendMgr.mm
│   │   │       ├── EmoticonStoreItem.mm
│   │   │       ├── EmoticonStoreMgr.mm
│   │   │       └── JumpEmoticonDetailCgi.mm
│   │   ├── Image
│   │   │   ├── DownloadImageCDNMgr.mm
│   │   │   ├── DownloadImageMgr.mm
│   │   │   ├── MessageImageUtil.mm
│   │   │   ├── MessageWrap+Img.mm
│   │   │   ├── SimpleMsgInfo.mm
│   │   │   ├── UploadImageCDNMgr.mm
│   │   │   └── UploadImageMgr.mm
│   │   ├── Location
│   │   │   └── MessageWrap+Location.mm
│   │   ├── MessageDB.mm
│   │   ├── MessageMgr.mm
│   │   ├── MessagePatternCacheMgr.mm
│   │   ├── MessageWrap.mm
│   │   ├── NewArrivalCountData.mm
│   │   ├── OpenAPI
│   │   │   ├── OpenDownloadCDNMgr.mm
│   │   │   ├── OpenDownloadMgr.mm
│   │   │   ├── OpenUploadCDNMgr.mm
│   │   │   └── OpenUploadMgr.mm
│   │   ├── QQ
│   │   │   ├── QQOfflineServerTips.mm
│   │   │   ├── QQOfflineServerTipsCgi.mm
│   │   │   └── QQSessionMgr.mm
│   │   ├── Record
│   │   │   ├── RecordDownloadCDNMgr.mm
│   │   │   └── RecordUploadCDNMgr.mm
│   │   ├── ThumbDownloadMgr.mm
│   │   └── Video
│   │       ├── DownloadVideoCDNMgr.mm
│   │       ├── DownloadVideoMgr.mm
│   │       ├── MessageWrap+Video.mm
│   │       ├── NetWorkEvent
│   │       │   ├── DownloadVideoEvent.mm
│   │       │   └── UploadVideoEvent.mm
│   │       ├── Protocol
│   │       │   ├── DownloadVideoPrtl.mm
│   │       │   └── UploadVideoPrtl.mm
│   │       ├── ShortVideoDownloadMgr.mm
│   │       ├── UploadVideoCDNMgr.mm
│   │       └── UploadVideoMgr.mm
│   └── Session
│       ├── MMNewSessionMgr.mm
│       ├── MMSessionFileItem.mm
│       ├── MMSessionStorageAbstractDB.mm
│       └── SessionSortLogic.mm
├── WebServer
│   ├── Core
│   │   ├── GCDWebServer.m
│   │   ├── GCDWebServerConnection.m
│   │   ├── GCDWebServerFunctions.m
│   │   └── GCDWebServerRequest.m
│   └── Requests
│       └── GCDWebServerMultiPartFormRequest.m
└── WhatsNew
    └── whatsnew_common
        └── WhatsnewViewController.mm

