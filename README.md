# Bootstrap-Responsive-Yapilar

Bu çalışmada bootstrap "none ve block" yapılarını kullanarak responsive yapıda istediğimiz objeleri gizleyip istediklerimizi gösteriyoruz.

<!-- Responsive yapıda ekranlar gözükmüyor -->
    <h1 class="d-block d-sm-none bg-secondary">XS Ekranlarda Göster</h1>
    <h1 class="d-none d-sm-block d-md-none bg-primary">SM Ekranlarda Göster</h1>
    <h1 class="d-none d-md-block d-lg-none bg-warning">MD Ekranlarda Göster</h1>
    <h1 class="d-none d-lg-block d-xl-none bg-danger">LG Ekranlarda Göster</h1>
    <h1 class="d-none d-xl-block bg-success">XL Ekranlarda Göster</h1>

     <!-- Responsive yapıda LG Ekranda istenmeyen kutular gözükmüyor -->
    <div class="container">
        <div class="row">
            <div class="col-sm-6 col-md-4 col-lg-3 col-xl-2 bg-info">LOREM</div>
            <div class="col-sm-6 col-md-4 col-lg-3 col-xl-2 bg-warning">LOREM</div>
            <div class="col-sm-6 col-md-4 col-lg-3 col-xl-2 bg-success">LOREM</div>
            <div class="col-sm-6 col-md-4 col-lg-3 col-xl-2 bg-danger">LOREM</div>
            <div class="col-sm-6 col-md-4 col-lg-3 col-xl-2 d-lg-none d-xl-block bg-primary">LOREM</div>
            <div class="col-sm-6 col-md-4 col-lg-3 col-xl-2 d-lg-none d-xl-block bg-secondary">LOREM</div>
        </div>
    </div>

