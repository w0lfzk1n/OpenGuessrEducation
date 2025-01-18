<script>
    import ArticleEmbedPanorama from "$lib/components/ArticleEmbedPanorama.svelte";
    import ArticleTip from "$lib/components/ArticleTip.svelte";
</script>

<!-- Menu -->
<div class="flex justify-center">
    <div class="menu bg-base-200 rounded-box w-56">
        <h2 class="text-xl font-bold mb-4">Navigation</h2>
        <ul class="menu p-0">
            <li><a href="#common-locations">Common Locations</a></li>
            <li><a href="#strategies">Strategies and Images</a></li>
            <li><a href="#features">Features</a></li>
            <li><a href="#language">Language</a></li>
            <li><a href="#license-plates">License Plates</a></li>
            <li><a href="#region-guessing">Region Guessing</a></li>
            <li><a href="#highways">Highways and Roads</a></li>
        </ul>
    </div>
</div>
<br>
<h2 id="common-locations" class="text-2xl font-bold mb-2">Common locations</h2>
<ul class="mb-2 list-disc list-inside">
    <li><b>Tirana:</b> Colorful facades and <b>Communist-era buildings</b>.</li>
    <li>
        <b>Berat:</b> Known for <b>Ottoman architecture</b> and
        <b>thousand windows</b>.
    </li>
    <li>
        <b>Butrint:</b> Ancient ruins from the <b>Greeks</b> and <b>Romans</b>.
    </li>
    <li>
        <b>Shkodra:</b> Features <b>Rozafa Castle</b> and <b>Lake Shkodra</b>.
    </li>
    <li>
        <b>Lezhe:</b> Recognized by a <b>castle on top of a hill</b>, located <b>northwest</b>.
    </li>
    <li>
        <b>Gjirokaster:</b> On a <b>west hillside</b> of a wide valley, located in bottom south.
    </li>
</ul>

<ArticleEmbedPanorama src="https://www.google.com/maps/embed?pb=!4v1730050531195!6m8!1m7!1sCoiClDnLS-FzE6IQfQ1PcA!2m2!1d41.31649709254255!2d19.83984365534879!3f231.53028426853183!4f0.9043993737237344!5f0.7820865974627469"/><br>
<p class="text-center mt-2">A drop in Tirana.</p>

<h2 id="Strategies" class="text-2xl font-bold mt-8 mb-2">Strategies</h2>
<ul class="mb-2 list-disc list-inside">
    <li>Water heaters on <b>roofs</b>, very common and almost on every single house.</li>
    <li>Two-storey houses, often <b>unfinished</b> or <b>run-down</b>.</li>
    <li>Bollards with a <b>black top</b> and <b>red and grey reflectors</b>, white bottom; <i>less common than in Italy</i>.</li>
    <li><b>Rifts at the top cameraview</b> due to bad image cropping, similar to <b>Montenegro</b> and rarely other countries.</li>
    <li><b>Stop signs</b> with uniquely <b>short ends of the 'S'</b>.</li>
    <li><b>Guard rails</b> with <b>flat and wide endings</b> <i>(also found in Italy)</i>.</li>
    <li><b>Road signs</b> often include <b>'rruga'</b> which means <i>'road'</i>.</li>
    <li><b>Chevrons</b> are <b>white arrows</b> on <b>black background</b> <i>(also used by other countries)</i>.</li>
    <li>More <b>mountains to the east</b> and <b>flat plains</b> with Mediterranean climate <b>to west</b>.</li>
    <li>A lot of <b>exposed red soil</b> <i>(can also be found in Greece at Albanian border)</i>.</li>
</ul>

<ArticleEmbedPanorama src="https://www.google.com/maps/embed?pb=!4v1730051802424!6m8!1m7!1sVS3kXPSfmU8uR4VtfmZgZA!2m2!1d41.11137968057349!2d20.0819716044217!3f195.42901557805902!4f7.429448022263529!5f2.868877958143495"/><br>
<p class="text-center mt-2">Water heaters in Elbasan.<br></p>
<br>
<hr class="my-4 border-t-2 border-gray-300">
<div class="flex justify-center w-full gap-4">
    <div class="flex flex-col items-center w-1/2">
        <img alt="albania camera rift" src="/assets/articles/albania/albania_camerarift.jpg" class="rounded-xl w-full"/>
        <p class="text-center mt-2">Rift at the top of camera view.</p>
    </div>
    <div class="flex flex-col items-center w-1/4">
        <img alt="albania riftmap" src="/assets/articles/albania/albania_riftmap.jpg" class="rounded-xl w-full"/>
        <p class="text-center"><a href="https://en.wikipedia.org/wiki/Highways_in_Albania#/media/File:Transport_in_Albania.png" target="_blank" class="text-blue-500 underline">Original Image [Wikipedia]</a></p>
        <p class="text-center mt-2"><b>Blue:</b> Rifts and long antenna.<br><b>Red:</b> No rifts and short antenna.</p>
    </div>
</div>
<br>
<div class="flex justify-center w-full gap-4">
    <div class="flex flex-col items-center w-1/2">
        <img alt="albania guardrail" src="/assets/articles/albania/albania_guardrail.jpg" class="rounded-xl w-full"/>
        <p class="text-center mt-2">Albanian <b>flat and wide</b> guardrail ending.</p>
    </div>
    <div class="flex flex-col items-center w-1/2">
        <img alt="albania chevron" src="/assets/articles/albania/albania_chevron.jpg" class="rounded-xl w-full"/>
        <p class="text-center mt-2">Albanian chevron <i>also used by Italy, Greece, and Spain</i>.</p>
    </div>
</div>
<br>
<div class="flex justify-center w-full gap-4">
    <div class="flex flex-col items-center w-1/2">
        <img alt="albania bollard" src="/assets/articles/albania/albania_bollard.jpg" class="rounded-xl w-full"/>
        <p class="text-center mt-2">Albanian bollard have a <b>black top</b> with a <b>grey and red reflector</b></p>
    </div>
    <div class="flex flex-col items-center w-1/2">
        <img alt="albania chevron" src="/assets/articles/albania/albania_backsign.jpg" class="rounded-xl w-full"/>
        <p class="text-center mt-2">Backside of signs are often painted black.</p>
    </div>
</div>
<br>
<div class="flex justify-center w-full gap-4">
    <img alt="albania utilitypole" src="/assets/articles/albania/albania_utilitypole1.jpg" class="rounded-xl w-1/4"/>
    <img alt="albania utilitypole" src="/assets/articles/albania/albania_utilitypole2.jpg" class="rounded-xl w-1/4"/>
    <img alt="albania utilitypole" src="/assets/articles/albania/albania_utilitypole3.jpg" class="rounded-xl w-1/4"/>
</div>
<p class="text-center mt-2">Albanian utilitypoles with <b>upside down triangles</b> or <b>horizontal bars</b>.</p>
<br>
<div class="flex justify-center w-full">
    <div class="flex flex-col items-center w-1/4">
        <img alt="albania stopsign" src="/assets/articles/albania/albania_stopsign.jpg" class="rounded-xl w-full"/>
        <p class="text-center mt-2">Albanian stopsign with <b>short endings on S</b>.</p>
    </div>
</div>
<hr class="my-4 border-t-2 border-gray-300">

<h2 id="features" class="text-2xl font-bold mt-8 mb-2">Features</h2>
<ul class="mb-2 list-disc list-inside">
    <li>Street signs in <b>Albanian language</b>.</li>
    <li>Public transportation vehicles with <b>Albanian symbols</b>.</li>
    <li>Environmental markers like <b>olive trees</b> and <b>rugged terrain</b>.</li>
    <li><b>Driving</b> on the <b>right side</b> of the road.</li>
    <li><b>Mercedes</b> is the most popular car brand. <i>Often a Sedan.</i></li>
    <li><b>Gen 3 coverage only</b>, limited to <b>main cities and roads</b>.</li>
</ul>
<br>

<div class="flex justify-center w-full gap-4">
    <div class="flex flex-col items-center w-1/2">
        <img alt="albania coverage" src="/assets/articles/albania/albania_coverage.jpg" class="rounded-xl w-full"/>
        <p class="text-center mt-2">Albanian streetview coverage</p>
    </div>
    <div class="flex flex-col items-center w-1/2">
        <img alt="albania terrain" src="/assets/articles/albania/albania_terrain.jpg" class="rounded-xl w-full"/>
        <p class="text-center mt-2">Albanian terrain overview</p>
    </div>
</div>
<hr class="my-4 border-t-2 border-gray-300">

<h2 id="language" class="text-2xl font-bold mt-8 mb-2">Language</h2>
<ul class="mb-2 list-disc list-inside">
    <li>Uses <b>Latin alphabet</b> with <b>some unique letters</b>: "ë" <i>(very common)</i> and "ç" <i>(less common)</i>.</li>
    <li>Words may sound like gibberish or a fake language.</li>
</ul>
<div class="flex justify-center w-full">
    <img alt="albania letters" src="/assets/articles/albania/albania_letters.jpg" class="rounded-xl w-1/2"/>
</div>
<p class="text-center mt-2">Albanian letters</p>
<hr class="my-4 border-t-2 border-gray-300">

<h2 id="license-plates" class="text-2xl font-bold mt-8 mb-2">License Plates</h2>
<ul class="mb-2 list-disc list-inside">
    <li><b>Current</b> <i>(since 2011)</i>: <b>Two blue stripes</b> on either side with <b>white center</b>.</li>
    <li><b>Old</b> <i>(pre-2011)</i>: <b>Red stripe on the left</b> with <b>white to the right</b> <i>(unique in Europe)</i>.</li>
</ul>
<div class="flex justify-center w-full">
    <img alt="albania new license plate" src="/assets/articles/albania/albania_license_current.jpg" class="w-1/2"/>
</div>
<p class="text-center mt-2">Albanian current license plate</p>
<div class="flex justify-center w-full">
    <img alt="albania old license plate" src="/assets/articles/albania/albania_license_old.jpg" class="w-1/2"/>
</div>
<p class="text-center mt-2">Albanian license plate before 2011</p>
<hr class="my-4 border-t-2 border-gray-300">

<h2 id="region-guessing" class="text-2xl font-bold mt-8 mb-2">Region Guessing</h2>
<ul class="mb-2 list-disc list-inside">
    <li><b><i>Southwest</i></b>: Sometimes <b>double white outer roadlines</b> on streets.</li>
    <li><b><i>Extreme southeast on E86</i></b>: Bollards similar to Turkey's <i>(fully white with vertical red stripe at the top)</i>.</li>
    <li><b><i>Mideast border, far south, and upper west border</i></b>: Road lines with <b>one yellow dash along center</b>.</li>
    <li><b><i>Bay of Vlore</i></b>: Commonly seen on <b>SH4</b> with <b>Karabarun peninsula visible</b> on the other side.</li>
    <li><b><i>North</i></b>: Jagged mountains, especially <b>near Theth National Park</b> and <b>along Montenegro border</b>.</li>
    <li><b><i>Northwest of Vlore</i></b>: <b>Aleppo pine forest</b> with coastal looks.</li>
    <li><b><i>Center</i></b>: <b>Wide dried river</b> valley <b>moving southeast</b> along <b>SH71</b>.</li>
</ul>
<hr class="my-4 border-t-2 border-gray-300">

<h2 id="highways" class="text-2xl font-bold mt-8 mb-2">Highways</h2>

<h3 class="text-2xl font-bold mt-8 mb-2">Divided Highways</h3>

<div class="overflow-x-auto">
    <table class="table">
        <thead>
            <tr>
                <th>Name</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>A1</td><td><b>Three guardrails</b>, located at the <b>upper west border</b>.</td>
            </tr>
        </tbody>
    </table>
</div>

<ul class="mb-2 list-disc list-inside">
    <li><b><i>SH2 and SH4</i></b> (some sections): Simple <b>concrete block barriers</b>, located <b>near midwest border</b>.</li>
    <li><b>A3 and SH3</b> south of Tirana: <b>Concrete blocks holding scenery</b> <i>(plants/grass)</i>.</li>
    <li><b>SH4</b>: <b>Basic double guardrails</b>, doesn't go through mountains, located <b>midwest border</b>.</li>
    <li><b>E851</b>: <b>Basic double guardrails</b>, goes through mountains, <b>unique landscape and barriers</b>, located in <b>northeast</b>.</li>
    <li><b>A2 north of Valore</b>: <b>Flat landscape</b> with <b>double guardrail</b> and <b>extra high fence</b> dividing the highway.</li>
</ul>

<h3 class="text-2xl font-bold mt-8 mb-2">Road Classification</h3>
<ul class="mb-2 list-disc list-inside">
    <li><b>Motorway</b> <i>(Rrugë Autostradale)</i>: <b>AX</b> <i>(A1, A2,...)</i>, has green background.</li>
    <li><b>State Road</b> <i>(Rrugë Shtetërore)</i>: <b>SHX</b> <i>(SH2, SH3,...)</i>, has blue background.</li>
</ul>

<div class="flex flex-col items-center w-1/2">
    <img alt="albania highways" src="/assets/articles/albania/albania_highways.jpg" class="rounded-xl w-full"/>
    <p class="text-center mt-2"><b>Green:</b> Motorways. <b>Blue:</b> State Roads </p>
</div>

<h3 class="text-2xl font-bold mt-8 mb-2">Motorways</h3>
<ul class="mb-2 list-disc list-inside">
    <li><b>A1</b>: Dürres/Tirana to Kosovo <i>(114km long)</i>, is part of E851 and E752.</li>
    <li><b>A2</b>: Fier - Vlöre <i>(46km long, 23.5km covered)</i>.</li>
    <li><b>A3</b>: Tirana to Elbasan <i>(31km long)</i>, is part of E852.</li>
</ul>

<h3 class="text-2xl font-bold mt-8 mb-2">State Roads</h3>
<div class="overflow-x-auto">
  <table class="table">
    <thead>
      <tr>
        <th>Name</th>
        <th>Length</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>SH1</b></td>
        <td>125km</td>
        <td><b>2 lanes</b>. Tirana to the Montenegro-Albania border north of Shkodër. Goes near the part where <i>E762 merges with A1</i>.</td>
      </tr>
      <tr>
        <td><b>SH2</b></td>
        <td>33km</td>
        <td><b>4 lanes</b>. Tirana to Durrës.</td>
      </tr>
      <tr>
        <td><b>SH3</b></td>
        <td>151km</td>
        <td><b>Mainly 2 lanes</b> <i>(no coverage where 4 lanes are completed; under construction)</i>. Tirana to the northernmost border with Greece. <b>Part of E852</b> from Elbasan to Lin (next to Macedonia) and <b>Part of E86</b> from Lin to the border.</td>
      </tr>
      <tr>
        <td><b>SH4</b></td>
        <td>212km</td>
        <td><b>4 lanes</b> from Durrës to Fier, <b>2 lanes</b> for the rest. Durrës to Greece. <b>Part of E853</b> from Fier to the border.</td>
      </tr>
      <tr>
        <td><b>SH5</b></td>
        <td>168km</td>
        <td><b>2 lanes</b>. Shkodër to Kosovo (near Prizren). <b>Mountainous road</b> with many turns.</td>
      </tr>
      <tr>
        <td><b>SH6</b></td>
        <td>116km</td>
        <td><b>2 lanes</b>. A1 near Laç to Peshkopi near Macedonia. <b>Mountainous road</b> with many turns.</td>
      </tr>
      <tr>
        <td><b>SH7</b></td>
        <td>77km</td>
        <td>Rrogozhinë to Elbasan. Covered <b>only from Rrogozhinë to Papër</b>, south of Elbasan.</td>
      </tr>
      <tr>
        <td><b>SH8</b></td>
        <td>148km</td>
        <td>Fier to Sarandë near Greece. Goes <b>near the Adriatic Sea</b>.</td>
      </tr>
      <tr>
        <td><b>SH9</b></td>
        <td>3km</td>
        <td>SH3 near Lin to Montenegro. Is <b>part of E852</b>.</td>
      </tr>
      <tr>
        <td><b>SH10</b></td>
        <td>-</td>
        <td>Currently <b>the A1</b>.</td>
      </tr>
    </tbody>
  </table>
</div>

<p class="italic mt-4">Enhanced by w0lfzk1nd and Nåchø17 from Discord</p>