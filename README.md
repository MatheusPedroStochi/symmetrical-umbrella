<?xml version="1.0" encoding="UTF-8"?><manifest versionCode="11000" versionName="1.10.0" compileSdkVersion="30" compileSdkVersionCodename="11" package="com.world.youcinemobile" platformBuildVersionCode="30" platformBuildVersionName="11">
  <uses-sdk minSdkVersion="18" targetSdkVersion="28"/>
  <uses-permission name="android.permission.INTERNET"/>
  <uses-permission name="android.permission.ACCESS_NETWORK_STATE"/>
  <uses-permission name="android.permission.CHANGE_NETWORK_STATE"/>
  <uses-permission name="android.permission.ACCESS_WIFI_STATE"/>
  <uses-permission name="android.permission.WRITE_EXTERNAL_STORAGE"/>
  <uses-permission name="android.permission.BROADCAST_STICKY"/>
  <uses-permission name="android.permission.WAKE_LOCK"/>
  <uses-permission name="android.permission.VIBRATE"/>
  <uses-permission name="android.permission.GET_TASKS"/>
  <uses-permission name="android.permission.CAMERA"/>
  <uses-permission name="android.permission.REQUEST_INSTALL_PACKAGES"/>
  <uses-permission name="android.permission.READ_CALENDAR"/>
  <uses-permission name="android.permission.WRITE_CALENDAR"/>
  <uses-permission name="android.permission.MANAGE_EXTERNAL_STORAGE"/>
  <uses-permission name="android.permission.READ_EXTERNAL_STORAGE"/>
  <uses-permission name="android.permission.WRITE_EXTERNAL_STORAGE"/>
  <uses-permission name="android.permission.READ_MEDIA_IMAGES"/>
  <uses-permission name="android.permission.FOREGROUND_SERVICE"/>
  <uses-permission name="com.google.android.finsky.permission.BIND_GET_INSTALL_REFERRER_SERVICE"/>
  <uses-permission name="com.google.android.c2dm.permission.RECEIVE"/>
  <uses-permission name="android.permission.CHANGE_WIFI_STATE"/>
  <uses-permission name="android.permission.CHANGE_WIFI_MULTICAST_STATE"/>
  <uses-permission name="android.permission.BLUETOOTH"/>
  <application theme="MobileAppTheme" label="YouCine" icon="res/mipmap-xhdpi-v4/ic_logo.png" name="s.h.e.l.l.S" allowBackup="false" largeHeap="true" supportsRtl="true" usesCleartextTraffic="true" appComponentFactory="s.h.e.l.l.A" requestLegacyExternalStorage="true">
    <activity name="com.mobile.brasiltv.activity.LivePlayAty" screenOrientation="6" configChanges="0x2fb0" windowSoftInputMode="0x13"/>
    <activity name="com.mobile.brasiltv.activity.LiveStreamMoreAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.MatchListActivity" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.MyFavListActivity" screenOrientation="1" configChanges="0x4a0"/>
    <activity theme="AppTheme.Splash" name="com.mobile.brasiltv.activity.SplashAty" screenOrientation="1">
      <intent-filter>
        <action name="android.intent.action.MAIN"/>
        <category name="android.intent.category.LAUNCHER"/>
      </intent-filter>
      <intent-filter>
        <data scheme="sxl" host="www.youcine.com"/>
        <action name="android.intent.action.VIEW"/>
        <category name="android.intent.category.DEFAULT"/>
        <category name="android.intent.category.BROWSABLE"/>
      </intent-filter>
    </activity>
    <activity name="com.mobile.brasiltv.activity.MainAty" launchMode="2" screenOrientation="1" configChanges="0x24b0">
      <intent-filter>
        <action name="android.intent.action.VIEW"/>
        <category name="android.intent.category.DEFAULT"/>
        <category name="android.intent.category.BROWSABLE"/>
        <data scheme="https" host="youcinemobile.page.link"/>
      </intent-filter>
    </activity>
    <activity name="com.mobile.brasiltv.activity.RecordsAty" screenOrientation="1" configChanges="0x4a0"/>
    <activity name="com.mobile.brasiltv.activity.WebViewAty" screenOrientation="1" configChanges="0x4a0"/>
    <activity name="com.mobile.brasiltv.activity.ScanLoginActivity" screenOrientation="1" configChanges="0x4a0"/>
    <activity name="com.mobile.brasiltv.activity.PlayAty" launchMode="1" screenOrientation="1" configChanges="0x2fb0" windowSoftInputMode="0x13"/>
    <activity name="com.mobile.brasiltv.mine.activity.OrderAty" launchMode="2" screenOrientation="1" configChanges="0x4a0"/>
    <service label="NetService" name="com.mobile.brasiltv.service.NetService" exported="false">
      <intent-filter>
        <action name="com.swl.amobile.service.netservice"/>
      </intent-filter>
    </service>
    <meta-data name="UMENG_APPKEY" value="60507f7e6ee47d382b860dad"/>
    <meta-data name="UMENG_MSG_SECRET" value="13a544877b7e3176a4587bdecd38758a"/>
    <meta-data name="UMENG_CHANNEL" value="Umeng"/>
    <meta-data name="com.google.android.gms.ads.APPLICATION_ID" value="ca-app-pub-8403581247282419~2129662664"/>
    <meta-data name="design_width" value="750"/>
    <meta-data name="design_height" value="1334"/>
    <meta-data name="LINK_VALUE" value="b109fe3f9cd0b310655516c07fb246d2"/>
    <meta-data name="LINK_ID" value="L21907"/>
    <meta-data name="com.google.firebase.messaging.default_notification_channel_id" value="fcm_default_channel"/>
    <meta-data name="com.google.android.gms.cast.framework.OPTIONS_PROVIDER_CLASS_NAME" value="com.mobile.brasiltv.cast.CastOptionsProvider"/>
    <activity name="com.mobile.brasiltv.activity.SettingLanguageAty" screenOrientation="1"/>
    <activity theme="TransitionLanguage" name="com.mobile.brasiltv.activity.TransitionLanguageAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.LoginAty" launchMode="2" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.SelectNationAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.SettingAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.SubtitleAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.AboutAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.ExperienceCastPlayAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.FindPwdByPhoneAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.SearchAty" screenOrientation="1"/>
    <activity theme="ThemeIntroduce" name="com.mobile.brasiltv.activity.IntroduceAty" screenOrientation="1" configChanges="0x4a0"/>
    <activity name="com.mobile.brasiltv.activity.Search1Aty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.ColumnListAty" screenOrientation="1" configChanges="0xb0"/>
    <activity name="com.mobile.brasiltv.mine.activity.AccountAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.EmailAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.ChangePwdAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.ForgetPasswordAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.ScanLoginAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.RedemptionAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.PhoneBindAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.SetPassWordAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.PhoneBindSuccessAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.PhoneAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.SendEmailAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.ResetAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.VIPMemberActivity" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.EmailManagerAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.AccountBindAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.BindEmailSucAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.SetPwdOnBeAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.SetPwdOnResetAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.ResetPwdSucAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.ChangeEmailAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.MyBenefitsAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.NotificationSettingAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.SingleColumnAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.CastDeviceAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.CastModeAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.FreeGameCenterAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.mine.activity.AccountSwitchAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.SpecialAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.OrderConfirmAty" screenOrientation="1"/>
    <activity theme="TranslucentTheme" name="com.mobile.brasiltv.activity.MsgBoxAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.DMCAAty" screenOrientation="1"/>
    <activity name="com.mobile.brasiltv.activity.MatchPlayAty" screenOrientation="6" configChanges="0x2fb0" windowSoftInputMode="0x13"/>
    <service name="com.mobile.brasiltv.service.MyFirebaseMessagingService" exported="false">
      <intent-filter>
        <action name="com.google.firebase.MESSAGING_EVENT"/>
      </intent-filter>
    </service>
    <provider name="androidx.core.content.FileProvider" exported="false" authorities="com.world.youcinemobile.fileprovider" grantUriPermissions="true">
      <meta-data name="android.support.FILE_PROVIDER_PATHS" resource="file_path"/>
    </provider>
    <service name="com.mobile.brasiltv.business.upgrade.UpgradeService" exported="false"/>
    <service name="com.taobao.accs.ChannelService" exported="false" process=":channel">
      <intent-filter>
        <action name="com.taobao.accs.intent.action.SERVICE"/>
      </intent-filter>
      <intent-filter>
        <action name="com.taobao.accs.intent.action.ELECTION"/>
      </intent-filter>
    </service>
    <service name="com.taobao.accs.data.MsgDistributeService" exported="false">
      <intent-filter>
        <action name="com.taobao.accs.intent.action.RECEIVE"/>
      </intent-filter>
    </service>
    <receiver name="com.taobao.accs.EventReceiver" exported="false" process=":channel">
      <intent-filter>
        <action name="android.intent.action.BOOT_COMPLETED"/>
      </intent-filter>
      <intent-filter>
        <action name="android.net.conn.CONNECTIVITY_CHANGE"/>
      </intent-filter>
      <intent-filter>
        <action name="android.intent.action.USER_PRESENT"/>
      </intent-filter>
      <intent-filter>
        <action name="android.intent.action.PACKAGE_REMOVED"/>
        <data scheme="package"/>
      </intent-filter>
    </receiver>
    <receiver name="com.taobao.accs.ServiceReceiver" exported="false" process=":channel">
      <intent-filter>
        <action name="com.taobao.accs.intent.action.COMMAND"/>
      </intent-filter>
      <intent-filter>
        <action name="com.taobao.accs.intent.action.START_FROM_AGOO"/>
      </intent-filter>
    </receiver>
    <service name="org.android.agoo.accs.AgooService" exported="false">
      <intent-filter>
        <action name="com.taobao.accs.intent.action.RECEIVE"/>
      </intent-filter>
    </service>
    <service name="com.umeng.message.UmengIntentService" exported="false" process=":channel">
      <intent-filter>
        <action name="org.agoo.android.intent.action.RECEIVE"/>
      </intent-filter>
    </service>
    <service name="com.umeng.message.XiaomiIntentService" exported="false" process=":channel">
      <intent-filter>
        <action name="org.agoo.android.intent.action.RECEIVE"/>
      </intent-filter>
    </service>
    <receiver name="com.taobao.agoo.AgooCommondReceiver" exported="false" process=":channel">
      <intent-filter>
        <action name="com.world.youcinemobile.intent.action.COMMAND"/>
      </intent-filter>
      <intent-filter>
        <action name="android.intent.action.PACKAGE_REMOVED"/>
        <data scheme="package"/>
      </intent-filter>
    </receiver>
    <service name="com.umeng.message.UmengMessageIntentReceiverService" exported="false" process=":channel">
      <intent-filter>
        <action name="org.android.agoo.client.MessageReceiverService"/>
      </intent-filter>
    </service>
    <service name="com.google.firebase.components.ComponentDiscoveryService" exported="false" directBootAware="true">
      <meta-data name="com.google.firebase.components:com.google.firebase.dynamiclinks.ktx.FirebaseDynamicLinksKtxRegistrar" value="com.google.firebase.components.ComponentRegistrar"/>
      <meta-data name="com.google.firebase.components:com.google.firebase.messaging.ktx.FirebaseMessagingKtxRegistrar" value="com.google.firebase.components.ComponentRegistrar"/>
      <meta-data name="com.google.firebase.components:com.google.firebase.ktx.FirebaseCommonKtxRegistrar" value="com.google.firebase.components.ComponentRegistrar"/>
      <meta-data name="com.google.firebase.components:com.google.firebase.analytics.connector.internal.AnalyticsConnectorRegistrar" value="com.google.firebase.components.ComponentRegistrar"/>
      <meta-data name="com.google.firebase.components:com.google.firebase.crashlytics.ndk.CrashlyticsNdkRegistrar" value="com.google.firebase.components.ComponentRegistrar"/>
      <meta-data name="com.google.firebase.components:com.google.firebase.iid.Registrar" value="com.google.firebase.components.ComponentRegistrar"/>
      <meta-data name="com.google.firebase.components:com.google.firebase.dynamiclinks.internal.FirebaseDynamicLinkRegistrar" value="com.google.firebase.components.ComponentRegistrar"/>
      <meta-data name="com.google.firebase.components:com.google.firebase.crashlytics.CrashlyticsRegistrar" value="com.google.firebase.components.ComponentRegistrar"/>
      <meta-data name="com.google.firebase.components:com.google.firebase.messaging.FirebaseMessagingRegistrar" value="com.google.firebase.components.ComponentRegistrar"/>
      <meta-data name="com.google.firebase.components:com.google.firebase.installations.FirebaseInstallationsRegistrar" value="com.google.firebase.components.ComponentRegistrar"/>
      <meta-data name="com.google.firebase.components:com.google.firebase.datatransport.TransportRegistrar" value="com.google.firebase.components.ComponentRegistrar"/>
    </service>
    <receiver name="com.google.android.gms.cast.framework.media.MediaIntentReceiver" exported="false"/>
    <service name="com.google.android.gms.cast.framework.media.MediaNotificationService" exported="false"/>
    <service name="com.google.android.gms.cast.framework.ReconnectionService" exported="false"/>
    <activity theme="Theme.Translucent.NoTitleBar" name="com.google.android.gms.auth.api.signin.internal.SignInHubActivity" exported="false" excludeFromRecents="true"/>
    <service name="com.google.android.gms.auth.api.signin.RevocationBoundService" permission="com.google.android.gms.auth.api.signin.permission.REVOCATION_NOTIFICATION" exported="true"/>
    <receiver name="com.google.android.gms.measurement.AppMeasurementReceiver" enabled="true" exported="false"/>
    <service name="com.google.android.gms.measurement.AppMeasurementService" enabled="true" exported="false"/>
    <service name="com.google.android.gms.measurement.AppMeasurementJobService" permission="android.permission.BIND_JOB_SERVICE" enabled="true" exported="false"/>
    <activity theme="Theme.Translucent" name="com.google.android.gms.ads.AdActivity" exported="false" configChanges="0xfb0"/>
    <provider name="com.google.android.gms.ads.MobileAdsInitProvider" exported="false" authorities="com.world.youcinemobile.mobileadsinitprovider" initOrder="100"/>
    <activity theme="Theme.Translucent.NoTitleBar" name="com.google.android.gms.common.api.GoogleApiActivity" exported="false"/>
    <receiver name="com.google.firebase.iid.FirebaseInstanceIdReceiver" permission="com.google.android.c2dm.permission.SEND" exported="true">
      <intent-filter>
        <action name="com.google.android.c2dm.intent.RECEIVE"/>
      </intent-filter>
    </receiver>
    <service name="com.google.firebase.messaging.FirebaseMessagingService" exported="false" directBootAware="true">
      <intent-filter priority="-500">
        <action name="com.google.firebase.MESSAGING_EVENT"/>
      </intent-filter>
    </service>
    <provider name="com.google.firebase.provider.FirebaseInitProvider" exported="false" authorities="com.world.youcinemobile.firebaseinitprovider" initOrder="100" directBootAware="true"/>
    <meta-data name="com.google.android.gms.version" value="12451000"/>
    <service name="com.hpplay.sdk.source.process.LelinkSdkService" exported="false" process=":lelinkps">
      <intent-filter>
        <action name="com.hpplay.sdk.source.LelinkSdkService.ACTION"/>
      </intent-filter>
    </service>
    <activity theme="Theme.Translucent.NoTitleBar.Fullscreen" name="com.hpplay.sdk.source.permission.PermissionBridgeActivity" exported="false" process=":lelinkps" excludeFromRecents="true"/>
    <receiver name="com.hpplay.sdk.source.process.LelinkReceiver" exported="false" process=":lelinkps">
      <intent-filter>
        <action name="com.hpplay.source.service.close"/>
      </intent-filter>
    </receiver>
    <service name="com.taobao.accs.internal.AccsJobService" permission="android.permission.BIND_JOB_SERVICE" exported="false" process=":channel"/>
    <service name="com.taobao.accs.ChannelService$KernelService" exported="false" process=":channel"/>
    <receiver name="com.umeng.message.NotificationProxyBroadcastReceiver" exported="false"/>
    <service name="com.umeng.message.UmengMessageCallbackHandlerService" permission="android.permission.BIND_JOB_SERVICE" exported="false">
      <intent-filter>
        <action name="com.umeng.messge.registercallback.action"/>
      </intent-filter>
      <intent-filter>
        <action name="com.umeng.message.enablecallback.action"/>
      </intent-filter>
      <intent-filter>
        <action name="com.umeng.message.disablecallback.action"/>
      </intent-filter>
      <intent-filter>
        <action name="com.umeng.message.message.handler.action"/>
      </intent-filter>
      <intent-filter>
        <action name="com.umeng.message.message.sendmessage.action"/>
      </intent-filter>
    </service>
    <service name="com.umeng.message.UmengDownloadResourceService" permission="android.permission.BIND_JOB_SERVICE" exported="false"/>
    <provider name="com.umeng.message.provider.MessageProvider" exported="false" authorities="com.world.youcinemobile.umeng.message">
      <grant-uri-permission pathPattern=".*"/>
    </provider>
    <activity theme="UPushNotifyActivity" name="com.umeng.message.notify.UPushMessageNotifyActivity" exported="false" taskAffinity="com.world.youcinemobile.umeng.push" excludeFromRecents="true" launchMode="2" screenOrientation="3" noHistory="true"/>
    <activity-alias name="com.umeng.message.UMessageNotifyActivity" exported="true" taskAffinity="com.world.youcinemobile.umeng.push" targetActivity="com.umeng.message.notify.UPushMessageNotifyActivity">
      <intent-filter>
        <action name="com.umeng.message.action.notify"/>
      </intent-filter>
    </activity-alias>
    <activity theme="UPushNotifyActivity" name="com.umeng.message.UPushBoardActivity" exported="false" taskAffinity="com.world.youcinemobile.umeng.banner" excludeFromRecents="true" launchMode="2" screenOrientation="3" noHistory="true"/>
    <service name="com.google.android.datatransport.runtime.backends.TransportBackendDiscovery" exported="false">
      <meta-data name="backend:com.google.android.datatransport.cct.CctBackendFactory" value="cct"/>
    </service>
    <service name="com.google.android.datatransport.runtime.scheduling.jobscheduling.JobInfoSchedulerService" permission="android.permission.BIND_JOB_SERVICE" exported="false"/>
    <receiver name="com.google.android.datatransport.runtime.scheduling.jobscheduling.AlarmManagerSchedulerBroadcastReceiver" exported="false"/>
    <receiver label="NetworkConnection" name="com.qiniu.android.dns.NetworkReceiver" exported="false">
      <intent-filter>
        <action name="android.net.conn.CONNECTIVITY_CHANGE"/>
        <action name="android.intent.action.USER_PRESENT"/>
      </intent-filter>
    </receiver>
  </application>
</manifest>
