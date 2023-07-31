## 方案框架

以 前端 UI 與後端 API 的方式做為大框架
前端主要以 Vue 為主，後端主要以 Java 為主

### 大致用到的技術與套件
| 名稱 | 作用 | 授權 |
|------|------|-------|
| Vue2 + Typescript | 主要開發 UI / UX                                       | [MIT](https://zh.wikipedia.org/zh-tw/MIT%E8%A8%B1%E5%8F%AF%E8%AD%89) |
| Axios                     | 通過 http 呼叫 api 與 Java 程式互動         | [MIT](https://zh.wikipedia.org/zh-tw/MIT%E8%A8%B1%E5%8F%AF%E8%AD%89) |
| electron                 | 將 Vue 發行的 Web 包裝成桌面應用程式 | LGPL |
| Java (Spring Boot) | Web API 主要寫資料處理邏輯                   | |
| Micrometer           | 監聽本機的 Http                                        | [Apache Software License 2.0](https://www.apache.org/licenses/LICENSE-2.0) |
| MariaDB                | 資料庫                                                       | |
| mybatis                 | 將 SQL 寫在 xml 檔與 Java 程式分離         | [Apache Software License 2.0](https://www.apache.org/licenses/LICENSE-2.0) |

## 參考
### 官網
[Vue2](https://v2.vuejs.org/v2/guide/)
[electron](https://www.electronjs.org/)
[Micrometer](https://micrometer.io/)

### 技術文章
[electron](https://ithelp.ithome.com.tw/articles/10254357)
[electron + Vue](https://ithelp.ithome.com.tw/articles/10254290)
[Spring Boot + Micrometer](https://www.baeldung.com/spring-boot-self-hosted-monitoring)
[Spring Boot + Micrometer](https://blog.csdn.net/aixiaoyang168/article/details/100866159)