## EFK là gì

EFK là viết tắt của Elasticsearch - Fluentd/Fluentbit - Kibana.

EFK là một stack các app kết hợp với nhau để thu thập, phân tích, lưu trữ, tìm kiếm, hiển thị dữ liệu log.

## Khi nào nên sử dụng EFK

Bất kỳ ứng dụng nào hoạt động trong hệ thống cũng đều phải ghi log, vì log là phản ánh trực quan nhất tình trạng hoạt động của tiến trình. Ví dụ như load module có đủ không, token có hết hạn không, xử lý có bị chậm không, ....

Nên một hệ thống càng lớn thì việc xử lý phân tích log tập trung càng phải được chú trọng. 

Hiện ta




## EFK khác gì ELK

EFK và ELK là cùng là stack có chức năng quản trị tập trung dữ liệu log. Khác nhau duy nhất ở đây là trong ELK stack thì ta sử dụng logstash có nhiệm vụ parser log, và khi sử dụng ELK ta cần khá nhiều shipper log như: filebeat, packetbeat, metricbeat, winlogbeat.

Còn EFK stack thì đã thay thế logstash bằng fluentd/fluentbit để xử lý parser log. Ngoài ra, fluentd/fluentbit còn có thể thực hiện chức năng shipper log.


















