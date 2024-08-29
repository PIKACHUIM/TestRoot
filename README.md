# 皮卡丘公共服务测试根证书 RSA (Pikachu Public Test Root RSA)

## 本网站介绍

皮卡丘公共服务测试根证书 RSA提供公共自签名代码签名、时间戳服务、UEFI固件认证签名、Windows驱动签名以及驱动签名策略自定义服务

Pikachu Public Service Test Root Certificate RSA provides public self signed code signature, timestamp service, UEFI firmware authentication signature, Windows driver signature, and driver signature policy customization service

## 根证书列表



| 证书                | 说明                                                         | 证书下载                                                     | CRL列表              |
| ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------- |
| Pikachu Test CA RSA | 皮卡丘公共服务测试根证书 RSA (Pikachu Public Test Root RSA)<br/>UEFI中作为平台密钥PK  (As Platform Key in UEFI Signing) | [CER](root.cer)  [CRT](root.crt)  [DER](root.der)  [P7B](root.p7b) | [CRL List](root.crl) |
| Pikachu UEFI Sub CA | 皮卡丘UEFI密钥交换证书中间CA (Pikachu UEFI Key Exchange CA)<br/>UEFI中作为密钥交换密钥KEK  (As Key Exchange Keys in UEFI Signing) | [CER](uefi.cer)  [CRT](uefi.crt)  [DER](uefi.der)  [P7B](uefi.p7b) | [CRL List](uefi.crl) |

## 子证书列表

| 证书                | 说明                                                         | 证书下载                                                     |
| ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Pikachu UEFI Signer | 皮卡丘UEFI启动EFI签名证书RSA (Pikachu UEFI Allow DataBases)<br/>UEFI中作为EFI数据库证书(DB)  (As Allow Database in UEFI Signing) | [CER](efis.cer)  [CRT](efis.crt)  [DER](efis.der)  [P7B](efis.p7b) |