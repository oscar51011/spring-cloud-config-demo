# spring-cloud-config-demo
搭配 spring cloud demo 提供的配置檔 專案
對應 springclouddemo 中的 module cloud-config 專案使用

啟動順序: 啟動 springclouddemo 中的 2個專案
1. eureka-server ( 為一個 eureka server )
2. cloud-config ( 為一個 eureka client )
-> cloud-config 的 application.yml 需要使用自己的 repository 建置 (置換 uri, username, password)
