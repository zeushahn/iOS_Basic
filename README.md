# iOS_Basic
IOS 앱 제작 SWIFT프로그래밍 입문 (2022-07-06 ~ 2022-08-21)

연락처 : kennysy@naver.com


Zoom 연결 : 
    https://us02web.zoom.us/j/6962261155?pwd=WWZsSDFQZ3ZsU2tndzg4Z0FybGZpUT09


*Swift

    // 아무곳이나 눌러 softkeyboard 지우기
    override func touchesBegan(_ touches: Set<UITouch>, with event: UIEvent?) {
        self.view.endEditing(true)
    }
