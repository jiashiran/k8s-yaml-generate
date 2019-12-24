# k8s-yaml-generate
generate kubernetes yaml template with all field

使用Kubernetes源码，用反射递归方式生成包含所有属性的yaml模板，设置需要的属性后点击整理可以生成最终yaml文件

Kubernetes版本：release-1.17

包含yaml模板类型：[ConfigMap,Ingress,Service,ReplicaSet,Deployment,Secret,Namespace,Pod,Volume,Job]

使用方式：下载https://github.com/jiashiran/k8s-yaml-generate/releases/tag/v1 ，运行k8s-yaml-generate-XXX，打开浏览器访问 http://localhost:8080
