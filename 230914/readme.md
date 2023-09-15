# 分享會

## 單元測試 JUnit+Mockito

+ [基本用法1](https://github.com/ls975407-WaveGIS/self-note/blob/master/note/002-002%20SpringBoot%20JUnit%20Test.md)
+ [基本用法2](https://github.com/ls975407-WaveGIS/self-note/blob/master/note/005%20%E6%B8%AC%E8%A9%A6%E5%B7%A5%E5%85%B7Mockito%E7%94%A8%E6%B3%95.md)
+ [範例程式](https://github.com/WaveGIS-Co/kaohsiungWrb/blob/master/src/test/java/com/wavegis/kaohsiungwrb/service/TestDeviceService.java)

## 服務優化: 顯示錯誤

### 單一方法報錯方式

+ [接收錯誤](https://github.com/WaveGIS-Co/kaohsiungWrb/blob/master/src/main/java/com/wavegis/kaohsiungwrb/controller/UploadController.java#L69)
+ [產生錯誤](https://github.com/WaveGIS-Co/kaohsiungWrb/blob/master/src/main/java/com/wavegis/kaohsiungwrb/util/Util.java#L91)
+ [範例](http://52.187.182.187/api/kaohsiungWrb/swagger-ui.html#/upload-controller/sewerwaterlogUsingGET)

### 全域報錯方式

+ [接收錯誤](https://github.com/WaveGIS-Co/amuping_api/blob/master/src/main/java/com/wavegis/amuping/Controller/GlobalExceptionHandler.java)
+ [範例](http://192.168.1.23:8082/amuping/swagger-ui.html#/flood-controller/getFloodLogUsingGET)
