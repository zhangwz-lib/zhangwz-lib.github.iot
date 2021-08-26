---
title: test
date: 2021-08-06 16:36:47
categories: server
tags:
comments: true

---

## test

```java
log.info("查询曝光模块参数:{}", JSON.toJSONString(sdcDeviceImgCapabilityBo));   

checkArgument(!Objects.isNull(sdcDeviceImgCapabilityBo.getUUID()), "uuid is empty or error");
 String url=BusinessUtil.buildRequestUrl(HuaWeiSdcUrlConstants.SDC_DEVICE_IMG_AE_URL,sdcDeviceImgCapabilityBo);
url = url + "?UUID=" + sdcDeviceImgCapabilityBo.getUUID();
```



