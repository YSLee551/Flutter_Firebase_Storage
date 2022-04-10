# Flutter_Firebase_Storage

한동대학교 모바일앱개발 수업 실습에 활용되는 Flutter Firebase Storage Example 입니다.

공식 [FlutterFire Storage Example 원본](https://github.com/FirebaseExtended/flutterfire/tree/master/packages/firebase_storage/firebase_storage
) 코드를 일부 수정하여 사용하였습니다.

> TODO: 본인의 Firebase 프로젝트를 만들고, 이 샘플 Flutter 프로젝트에 연결하셔야 합니다.(iOS - GoogleService-Info.plist 추가, Android - google-services.json 추가)

시연 영상: https://drive.google.com/file/d/1b9_T3cuSI8sDCj-SPnATjIMLJgKmf2AD/view?usp=sharing

Storage 권한 관련 에러가 발생할 경우 참고: https://stackoverflow.com/questions/65048371/fire-storage-exception-firebase-storage-unauthorized-user-is-not-authorized-t

## [예시 코드에서 수정된 사항]

1. Upload from String 의 txt 파일명이 중복되지 않고 업로드 가능하도록, 시간 기반으로 파일명 수정

2. Upload from File 기능 제거


# Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
