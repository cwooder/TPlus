**연결 가능한 WiFi 목록 조회**
---
  JSON 포맷의 WiFi 목록 데이터 반환
* **URL**
  * /scan
* **Method**
  * `GET`
* **URL Params**
  * 없음
* **Data Params**
  `-`
* **Success Response**
  * **Code:** 200<br />
  * **Content:** `{ 'rssi': (double), 'ssid': (string), 'bssid': (string), 'channel': (string), 'secure': (int), 'hidden': (bool) }`
* **Error Response**
  * **Code:** 500<br />
  * **Content:** `-`
