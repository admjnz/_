# 🧸 Apple

## Lời nói đầu

![](https://shields.io/badge/-移除重复规则-ff69b4) ![](https://shields.io/badge/-DOMAIN与DOMAIN--SUFFIX合并-green) ![](https://shields.io/badge/-DOMAIN--SUFFIX间合并-critical) ![](https://shields.io/badge/-DOMAIN--SUFFIX与DOMAIN--KEYWORD合并-blue) ![](https://shields.io/badge/-IP--CIDR(6)合并-blueviolet) 

Các quy tắc của Apple được tạo tự động bởi RULE GENERATOR。

Quy tắc chuyển hướng là bản tóm tắt tên miền và địa chỉ IP của các dịch vụ công cộng Internet. Tất cả dữ liệu được thu thập từ thông tin công khai trên Internet, điều đó không có nghĩa là chúng tôi hỗ trợ hoặc sử dụng các dịch vụ này。

Vui lòng vượt qua địa chỉ trong các quy tắc truy cập kênh truy cập Internet hợp pháp của [Cộng hòa Nhân dân Trung Hoa] và đảm bảo tuân thủ các luật và quy định có liên quan trong quá trình sử dụng。
## Thống kê quy tắc

Thời gian cập nhật cuối cùng：2024-04-14 02:25:11

Thống kê các loại quy tắc khác nhau：
| Loại | Số lượng (Bài viết)  | 
| ---- | ----  |
| DOMAIN | 9  | 
| DOMAIN-KEYWORD | 7  | 
| DOMAIN-SUFFIX | 1549  | 
| IP-CIDR | 10  | 
| PROCESS-NAME | 14  | 
| TOTAL | 1589  | 


## (Stash) Clash 

#### Hướng dẫn sử dụng
- Apple-Classical.yaml，Vui lòng sử dụng behavior: "classical"。
- Apple-Classical-No-Resolve.yaml，Vui lòng sử dụng behavior: "classical"。
- Apple-Domain.yaml，Vui lòng sử dụng behavior: "domain"。
- Apple-Domain-Clash.yaml，Vui lòng sử dụng behavior: "domain"。

#### Đề xuất cấu hình
- Apple-Classical.yaml Sử dụng một mình。
- Apple-Classical-No-Resolve.yaml Sử dụng phổ biến。
- Apple-Domain.yaml, Apple-Domain-Clash.yaml Sử dụng phổ biến。

#### Liên kết quy tắc
**MASTER Chi nhánh (Cập nhật hàng ngày)**

https://raw.gitmirror.com/TenChina/TenSeries/main/rule/Stash/Apple/Apple-Classical.yaml

https://raw.gitmirror.com/TenChina/TenSeries/main/rule/Stash/Apple/Apple-Classical-No-Resolve.yaml

https://raw.gitmirror.com/TenChina/TenSeries/main/rule/Stash/Apple/Apple-Domain.yaml

https://raw.gitmirror.com/TenChina/TenSeries/main/rule/Stash/Apple/Apple-Domain-Clash.txt

## Quy tắc phụ/Quy tắc loại trừ

Các quy tắc chuyển hướng hiện tại bao gồm các quy tắc phụ sau. Các tham chiếu lặp đi lặp lại không được khuyến nghị trừ khi có một yêu cầu đặc biệt：
| Các quy tắc phụ |  |  |  |  | 
| ---- | ---- | ---- | ---- | ----  |
| AppStore | AppleFirmware | AppleHardware | AppleMail | AppleMedia  | 
| AppleMusic | AppleNews | AppleProxy | AppleTV | FindMy  | 
| FitnessPlus | Siri | TestFlight | iCloud | iCloudPrivateRelay  | 


## Nguồn dữ liệu

Dữ liệu của Apple đến từ các liên kết sau. Nếu nó được trộn lẫn với các quy tắc của Apple của dự án này, nó có thể gây ra rất nhiều sự lặp lại của các quy tắc。
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/AppStore/AppStore.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Apple/iCloud.list
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/icloud.txt
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/TestFlight/TestFlight.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/TestFlight.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Apple/FitnessPlus.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Apple/Mail.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Apple/Music.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/AppleNews.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/AppleTV.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Apple.list
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/apple.txt
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Apple/AppStore.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Apple/AppStoreConnect.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Apple/Apple.list
- https://raw.githubusercontent.com/GeQ1an/Rules/master/QuantumultX/Filter/Apple.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Services/Apple.list
- https://raw.githubusercontent.com/Hackl0us/SS-Rule-Snippet/master/Rulesets/Surge/Basic/Apple-proxy.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/AppleBlock/AppleBlock.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/Apple.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/FindMy.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/FitnessPlus.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/Mail.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/Music.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/Siri.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/TV.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/iCloud.list
- https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/apple.txt
- https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/icloud.txt
- https://raw.githubusercontent.com/dler-io/Rules/main/Clash/Provider/Apple.yaml
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Apple/AppleFirmware.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Apple/AppleHardware.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Apple/AppleMedia.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Providers/Ruleset/Apple.yaml
- https://raw.githubusercontent.com/zqzess/rule_for_quantumultX/master/QuantumultX/rules/Apple.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Providers/Ruleset/AppleNews.yaml
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Providers/Ruleset/AppleTV.yaml
- https://ruleset.isagood.day/apple_cdn_domain.conf
- https://ruleset.isagood.day/apple_services.conf
- https://raw.githubusercontent.com/Elysian-Realme/FuGfConfig/main/ConfigFile/QuantumultX/Apple/AppleAPIRules.conf
- https://raw.githubusercontent.com/Elysian-Realme/FuGfConfig/main/ConfigFile/QuantumultX/Apple/AppleNoChinaCDNRules.conf
- https://raw.githubusercontent.com/Elysian-Realme/FuGfConfig/main/ConfigFile/QuantumultX/Apple/AppleCDNRules.conf
- https://raw.githubusercontent.com/Elysian-Realme/FuGfConfig/main/ConfigFile/QuantumultX/Apple/AppleRules.conf


Cảm ơn tác giả của các quy tắc trên vì sự chăm chỉ của anh ấy (không theo thứ tự cụ thể).

## Cái cuối cùng

### Cảm ơn

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) [@vhdj](https://github.com/vhdj)

Cung cấp các nguồn dữ liệu quy tắc và các đề xuất để cải thiện。

### Khác

Vui lòng không công khai dự án này。