# Harita bileşenleri ve atıflar

- **Leaflet 1.9.4** — https://leafletjs.com — BSD-2-Clause. Tam lisans `vendor/LEAFLET-LICENSE.txt` dosyasında ve üretilen HTML içinde korunur. JavaScript ve CSS yereldir; CDN çağrısı yapılmaz.
- **Natural Earth 1:50m Admin 0 Countries** — https://www.naturalearthdata.com/about/terms-of-use/ — kamu malı. Türkiye ve 12 komşu/çevre ülke geometrisi seçilip sadeleştirildi. Kaynak: https://github.com/nvkelso/natural-earth-vector/blob/master/geojson/ne_50m_admin_0_countries.geojson
- **OpenStreetMap** — https://www.openstreetmap.org/copyright — © OpenStreetMap contributors. İsteğe bağlı çevrimiçi altlık; atıf haritada görünür. Kullanım: https://operations.osmfoundation.org/policies/tiles/
- **OpenRailwayMap** — https://www.openrailwaymap.org — veriler © OpenStreetMap contributors; stil CC-BY-SA 2.0, https://creativecommons.org/licenses/by-sa/2.0/ . API ve kullanım kuralları: https://wiki.openstreetmap.org/wiki/OpenRailwayMap/API

Çevrimiçi harita yalnız kullanıcı isteğiyle yüklenir; ön indirme, toplu indirme ve çevrimdışı tile arşivi oluşturulmaz. Geçerli HTTP(S) Referer gerektiren servisler file:// altında çağrılmaz. Çevrimdışı ülke altlığı ve yaklaşık pilot çizgileri uygulamanın parçasıdır; gerçek ray konumları oldukları iddia edilmez.

Bileşenler 25 Eylül 2026 tarihinde kontrol edilmiştir.
