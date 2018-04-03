<?xml version="1.0" encoding="utf-8" standalone="no"?>
<widget version="1.0.0">
    <statusbar color="#00000000"/>
    <config desc="statusBar" type="STATUSBARSTYLE">
        <permission platform="iOS" info="StatusBarStyle" value="Light"/>
        <permission platform="iOS" info="StatusBarStyleIOS7" value="1"/>
    </config>
    <config desc="coracle" type="URLSCHEME">
        <urlScheme name="corQQ" schemes="['tencent1105924409','QQ41eb1139','mqzone']"/>
    </config>
    <config desc="corBaiduMap" type="KEY">
        <param platform="iOS"  name="$corBaiduMap_APIKey$" value="qwerty"/>
        <param platform="Android"  name="$corBaiduMap_APIKey$" value="123456"/>
    </config>
    <config desc="backgroundConfig" type="AUTHORITY">
        <permission platform="iOS" info="backgroundMode" flag="1"/>
        <permission platform="iOS" info="backgroundMode" flag="2"/>
    </config>
    <config type="KEYCHAIN">
        <permission platform="iOS" info="com.coracle.demo"/>
        <permission platform="iOS" info="com.coracle.debug"/>
    </config>
    <config desc="privacyConfig" type="AUTHORITY">
        <permission platform="iOS" info="privacy" type="camera">
            <string>录制视频需要使用摄像头</string>
        </permission>
        <permission platform="iOS" info="privacy" type="microphone">
            <string>录制视频需要使用麦克风</string>
        </permission>
    </config>
</widget>
