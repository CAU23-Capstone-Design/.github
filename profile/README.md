## ABOUT
- 중앙대학교 캡스톤 디자인 프로젝트 ( 2023-03 ~ 2023-06 )


## 💕 Lovestory 💕
연인간의 추억을 자동으로 기록해주는 서비스

![KakaoTalk_20230602_124349554](https://github.com/CAU23-Capstone-Design/.github/assets/33647663/ae8e8419-e45d-417e-9023-fc9fb4f907f4)


## 🐥 TEAM 
![member](https://github.com/CAU23-Capstone-Design/.github/assets/29995267/d647da2b-9c72-4571-804d-d835cf480ccb)

server: https://github.com/CAU23-Capstone-Design/server

client: https://github.com/CAU23-Capstone-Design/client

## 🍀 Service 
여러분들은 애인과의 추억을 어떻게 관리를 하시나요? 

캘린더에 언제 어디서 만났는지 기록을 한 경험이 있으신가요? 

혹은 함께 있을 때 찍은 사진들을 상대방과 공유하기 위해서 공유앨범을 만들고 있으신가요?

하지만 이러한 일들이 시간이 지나면서 조금씩 소홀해 지면서 추억을 잃어버리고 있지는 않으신가요?

여러분들의 추억을 잃지 않도록 저장해주는 서비스가 필요하지 않으신가요?

```두 사람의 사랑 이야기를 기록해주는 서비스, Lovestory``` 입니다.

## Project Description
### Project Name
Lovestory

### Project Logo
![image](https://github.com/CAU23-Capstone-Design/.github/assets/33647663/4beda672-d261-4cc7-9c1e-e2b807600606)

### Project Introduction
여러분들은 애인과의 추억을 어떻게 관리를 하시나요? 

캘린더에 언제 어디서 만났는지 기록을 한 경험이 있으신가요? 

혹은 함께 있을 때 찍은 사진들을 상대방과 공유하기 위해서 공유앨범을 만들고 있으신가요?

하지만 이러한 일들이 시간이 지나면서 조금씩 소홀해 지면서 추억을 잃어버리고 있지는 않으신가요?

여러분들의 추억을 잃지 않도록 저장해주는 서비스가 필요하지 않으신가요?

```두 사람의 사랑 이야기를 기록해주는 서비스, Lovestory``` 입니다.

### Team
![member](https://github.com/CAU23-Capstone-Design/.github/assets/29995267/d647da2b-9c72-4571-804d-d835cf480ccb)

강명석 - BackEnd, Project Manager
김용환 - FrontEnd
박상현 - FrontEnd, Designer

### Directory
Front
```swift
Lovestory
 ┣ api
 ┃ ┣ Calendar.kt
 ┃ ┣ Couple.kt
 ┃ ┣ Location.kt
 ┃ ┣ Photo.kt
 ┃ ┣ Token.kt
 ┃ ┗ User.kt
 ┣ broadcasts
 ┃ ┗ BoardCastContent.kt
 ┣ database
 ┃ ┣ entities
 ┃ ┃ ┣ AdditionalPhoto.kt
 ┃ ┃ ┣ PhotoForSync.kt
 ┃ ┃ ┗ SyncedPhoto.kt
 ┃ ┣ repository
 ┃ ┃ ┣ AdditionalPhotoRepository.kt
 ┃ ┃ ┣ PhotoForSyncRepository.kt
 ┃ ┃ ┗ SyncedPhotoRepository.kt
 ┃ ┗ Photos.kt
 ┣ graphs
 ┃ ┣ AuthNavigationGraph.kt
 ┃ ┣ MainNavigationGraph.kt
 ┃ ┗ RootNavigationGraph.kt
 ┣ model
 ┃ ┣ Calendar.kt
 ┃ ┣ Clustering.kt
 ┃ ┣ Comment.kt
 ┃ ┣ Couple.kt
 ┃ ┣ Location.kt
 ┃ ┣ Photo.kt
 ┃ ┣ Token.kt
 ┃ ┗ User.kt
 ┣ module
 ┃ ┣ auth
 ┃ ┃ ┗ DisconnectCouple.kt
 ┃ ┣ dashboard
 ┃ ┃ ┣ getCoupleInfo.kt
 ┃ ┃ ┗ saveAndGetCoupleInfo.kt
 ┃ ┣ map
 ┃ ┃ ┗ Map.kt
 ┃ ┣ photo
 ┃ ┃ ┣ AddPhotoFromGallery.kt
 ┃ ┃ ┣ DeletePhotoById.kt
 ┃ ┃ ┣ getDetailPhoto.kt
 ┃ ┃ ┣ GetThumbnailForPhoto.kt
 ┃ ┃ ┗ UploadPhoto.kt
 ┃ ┣ shared
 ┃ ┃ ┗ SharedDistance.kt
 ┃ ┣ CheckCode.kt
 ┃ ┣ CheckCouple.kt
 ┃ ┣ CheckExistNeedPhotoForSync.kt
 ┃ ┣ CheckNearby.kt
 ┃ ┣ CheckRunningService.kt
 ┃ ┣ DiskCache.kt
 ┃ ┣ GetExifInfo.kt
 ┃ ┣ GetIamgeById.kt
 ┃ ┣ GetImageInfoById.kt
 ┃ ┣ GetPermission.kt
 ┃ ┣ GetTokenInfo.kt
 ┃ ┣ KakaoLogin.kt
 ┃ ┣ LinkCouple.kt
 ┃ ┣ MapClustering.kt
 ┃ ┣ SavedComment.kt
 ┃ ┣ SaveLocation.kt
 ┃ ┣ SharedToken.kt
 ┃ ┗ StartService.kt
 ┣ network
 ┃ ┣ Comment.kt
 ┃ ┣ Couple.kt
 ┃ ┣ CreateApiService.kt
 ┃ ┣ Gps.kt
 ┃ ┣ Location.kt
 ┃ ┣ Photo.kt
 ┃ ┣ Token.kt
 ┃ ┗ User.kt
 ┣ resource
 ┃ ┣ font.kt
 ┃ ┗ test.kt
 ┣ services
 ┃ ┣ LocationService.kt
 ┃ ┗ PhotoService.kt
 ┣ ui
 ┃ ┣ components
 ┃ ┃ ┣ AlertDialog.kt
 ┃ ┃ ┣ Animation.kt
 ┃ ┃ ┣ Avatar.kt
 ┃ ┃ ┣ Button.kt
 ┃ ┃ ┣ Calendar.kt
 ┃ ┃ ┣ CalendarDialogForSignUp.kt
 ┃ ┃ ┣ DayGroupedGallery.kt
 ┃ ┃ ┣ Dialog.kt
 ┃ ┃ ┣ DropDownIcon.kt
 ┃ ┃ ┣ GroupedGallery.kt
 ┃ ┃ ┣ Image.kt
 ┃ ┃ ┣ ImageFromURI.kt
 ┃ ┃ ┣ Marker.kt
 ┃ ┃ ┣ Navigation.kt
 ┃ ┃ ┣ PdfViewer.kt
 ┃ ┃ ┣ PhotoForCalendar.kt
 ┃ ┃ ┣ RepresentPeriodGallery.kt
 ┃ ┃ ┣ ScreenHeader.kt
 ┃ ┃ ┣ SelectMenuButtons.kt
 ┃ ┃ ┣ SettingMenuList.kt
 ┃ ┃ ┣ TestImage.kt
 ┃ ┃ ┗ TextField.kt
 ┃ ┣ screens
 ┃ ┃ ┣ CalendarScreen.kt
 ┃ ┃ ┣ CoupleSyncScreen.kt
 ┃ ┃ ┣ DashBoardScreen.kt
 ┃ ┃ ┣ GalleyScreen.kt
 ┃ ┃ ┣ HelpScreen.kt
 ┃ ┃ ┣ LoginScreen.kt
 ┃ ┃ ┣ MainScreen.kt
 ┃ ┃ ┣ MapScreen.kt
 ┃ ┃ ┣ PhotoDetailScreen.kt
 ┃ ┃ ┣ PhotoSyncScreen.kt
 ┃ ┃ ┣ PrivacyScreen.kt
 ┃ ┃ ┗ ProfileScreen.kt
 ┃ ┗ theme
 ┃ ┃ ┣ Color.kt
 ┃ ┃ ┣ Shape.kt
 ┃ ┃ ┣ Theme.kt
 ┃ ┃ ┗ Type.kt
 ┣ view
 ┃ ┣ ImageSyncView.kt
 ┃ ┣ ImageSyncViewFactory.kt
 ┃ ┣ PhotoForSyncView.kt
 ┃ ┣ PhotoForSyncViewFactory.kt
 ┃ ┣ SyncedPhotoView.kt
 ┃ ┗ SyncedPhotoViewFactory.kt
 ┗ MainActivity.kt
 ```

## 🎀 App Logo 
![image](https://github.com/CAU23-Capstone-Design/.github/assets/33647663/4beda672-d261-4cc7-9c1e-e2b807600606)

## 🐲 Architecture 
![image](https://github.com/CAU23-Capstone-Design/.github/assets/33647663/839d36c4-badf-40d0-b339-c13624c80e91)

## 🎬 Demo 

### 1. 커플 연동

### 2. 대시보드

### 3. 갤러리

### 4. 캘린더

### 5. 프로필
