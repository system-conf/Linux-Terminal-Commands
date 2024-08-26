
# Linux Terminal Commands

## Dosya ve Dizin Yönetimi:
1. **`ls`** - Mevcut dizindeki dosya ve dizinleri listelemek için kullanılır.
   ```bash
   ls
   ```

2. **`cd`** - Dizin değiştirmek için kullanılır.
   ```bash
   cd /path/to/directory
   ```

3. **`pwd`** - Geçerli dizini (bulunduğun yerin yolunu) gösterir.
   ```bash
   pwd
   ```

4. **`cp`** - Dosya veya dizin kopyalamak için kullanılır.
   ```bash
   cp source_file destination_file
   ```

5. **`mv`** - Dosya veya dizin taşımak veya yeniden adlandırmak için kullanılır.
   ```bash
   mv old_name new_name
   ```

6. **`rm`** - Dosya veya dizin silmek için kullanılır.
   ```bash
   rm file_name
   ```

7. **`mkdir`** - Yeni bir dizin oluşturmak için kullanılır.
   ```bash
   mkdir new_directory
   ```

8. **`rmdir`** - Boş bir dizini silmek için kullanılır.
   ```bash
   rmdir directory_name
   ```

## Sistem Bilgisi:
1. **`top`** - Çalışan işlemleri ve sistem kaynaklarının kullanımını gerçek zamanlı olarak gösterir.
   ```bash
   top
   ```

2. **`df`** - Disk kullanımını gösterir.
   ```bash
   df -h
   ```

3. **`du`** - Bir dizinin veya dosyanın disk üzerindeki boyutunu gösterir.
   ```bash
   du -sh /path/to/directory_or_file
   ```

4. **`free`** - Bellek kullanımını gösterir.
   ```bash
   free -h
   ```

5. **`uname`** - Sistem hakkında bilgi verir (kernel versiyonu vb.).
   ```bash
   uname -a
   ```

6. **`uptime`** - Sistemin ne kadar süredir çalıştığını gösterir.
   ```bash
   uptime
   ```

## Dosya ve Dizin İçeriklerini Görüntüleme:
1. **`cat`** - Dosyanın içeriğini terminalde gösterir.
   ```bash
   cat file_name
   ```

2. **`less`** - Büyük dosyaların içeriğini sayfa sayfa görüntülemek için kullanılır.
   ```bash
   less file_name
   ```

3. **`head`** - Bir dosyanın başındaki belirli sayıda satırı gösterir.
   ```bash
   head -n 10 file_name
   ```

4. **`tail`** - Bir dosyanın sonundaki belirli sayıda satırı gösterir.
   ```bash
   tail -n 10 file_name
   ```

5. **`grep`** - Bir dosya içinde belirli bir metin aramak için kullanılır.
   ```bash
   grep "search_term" file_name
   ```

## Ağ İşlemleri:
1. **`ping`** - Bir hedefe veri paketi göndererek bağlantıyı test eder.
   ```bash
   ping google.com
   ```

2. **`ifconfig`** - Ağ arayüzlerinin yapılandırmasını ve durumunu gösterir.
   ```bash
   ifconfig
   ```

3. **`wget`** - Komut satırından dosya indirmek için kullanılır.
   ```bash
   wget http://example.com/file.zip
   ```

4. **`curl`** - URL'leri komut satırından işlemek için kullanılır, genellikle veri indirme veya API çağrıları yapmak için.
   ```bash
   curl http://example.com
   ```

## Diğer Faydalı Komutlar:
1. **`chmod`** - Dosya veya dizinlerin izinlerini değiştirmek için kullanılır.
   ```bash
   chmod 755 file_name
   ```

2. **`chown`** - Dosya veya dizin sahibini değiştirmek için kullanılır.
   ```bash
   chown user:group file_name
   ```

3. **`find`** - Belirli bir kriterle dosya veya dizin aramak için kullanılır.
   ```bash
   find /path/to/search -name "file_name"
   ```

4. **`history`** - Önceki komutları listeler.
   ```bash
   history
   ```

5. **`man`** - Bir komutun kullanım kılavuzunu (manual) gösterir.
   ```bash
   man command_name
   ```
