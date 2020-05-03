//BU SAYFADA BÜTÜN GRUP ÜYELERÝNÝN YAPMIÞ OLDUÐU KATKILAR GÖRÜNMEKTEDÝR.
<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Sanal Eðitim</title>
    
    <!-- Bootstrap -->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="css/font-awesome.min.css">
    
    <!-- Custom CSS -->
    <link rel="stylesheet" href="css/owl.carousel.css">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="css/responsive.css">

  </head>
  <body>
   
    <div class="header-area">
        <div class="container">
            <div class="row">
                <div class="col-md-8">
                    <div class="user-menu">
                        <ul>
                            <li><a href="#"><i class="fa fa-user"></i> Hesabým</a></li>
                            <li><a href="#"><i class="fa fa-heart"></i>Beðendiklerim</a></li>
                            <li><a href="#"><i class="fa fa-user"></i> Sepetim</a></li>
                            <li><a href="#"><i class="fa fa-user"></i> Ödeme</a></li>
                            <li><a href="#"><i class="fa fa-user"></i> Oturum Aç</a></li>
                        </ul>
                    </div>
                </div>
                
                <div class="col-md-4">
                    <div class="header-right">
                        <ul class="list-unstyled list-inline">

                            <li class="dropdown dropdown-small">
                                <a data-toggle="dropdown" data-hover="dropdown" class="dropdown-toggle" href="#"><span class="key">Diller :</span><span class="value">Türkçe </span><b class="caret"></b></a>
                                <ul class="dropdown-menu">
                                    <li><a href="#">Ýngilizce</a></li>
                                </ul>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div> <!-- End header area -->
  //KODLARIN BU KISMINI DÝLEK SARIYERLÝOÐLU OLUÞTURMUÞTUR. BURADA SAYFANIN EN ÜSTÜNDEKÝ MENÜLER OLUÞTURULMUÞTUR. HESABIM,BEÐENDÝKLERÝM, SEPETÝM, ÖDEME, OTURUM AÇMA GÝBÝ.
  //BUNUN YANI SIRA EN SAÐA DÝL ÝLE ÝLGÝLÝ SEÇÝM KOYULMUÞTUR.  
  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------
    <div class="site-branding-area">
        <div class="container">
            <div class="row">
                <div class="col-sm-6">
                    <div class="logo">
                        <h1><a href="./"><img src="img/logo.png"></a></h1>
                    </div>
                </div>
                
                <div class="col-sm-6">
                    <div class="shopping-item">
                        <a href="#">Sepet<span class="cart-amunt"></span> <i class="fa fa-shopping-cart"></i> <span class="product-count">0</span></a>
                    </div>
                </div>
            </div>
        </div>
    </div> <!-- End site branding area -->
  //KODLARIN BU KISMINI DÝLEK SARIYERLÝOÐLU OLUÞTURMUÞTUR. BU KISIMDA ÝSE SÝTENÝN LOGOSU YERLEÞTÝRÝLMÝÞTÝR VE YAN TARAFINA SEPET ÖÐESÝ KONULMUÞTUR.  
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------
    <div class="mainmenu-area">
        <div class="container">
            <div class="row">
                <div class="navbar-header">
                    <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>
                </div> 
                <div class="navbar-collapse collapse">
                    <ul class="nav navbar-nav">
                        <li class="active"><a href="index.html">Anasayfa</a></li>
                        <li><a href="#">TYT</a></li>
                        <li><a href="#">AYT</a></li>
                        <li><a href="#">LÝSE</a></li>
                        <li><a href="#">SORU ÇÖZÜMLERÝ</a></li>
                        <li><a href="#">DENEME SINAVLARI</a></li>
                        <li><a href="#">KÝTAPLAR</a></li>
                        <li><a href="#">ÝLETÝÞÝM</a></li>
                    </ul>
                </div>  
            </div>
        </div>
    </div> <!-- End mainmenu area -->
  //KODUN BU KISMINI BÜÞRA KINACI OLUÞTURMUÞTUR. BU AÞAMADA SÝTEDEKÝ KATEGORÝLER BELÝRTÝLMÝÞTÝR.
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------
    <div class="slider-area">
        	<!-- Slider -->
			<div class="block-slider block-slider4">
				<ul class="" id="bxslider-home4">
					<li>
						<img src="img/slider1.jpg" alt="Slide">					
					</li>
					<li><img src="img/slider2.jpg" alt="Slide">					
					</li>
					<li><img src="img/slider3.jpg" alt="Slide">					
					</li>
					<li><img src="img/slider4.jpg" alt="Slide">	
					</li>
				</ul>
			</div>
			<!-- ./Slider -->
    </div> <!-- End slider area -->
    //KODUN BU KISMINI BÜÞRA KINACI OLUÞTURMUÞTUR VE BURADA SLÝDERLER VARDIR. KAYAN RESÝMLER REKLAM YAPMAK ÝÇÝN KOYULMUÞTUR.
    ----------------------------------------------------------------------------------------------------------------------------------------------------------------
    <div class="promo-area">
        <div class="zigzag-bottom"></div>
        <div class="container">
            <div class="row">
                <div class="col-md-3 col-sm-6">
                    <div class="single-promo promo1">
                        <i class="fa fa-refresh"></i>
                        <p>30 Gün Ýade</p>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="single-promo promo2">
                        <i class="fa fa-truck"></i>
                        <p>Ücretsiz Kargo</p>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="single-promo promo3">
                        <i class="fa fa-lock"></i>
                        <p>Güvenli Ödeme</p>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="single-promo promo4">
                        <i class="fa fa-gift"></i>
                        <p>Yeni Dersler</p>
                    </div>
                </div>
            </div>
        </div>
    </div> <!-- End promo area -->
    //BU KODLARI GURBET POLAT OLUÞTURMUÞTUR. BU KODLARLA ALIÞVERÝÞ ÝLE ÝLGÝLÝ BÝLGÝLER VERÝLMÝÞTÝR. KARGO ÜCRETLERÝ, ÐÜVENLÝ ÖDEME ÝLE ÝLGÝLÝ.
    -----------------------------------------------------------------------------------------------------------------------------------------------------------------------
    <div class="maincontent-area">
        <div class="zigzag-bottom"></div>
        <div class="container">
            <div class="row">
                
            </div>
        </div>
    </div> <!-- End main content area -->
    
    <div class="brands-area">
        <div class="zigzag-bottom"></div>
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="brand-wrapper">
                        <div class="brand-list">
                            <img src="img/yayýn1.png" alt="">
                            <img src="img/yayýn2.jpg" alt="">
                            <img src="img/yayýn3.jpg" alt="">
                            <img src="img/yayýn4.png" alt="">
                            <img src="img/yayýn5.jpg" alt="">
                            <img src="img/yayýn6.jpg" alt="">                          
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div> <!-- End brands area -->
    //BU KODLARI GURBET POLAT OLUÞTURMUÞTUR. BURADA SÝTENÝN REFERANSLARI YER ALMAKTADIR.
    -------------------------------------------------------------------------------------------------------------------------------------------------------------
    <div class="product-widget-area">
        <div class="zigzag-bottom"></div>
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <div class="single-product-widget">
                        <h2 class="product-wid-title">Çok Satanlar</h2>
                        <a href="" class="wid-view-more">Hepsi</a>
                        <div class="single-wid-product">
                            <a href="#"><img src="img/tyt_matematik.png" alt="" class="product-thumb"></a>
                            <h2><a href="#">TYT Matematik</a></h2>
                            <div class="product-wid-rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                            <div class="product-wid-price">
                                <ins>?25.00</ins> <del>?35.00</del>
                            </div>                            
                        </div>
                        <div class="single-wid-product">
                            <a href="#"><img src="img/tyt_fenbilgisi.png" alt="" class="product-thumb"></a>
                            <h2><a href="#">TYT Fen Bilgisi</a></h2>
                            <div class="product-wid-rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                            <div class="product-wid-price">
                                <ins>?25.00</ins> <del>?35.00</del>
                            </div>                            
                        </div>
                        <div class="single-wid-product">
                            <a href="#"><img src="img/12_matematik.png" alt="" class="product-thumb"></a>
                            <h2><a href="#">12.Sýnýf Matematik</a></h2>
                            <div class="product-wid-rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                            <div class="product-wid-price">
                                <ins>?25.00</ins> <del>?35.00</del>
                            </div>                            
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="single-product-widget">
                        <h2 class="product-wid-title">Son Görüntülenenler</h2>
                        <a href="#" class="wid-view-more">Hepsi</a>
                        <div class="single-wid-product">
                            <a href="#"><img src="img/ayt_turkce.png" alt="" class="product-thumb"></a>
                            <h2><a href="#">AYT Türkçe</a></h2>
                            <div class="product-wid-rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                            <div class="product-wid-price">
                                <ins>?25.00</ins> <del>?35.00</del>
                            </div>                            
                        </div>
                        <div class="single-wid-product">
                            <a href="#"><img src="img/tyt_turkce.png" alt="" class="product-thumb"></a>
                            <h2><a href="#">TYT Türkçe</a></h2>
                            <div class="product-wid-rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                            <div class="product-wid-price">
                                <ins>?25.00</ins> <del>?35.00</del>
                            </div>                            
                        </div>
                        <div class="single-wid-product">
                            <a href="#"><img src="img/11_matematik.png" alt="" class="product-thumb"></a>
                            <h2><a href="#">11.Sýnýf Matematik</a></h2>
                            <div class="product-wid-rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                            <div class="product-wid-price">
                                <ins>?25.00</ins> <del>?35.00</del>
                            </div>                            
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="single-product-widget">
                        <h2 class="product-wid-title">Yeni Çýkanlar</h2>
                        <a href="#" class="wid-view-more">Hepsi</a>
                        <div class="single-wid-product">
                            <a href="#"><img src="img/tyt_deneme.png" alt="" class="product-thumb"></a>
                            <h2><a href="#">TYT Deneme Sýnavý</a></h2>
                            <div class="product-wid-rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                            <div class="product-wid-price">
                                <ins>?25.00</ins> <del>?35.00</del>
                            </div>                            
                        </div>
                        <div class="single-wid-product">
                            <a href="#"><img src="img/12_fenbilgisi.png" alt="" class="product-thumb"></a>
                            <h2><a href="#">12.Sýnýf Fen Bilgisi</a></h2>
                            <div class="product-wid-rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                            <div class="product-wid-price">
                                <ins>?25.00</ins> <del>?35.00</del>
                            </div>                            
                        </div>
                        <div class="single-wid-product">
                            <a href="#"><img src="img/universite.png" alt="" class="product-thumb"></a>
                            <h2><a href="#">Üniversite Hazýlýrlýk</a></h2>
                            <div class="product-wid-rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                            <div class="product-wid-price">
                                <ins>?25.00</ins> <del>?35.00</del>
                            </div>                            
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div> <!-- End product widget area -->
    //BU KODLARI MELÝKE KAYAALP OLUÞTURMUÞTUR. BURADA KOLAYLIK SAÐLANMASI AÇISINDAN EN SON ÐÖRÜNTÜLENENLER, ÇOK SATANLAR, YENÝ ÇIKANLAR GÖRÜNTÜLENMEKTEDÝR.
    ---------------------------------------------------------------------------------------------------------------------------------------------------------------
    <div class="footer-top-area">
        <div class="zigzag-bottom"></div>
        <div class="container">
            <div class="row">
                <div class="col-md-3 col-sm-6">
                    <div class="footer-about-us">
                        <h2><span>Sanal Eðitim</span></h2>
                        <p>Sanal eðitim labaratuvarý öðrencilere eðitimlerinde destek çýkmak özellikle zor dönemlerinde 8.Sýnýf ve lise'de gerekli desteði vermek için buradayýz.Eðitimler de ücretsiz deneme,uygun fiyata dersler ve 30 gün içinde geri iade yapabilme avantajý. </p>
                        <div class="footer-social">
                            <a href="#" target="_blank"><i class="fa fa-facebook"></i></a>
                            <a href="#" target="_blank"><i class="fa fa-twitter"></i></a>
                            <a href="#" target="_blank"><i class="fa fa-youtube"></i></a>
                            <a href="#" target="_blank"><i class="fa fa-linkedin"></i></a>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-3 col-sm-6">
                    <div class="footer-menu">
                        <h2 class="footer-wid-title">Üyelik Paketleri </h2>
                        <ul>
                            <li><a href="#">Ücretsiz Üyelik</a></li>
                            <li><a href="#">YKS 2020 FIRSAT PAKETÝ 1 (SAYISAL)</a></li>
                            <li><a href="#">YKS 2020 FIRSAT PAKETÝ 2 (EA-SÖZ)</a></li>
                            <li><a href="#">YKS 2020 FIRSAT PAKETÝ 3 (TYT)</a></li>
                            <li><a href="#">YKS 2020 FIRSAT PAKETÝ 4 (AYT)</a></li>
                        </ul>                        
                    </div>
                </div>
                
                <div class="col-md-3 col-sm-6">
                    <div class="footer-menu">
                        <h2 class="footer-wid-title">Bilgilendirme</h2>
                        <ul>
                            <li><a href="#">Üyelik Sözleþmesi</a></li>
                            <li><a href="#">Kiþisel Veriler Politikasý</a></li>
                            <li><a href="#">Nasýl Üye Olurum?</a></li>
                            <li><a href="#">Sýkça Sorulan Sorular</a></li>
                            <li><a href="#">Ýletiþim</a></li>
                        </ul>                        
                    </div>
                </div>
                
                <div class="col-md-3 col-sm-6">
                    <div class="footer-newsletter">
                        <h2 class="footer-wid-title">Ýletiþim</h2>
                        <p>Bize Ulaþýn, Destek ve Yardýmlarýnýzý her zaman ihtiyacýmýz var.</p>
                        <div class="newsletter-form">
                            <form action="#">
                                <input type="email" placeholder="Mesaj Yaz...">
                                <input type="submit" value="Gönder">
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div> <!-- End footer top area -->
    
    <div class="footer-bottom-area">
        <div class="container">
            <div class="row">
                <div class="col-md-8">
                    <div class="copyright">
                        <p>&copy; Telif Hakký © 2020 Sanal Eðitim Labaratuvarý</p>
                    </div>
                </div>
                
                <div class="col-md-4">
                    <div class="footer-card-icon">
                        <i class="fa fa-cc-mastercard"></i>
                        <i class="fa fa-cc-paypal"></i>
                        <i class="fa fa-cc-visa"></i>
                    </div>
                </div>
            </div>
        </div>
    </div> <!-- End footer bottom area -->
   //SÝTENÝN BU ALT BÝLGÝLER BÖLÜMÜNÜ YUSUF SAHA KODLAMIÞTIR. BURADA SÝTE HAKKINDA BÝLGÝLER, AVANTAJLI PAKETLER VE SÝTENÝN SOSYAL MEDYA HESAPLARI YER ALMAKTADIR.
   --------------------------------------------------------------------------------------------------------------------------------------------------------------
    <!-- JQuery Form Sunucusu -->
    <script src="https://code.jquery.com/jquery.min.js"></script>
    
    
    <!-- jQuery yapýþkan menu -->
    <script src="js/owl.carousel.min.js"></script>
    <script src="js/jquery.sticky.js"></script>
    
    <!-- Main Script -->
    <script src="js/main.js"></script>
    
    <!-- Slider -->
    <script type="text/javascript" src="js/bxslider.min.js"></script>
	<script type="text/javascript" src="js/script.slider.js"></script>
  </body>
</html>