🌟 Kümelenmiş Yıldız Topolojisi (Clustered Star Topology) Simülasyonu
Bu depo (repository), Cisco Packet Tracer kullanılarak tasarlanmış ve yapılandırılmış, yüksek düzeyde yedekli (redundant) ve ölçeklenebilir bir Kümelenmiş Yıldız Topolojisi uygulamasını içermektedir.

Bu proje, karmaşık ağ mimarilerindeki hata toleransı (fault tolerance) ve yüksek erişilebilirlik (high availability) prensiplerini pratik olarak göstermek amacıyla geliştirilmiştir.

🖼️ Topoloji Özeti
Kurulum, üç ana mantıksal kümeden (Cluster 1, Cluster 2 ve Merkez Omurga) oluşmaktadır.

Merkez Omurga: Merkez Switch, trafiği yönetir ve ana ağ geçidi işlevi görür.

Küme (Cluster) Cihazları: Her küme, yerel cihazları (uç noktaları) temsil eden uç Switch'ler içerir.

Yedekli Bağlantılar: Kritik cihazlar arasında, bir bağlantı kesilse bile iletişimin devam etmesini sağlayan birden fazla fiziksel bağlantı bulunmaktadır.
