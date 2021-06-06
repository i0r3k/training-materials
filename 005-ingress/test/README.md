前置条件：
- k8s 1.19及以上版本。
- 使用Ingress v1创建测试用例。

按照编号顺序依次部署：
- 001-deps：安装cert-manager v1.3.1，如果集群里已经安装过则可以忽略。
- 002-ingress：安装Ingress Controller
- 003-testcase：测试用例，可以按照需求情况增加/修改。
