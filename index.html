<!DOCTYPE html>
<html>
  <head>
    <title>μαζί</title>
    <meta name="viewport" content="initial-scale=1.0">
    <meta charset="utf-8">
    <link rel="stylesheet" href="styles.css">
    <script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
  </head>
  <body>
      <div class="overlay"></div>
      <div class="text">
          <div>Τη χρονιά που μας πέρασε</div>
          <div id="prespes">περπατήσαμε πάνω στο νερό</div>
          <div id="alpeis">χιονοτσουλήσαμε</div>
          <div id="maganiakos">χορέψαμε</div>
          <div id="sandpiper">υδροβατήσαμε</div>
          <div id="ithaki">κάναμε μία...</div>
          <div id="oikopedo">...ωραίο σκέψη</div>
          <div id="treis">και οι δύο σιγά σιγά γινόμαστε</div>
    </div>
        <div id="panoContainer">
            <div id="pano"></div>
            <video id="maganiakosVideo" width="100%" height="100%" autoplay muted loop>
                <source src="maganiakos.mp4" type="video/mp4">
            </video>
            <video id="sandpiperVideo" width="100%" height="100%" autoplay muted loop>
                <source src="sandpiper.mp4" type="video/mp4">
            </video>
            <img id="oikopedoImg" src="./oikopedo.jpg"/>
            <div id="treisImg">
                <img src="./treis.jpg"/>
            </div>
        </div>
    <script>
        function initialize() {
            var prespesCoords = {lat: 40.7924734, lng: 21.0749567};
            var alpeisCoords = {lat: 46.9482333, lng: 8.97918},
                ithakiCoords = {lat: 38.4540426, lng: 20.6835162},
                $prespes = $('#prespes'),
                $alpeis = $('#alpeis'),
                $ithaki = $('#ithaki'),
                $maganiakosVideo = $('#maganiakosVideo'),
                $maganiakos = $('#maganiakos'),
                $sandpiperVideo = $('#sandpiperVideo'),
                $sandpiper = $('#sandpiper'),
                $overlay = $('.overlay'),
                $oikopedo = $('#oikopedo'),
                $oikopedoImg = $('#oikopedoImg'),
                $treis = $('#treis'),
                $treisImg = $('#treisImg');
            var panorama = new google.maps.StreetViewPanorama(
                document.getElementById('pano'), {
                    position: prespesCoords,
                    zoom: 1,
                    panControl: false,
                    addressControl: false,
                    fullscreenControl: false,
                    linksControl: false,
                    pov: {
                        heading: 80,
                        pitch: -20
                    }
                });
            var elementAlreadyInViewport;

            $('.text').scroll(function() {
                if (isElementInViewport($alpeis) && elementAlreadyInViewport !== 'alpeis') {
                    panorama.setPosition(alpeisCoords);
                    $maganiakosVideo.hide();
                    $sandpiperVideo.hide();
                    $oikopedoImg.hide();
                    elementAlreadyInViewport = 'alpeis';
                    
                } else if (isElementInViewport($prespes) && elementAlreadyInViewport !== 'prespes') {
                    panorama.setPosition(prespesCoords);
                    $maganiakosVideo.hide();
                    $sandpiperVideo.hide();
                    elementAlreadyInViewport = 'prespes';
                    $overlay.fadeOut();
                    $oikopedoImg.hide();
                    $treisImg.hide();
                } else if (isElementInViewport($maganiakos) && elementAlreadyInViewport !== 'maganiakos') {
                    elementAlreadyInViewport = 'maganiakos';
                    $sandpiperVideo.hide();
                    $treisImg.hide();
                    $maganiakosVideo.show();
                    $oikopedoImg.hide();
                }  else if (isElementInViewport($sandpiper) && elementAlreadyInViewport !== 'sandpiper') {
                    elementAlreadyInViewport = 'sandpiper';
                    $maganiakosVideo.hide();
                    $treisImg.hide();
                    $sandpiperVideo.show();
                    $oikopedoImg.hide();
                } else if (isElementInViewport($ithaki) && elementAlreadyInViewport !== 'ithaki') {
                    panorama.setPosition(ithakiCoords);
                    elementAlreadyInViewport = 'ithaki';
                    $maganiakosVideo.hide();
                    $sandpiperVideo.hide();
                    $treisImg.hide();
                    $oikopedoImg.hide();
                } else if (isElementInViewport($oikopedo) && elementAlreadyInViewport !== 'oikopedo') {
                    elementAlreadyInViewport = 'oikopedo';
                    $maganiakosVideo.hide();
                    $sandpiperVideo.hide();
                    $treisImg.hide();
                    $oikopedoImg.css({left: 0}).show().css({left: -($oikopedoImg.outerWidth() - $(window).outerWidth())});
                } else if (isElementInViewport($treis) && elementAlreadyInViewport !== 'treis') {
                    elementAlreadyInViewport = 'treis';
                    $maganiakosVideo.hide();
                    $sandpiperVideo.hide();
                    $oikopedoImg.hide();
                    $treisImg.show();
                }
            });
            
            function isElementInViewport (el) {
                //special bonus for those using jQuery
                if (typeof jQuery === "function" && el instanceof jQuery) {
                    el = el[0];
                }

                var rect = el.getBoundingClientRect();

                return (
                    rect.top >= 0 &&
                    rect.left >= 0 &&
                    rect.bottom <= (window.innerHeight || document.documentElement.clientHeight) && /*or $(window).height() */
                    rect.right <= (window.innerWidth || document.documentElement.clientWidth) /*or $(window).width() */
                );
            }
        }
    </script>
    <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDfZd_a5zNU1c6Ca9vWGVmBMzeq892g7pU&callback=initialize"
    async defer></script>
  </body>
</html>