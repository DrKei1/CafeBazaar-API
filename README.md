# <img src="https://s4.uupload.ir/files/bazaaar2_eba6.jpg" width="30px" height="30px"> CafeBazaar-API

A List Of CafeBazaar API sample that intercepted by HTTP Toolkit

# List OF API:

CafeBazaar API
CafeBazaar API Sample By @Dr_key


Open App
#1 RegisterDeviceRequest
#2 GetUpgradableAppsRequest
#3 GetAppConfigRequest
#4 register c2dm
#5 GetPageV2Request
#6 RegisterDeviceRequest
Click on App (in home page)
#8 AppDetailsV2Request
#7 ReviewRequest
Click on Download Button
#8 AppDownloadInfoRequest
#9 Downloading app
#10 SubmitInstallFromBazaarRequest
      New Session
Search
#12 PredictionRequest
#13 SearchV2Request
نصب مستقیم از سرچ
#14 appDownloadInfoRequest
#15 SubmitInstallFromBazaarRequest
نصب غیرمستقیم از سرچ
#16 AppDetailsV2Request
#17 ReviewRequest
#18 AppDownloadInfoRequest
#19 APK Downloading...
#20 SubmitInstallFromBazaarRequest




🟢 Open App
#1 RegisterDeviceRequest
https://api.cafebazaar.ir/rest-v1/process/RegisterDeviceRequest

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "y0afm27vR3SxHA6BZHunaQ",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "registerDeviceRequest": {
      "gcmID": "",
      "systemLanguage": "fa"
    }
  }
}




Response:
{
  "properties": {
    "statusCode": 200,
    "maxAge": 0,
    "etag": "",
    "errorMessage": "",
    "errorCode": 0
  },
  "internalProperties": null,
  "singleReply": {
    "registerDeviceReply": {
      "deviceID": 648829726
    }
  }
}





#2 GetUpgradableAppsRequest
https://api.cafebazaar.ir/rest-v1/process/GetUpgradableAppsRequest

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "y0afm27vR3SxHA6BZHunaQ",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "getUpgradableAppsRequest": {
      "deviceID": -1,
      "installedAppsInfo": [
        {
          "installDelta": 1323623,
          "isPreInstall": false,
          "packageName": "com.android.browser",
          "signs": [
            "FA4C9115"
          ],
          "updateDelta": 1323623,
          "versionCode": 22
        },
        {
          "installDelta": 419,
          "isPreInstall": false,
          "packageName": "de.robv.android.xposed.installer",
          "signs": [
            "2E8C9965"
          ],
          "updateDelta": 419,
          "versionCode": 43
        },
        {
          "installDelta": 1323627,
          "isPreInstall": false,
          "packageName": "com.android.providers.downloads.ui",
          "signs": [
            "FA4C9115"
          ],
          "updateDelta": 1323627,
          "versionCode": 22
        },
        {
          "installDelta": 1818175,
          "isPreInstall": false,
          "packageName": "com.android.vending",
          "signs": [
            "2CED5788"
          ],
          "updateDelta": 370,
          "versionCode": 82242510
        },
        {
          "installDelta": 411,
          "isPreInstall": false,
          "packageName": "mobi.acpm.inspeckage",
          "signs": [
            "A8016A9F"
          ],
          "updateDelta": 411,
          "versionCode": 10
        },
        {
          "installDelta": 387,
          "isPreInstall": false,
          "packageName": "com.farsitel.bazaar",
          "signs": [
            "AA3654B2"
          ],
          "updateDelta": 387,
          "versionCode": 801600
        },
        {
          "installDelta": 1323623,
          "isPreInstall": false,
          "packageName": "com.android.gallery3d",
          "signs": [
            "FA4C9115"
          ],
          "updateDelta": 1323623,
          "versionCode": 40030
        },
        {
          "installDelta": 1818157,
          "isPreInstall": false,
          "packageName": "com.google.android.gms",
          "signs": [
            "2CED5788"
          ],
          "updateDelta": 1818157,
          "versionCode": 12529013
        },
        {
          "installDelta": 1323623,
          "isPreInstall": false,
          "packageName": "com.cyanogenmod.filemanager",
          "signs": [
            "FA4C9115"
          ],
          "updateDelta": 1323623,
          "versionCode": 104
        },
        {
          "installDelta": 1322781,
          "isPreInstall": false,
          "packageName": "com.facebook.lite",
          "signs": [
            "C86FA2B9"
          ],
          "updateDelta": 1322781,
          "versionCode": 131057094
        },
        {
          "installDelta": 5,
          "isPreInstall": false,
          "packageName": "tech.httptoolkit.android.v1",
          "signs": [
            "665E8C3D"
          ],
          "updateDelta": 5,
          "versionCode": 20
        },
        {
          "installDelta": 1323621,
          "isPreInstall": false,
          "packageName": "com.android.settings",
          "signs": [
            "FA4C9115"
          ],
          "updateDelta": 1323621,
          "versionCode": 22
        },
        {
          "installDelta": 419,
          "isPreInstall": false,
          "packageName": "eu.chainfire.supersu",
          "signs": [
            "FAA5AF81"
          ],
          "updateDelta": 419,
          "versionCode": 279
        },
        {
          "installDelta": 1323641,
          "isPreInstall": false,
          "packageName": "com.google.android.play.games",
          "signs": [
            "2CED5788"
          ],
          "updateDelta": 1323641,
          "versionCode": 87040070
        }
      ],
      "sdkVersion": 22
    }
  }
}




Response:
{
  "properties": {
    "statusCode": 200,
    "maxAge": 0,
    "etag": "",
    "errorMessage": "",
    "errorCode": 0
  },
  "internalProperties": null,
  "singleReply": {
    "getUpgradableAppsReply": {
      "upgradableApps": [
        {
          "packageName": "com.farsitel.bazaar",
          "versionName": "14.1.0",
          "versionCode": 1400100,
          "isFree": "0",
          "price": 0,
          "size": "11630981",
          "iconUrl": "https://s.cafebazaar.ir/images/icons/com.farsitel.bazaar-1e466c99-7809-4062-a0e5-388147d475aa_72x72.webp",
          "name": {
            "en": "Bazaar",
            "fa": "بازار"
          },
          "originalVerboseSize": {
            "en": "11 MB",
            "fa": "۱۱ مگابایت"
          },
          "verboseSize": {
            "en": "11 MB",
            "fa": "۱۱ مگابایت"
          },
          "latestUpdateDate": {
            "en": "2021 August 16",
            "fa": "۲۵ مرداد ۱۴۰۰"
          },
          "changelog": {
            "en": "Redesign the video playback page\nAdded the ability to change the subtitle font size in the video player\nAdded the ability to save playback quality in video\nAdded the ability to receive and display Bazaar badges\nAdded description for rejected comments\nImproved search functionality on the app and video pages\nFixed an issue with video playback in the episode list\nImprovement in functionality\nSome changes in UI\nFixed some bugs and problems",
            "fa": "بازطراحی صفحه‌ی پخش ویدیو\nاضافه شدن امکان تغییر اندازه فونت زیرنویس در پخش ویدیو\nاضافه شدن امکان ذخیره‌ی کیفیت پخش در ویدیو\nاضافه شدن امکان دریافت و نمایش مدال‌های بازار\nاضافه شدن توضیحات برای نظرات رد شده\nبهبود عملکرد جستجو در صفحات برنامه و ویدیو\nرفع یک مشکل در پخش ویدیو در لیست اپیزودها\nبرخی بهبودهای عملکردی\nبرخی تغییرات ظاهری\nرفع برخی مشکلات جزئی"
          },
          "smartUpdate": false,
          "VerboseSizeDiff": null
        },
        {
          "packageName": "com.google.android.play.games",
          "versionName": "2021.06.27260 (385628067.385628067-000300)",
          "versionCode": 272600030,
          "isFree": "0",
          "price": 0,
          "size": "18922220",
          "iconUrl": "https://s.cafebazaar.ir/images/icons/com.google.android.play.games-4e8d3be9-3939-4651-89fd-a4aeeea2da4c_72x72.webp",
          "name": {
            "en": "Google Play Games",
            "fa": "Google Play Games"
          },
          "originalVerboseSize": {
            "en": "18 MB",
            "fa": "۱۸ مگابایت"
          },
          "verboseSize": {
            "en": "18 MB",
            "fa": "۱۸ مگابایت"
          },
          "latestUpdateDate": {
            "en": "2021 July 22",
            "fa": "۳۱ تیر ۱۴۰۰"
          },
          "changelog": {
            "en": "",
            "fa": ""
          },
          "smartUpdate": false,
          "VerboseSizeDiff": null
        }
      ],
      "maliciousApps": []
    }
  }
}






#3 GetAppConfigRequest
https://api.cafebazaar.ir/rest-v1/process/GetAppConfigRequest

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "y0afm27vR3SxHA6BZHunaQ",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "getAppConfigRequest": {}
  }
}




Response:
{
  "properties": {
    "statusCode": 200,
    "maxAge": 0,
    "etag": "",
    "errorMessage": "",
    "errorCode": 0
  },
  "internalProperties": null,
  "singleReply": {
    "getAppConfigReply": {
      "search": {
        "isSearchInVideoHomeVisible": false,
        "isSearchFiltersVisible": false,
        "searchFiltersData": [
          {
            "textFa": "همه",
            "textEn": "All",
            "scope": ""
          }
        ]
      },
      "discovery": {
        "isTopChartsVisible": true,
        "kidsPreference": {
          "isVisible": true
        },
        "tabBarsPreference": [
          {
            "slug": "home",
            "tabIconUrl": "https://cafedata.kise.roo.cloud/menus/home_grey_96x96.png",
            "titleEn": "Home",
            "titleFa": "خانه",
            "isDefault": true,
            "pressedIconURL": "",
            "localIcon": "home-new",
            "backupIcon": "",
            "landMemorable": true
          },
          {
            "slug": "videos-home",
            "tabIconUrl": "https://cafedata.kise.roo.cloud/menus/video_grey_96x96.png",
            "titleEn": "Video",
            "titleFa": "ویدیو",
            "isDefault": false,
            "pressedIconURL": "",
            "localIcon": "video-new",
            "backupIcon": "",
            "landMemorable": true
          },
          {
            "slug": "categories",
            "tabIconUrl": "https://cafedata.kise.roo.cloud/menus/category_grey_96x96.png",
            "titleEn": "Categories",
            "titleFa": "دسته‌ها",
            "isDefault": false,
            "pressedIconURL": "",
            "localIcon": "category-new",
            "backupIcon": "",
            "landMemorable": false
          },
          {
            "slug": "search",
            "tabIconUrl": "https://cafedata.kise.roo.cloud/menus/search_grey_96x96.png",
            "titleEn": "Search",
            "titleFa": "جستجو",
            "isDefault": false,
            "pressedIconURL": "",
            "localIcon": "search-new",
            "backupIcon": "",
            "landMemorable": false
          },
          {
            "slug": "myBazaar",
            "tabIconUrl": "https://cafedata.kise.roo.cloud/menus/profile_grey_96x96.png",
            "titleEn": "My Bazaar",
            "titleFa": "بازار من",
            "isDefault": false,
            "pressedIconURL": "",
            "localIcon": "my-bazaar-new",
            "backupIcon": "",
            "landMemorable": false
          }
        ],
        "isSearchBarEnabled": false,
        "landingTabPreference": 0
      },
      "core": {
        "bazaarLatestVersionCode": "1000000",
        "forceUpdate": {
          "isActive": false,
          "isDirectLink": false,
          "link": ""
        },
        "softUpdate": {
          "isActive": false,
          "timeInterval": 86400000
        }
      },
      "video": {},
      "payment": {
        "directDebitPreference": {
          "isVisible": true
        },
        "postpaidCreditPreference": {
          "isVisible": false
        }
      },
      "delivery": {
        "isUpdateAllEnabled": true,
        "review": {
          "maxLength": 300
        },
        "downloadRecoveryActive": true,
        "noActivityLauncherUpdateActive": true
      }
    }
  }
}





#4 register c2dm
https://android.clients.google.com/c2dm/register3

Request:
X-subtype=9004572526&sender=9004572526&X-app_ver=801600&X-osv=22&X-cliv=fiid-20.0.2&X-gmsv=12529013&X-appid=dd2tiTaoV-I&X-scope=*&X-gmp_app_id=1%3A9004572526%3Aandroid%3Aef661477883c810d&X-Firebase-Client=fire-android%2F+kotlin%2F1.3.72+fire-iid%2F20.0.2+fire-core%2F19.3.0&X-Firebase-Client-Log-Type=3&X-app_ver_name=8.16.0&app=com.farsitel.bazaar&device=4217825771275038693&cert=7754504df5ba2b60dbe8c2b2aaef2b95aa3654b2&app_ver=801600&info=U0MrmKBCQ2EQoLPgN7e-uDATG-yzvBc&gcm_ver=12529013


Response:
token=dd2tiTaoV-I:APA91bFRQLDWMmmbW6KM2HIcBoLh9_Eh_wpjEsSMUWzp9vSFWRdjMC1XbJVKJw7xQXISYP1WpW4EfWa6OjE-nv0U4eEhAve4WuyrJ6MVVBP70V89IuyyI2nhK1r_XJHI12p3sOnQo3rX



#5 GetPageV2Request
https://api.cafebazaar.ir/rest-v1/process/GetPageV2Request

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "y0afm27vR3SxHA6BZHunaQ",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "getPageV2Request": {
      "path": "home",
      "referrers": []
    }
  }
}





Response : Logn text! See More»»

#6 RegisterDeviceRequest
https://api.cafebazaar.ir/rest-v1/process/RegisterDeviceRequest

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "y0afm27vR3SxHA6BZHunaQ",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "registerDeviceRequest": {
      "gcmID": "dd2tiTaoV-I:APA91bFRQLDWMmmbW6KM2HIcBoLh9_Eh_wpjEsSMUWzp9vSFWRdjMC1XbJVKJw7xQXISYP1WpW4EfWa6OjE-nv0U4eEhAve4WuyrJ6MVVBP70V89IuyyI2nhK1r_XJHI12p3sOnQo3rX",
      "systemLanguage": "fa"
    }
  }
}




Response:
{
  "properties": {
    "statusCode": 200,
    "maxAge": 0,
    "etag": "",
    "errorMessage": "",
    "errorCode": 0
  },
  "internalProperties": null,
  "singleReply": {
    "registerDeviceReply": {
      "deviceID": 648829726
    }
  }
}




🟢 Click App (in home page)
#7 AppDetailsV2Request
https://api.cafebazaar.ir/rest-v1/process/AppDetailsV2Request

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "y0afm27vR3SxHA6BZHunaQ",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "appDetailsV2Request": {
      "packageName": "ir.divar",
      "referrers": [
        {
          "type": 11,
          "extraJson": "{\"service\":\"vitrin\",\"slug\":\"home\"}"
        },
        {
          "type": 21,
          "extraJson": "{\"service\":\"vitrin\",\"slug\":\"home\"}"
        },
        {
          "type": 1,
          "extraJson": "{\"service\":\"vitrin\",\"index\":1,\"title\":\"برنامه‌های پیشنهادی برای شما\",\"source\":\"normal\",\"is_shuffled\":false,\"referrer_identifier\":\"external_Recommended Apps For You_\"}"
        },
        {
          "type": 2,
          "extraJson": "{\"service\":\"vitrin\",\"index\":0,\"referrer_identifier\":\"\"}"
        }
      ]
    }
  }
}




Response : Logn text! See More»»

#8 ReviewRequest
https://api.cafebazaar.ir/rest-v1/process/ReviewRequest

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "y0afm27vR3SxHA6BZHunaQ",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "reviewRequest": {
      "end": 3,
      "packageName": "ir.divar",
      "sortType": "",
      "start": 0
    }
  }
}




Response:
{"properties":{"statusCode":200,"maxAge":0,"etag":"","errorMessage":"","errorCode":0},"internalProperties":null,"singleReply":{"reviewReply":{"reviews":[{"id":121058108,"user":"noori","comment":"برنامه خوبیه اما باید نظارت بیشتر بشه چون خیلی بیشتر برا مزاحمت برای خانم ها میان لطفا رسیدگی کنید","likes":30,"total":52,"rate":2,"versionCode":230006080,"date":"۱۴۰۰/۰۶/۱۰","reply":null,"likedByMe":0,"accountID":"f93d2f25-78ad-4384-bb73-d4900d8a42cf","badgeIconURL":"","avatarURL":"https://35863b3675871c5199d58bc2f1d8fe54.cdn.cafebazaar.cloud/avatars/ic_default_144dp.png","userRepliesCount":0,"userRepliesAvatarUrls":[],"fromDeveloper":false},{"id":121010524,"user":"فرخ","comment":"خوبه...ولی قبلا بهتر بود","likes":23,"total":44,"rate":3,"versionCode":230006080,"date":"۱۴۰۰/۰۶/۰۹","reply":null,"likedByMe":0,"accountID":"77bf9002-98cc-4ef3-ad5d-ac5df106af09","badgeIconURL":"","avatarURL":"https://35863b3675871c5199d58bc2f1d8fe54.cdn.cafebazaar.cloud/avatars/ic_default_144dp.png","userRepliesCount":0,"userRepliesAvatarUrls":[],"fromDeveloper":false},{"id":121061261,"user":"مهدی","comment":"با سلام عرض ادب اول اینکه ممنون از برنامه نویس این برنامه کاربردی که واقعا یکی از نیازهای مردمی می باشد مورد بعدی اینکه یه ایراد بزرگی که این برنامه داره اینکه بی دلیل آگهی رو حذف میکنه بنده آگهی دادم ۲۵ هزار تومان از بنده کسر شده ۲۴ ساعت آگهی فعال نبود حذف شد ... مگه مردم پولشان رو پیدا کردن...","likes":33,"total":41,"rate":1,"versionCode":230006080,"date":"۱۴۰۰/۰۶/۱۰","reply":null,"likedByMe":0,"accountID":"78dc1e76-ee19-4e8d-8e3c-d98ee4ce3480","badgeIconURL":"","avatarURL":"https://35863b3675871c5199d58bc2f1d8fe54.cdn.cafebazaar.cloud/avatars/ic_default_144dp.png","userRepliesCount":0,"userRepliesAvatarUrls":[],"fromDeveloper":false}],"nextPageCursor":""}}}


🟢 Click Download Button
#9 AppDownloadInfoRequest
https://api.cafebazaar.ir/rest-v1/process/AppDownloadInfoRequest

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "y0afm27vR3SxHA6BZHunaQ",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "appDownloadInfoRequest": {
      "downloadStatus": 1,
      "packageName": "ir.divar",
      "referrers": [
        {
          "type": 11,
          "extraJson": "{\"service\":\"vitrin\",\"slug\":\"home\"}"
        },
        {
          "type": 21,
          "extraJson": "{\"service\":\"vitrin\",\"slug\":\"home\"}"
        },
        {
          "type": 1,
          "extraJson": "{\"service\":\"vitrin\",\"index\":1,\"title\":\"برنامه‌های پیشنهادی برای شما\",\"source\":\"normal\",\"is_shuffled\":false,\"referrer_identifier\":\"external_Recommended Apps For You_\"}"
        },
        {
          "type": 2,
          "extraJson": "{\"service\":\"vitrin\",\"index\":0,\"referrer_identifier\":\"\"}"
        },
        {
          "type": 17,
          "extraJson": "{\"service\":\"sejel\",\"package_name\":\"ir.divar\"}"
        }
      ]
    }
  }
}




Response:
{
  "properties": {
    "statusCode": 200,
    "maxAge": 0,
    "etag": "",
    "errorMessage": "",
    "errorCode": 0
  },
  "internalProperties": null,
  "singleReply": {
    "appDownloadInfoReply": {
      "token": "129394260818.apk?expire=1631495553&token=fa1882ae26fde7e7acddf77b868922f1&a=",
      "hashCode": "e035e24c80a10a4a4e802c182eb655b062e036e0",
      "cdnPrefix": [
        "https://appcdn.cafebazaar.ir/"
      ],
      "ipAddress": "31.14.90.26",
      "packageSize": "19937814",
      "versionCode": 230006080,
      "multiConnectionDownload": true,
      "compatibleDevices": [],
      "packageDiffs": [],
      "baseReferrers": [],
      "hasSplits": false,
      "hasAdditionalFiles": false,
      "splits": [],
      "additionalFiles": [],
      "installationSize": "29906721",
      "installType": 0
    }
  }
}





#10 Downloading app
https://appcdn.cafebazaar.ir/apks/129394260818.apk?expire=1631495553&token=fa1882ae26fde7e7acddf77b868922f1&a=.apk

Request (GET)
https://appcdn.cafebazaar.ir/apks/129394260818.apk?expire=1631495553&token=fa1882ae26fde7e7acddf77b868922f1&a=.apk


Response:
apk file



#11 SubmitInstallFromBazaarRequest
https://api.cafebazaar.ir/rest-v1/process/SubmitInstallFromBazaarRequest

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "y0afm27vR3SxHA6BZHunaQ",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "submitInstallFromBazaarRequest": {
      "isAd": false,
      "packageName": "ir.divar",
      "referrer": "[{\"type\":11,\"extraJson\":\"{\\\"service\\\":\\\"vitrin\\\",\\\"slug\\\":\\\"home\\\"}\"}, {\"type\":21,\"extraJson\":\"{\\\"service\\\":\\\"vitrin\\\",\\\"slug\\\":\\\"home\\\"}\"}, {\"type\":1,\"extraJson\":\"{\\\"service\\\":\\\"vitrin\\\",\\\"index\\\":1,\\\"title\\\":\\\"برنامه‌های پیشنهادی برای شما\\\",\\\"source\\\":\\\"normal\\\",\\\"is_shuffled\\\":false,\\\"referrer_identifier\\\":\\\"external_Recommended Apps For You_\\\"}\"}, {\"type\":2,\"extraJson\":\"{\\\"service\\\":\\\"vitrin\\\",\\\"index\\\":0,\\\"referrer_identifier\\\":\\\"\\\"}\"}, {\"type\":17,\"extraJson\":\"{\\\"service\\\":\\\"sejel\\\",\\\"package_name\\\":\\\"ir.divar\\\"}\"}]",
      "versionCode": 230006080
    }
  }
}




Response:
{
  "properties": {
    "statusCode": 200,
    "maxAge": 0,
    "etag": "",
    "errorMessage": "",
    "errorCode": 0
  },
  "internalProperties": null,
  "singleReply": {
    "submitInstallFromBazaarReply": {}
  }
}




➖New Session
🟢 Search
 #12 PredictionRequest
https://api.cafebazaar.ir/rest-v1/process/PredictionRequest

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "1-sLNSXxTem2-VrMAVnueA",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "predictionRequest": {
      "text": "تافل"
    }
  }
}




Response:
{
  "properties": {
    "statusCode": 200,
    "maxAge": 1,
    "etag": "",
    "errorMessage": "",
    "errorCode": 0
  },
  "internalProperties": null,
  "singleReply": {
    "predictionReply": {
      "items": [
        {
          "title": "تافل باز اموزش کلمات زبان toefl",
          "type": "prediction",
          "subtitle": "",
          "referrer": {
            "type": 14,
            "extraJson": "{\"index\":0,\"text\":\"تافل\",\"test_group\":\"\",\"source\":\"prediction\"}"
          }
        },
        {
          "title": "تافل 1400",
          "type": "prediction",
          "subtitle": "",
          "referrer": {
            "type": 14,
            "extraJson": "{\"index\":1,\"text\":\"تافل\",\"test_group\":\"\",\"source\":\"prediction\"}"
          }
        },
        {
          "title": "تافل ایلتس و جی ار ای صوتی تصویری",
          "type": "prediction",
          "subtitle": "",
          "referrer": {
            "type": 14,
            "extraJson": "{\"index\":2,\"text\":\"تافل\",\"test_group\":\"\",\"source\":\"prediction\"}"
          }
        },
        {
          "title": "تافل را قورت بده",
          "type": "prediction",
          "subtitle": "",
          "referrer": {
            "type": 14,
            "extraJson": "{\"index\":3,\"text\":\"تافل\",\"test_group\":\"\",\"source\":\"prediction\"}"
          }
        }
      ],
      "baseReferrers": []
    }
  }
}




 #13 SearchV2Request
https://api.cafebazaar.ir/rest-v1/process/SearchV2Request

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "1-sLNSXxTem2-VrMAVnueA",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "searchV2Request": {
      "canReplaceSpellCheckerQuery": true,
      "language": "fa",
      "query": "تافل",
      "referrers": [],
      "scope": "general"
    }
  }
}




Response:
Long Text : See More»»


🟣 نصب مستقیم از سرچ
#14 AppDownloadInfoRequest

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "1-sLNSXxTem2-VrMAVnueA",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "appDownloadInfoRequest": {
      "downloadStatus": 1,
      "packageName": "com.himia.learn.english.toefl",
      "referrers": [
        {
          "type": 12,
          "extraJson": "{\"AdInfo\":\"{\\\"ad_uuid\\\":\\\"edc9d8b8-030f-4b59-bba6-b249a24f54d5\\\",\\\"ad_type\\\":\\\"search\\\",\\\"search_query\\\":\\\"تافل\\\",\\\"package_name\\\":\\\"ir.gharar\\\",\\\"bid_id\\\":\\\"120045\\\",\\\"campaign_id\\\":\\\"8515\\\",\\\"bid_query\\\":\\\"زبان انگلیسی\\\",\\\"install_cost\\\":\\\"3X1UT9jDVN8IIjvMooS/rpD69ctvARGcS48gEr9E4wg=\\\",\\\"show\\\":true,\\\"user_has_app\\\":false,\\\"is_detailed\\\":false,\\\"ad_detail_subtitle\\\":\\\"\\\",\\\"suggested\\\":false,\\\"impression_tracker_link\\\":\\\"https://view.adtrace.io/impression/91urw6e\\\",\\\"user_agent\\\":\\\"Bazaar/801600 (Android 22; samsung SM-G955N)\\\",\\\"participation_type\\\":\\\"relevant\\\",\\\"ab_test_flags\\\":{\\\"Bayesian_1\\\":false,\\\"Bayesian_2\\\":true,\\\"Bayesian_3\\\":false,\\\"Bayesian_4\\\":false,\\\"Bayesian_5\\\":false,\\\"Bayesian_6\\\":false,\\\"adrow\\\":true,\\\"is_detailed_1\\\":false,\\\"is_detailed_2\\\":false,\\\"no_ad\\\":false,\\\"no_rtb\\\":false,\\\"run_by_bayesian\\\":false,\\\"smart_budget\\\":false,\\\"tractor\\\":true}}\",\"Extra\":\"{\\\"filter\\\":\\\"general\\\",\\\"must_have_query\\\":\\\"\\\",\\\"normalized_query\\\":\\\"تافل\\\"}\",\"IsKid\":\"false\",\"SearchQuery\":\"تافل\",\"Slug\":\"search\",\"TestGroup\":\"engine_pop:revised_pop;filter:o;install_count:o;result-display:o;search:bar;watch-later:o\"}"
        },
        {
          "type": 2,
          "extraJson": "{\"visit_index\":2,\"is_ad\":false,\"item_type\":\"app\",\"row_type\":\"app\"}"
        }
      ]
    }
  }
}




Response:
{
  "properties": {
    "statusCode": 200,
    "maxAge": 0,
    "etag": "",
    "errorMessage": "",
    "errorCode": 0
  },
  "internalProperties": null,
  "singleReply": {
    "appDownloadInfoReply": {
      "token": "844033238985.apk?expire=1632216756&token=8fc315eaa0eb6a70c6dd7674b326926f&a=",
      "hashCode": "ddd337cc80dae5df530c5d6c8707e73ec9451fe7",
      "cdnPrefix": [
        "https://appcdn.cafebazaar.ir/"
      ],
      "ipAddress": "31.14.92.31",
      "packageSize": "8215356",
      "versionCode": 4,
      "multiConnectionDownload": true,
      "compatibleDevices": [],
      "packageDiffs": [],
      "baseReferrers": [],
      "hasSplits": false,
      "hasAdditionalFiles": false,
      "splits": [],
      "additionalFiles": [],
      "installationSize": "12323034",
      "installType": 0
    }
  }
}





 #15 SubmitInstallFromBazaarRequest
https://api.cafebazaar.ir/rest-v1/process/SubmitInstallFromBazaarRequest

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "1-sLNSXxTem2-VrMAVnueA",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "submitInstallFromBazaarRequest": {
      "isAd": false,
      "packageName": "com.himia.learn.english.toefl",
      "referrer": "[{\"type\":12,\"extraJson\":\"{\\\"AdInfo\\\":\\\"{\\\\\\\"ad_uuid\\\\\\\":\\\\\\\"edc9d8b8-030f-4b59-bba6-b249a24f54d5\\\\\\\",\\\\\\\"ad_type\\\\\\\":\\\\\\\"search\\\\\\\",\\\\\\\"search_query\\\\\\\":\\\\\\\"تافل\\\\\\\",\\\\\\\"package_name\\\\\\\":\\\\\\\"ir.gharar\\\\\\\",\\\\\\\"bid_id\\\\\\\":\\\\\\\"120045\\\\\\\",\\\\\\\"campaign_id\\\\\\\":\\\\\\\"8515\\\\\\\",\\\\\\\"bid_query\\\\\\\":\\\\\\\"زبان انگلیسی\\\\\\\",\\\\\\\"install_cost\\\\\\\":\\\\\\\"3X1UT9jDVN8IIjvMooS\\/rpD69ctvARGcS48gEr9E4wg=\\\\\\\",\\\\\\\"show\\\\\\\":true,\\\\\\\"user_has_app\\\\\\\":false,\\\\\\\"is_detailed\\\\\\\":false,\\\\\\\"ad_detail_subtitle\\\\\\\":\\\\\\\"\\\\\\\",\\\\\\\"suggested\\\\\\\":false,\\\\\\\"impression_tracker_link\\\\\\\":\\\\\\\"https:\\/\\/view.adtrace.io\\/impression\\/91urw6e\\\\\\\",\\\\\\\"user_agent\\\\\\\":\\\\\\\"Bazaar\\/801600 (Android 22; samsung SM-G955N)\\\\\\\",\\\\\\\"participation_type\\\\\\\":\\\\\\\"relevant\\\\\\\",\\\\\\\"ab_test_flags\\\\\\\":{\\\\\\\"Bayesian_1\\\\\\\":false,\\\\\\\"Bayesian_2\\\\\\\":true,\\\\\\\"Bayesian_3\\\\\\\":false,\\\\\\\"Bayesian_4\\\\\\\":false,\\\\\\\"Bayesian_5\\\\\\\":false,\\\\\\\"Bayesian_6\\\\\\\":false,\\\\\\\"adrow\\\\\\\":true,\\\\\\\"is_detailed_1\\\\\\\":false,\\\\\\\"is_detailed_2\\\\\\\":false,\\\\\\\"no_ad\\\\\\\":false,\\\\\\\"no_rtb\\\\\\\":false,\\\\\\\"run_by_bayesian\\\\\\\":false,\\\\\\\"smart_budget\\\\\\\":false,\\\\\\\"tractor\\\\\\\":true}}\\\",\\\"Extra\\\":\\\"{\\\\\\\"filter\\\\\\\":\\\\\\\"general\\\\\\\",\\\\\\\"must_have_query\\\\\\\":\\\\\\\"\\\\\\\",\\\\\\\"normalized_query\\\\\\\":\\\\\\\"تافل\\\\\\\"}\\\",\\\"IsKid\\\":\\\"false\\\",\\\"SearchQuery\\\":\\\"تافل\\\",\\\"Slug\\\":\\\"search\\\",\\\"TestGroup\\\":\\\"engine_pop:revised_pop;filter:o;install_count:o;result-display:o;search:bar;watch-later:o\\\"}\"}, {\"type\":2,\"extraJson\":\"{\\\"visit_index\\\":2,\\\"is_ad\\\":false,\\\"item_type\\\":\\\"app\\\",\\\"row_type\\\":\\\"app\\\"}\"}]",
      "versionCode": 4
    }
  }
}




Response:
{
  "properties": {
    "statusCode": 200,
    "maxAge": 0,
    "etag": "",
    "errorMessage": "",
    "errorCode": 0
  },
  "internalProperties": null,
  "singleReply": {
    "submitInstallFromBazaarReply": {}
  }
}




 


🟣 نصب غیرمستقیم از سرچ

#16 AppDetailsV2Request
https://api.cafebazaar.ir/rest-v1/process/AppDetailsV2Request

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "1-sLNSXxTem2-VrMAVnueA",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "appDetailsV2Request": {
      "packageName": "com.himia.learn.english.toefl",
      "referrers": [
        {
          "type": 14,
          "extraJson": "{\"index\":0,\"text\":\"\",\"test_group\":\"\",\"source\":\"history\"}"
        },
        {
          "type": 12,
          "extraJson": "{\"AdInfo\":\"{\\\"ad_uuid\\\":\\\"a92fcf71-4f48-49c8-ae39-52054655f2f0\\\",\\\"ad_type\\\":\\\"search\\\",\\\"search_query\\\":\\\"تافل\\\",\\\"package_name\\\":\\\"com.karnameh\\\",\\\"bid_id\\\":\\\"39\\\",\\\"campaign_id\\\":\\\"39\\\",\\\"bid_query\\\":\\\"RTB\\\",\\\"install_cost\\\":\\\"YsE4/Hch/cU4TyXU2it7my8vIBV/Pmhbfv9ihqRWjxE=\\\",\\\"show\\\":true,\\\"user_has_app\\\":false,\\\"is_detailed\\\":true,\\\"ad_detail_subtitle\\\":\\\"قیمت روز انواع ماشین: صفر و کارکرده ؛ به سرویس «تخمین قیمت خودرو» کارنامه سر بزن.\\\",\\\"suggested\\\":false,\\\"impression_tracker_link\\\":\\\"RTB\\\",\\\"user_agent\\\":\\\"Bazaar/801600 (Android 22; samsung SM-G955N)\\\",\\\"participation_type\\\":\\\"rtb_basic\\\",\\\"ab_test_flags\\\":{\\\"Bayesian_1\\\":false,\\\"Bayesian_2\\\":false,\\\"Bayesian_3\\\":false,\\\"Bayesian_4\\\":false,\\\"Bayesian_5\\\":true,\\\"Bayesian_6\\\":false,\\\"adrow\\\":true,\\\"is_detailed_1\\\":false,\\\"is_detailed_2\\\":false,\\\"no_ad\\\":false,\\\"no_rtb\\\":false,\\\"run_by_bayesian\\\":false,\\\"smart_budget\\\":false,\\\"tractor\\\":true},\\\"currency\\\":\\\"IRR\\\",\\\"lurl\\\":\\\"https://basic.cafebazaar.ir/postback/lose-notice/batch/?surplus=417218\\\\u0026ab_flags=surplus_test_20210823_var_keyword_1_cdf_phat\\\",\\\"nurl\\\":\\\"https://basic.cafebazaar.ir/postback/win-notice/batch/?surplus=417218\\\\u0026ab_flags=surplus_test_20210823_var_keyword_1_cdf_phat\\\",\\\"suggestion_id\\\":\\\"a212a52d-6173-4e97-9ee4-0fc501f09cea\\\",\\\"rtb_click_postback_urls\\\":[\\\"https://basic.cafebazaar.ir/postback/view/batch/\\\"],\\\"rtb_install_postback_urls\\\":[\\\"https://basic.cafebazaar.ir/postback/install/batch/\\\"],\\\"rtb_install_completed_postback_urls\\\":[\\\"https://basic.cafebazaar.ir/postback/install-completed/batch/\\\"],\\\"rtb_impression_postback_urls\\\":[\\\"https://basic.cafebazaar.ir/postback/impression/batch/\\\"]}\",\"Extra\":\"{\\\"filter\\\":\\\"general\\\",\\\"must_have_query\\\":\\\"\\\",\\\"normalized_query\\\":\\\"تافل\\\"}\",\"IsKid\":\"false\",\"SearchQuery\":\"تافل\",\"Slug\":\"search\",\"TestGroup\":\"engine_pop:revised_pop;filter:o;install_count:o;result-display:o;search:bar;watch-later:o\"}"
        },
        {
          "type": 2,
          "extraJson": "{\"visit_index\":2,\"is_ad\":false,\"item_type\":\"app\",\"row_type\":\"app\"}"
        }
      ]
    }
  }
}




Response:
Long text: see more»»


 #17 ReviewRequest
https://api.cafebazaar.ir/rest-v1/process/ReviewRequest

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "1-sLNSXxTem2-VrMAVnueA",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "reviewRequest": {
      "end": 3,
      "packageName": "com.himia.learn.english.toefl",
      "sortType": "",
      "start": 0
    }
  }
}




Response:
{
  "properties": {
    "statusCode": 200,
    "maxAge": 0,
    "etag": "",
    "errorMessage": "",
    "errorCode": 0
  },
  "internalProperties": null,
  "singleReply": {
    "reviewReply": {
      "reviews": [
        {
          "id": 120479949,
          "user": "zahra",
          "comment": "عالیه سپاس ازشما",
          "likes": 0,
          "total": 0,
          "rate": 5,
          "versionCode": 104,
          "date": "۱۴۰۰/۰۵/۳۰",
          "reply": null,
          "likedByMe": 0,
          "accountID": "a56af971-cf03-4903-8281-60ae2763b50b",
          "badgeIconURL": "",
          "avatarURL": "https://35863b3675871c5199d58bc2f1d8fe54.cdn.cafebazaar.cloud/avatars/ic_default_144dp.png",
          "userRepliesCount": 0,
          "userRepliesAvatarUrls": [],
          "fromDeveloper": false,
          "reviewAuditState": 0
        },
        {
          "id": 118763204,
          "user": "شیرین",
          "comment": "‌قیمت هر روز تغییر نده همون 8تومن خوب بود سپاس از زحمات شما",
          "likes": 1,
          "total": 1,
          "rate": 1,
          "versionCode": 4,
          "date": "۱۴۰۰/۰۴/۲۸",
          "reply": null,
          "likedByMe": 0,
          "accountID": "d201aef1-46fa-4706-9c3a-c16fc7557a5d",
          "badgeIconURL": "",
          "avatarURL": "https://35863b3675871c5199d58bc2f1d8fe54.cdn.cafebazaar.cloud/avatars/ic_default_144dp.png",
          "userRepliesCount": 0,
          "userRepliesAvatarUrls": [],
          "fromDeveloper": false,
          "reviewAuditState": 0
        },
        {
          "id": 121654320,
          "user": "سوگند",
          "comment": "واقعا ازتون ممنونم ب این روش خییلی سریع میشه حفظ کرد و فراموشی هم خیلی کمتره",
          "likes": 0,
          "total": 0,
          "rate": 5,
          "versionCode": 4,
          "date": "۱۴۰۰/۰۶/۲۲",
          "reply": null,
          "likedByMe": 0,
          "accountID": "d760a3a9-70e0-4e52-8348-5370ea266a85",
          "badgeIconURL": "",
          "avatarURL": "https://35863b3675871c5199d58bc2f1d8fe54.cdn.cafebazaar.cloud/avatars/ic_default_144dp.png",
          "userRepliesCount": 0,
          "userRepliesAvatarUrls": [],
          "fromDeveloper": false,
          "reviewAuditState": 0
        }
      ],
      "nextPageCursor": ""
    }
  }
}




 #18 AppDownloadInfoRequest
https://api.cafebazaar.ir/rest-v1/process/AppDownloadInfoRequest

Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "1-sLNSXxTem2-VrMAVnueA",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "appDownloadInfoRequest": {
      "downloadStatus": 1,
      "packageName": "com.himia.learn.english.toefl",
      "referrers": [
        {
          "type": 14,
          "extraJson": "{\"index\":0,\"text\":\"\",\"test_group\":\"\",\"source\":\"history\"}"
        },
        {
          "type": 12,
          "extraJson": "{\"AdInfo\":\"{\\\"ad_uuid\\\":\\\"a92fcf71-4f48-49c8-ae39-52054655f2f0\\\",\\\"ad_type\\\":\\\"search\\\",\\\"search_query\\\":\\\"تافل\\\",\\\"package_name\\\":\\\"com.karnameh\\\",\\\"bid_id\\\":\\\"39\\\",\\\"campaign_id\\\":\\\"39\\\",\\\"bid_query\\\":\\\"RTB\\\",\\\"install_cost\\\":\\\"YsE4/Hch/cU4TyXU2it7my8vIBV/Pmhbfv9ihqRWjxE=\\\",\\\"show\\\":true,\\\"user_has_app\\\":false,\\\"is_detailed\\\":true,\\\"ad_detail_subtitle\\\":\\\"قیمت روز انواع ماشین: صفر و کارکرده ؛ به سرویس «تخمین قیمت خودرو» کارنامه سر بزن.\\\",\\\"suggested\\\":false,\\\"impression_tracker_link\\\":\\\"RTB\\\",\\\"user_agent\\\":\\\"Bazaar/801600 (Android 22; samsung SM-G955N)\\\",\\\"participation_type\\\":\\\"rtb_basic\\\",\\\"ab_test_flags\\\":{\\\"Bayesian_1\\\":false,\\\"Bayesian_2\\\":false,\\\"Bayesian_3\\\":false,\\\"Bayesian_4\\\":false,\\\"Bayesian_5\\\":true,\\\"Bayesian_6\\\":false,\\\"adrow\\\":true,\\\"is_detailed_1\\\":false,\\\"is_detailed_2\\\":false,\\\"no_ad\\\":false,\\\"no_rtb\\\":false,\\\"run_by_bayesian\\\":false,\\\"smart_budget\\\":false,\\\"tractor\\\":true},\\\"currency\\\":\\\"IRR\\\",\\\"lurl\\\":\\\"https://basic.cafebazaar.ir/postback/lose-notice/batch/?surplus=417218\\\\u0026ab_flags=surplus_test_20210823_var_keyword_1_cdf_phat\\\",\\\"nurl\\\":\\\"https://basic.cafebazaar.ir/postback/win-notice/batch/?surplus=417218\\\\u0026ab_flags=surplus_test_20210823_var_keyword_1_cdf_phat\\\",\\\"suggestion_id\\\":\\\"a212a52d-6173-4e97-9ee4-0fc501f09cea\\\",\\\"rtb_click_postback_urls\\\":[\\\"https://basic.cafebazaar.ir/postback/view/batch/\\\"],\\\"rtb_install_postback_urls\\\":[\\\"https://basic.cafebazaar.ir/postback/install/batch/\\\"],\\\"rtb_install_completed_postback_urls\\\":[\\\"https://basic.cafebazaar.ir/postback/install-completed/batch/\\\"],\\\"rtb_impression_postback_urls\\\":[\\\"https://basic.cafebazaar.ir/postback/impression/batch/\\\"]}\",\"Extra\":\"{\\\"filter\\\":\\\"general\\\",\\\"must_have_query\\\":\\\"\\\",\\\"normalized_query\\\":\\\"تافل\\\"}\",\"IsKid\":\"false\",\"SearchQuery\":\"تافل\",\"Slug\":\"search\",\"TestGroup\":\"engine_pop:revised_pop;filter:o;install_count:o;result-display:o;search:bar;watch-later:o\"}"
        },
        {
          "type": 2,
          "extraJson": "{\"visit_index\":2,\"is_ad\":false,\"item_type\":\"app\",\"row_type\":\"app\"}"
        },
        {
          "type": 17,
          "extraJson": "{\"service\":\"sejel\",\"package_name\":\"com.himia.learn.english.toefl\"}"
        }
      ]
    }
  }
}




Response:
{
  "properties": {
    "statusCode": 200,
    "maxAge": 0,
    "etag": "",
    "errorMessage": "",
    "errorCode": 0
  },
  "internalProperties": null,
  "singleReply": {
    "appDownloadInfoReply": {
      "token": "844033238985.apk?expire=1632223855&token=7ed2ad3fc322b65f15b723435107468e&a=",
      "hashCode": "ddd337cc80dae5df530c5d6c8707e73ec9451fe7",
      "cdnPrefix": [
        "https://appcdn.cafebazaar.ir/"
      ],
      "ipAddress": "31.14.86.12",
      "packageSize": "8215356",
      "versionCode": 4,
      "multiConnectionDownload": true,
      "compatibleDevices": [],
      "packageDiffs": [],
      "baseReferrers": [],
      "hasSplits": false,
      "hasAdditionalFiles": false,
      "splits": [],
      "additionalFiles": [],
      "installationSize": "12323034",
      "installType": 0
    }
  }
}




 #19 APK Downloading...

[Get] Request:
https://api.cafebazaar.ir/rest-v1/process/AppDownloadInfoRequest


Response:
apk downloading...


#20 SubmitInstallFromBazaarRequest
https://api.cafebazaar.ir/rest-v1/process/SubmitInstallFromBazaarRequest


Request:
{
  "properties": {
    "androidClientInfo": {
      "adId": "ef60dedb-3992-45a8-b4b7-aca084affbf9",
      "adOptOut": false,
      "androidId": "25372847a64538a2",
      "city": "NA",
      "country": "NA",
      "cpu": "x86,armeabi-v7a,armeabi",
      "device": "",
      "dpi": 320,
      "hardware": "",
      "height": 1600,
      "locale": "",
      "manufacturer": "samsung",
      "mcc": 204,
      "mnc": 0,
      "model": "SM-G955N",
      "osBuild": "",
      "product": "SM-G955N",
      "province": "NA",
      "sdkVersion": 22,
      "width": 900
    },
    "appThemeState": 0,
    "clientID": "1-sLNSXxTem2-VrMAVnueA",
    "clientVersion": "8.16.0",
    "clientVersionCode": 801600,
    "isKidsEnabled": false,
    "language": 2
  },
  "singleRequest": {
    "submitInstallFromBazaarRequest": {
      "isAd": false,
      "packageName": "com.himia.learn.english.toefl",
      "referrer": "[{\"type\":14,\"extraJson\":\"{\\\"index\\\":0,\\\"text\\\":\\\"\\\",\\\"test_group\\\":\\\"\\\",\\\"source\\\":\\\"history\\\"}\"}, {\"type\":12,\"extraJson\":\"{\\\"AdInfo\\\":\\\"{\\\\\\\"ad_uuid\\\\\\\":\\\\\\\"a92fcf71-4f48-49c8-ae39-52054655f2f0\\\\\\\",\\\\\\\"ad_type\\\\\\\":\\\\\\\"search\\\\\\\",\\\\\\\"search_query\\\\\\\":\\\\\\\"تافل\\\\\\\",\\\\\\\"package_name\\\\\\\":\\\\\\\"com.karnameh\\\\\\\",\\\\\\\"bid_id\\\\\\\":\\\\\\\"39\\\\\\\",\\\\\\\"campaign_id\\\\\\\":\\\\\\\"39\\\\\\\",\\\\\\\"bid_query\\\\\\\":\\\\\\\"RTB\\\\\\\",\\\\\\\"install_cost\\\\\\\":\\\\\\\"YsE4\\/Hch\\/cU4TyXU2it7my8vIBV\\/Pmhbfv9ihqRWjxE=\\\\\\\",\\\\\\\"show\\\\\\\":true,\\\\\\\"user_has_app\\\\\\\":false,\\\\\\\"is_detailed\\\\\\\":true,\\\\\\\"ad_detail_subtitle\\\\\\\":\\\\\\\"قیمت روز انواع ماشین: صفر و کارکرده ؛ به سرویس «تخمین قیمت خودرو» کارنامه سر بزن.\\\\\\\",\\\\\\\"suggested\\\\\\\":false,\\\\\\\"impression_tracker_link\\\\\\\":\\\\\\\"RTB\\\\\\\",\\\\\\\"user_agent\\\\\\\":\\\\\\\"Bazaar\\/801600 (Android 22; samsung SM-G955N)\\\\\\\",\\\\\\\"participation_type\\\\\\\":\\\\\\\"rtb_basic\\\\\\\",\\\\\\\"ab_test_flags\\\\\\\":{\\\\\\\"Bayesian_1\\\\\\\":false,\\\\\\\"Bayesian_2\\\\\\\":false,\\\\\\\"Bayesian_3\\\\\\\":false,\\\\\\\"Bayesian_4\\\\\\\":false,\\\\\\\"Bayesian_5\\\\\\\":true,\\\\\\\"Bayesian_6\\\\\\\":false,\\\\\\\"adrow\\\\\\\":true,\\\\\\\"is_detailed_1\\\\\\\":false,\\\\\\\"is_detailed_2\\\\\\\":false,\\\\\\\"no_ad\\\\\\\":false,\\\\\\\"no_rtb\\\\\\\":false,\\\\\\\"run_by_bayesian\\\\\\\":false,\\\\\\\"smart_budget\\\\\\\":false,\\\\\\\"tractor\\\\\\\":true},\\\\\\\"currency\\\\\\\":\\\\\\\"IRR\\\\\\\",\\\\\\\"lurl\\\\\\\":\\\\\\\"https:\\/\\/basic.cafebazaar.ir\\/postback\\/lose-notice\\/batch\\/?surplus=417218\\\\\\\\u0026ab_flags=surplus_test_20210823_var_keyword_1_cdf_phat\\\\\\\",\\\\\\\"nurl\\\\\\\":\\\\\\\"https:\\/\\/basic.cafebazaar.ir\\/postback\\/win-notice\\/batch\\/?surplus=417218\\\\\\\\u0026ab_flags=surplus_test_20210823_var_keyword_1_cdf_phat\\\\\\\",\\\\\\\"suggestion_id\\\\\\\":\\\\\\\"a212a52d-6173-4e97-9ee4-0fc501f09cea\\\\\\\",\\\\\\\"rtb_click_postback_urls\\\\\\\":[\\\\\\\"https:\\/\\/basic.cafebazaar.ir\\/postback\\/view\\/batch\\/\\\\\\\"],\\\\\\\"rtb_install_postback_urls\\\\\\\":[\\\\\\\"https:\\/\\/basic.cafebazaar.ir\\/postback\\/install\\/batch\\/\\\\\\\"],\\\\\\\"rtb_install_completed_postback_urls\\\\\\\":[\\\\\\\"https:\\/\\/basic.cafebazaar.ir\\/postback\\/install-completed\\/batch\\/\\\\\\\"],\\\\\\\"rtb_impression_postback_urls\\\\\\\":[\\\\\\\"https:\\/\\/basic.cafebazaar.ir\\/postback\\/impression\\/batch\\/\\\\\\\"]}\\\",\\\"Extra\\\":\\\"{\\\\\\\"filter\\\\\\\":\\\\\\\"general\\\\\\\",\\\\\\\"must_have_query\\\\\\\":\\\\\\\"\\\\\\\",\\\\\\\"normalized_query\\\\\\\":\\\\\\\"تافل\\\\\\\"}\\\",\\\"IsKid\\\":\\\"false\\\",\\\"SearchQuery\\\":\\\"تافل\\\",\\\"Slug\\\":\\\"search\\\",\\\"TestGroup\\\":\\\"engine_pop:revised_pop;filter:o;install_count:o;result-display:o;search:bar;watch-later:o\\\"}\"}, {\"type\":2,\"extraJson\":\"{\\\"visit_index\\\":2,\\\"is_ad\\\":false,\\\"item_type\\\":\\\"app\\\",\\\"row_type\\\":\\\"app\\\"}\"}, {\"type\":17,\"extraJson\":\"{\\\"service\\\":\\\"sejel\\\",\\\"package_name\\\":\\\"com.himia.learn.english.toefl\\\"}\"}]",
      "versionCode": 4
    }
  }
}




Response:
{
  "properties": {
    "statusCode": 200,
    "maxAge": 0,
    "etag": "",
    "errorMessage": "",
    "errorCode": 0
  },
  "internalProperties": null,
  "singleReply": {
    "submitInstallFromBazaarReply": {}
  }
}





#x soon...

Request:
1


Response:
2




