# simple-web
simple website

link to site: https://katiepelch.github.io/simple-web/

here is where you enter text

function initializeViz() {

  var placeholderDiv = document.getElementById("tableauViz");
  
  var url = "https://public.tableau.com/views/KP_20_08_09/HomePage?:language=en&:display_count=y&publish=yes&:origin=viz_share_link";
  // An object that contains options specifying how to embed the viz
  var options = {
    width: '600px',
    height: '600px',
    hideTabs: true,
    hideToolbar: true,
  };
  viz = new tableau.Viz(placeholderDiv, url, options);
}



