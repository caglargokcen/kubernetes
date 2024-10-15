<h1 align="left">
Kubernetes
</h1>

<h1 align="left">
🚀🚀🚀
</h1>

<br>

- [Nginx Status: Kubernetes ile Anlık İzleme ve Yönetimde Yeni Bir Dönem](#nginx-status)
- [Vote - Result: Kubernetes ve NFS ile Güçlü Veri Yönetimi Stratejileri](#vote-result)

<br>

## Nginx Status: Kubernetes ile Anlık İzleme ve Yönetimde Yeni Bir Dönem

<br>

Bu proje kubeadm kullanarak bir Kubernetes ortamı kurmayı ve bu ortamda hasangural/nginx-status adlı container image'ını deploy etmeyi kapsamaktadır. Proje Hyper-V üzerinde bir Master node ve iki Worker node içeren bir yapılandırma ile oluşturulmuştur. Bu mimari Kubernetes'in sağladığı ölçeklenebilirlik ve yönetim kolaylıklarından faydalanarak uygulama dağıtımını kolaylaştırmaktadır.

<br>

Kubernetes cluster oluşturulduktan sonra her bir node üzerinde nginx-status uygulaması dağıtılmıştır. Bu uygulama dış dünya ile etkileşim sağlamak üzere bir Ingress kaydı ile yapılandırılmıştır. Ingress MetalLB ile birlikte çalışarak belirlenen bir IP adresi üzerinden HTTP protokolü ile dış bağlantıları yönetmektedir. Böylece kullanıcılar uygulamaya tarayıcıları aracılığıyla belirlenen DNS adresi üzerinden erişebilirler.

<br>

Projenin sonunda bulut tabanlı uygulamaların dağıtımı ve yönetimi konularında önemli bir deneyim sağlanarak modern yazılım geliştirme becerilerinizi geliştirmeyi amaçlamaktadır. Kubernetes'in esnekliği ve güçlü özellikleri ile uygulama yönetiminin nasıl gerçekleştirileceğine dair önemli bilgiler edinilmektedir.

<br>

## Vote - Result: Kubernetes ve NFS ile Güçlü Veri Yönetimi Stratejileri

<br>

Bu proje Kubernetes ortamında NFS (Network File System) kullanarak veri saklama çözümlerini keşfetmeyi amaçlamaktadır. Proje kubeadm aracı ile oluşturulan bir Kubernetes cluster aracılığıyla uygulama veri yönetimini bir NFS sunucusu üzerinden gerçekleştirmektedir.

<br>

Uygulama mimarisi Hyper-V üzerinde bir NFS node, bir Master node ve iki Worker node'dan oluşmaktadır. Kubernetes cluster oluşturulduktan sonra PostgreSQL, Redis, Result, Vote ve Worker gibi çeşitli uygulamalar dağıtılmıştır. Bu uygulamalar verilerini NFS sunucusuna depolamak için Persistent Volume ve Persistent Volume Claim yapılandırmalarını kullanmaktadır. Böylece pod'lar silinse bile veriler Kubernetes cluster dışındaki NFS sunucusundan erişilebilir durumda kalmakta ve veri kaybı yaşanmamaktadır.

<br>

Proje HTTP protokolü üzerinden dış dünya ile etkileşim sağlamak amacıyla Ingress ve MetalLB kullanarak uygulamanın erişilebilirliğini artırmaktadır. Kullanıcılar belirlenen DNS adresleri üzerinden uygulamalara kolaylıkla erişim sağlayabilmektedir.

<br>

Projenin sonunda Kubernetes'in esnekliğinden faydalanarak veri yönetimi ve uygulama dağıtım süreçlerinin nasıl gerçekleştirileceği gösterilmekte olup bulut tabanlı uygulamaların dağıtımı ve yönetimi konularında değerli bir deneyim sunmaktadır. Ayrıca modern yazılım geliştirme becerilerinizi pekiştirirken Kubernetes ortamında veri saklama stratejileri hakkında derinlemesine bilgi edinmenizi sağlamaktadır.