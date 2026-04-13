# Video Input Interface (Интерфейс ввода видео)

## MIPI interface (Интерфейс MIPI)
- **Two MIPI DC(DPHY/CPHY) combo PHY** (Два комбинированных PHY MIPI DC (DPHY/CPHY))
  - Support to use **DPHY** or **CPHY** (Поддержка использования DPHY или CPHY)
  - Each **MIPI DPHY V1.2**, **4lanes** (4 линии), **2.5Gbps per lane** (2.5 Гбит/с на линию)
  - Each **MIPI CPHY V1.1**, **3lanes** (3 линии), **2.5Gbps per lane** (2.5 Гбит/с на линию)

- **Four MIPI CSI DPHY** (Четыре MIPI CSI DPHY)
  - Each **MIPI DPHY V1.2**, **2lanes** (2 линии), **2.5Gbps per lane** (2.5 Гбит/с на линию)
  - Support to combine **2 DPHY** together to one **4lanes** (Поддержка объединения двух DPHY в один 4-линейный)

- **Support camera input combination** (Поддерживаемые комбинации входа камер):
  1. **MIPI DCPHY + 4 MIPI CSI DPHY (2 lanes)** – totally support **6 cameras** input (всего 6 камер)
  2. **MIPI DCPHY + 1 MIPI CSI DPHY (4 lanes) + 2 MIPI CSI DPHY (2 lanes)** – totally support **5 cameras** input (всего 5 камер)
  3. **MIPI DCPHY + 2 MIPI CSI DPHY (4 lanes)** – totally support **4 cameras** input (всего 4 камеры)

## DVP interface (Интерфейс DVP)
- **One 8/10/12/16-bit standard DVP interface** (Один стандартный 8/10/12/16-битный интерфейс DVP), up to **150MHz input data** (входные данные до 150 МГц)
- Support **BT.601**/**BT.656** and **BT.1120 VI interface** (Поддержка интерфейсов BT.601/BT.656 и BT.1120 VI)
- Support the polarity of **pixel_clk**, **hsync**, **vsync** configurable (Поддержка настройки полярности pixel_clk, hsync, vsync)

## HDMI RX interface (Интерфейс HDMI RX)
- **Single-port HDMI 2.0 RX PHY**, **4 lanes** (4 линии), no sideband channels (без боковых каналов)
- **Data rate support in HDMI 2.0 mode** (Поддержка скорости передачи в режиме HDMI 2.0)
  - **6Gbps down to 3.4Gbps** (от 6 Гбит/с до 3.4 Гбит/с)
- **Data rate support in HDMI 1.4 mode** (Поддержка скорости передачи в режиме HDMI 1.4)
  - **3.4Gbps down to 250Mbps** (от 3.4 Гбит/с до 250 Мбит/с)

### HDMI 2.0 video formats (Видеоформаты HDMI 2.0)
- **TMDS Scrambler** to enable support for **2160p@60 Hz** with **RGB**/**YCbCr4:4:4** or **YCbCr4:2:2** (Скремблер TMDS для поддержки 2160p@60 Гц с RGB/YCbCr4:4:4 или YCbCr4:2:2)

### YCbCr4:2:2
- Supports **YCbCr 4:2:0** to enable **2160p@60Hz** at lower HDMI link speeds (Поддержка YCbCr 4:2:0 для обеспечения 2160p@60 Гц на более низких скоростях HDMI-линка)

### HDMI 1.4b video formats (Видеоформаты HDMI 1.4b)
- All **CEA-861-E** video formats up to **1080p@120Hz** (Все видеоформаты CEA-861-E до 1080p@120 Гц)
- **HDMI 1.4b 4K x 2K** video formats: **3840x2160p@24Hz/25Hz/30Hz** and **4096x2160p@24Hz**
- **HDMI 1.4b 3D** video modes with up to **340 MHz (TMDS clock)** (3D-видеорежимы HDMI 1.4b с тактовой частотой TMDS до 340 МГц)

### HDCP support (Поддержка HDCP)
- Support **HDCP2.3** and **HDCP1.4** (Поддержка HDCP2.3 и HDCP1.4)
