# Responsive
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, width=device-width">
    <meta name="author" content="webstoryboy">
    <meta name="description" content="반응형 사이트 따라하기">
    <meta name="keywords" content="반응형사이트, 웹퍼블리셔, 웹접근성, HTML5, webstoryboy, webs">
    <title>반응형 사이트 만들기 : 아웃 라이너</title>

    <!-- style -->
    <link rel="stylesheet" href="css/reset.css">
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/font-awesome.css">
    <link rel="stylesheet" href="css/slick.css">
    <link rel="stylesheet" href="css/lightgallery.css">

    <!-- Facebook meta tags -->
    <meta property="og:type" content="article" />
    <meta property="og:title" content="반응형 사이트 만들기(title)" />
    <meta property="og:url" content="http://richclub8.dothome.co.kr/responsive/html5/index.html" />
    <meta property="og:image" content="http://richclub8.dothome.co.kr/assets/ico/icon.png" />
    <meta property="og:site_name" content="반응형 사이트 만들기(site_name)" />
    <meta property="og:description" content="반응형 사이트 따라하기(description)" />

    <!-- twitter meta tags -->
    <meta name="twitter:card" content="summary_large_image" />
    <meta name="twitter:site" content="@webstoryboy" />
    <meta name="twitter:title" content="반응형 사이트 만들기(title)" />
    <meta name="twitter:description" content="반응형 사이트 만들기(description)." />
    <meta property="twitter:image" content="http://richclub8.dothome.co.kr/assets/ico/icon.png" />

    <!-- 파비콘 -->
    <link rel="shortcut icon" href="icon/favicon-152.png">
    <link rel="apple-touch-icon-precomposed" href="icon/favicon-152.png">
    <link rel="icon" href="path/to/favicon.png">
    <link rel="icon" href="icon/favicon-16.png" sizes="16x16"> 
    <link rel="icon" href="icon/favicon-32.png" sizes="32x32"> 
    <link rel="icon" href="icon/favicon-48.png" sizes="48x48"> 
    <link rel="icon" href="icon/favicon-64.png" sizes="64x64"> 
    <link rel="icon" href="icon/favicon-128.png" sizes="128x128">


    <!-- 웹 폰트 -->
    <link href="https://fonts.googleapis.com/css?family=Nanum+Gothic" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Nanum+Brush+Script" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Abel&display=swap" rel="stylesheet">

    <!-- HTLM5shiv ie6~8 -->
    <!--[if lt IE 9]> 
        <script src="js/html5shiv.min.js"></script>
        <script type="text/javascript">
            alert("현재 당신이 보는 브라우저는 지원하지 않습니다. 최신 브라우저로 업데이트해주세요!");
        </script>
    <![endif]-->

</head>
<body>

    <header id="header">
    	<div class="container">
    		<div class="row">
	    		<div class="header">
	    			<div class="header_menu">
			        	<a href="#">Blog</a>
			        	<a href="#">Github</a>
			        	<a href="#">Webstandard</a>
			        </div>
			        <!-- //header_menu -->
			        <div class="header_tit">
			        	<h1>Professional Web Publihser</h1><br>
			        	<a href="http://webstoryboy.co.kr">http://webstoryboy.co.kr</a>
			        </div>
			        <!-- //header_tit -->
			        <div class="header_icon">
			        	<ul>
			        		<li><a href="#"><i class="fa-brands fa-html5"></i><span>HTML5</span></a></li>
			        		<li><a href="#"><i class="fa-brands fa-github"></i><span>Github</span></a></li>
			        		<li><a href="#" class="facebook"><i class="fa-brands fa-facebook"></i><span>Facebook</span></a></li>
			        		<li><a href="#" class="twitter"><i class="fa-brands fa-twitter"></i><span>twitter</span></a></li>
			        	</ul>
			        </div>
                    <!-- //header_icon -->

                    <!-- 
                        https://developers.facebook.com/tools/debug/
                        https://cards-dev.twitter.com/validator
                    -->

	    		</div>
    		</div>
    	</div>
    </header>
    <!-- header -->

    <nav id="nav">
        <div class="container">
            <div class="row">
                <div class="nav">
                    <h2 class="ir_su">반응형 사이트 전체 메뉴</h2>
                     <div>
                        <h3>HTML Reference</h3>
                        <ol>
                            <li><a href="#">HTML 태그(Tag)</a></li>
                            <li><a href="#">블록 요소/인라인 요소</a></li>
                            <li><a href="#">DTD 선언</a></li>
                            <li><a href="#">언어 속성 설정</a></li>
                            <li><a href="#">HTML &lt;title&gt;</a></li>
                            <li><a href="#">HTML &lt;meta&gt;</a></li>
                            <li><a href="#">특수문자</a></li>
                            <li><a href="#">하이퍼 링크</a></li>
                            <li><a href="#">HTML &lt;style&gt;</a></li>
                            <li><a href="#">HTML &lt;html&gt;</a></li>
                            <li><a href="#">HTML &lt;head&gt;</a></li>
                            <li><a href="#">HTML &lt;div&gt;</a></li>
                            <li><a href="#">HTML &lt;colgroup&gt;</a></li>
                            <li><a href="#">HTML &lt;caption&gt;</a></li>
                        </ol>
                    </div>
                    <div>
                        <h3>CSS  Reference</h3>
                        <ol>
                            <li><a href="#">CSS 선택자</a></li>
                            <li><a href="#">CSS 단위</a></li>
                            <li><a href="#">CSS 색상</a></li>
                            <li><a href="#">CSS 선언 방법</a></li>
                            <li><a href="#">상대주소와 절대주소</a></li>
                            <li><a href="#">CSS float</a></li>
                            <li><a href="#">이미지 표현 방법</a></li>
                            <li><a href="#">이미지 스프라이트</a></li>
                            <li><a href="#">IR 효과</a></li>
                            <li><a href="#">이미지 최적화</a></li>
                            <li><a href="#">background-color</a></li>
                            <li><a href="#">border-style</a></li>
                            <li><a href="#">font-size</a></li>
                            <li><a href="#">text-align</a></li>
                        </ol>
                    </div>
                    <div class="last">
                        <h3>Webstandard</h3>
                        <ol>
                            <li><a href="#">웹 표준</a></li>
                            <li><a href="#">웹 접근성</a></li>
                            <li><a href="#">W3C</a></li>
                            <li><a href="#">웹 접근성 연구소</a></li>
                            <li><a href="#">네이버 널리</a></li>
                            <li><a href="#">다음 다룸</a></li>
                            <li><a href="#">Webstandard</a></li>
                        </ol>
                    </div>  
                </div>
            </div>
        </div>
    </nav>
    <!-- //nav -->

    <article id="title">
        <div class="containaer">
            <div class="title">
                <h2>"나는 퍼블리셔다"</h2>
                <a href="#" class="btn">
                    <i class="fa fa-angle-down" aria-hidden="true"></i>
                    <span class="ir_su">전체메뉴 보기</span>
                </a>
            </div>
        </div>
    </article>
    <!-- //title -->

    <main>
        <section id="contents">
            <div class="container">
                <h2 class="ir_su">반응형 사이트 컨텐츠</h2>
                <section id="cont_left">
                    <h3 class="ir_su">반응형 사이트 왼쪽 컨텐츠</h3>
                    <article class="colum col1">
                        <h4 class="col_tit">Menu</h4>
                        <p class="col_desc">box-shadow를 이용한 마우스 오버 효과입니다.</p>
                        <!-- 메뉴 -->
                        <div class="menu">
                            <ul>
                                <li><a href="#">Cafe <i class="fa fa-angle-double-right" aria-hidden="true"></i></a></li>
                                <li><a href="#">Tutorial <i class="fa fa-angle-double-right" aria-hidden="true"></i></a></li>
                                <li><a href="#">WebSite <i class="fa fa-angle-double-right" aria-hidden="true"></i></a></li>
                                <li><a href="#">Reference <i class="fa fa-angle-double-right" aria-hidden="true"></i></a></li>
                                <li><a href="#">CSS3 <i class="fa fa-angle-double-right" aria-hidden="true"></i></a></li>
                                <li><a href="#">HTML5 <i class="fa fa-angle-double-right" aria-hidden="true"></i></a></li>
                            </ul>
                        </div>
                        <!-- //메뉴 -->
                    </article>
                    <!-- //col1 -->
                    <article class="colum col2">
                        <h4 class="col_tit">Notice</h4>
                        <p class="col_desc">게시판 영역의 한줄 효과와 두줄 효과 게시판입니다.</p>
                        <!-- 게시판 -->
                        <div class="notice1">
                            <h5>Notice1</h5>
                            <ul>
                                <li><a href="#">이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다.</a></li>
                                <li><a href="#">이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다.</a></li>
                                <li><a href="#">이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다.</a></li>
                                <li><a href="#">이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다.</a></li>
                            </ul>
                            <a href="#" class="more" title="더 보기">More <i class="fa-solid fa-circle-plus"></i></a>
                        </div>
                        <!-- //게시판 -->
                        <!-- 게시판2-->
                        <div class="notice2 mt15">
                            <h5>Notice2</h5>
                            <ul>
                                <li><a href="#">이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다. </a></li>
                                <li><a href="#">이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다.</a></li>
                                <li><a href="#">이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다.</a></li>
                                <li><a href="#">이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다. 이 줄은 한 줄 효과입니다.</a></li>
                            </ul>
                            <a href="#" class="more" title="더 보기">More <i class="fa-solid fa-circle-plus"></i></a>
                        </div>
                        <!-- //게시판2 -->
                    </article>
                    <!-- //col2 -->
                    <article class="colum col3">
                        <h4 class="col_tit">Blog</h4>
                        <p class="col_desc">해상도에 따라 이미지를 다르게 표현하는 방법입니다.</p>
                        <!-- blog1 -->
                            <div class="blog1">
                                <h5 class="ir_su">image1</h5>
                                <figure>
                                    <!-- <img src="img/blog1_@1.jpg" class="img-normal" alt="normal image">
                                    <img src="img/blog1_@2.jpg" class="img-retina" alt="retina image" width="100%"> -->
                                    <img src="img/blog3_@1.jpg" srcset="img/blog3_@1.jpg 1x, img/blog3_@2.jpg 2x, img/blog3_@3.jpg" alt="normal image"> 
                                    <figcaption>반응형 웹 사이트 이미지 글입니다. 반응형 웹 사이트 이미지 글입니다. 반응형 웹 사이트 이미지 글입니다. 반응형 웹 사이트 이미지 글입니다.</figcaption>
                                </figure>
                            </div>
                        <!-- //blog1 -->
                        <!-- blog2 -->
                            <div class="blog2 mt15">
                                <div class="img-retina">
                                    <h5>image2</h5>
                                </div>
                                <p>반응형 웹 사이트 이미지 글입니다. 반응형 웹 사이트 이미지 글입니다. 반응형 웹 사이트 이미지 글입니다.</p>
                            </div>
                        <!-- //blog2 -->
                    </article>
                    <!-- //col3 -->
                </section>
                <section id="cont_center">
                    <h3 class="ir_su">반응형 사이트 가운데 컨텐츠</h3>
                    <article class="colum col4">
                        <h4 class="col_tit">Slick Slider</h4>
                        <p class="col_desc">Slick.js를 이용한 이미지 슬라이드 효과입니다.</p>
                        <!-- 이미지 슬라이드 -->
                            <div class="slider">
                                <div>
                                    <figure>
                                        <img src="img/slider001.jpg" alt="이미지1">
                                        <figcaption><em>Responsive Site1</em><span>슬라이드 플러그인을 이용한 반응형 이미지 슬라이드 입니다.</span></figcaption>        
                                    </figure>
                                </div>
                                <div>
                                    <figure>
                                        <img src="img/slider001.jpg" alt="이미지2">
                                        <figcaption><em>Responsive Site2</em><span>슬라이드 플러그인을 이용한 반응형 이미지 슬라이드 입니다.</span></figcaption>        
                                    </figure>
                                </div>
                                <div>
                                    <figure>
                                        <img src="img/slider001.jpg" alt="이미지3">
                                        <figcaption><em>Responsive Site3</em><span>슬라이드 플러그인을 이용한 반응형 이미지 슬라이드 입니다.</span></figcaption>        
                                    </figure>
                                </div>
                            </div>
                        <!-- //이미지 슬라이드 -->
                    </article>
                    <!-- //col4 -->
                    <article class="colum col5">
                        <h4 class="col_tit">Blend Effect</h4>
                        <p class="col_desc">Background-blend-mode와 mix-blend-mode</p>
                        <!-- lightbox -->
                        <div class="lightbox square clearfix">
                            <a href="img/light01_s.jpg"><img src="img/light01.jpg" alt="이미지1"><em>blur</em></a>
                            <a href="img/light02_s.jpg"><img src="img/light02.jpg" alt="이미지2"><em>brightness</em></a>
                            <a href="img/light03_s.jpg"><img src="img/light03.jpg" alt="이미지3"><em>contrast</em></a>
                            <a href="img/light04_s.jpg"><img src="img/light04.jpg" alt="이미지4"><em>grayscale</em></a>
                            <a href="img/light05_s.jpg"><img src="img/light05.jpg" alt="이미지5"><em>hur-rotate</em></a>
                            <a href="img/light06_s.jpg"><img src="img/light06.jpg" alt="이미지6"><em>invert</em></a>
                            <a href="img/light07_s.jpg"><img src="img/light07.jpg" alt="이미지7"><em>opacity</em></a>
                            <a href="img/light08_s.jpg"><img src="img/light08.jpg" alt="이미지8"><em>saturate</em></a>
                            <a href="img/light09_s.jpg"><img src="img/light09.jpg" alt="이미지9"><em>sepia</em></a>
                            <a href="img/light10_s.jpg"><img src="img/light10.jpg" alt="이미지10"><em>Mix</em>    </a>
                        </div>
                        <!-- //lightbox -->
                    </article>
                    <!-- //col5 -->
                    <article class="colum col6">
                        <h4 class="col_tit">Video</h4>
                        <p class="col_desc">반응형 영상을 보여주는 영역입니다.</p>
                        <!-- Video -->
                            <!-- <video autoplay="autoplay" controls="controls" loop="loop">
                                <source src="img/video.mp4" type="video/mp4">
                            </video> -->
                            <div class="video">
                                <iframe src="https://www.youtube.com/embed/a7Zh4XeBZlU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                            </div>
                        <!-- //Video -->
                    </article>
                    <!-- //col6 -->
                </section>
                <section id="cont_right">
                    <h3 class="ir_su">반응형 사이트 오른쪽 컨텐츠</h3>
                    <article class="colum col7">
                        <h4 class="col_tit">Effect1</h4>
                        <p class="col_desc">CSS3의 transform을 이용한 마우스 오버효과입니다.</p>
                        <!-- side1 -->
                            <div class="side1">
                                <figure class="front">
                                    <img src="img/side1.jpg" alt="이미지1">
                                </figure>
                                <div class="back">
                                    <i class="fa fa-heart" aria-hidden="true"></i>
                                </div>
                            </div>
                        <!-- //side1 -->
                    </article>
                    <!-- //col7 -->
                    <article class="colum col8">
                        <h4 class="col_tit">Effect2</h4>
                        <p class="col_desc">CSS3의 transform을 이용한 마우스 오버효과입니다.</p>
                        <!-- side2 -->
                            <div class="side2">
                                <figure class="front">
                                    <img src="img/side4.jpg" alt="이미지2">
                                    <figcaption>
                                        Hover Effect
                                    </figcaption>
                                </figure>
                                <figure class="back">
                                    <img src="img/side2.jpg" alt="이미지2">
                                    <figcaption>
                                        Hover Effect
                                    </figcaption>
                                </figure>
                            </div>
                        <!-- //side2 -->
                    </article>
                    <!-- //col8 -->
                    <article class="colum col9">
                        <h4 class="col_tit">Effect3</h4>
                        <p class="col_desc">CSS3의 transform을 이용한 마우스 오버효과입니다.</p>
                        <!-- side3 -->
                            <div class="side3">
                                <figure>
                                    <img src="img/side3.jpg" alt="이미지3">
                                    <figcaption>
                                        <h3>Hover<em>Effect</em></h3>
                                    </figcaption>
                                </figure>
                            </div>
                        <!-- //side3 -->
                    </article>
                    <!-- //col9 -->
                </section>
            </section>
        <!-- contents -->
    </main>

    <footer id="footer">
        <div class="container">
            <div class="row">
                <div class="footer">
                    <ul>
                        <li><a href="#">사이트 도움말</a></li>
                        <li><a href="#">사이트 이용약관</a></li>
                        <li><a href="#">사이트 운영원칙</a></li>
                        <li><a href="#"><strong>개인정보취급방침</strong></a></li>
                        <li><a href="#">책임의 한계와 법적고지</a></li>
                        <li><a href="#">게시중단요청서비스</a></li>
                        <li><a href="#">고객센터</a></li>
                    </ul>
                    <address>
                        Copyright ©
                        <a href="http://webstoryboy.co.kr"><strong>webstoryboy</strong></a>
                        All Rights Reserved.
                    </address>
                </div>
            </div>
        </div>
    </footer>
    <!-- footer -->

    
    <!-- JavaScript Libraries -->
    <script src="js/jquery.min_1.12.4.js"></script>
    <script src="js/modernizr-custom.js"></script>
    <script src="js/slick.min.js"></script>
    <script src="js/lightgallery.min.js"></script>
    <script src="https://kit.fontawesome.com/8f66b29f43.js" crossorigin="anonymous"></script>
    <script>
        //접기/펼치기
        $(".btn").click(function(e){
            e.preventDefault();
            $(".nav").slideToggle();
            $(".btn").toggleClass("open");

            if($(".btn").hasClass("open")){
                //open이 있을 때
                $(".btn").find("i").attr("class","fa fa-angle-up");                
            } else {
                //open이 없을 때
                $(".btn").find("i").attr("class","fa fa-angle-down");
            }
        });

        $(window).resize(function(){
            var wWidth = $(window).width();
            if(wWidth > 600){
                $(".nav").removeAttr("style");
            }

        });

        //라이트 박스
        $(".lightbox").lightGallery({
            autoplay: true,
            pause: 3000,
            progressBar: true
        });

        //이미지 슬라이더
        $(".slider").slick({
            dots: true,
            autoplay: true,
            autoplaySpeed: 3000,
            arrows: true,
            responsive: [
                {
                    breakpoint: 768,
                    settings: {
                        autoplay: false,
                        }
                }
            ]
        });

        //sns 공유하기
        $(".facebook").click(function(e){
            e.preventDefault();
            window.open('https://www.facebook.com/sharer/sharer.php?u=' +encodeURIComponent(document.URL)+'&t='+encodeURIComponent(document.title), 'facebooksharedialog', 'menubar=no, toolbar=no, resizable=yes, scrollbars=yes, height=300, width=600'); 
        });
        $(".twitter").click(function(e){
            e.preventDefault();
            window.open('https://twitter.com/intent/tweet?text=[%EA%B3%B5%EC%9C%A0]%20' +encodeURIComponent(document.URL)+'%20-%20'+encodeURIComponent(document.title), 'twittersharedialog', 'menubar=no, toolbar=no, resizable=yes, scrollbars=yes, height=300, width=600');
        });
    </script>
</body>
</html>
