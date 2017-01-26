/**************************************************************/
/*  Change the weburl after thankyou page. Widget spanish only*/
/*  works if and iframe is inside a website                   */ 
/**************************************************************/

<script type="text/javascript">


if (typeof String.prototype.startsWith != 'function') {
  String.prototype.startsWith = function (str){
    return this.indexOf(str) == 0;
  };
}     

var pathname = window.location.pathname;
var url = window.location.href;
     
     console.log(pathname);
     console.log(window.location);
    
      if(url.startsWith("https://module.lafourchette.com/es_ES/") && pathname.search( 'thank-you' )!=-1){
          window.top.location.href= "  URL  "; //url to open
          
      }
</script>
