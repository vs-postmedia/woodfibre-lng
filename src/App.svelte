<script>
    // CSS
    import normalize from './css/normalize.css';
    import postmedia from './css/postmedia.css';
    import colours from './css/colors.css';
    import fonts from './css/fonts.css';
    import css from './css/main.css';

    // IMAGES
    import gfx from '/images/map.jpg';

    // SET CHART HEIGH & URL HERE...
    const chartId01 = '28786191';
    const chartHeight = '500px';
    const fullWidthId = '28724001'
    const fullWidthHeight = '400px';
</script>

<!-- MARKUP -->
<header>
    <h1>Woodfibre LNG violating waste permit</h1>
    <p class="subhead">For more than a year, a water treatment plant at the WoodFibre LNG facility near Squamish has been discharging effluent with higher than allowed levels of copper and aluminum into a creek that feeds into Átl’ka7tsem/Howe Sound, a UNESCO biosphere.</p>
</header>

<!-- SIDE-BY-SIDE -->
<div class="graphic-container full-width">
    <iframe src='https://flo.uri.sh/visualisation/{chartId01}/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:{chartHeight};' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe>
</div>

<!-- FULL WIDTH -->
<div class="graphic-container full-width">
    <iframe src='https://flo.uri.sh/visualisation/{fullWidthId}/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:{fullWidthHeight};' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe>
</div>


<footer>
    <p class="source">Source:
        <a href="https://talkingenergy.ca/water-quality-testing-results" target="_blank">Fortis B.C.</a>
    </p>
    <!-- flourish logo -->
    <div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/3706064/?utm_source=embed&utm_campaign=visualisation/3706064' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>
</footer>

<!-- CSS -->
<style>
    
</style>