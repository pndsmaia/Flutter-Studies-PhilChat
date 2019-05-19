# phil_chat

A new chat to studies

## Getting Started

To add firebase in iOS was added at ios/Runner/info.plist:

    <key>CFBundleURLTypes</key>
	<array>
		<dict>
			<key>CFBundleTypeRole</key>
			<string>Editor</string>
			<key>CFBundleURLSchemes</key>
			<array>
				<string>com.googleusercontent.apps.622590411513-ga05gfdfsdsptokho9panmahe4adljg1</string>
			</array>
		</dict>
	</array>

To use camera and gallery in iOS was added at ios/Runner/info.plist:

    <key>NSPhotoLibraryUsageDescription</key>
    <string>Tirar fotos dos contatos.</string>
    <key>NSCameraUsageDescription</key>
    <string>Selecionar uma foto de contato da galeria.</string>
    <key>NSMicrophoneUsageDescription</key>
    <string>Tirar fotos dos contatos.</string>


Plugins that was used:

  cupertino_icons: ^0.1.2
  cloud_firestore: ^0.8.2+3
  google_sign_in: ^3.2.4
  firebase_auth: ^0.7.0
  firebase_storage: ^1.0.4
  image_picker: ^0.4.12+1

