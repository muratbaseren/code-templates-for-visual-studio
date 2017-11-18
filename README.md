# Code Templates For Visual Studio

Visual Studio 'da oluşturduğunuz bir **ASP.NET MVC Razor** projenizin içerisine **CodeTemplates** klasörünü sürükle bırak ile ekleyerek **Scaffolding** ile oluşturulacak olan Controller ve View'lar için farklı bir **T4 template** kullanmış olursunuz.

**CodeTemplates** klasörünü ekledikten sonra ASP.NET MVC projenizde **Controllers** klasörüne sağ tıklayarak **Add Controller** diyerek **MVC 5 Controller with views, using Entity Framework** ile Controller ve View'ları oluşturmak istediğinizde CodeTemplates içindeki T4 şablonları kullanılacaktır.

![CodeTemplates klasörünün projeye eklenmesi](https://i0.wp.com/muratbaseren.files.wordpress.com/2017/11/code-templates-for-vs-0.png?ssl=1&w=300)

![Projeye bir controller eklenmesi](https://i0.wp.com/muratbaseren.files.wordpress.com/2017/11/code-templates-for-vs-1.png?ssl=1&w=700)

![Controller eklerken EF kullanılarak View larında oluşturulmasının sağlanması](https://i1.wp.com/muratbaseren.files.wordpress.com/2017/11/code-templates-for-vs-2.png?ssl=1&w=700)

Bu sayede şu farklılıklar da sayfalar oluşturulacaktır;

 1. Controller kodunda bazı action'larda eklenen **[Bind="..."]** parametre attribute 'un **eklenmemesi** sağlanmıştır.
 2. Index.cshtml de tablonun bootstrap'den gelen **tüm tablo class'larını kullanması** sağlanmıştır. (**table-condensed hariç**) Ayrıca **link'ler ikon içeren düğmeler** şeklinde minimum yer kaplayacak şekilde oluşturulmuştur.
 3. Create.cshtml, Edit.cshtml, Details.cshtml, Delete.cshtml sayfalarında **düğmeler ikon içeren** şekilde oluşturulmuştur.
 4. Tüm view'larda, sayfa başlığını gösteren **H2 elementi** içerisindeki metinin sayfanın **ViewBag.Title değişkeninden** okunması sağlanmıştır.

![Controller kodlarındaki Bind attribute'larının kullanılmaması](https://i2.wp.com/muratbaseren.files.wordpress.com/2017/11/code-templates-for-vs-3.png?ssl=1&w=700)

![Tablo görselliği ve düğmelerin ikonlu olarak tasarlanması](https://i1.wp.com/muratbaseren.files.wordpress.com/2017/11/code-templates-for-vs-4.png?ssl=1&w=700)

![Create, Edit, Details, Delete sayfalarındaki düğme tasarımları](https://i0.wp.com/muratbaseren.files.wordpress.com/2017/11/code-templates-for-vs-5.png?ssl=1&w=400)
