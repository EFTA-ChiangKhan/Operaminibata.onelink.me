# Operaminibata.onelink.me
https://maps.app.goo.gl/88wrSwoWLDBeJUcF7?g_st=ac
# Dealing with special characters in branch and tag names
is:open status:in-progress status:queued status:idle status:needs-attention status:failed status:completed status:cancelled status:timed_out author:@me type:cloud type:cli type:vscode agent:copilot-cli agent:copilot-in-vs-code agent:copilot-in-jetbrains

<img width="1280" height="1233" alt="9712" src="https://github.com/user-attachments/assets/8fc8248b-c28c-4557-ac61-0c0873565585" />

Opera Mini is a mobile web browser made by Opera. It was primarily designed for the Java ME platform, as a low-end sibling for Opera Mobile, but as of February 2026 only the Android port is still under active development. A 2021 build of Opera Mini 4.4 for the MAUI Runtime Environment is included with current feature phones manufactured by HMD Global. It had previously been developed for iOS, Windows 10 Mobile, Windows Phone 8.1, BlackBerry, Symbian, and Bada.

Opera Mini requests web pages through Opera Software's compression proxy server. The compression server processes and compresses the requested web pages before sending them to the mobile phone. The compression ratio is 90%, and the transfer speed is increased by two to three times as a result. The pre-processing increases compatibility with web pages not designed for mobile phones. However, interactive sites which depend on the device's processing JavaScript do not work properly.

In July 2012, Opera Software reported that Opera Mini had 168.8 million users as of March 2012.[10][11] In February 2013, Opera reported 300 million unique Opera Mini active users and 150 billion page views served during that month. This represented an increase of 25 million users from September 2012.[12]

History
Origin
Opera Mini was derived from the Opera web browser for personal computers, which has been publicly available since 1996.[13] Opera Mini was originally intended for use on mobile phones not capable of running a conventional Web browser.[14] It was introduced on 10 August 2005, as a pilot project in cooperation with the Norwegian television station TV 2,[15] and only available to TV 2 customers. The beta version was made available in Sweden, Denmark, Norway, and Finland on 20 October 2005.[16] After the final version was launched in Germany on 10 November 2005,[17] and quietly released to all countries through the Opera Mini website in December, the browser was officially launched worldwide on 24 January 2006.[18] On 3 May 2006, Opera Mini 2.0 was released. It included new features such as the ability to download files, new custom skins, more search engine options on the built-in search bar, a speed dial option, new search engines, and improved navigation.[19] On 1 November 2006, Opera Mini 3 beta introduced secure browsing, RSS feeds, photo uploading and content folding.[20] Content folding works by folding long lists such as navigation bars into a single line that can be expanded as needed. A second beta was released on 22 November,[21] and on 28 November, the final version of Opera Mini 3 was released.[22]

Opera Mini 4
On 7 November 2007, Opera Mini 4 was released. According to Johan Schön, technical lead of Opera Mini development, the entire code had been rewritten.[23] Opera Mini 4 includes the ability to view web pages similarly to a desktop-based browser by introducing Overview and Zoom functions, and a landscape view setting. In Overview mode, the user can scroll a zoomed-out version of certain web pages.[24] Using a built-in pointer, the user can zoom into a portion of the page to provide a clearer view; this is similar to the functionality of Opera's Nintendo-based web browsers. This version also includes the ability to synchronise with Opera on a personal computer.[25][26] Prior to Opera Mini 4, the browser was offered in two editions: Opera Mini Advanced for high-memory MIDP 2 phones, and Opera Mini Basic for low-memory MIDP 1 phones.[27] Opera Mini 4 replaced Opera Mini Advanced.[28] Originally, Google was the default search engine on Opera Mini.[29] On 8 January 2007, Opera Software and Yahoo! announced a partnership to make Yahoo! search the default instead.[30] On 27 February 2008, Opera Software announced that Google would henceforth be the default search engine for Opera Mini and Opera Mobile. A version for the Android operating system was announced on 10 April 2008. Rather than port the code to Android, a wrapper was created to translate Java ME API calls to Android API calls.[31]

Later versions
On 16 August 2009, Opera Software released Opera Mini 5.0 beta, which included tabbed browsing, a password manager, improved touch screen support, and a new interface, with a visual Speed Dial similar to the one introduced by Opera Software in their desktop browser.[32] The browser's use of compression and encrypted proxy-based technology to reduce traffic and speed page display has the side effect of allowing it to circumvent several approaches to Internet censorship. Since 20 November 2009, there have been reports from Chinese users that when they use Opera Mini, they are redirected to an error page, leading them to download the Opera Mini China version. This is almost certainly due to the Chinese government being concerned that users are using Opera Mini to bypass the Great Firewall of China. Opera agreed to route all of their traffic through government servers.[33][34] In 2009–10: A press release announcing that Indonesia's Smart Telecom had chosen Opera Mini for their devices said that Opera Mini was the world's most popular mobile browser, and that Russia and Indonesia were the largest users.[35] An iPhone version was approved for distribution by the Apple App Store on 13 April 2010.[36][37]

On 3 September 2014, Opera started taking registrations for the beta version of Opera Mini for Windows Phone.[38] The browser was released for Windows Phone on 9 September 2014, as a public beta,[39] the first Opera version for Microsoft's mobile platform since the discontinuation of Windows Mobile.
Git is very permissive about what characters are allowed in branch and tag names. When using Git from a command-line shell, you may need to escape or quote special characters.
Functionality
Opera Mini uses a server to translate HTML, CSS and JavaScript into a more compact format. It can also shrink any images to fit as the handset screen. This step makes Opera Mini fast.

Most Opera Mini versions use only the server-based compression method, with maximal compression but some issues with interactive web apps. Opera Mini can operate in three compression modes: "mini" (or "extreme" on Android versions), "turbo" (or "high" on Android versions) and uncompressed.[4][40] The turbo and mini modes reduce the amount of data transferred, thereby also increasing speed on slower connections.[4]

The functionality of the Mini mode is somewhat different from a conventional Web browser, with the amount of data which has to be transferred much reduced, but with some loss to functionality. Unlike straightforward web browsers, Opera Mini fetches all content through a proxy server, renders it using the Presto layout engine,[4] and reformats web pages into a format more suitable for small screens.[41] A page is compressed, then delivered to the phone in an interpreted markup language called Opera Binary Markup Language (OBML) supported by Opera Mini.[42] According to Opera Software, the data compression makes transfers about two to three times faster[24] and uses less data, and the pre-processing improves the display of web pages not designed for small screens.[43] The turbo mode was added later, and is similar to Mini mode but bypasses compression for interactive functionality, at the expense of less extreme data compression. The turbo and uncompressed modes use the "WebView" on Android and the WebKit layout engine on iOS.[4]

The Java ME and Windows Phone versions only have access to the mini compression mode.[4] Other versions can switch between various modes, gaining functionality at the cost of lower or no compression.[44] Opera Software claims that Opera Mini reduced the amount of data transmitted up to 90% in the mini (extreme) mode; in turbo (high) mode, it reduced amount up to 60%, similar to Google Chrome's Reduced Data mode.[40][45][46]
When a user requests a Web page using Opera Mini, the request is sent, via the connectivity used by the device to access the Internet (typically mobile broadband or Wi-Fi), to a proxy server run by the Opera Software company, which retrieves, processes and compresses the full page, and sends the smaller processed page back to the client's device.

By default, Opera Mini opens one connection to the proxy servers, which it keeps open and re-uses as required. This improves transfer speed and enables the servers to quickly synchronize changes to bookmarks stored in Opera Mini server.[47]

When the Opera Software company launched Opera Mini in 2006, they had over 100 Linux-based proxy servers to handle Opera Mini traffic.[18]

Standard support
From 16 March 2015, Opera Mini's extreme compression mode uses an upgraded version of the Presto layout engine that is included in Opera 12.[48] Consequently, Opera Mini supports most of the web standards supported in Opera 12. Presto's development has continued for Opera Mini and further support was added for HTML5 input types, CSS Flexbox model, CSS rem units and ECMAScript 5.[48] However, unlike the desktop edition of Opera, frames are flattened because of client limitations, and dotted or dashed borders are displayed as solid borders due to bandwidth and memory issues.[49] As Opera Mini reformats web pages, it does not pass the Acid2 standards compliance test.[50][51] Opera Mini supports bi-directional text and can correctly display right-to-left scripts such as Arabic and Hebrew in addition to languages written left-to-right. However, it will not display right-to-left text if the font size is set to small or very small.[23] Indic and Chinese scripts are supported only if an appropriate font is installed on the device as the default system font.

Small-Screen Rendering
For devices with screens 128 pixels wide or smaller, the default rendering mode is Small-Screen Rendering (SSR). In this mode, the page is reformatted into a single vertical column so that it only needs to be scrolled vertically.[24] Long lists and navigation bars are automatically collapsed (hiding most of the list or bar) by a feature known as "content folding". A plus (+) sign is displayed next to the collapsed content; when clicked, it toggles content folding.[52] Web developers can turn on SSR on the desktop edition of Opera to see how their websites will be displayed on mobile editions of Opera.[53] In SSR mode images are scaled down to no more than 70% of the screen size in either direction.[49]

Complex script rendering
Opera Mini can send content in bitmap image form if a font required is not available on the device, which is useful for indic scripts. Hindi, Bengali and a few other non-Latin character sets are supported.

JavaScript support
When browsing the Web in Opera Mini mode, JavaScript is processed by the proxy server, and is merely rendered on the device. This limits interactivity. Scripts cannot be run in the background on the device. If a script is paused (on the server), the browser must communicate with the server to unpause it. JavaScript will only run for a couple of seconds on the Mini server before pausing, due to resource constraints.[54] On Opera Mini, before the page is sent to the mobile device, its onLoad events are fired and all scripts are allowed a maximum of two seconds to execute. The setInterval and setTimeout functions are disabled, so scripts designed to wait a certain amount of time before executing will not execute.[55] After the scripts have finished or the timeout is reached, all scripts are stopped and the page is compressed and sent to the mobile device. Once on the device, only a handful of events are allowed to trigger scripts:[55]

onUnload: Fires when the user navigates away from a page[56]
onSubmit: Fires when a form is submitted[56]
onChange: Fires when the value of an input control is changed[56]
onClick: Fires when an element is clicked[56]
When one of these events is triggered, it sends a request to the proxy server to process the event. The proxy server then executes the JavaScript and returns the revised page to the mobile device.[55] Pop-ups, if not blocked by the JavaScript restrictions, replace the web page being viewed.[57] Opera has published Web content authoring guidelines to assist authors.[54]

Opera Mini can run in Turbo and Uncompressed modes, in addition to Mini mode. In Turbo mode, the amount of data transferred is still much reduced by compression, but, unlike Mini mode, JavaScript is not intercepted by the server and works properly. Opera Mini can be configured to choose compression mode automatically.

Privacy and security
Opera Mini encrypts the connection between the mobile device and the Opera proxy server for security. The encryption key is obtained on the first start by requesting random keys a certain number of times.[58] Opera Mini supports most advanced version of Transport Layer Security (TLS) protocol[59] it also supports modern secure ciphers such as AES-GCM and ECC. However, Opera Mini's Extreme mode does not offer true end-to-end security when visiting HTTPS encrypted websites only for data saving purpose.[60] With "Extreme/Mini mode" when visiting an encrypted web page, first the Opera Mini's servers decrypt the page, compress it for data saving then re-encrypt it themselves and finally forward it to the destination phone.[61] While browsing a secured site with "High/Turbo mode" or "Uncompressed mode" the connection is not intercepted by the Opera Mini server so that High and Uncompressed modes do not break end-to-end integrity.[62]

Features
Opera Mini uses cloud acceleration and data compression technology. Opera Mini servers act as a proxy which compresses and renders the data of web pages before sending it to users. This process helps to load web content faster.

The display may be toggled between portrait and landscape mode by keystrokes, or will switch automatically on phones with orientation sensors. The default orientation can be changed.[24] The image quality may be set to "Low", "Medium", or "High".[63] Load times of pages with images are affected by the chosen image quality setting.[64] Opera Mini supports only one font,[49] which can be set to "Small", "Medium", or "Large" size.[63] If a web page uses Courier or a generic monospaced font, the one font is still used, but the characters are spaced out so that each character takes up the same amount of space.[49]

Browsing tools
Opera Mini's address bar is capable of using several pre-configured search engines. The user can add more search engines.[63] The default search engines are Google and Wikipedia.

Opera Mini supports an ad blocker. When activated, Opera Mini servers try to filter out advertisements before rendering the page and sending it to the client phone.[65]

Opera Mini has an AI-powered news aggregator, serving personalised news,[66] night mode and private browsing. It can save bookmarks, download files, and web pages for offline reading. It supports streaming and remembers the user's browsing history.

Opera synchronization
If signed into an Opera Account, Saved Bookmarks, Speed Dials, and Opened Tabs can be backed up and synchronized between different phones or with the Opera browser on computers, using the "Opera Sync" service, and can be accessed through the web interface at Opera synchronization.

Market adoption
The overall share of the Opera family in the mobile Web browser market was about 5.01% in June 2018.[67]

<!-- wp:paragraph -->
<p id="mwKw"></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p id="mwPA"></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p id="mwQQ"></p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2 class="wp-block-heading" id="History">History</h2>
<!-- /wp:heading -->

<!-- wp:heading {"level":3} -->
<h3 class="wp-block-heading" id="Origin">Origin</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p id="mwUg"></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p id="mwgw"></p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3 class="wp-block-heading" id="Later_versions"></h3>
<!-- /wp:heading -->

<!-- wp:heading {"level":3} -->
<h3 class="wp-block-heading" id="Data_centers">Data centers</h3>
<!-- /wp:heading -->

<!-- wp:image {"linkDestination":"custom"} -->
<figure class="wp-block-image" id="mwAhw"><a class="mw-file-description" href="https://en.wikipedia.org/wiki/File:Total_data_consumed_by_Opera_Mini_users_worldwide_(TB).png"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d4/Total_data_consumed_by_Opera_Mini_users_worldwide_%28TB%29.png/330px-Total_data_consumed_by_Opera_Mini_users_worldwide_%28TB%29.png?utm_source=en.wikipedia.org&amp;utm_campaign=parser&amp;utm_content=thumbnail" alt=""/></a><figcaption class="wp-element-caption">Total data consumed by Opera Mini users worldwide from 2006 to mid-2008 in TB</figcaption></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p id="mwAiA">Opera Mini relies on data centers processing the Web page before sending it back to the phone in a compressed binary form. Opera Software operates data centers in the United States, Norway, China, Korea, Poland and Iceland.<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-68">[68]</a></sup><sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-69">[69]</a></sup></p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3 class="wp-block-heading" id="Network_operators">Network operators</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p id="mwAio">Several mobile network companies pre-install Opera Mini on their mobile phones, including&nbsp;<a href="https://en.wikipedia.org/wiki/Telenor">Telenor</a>,&nbsp;<a href="https://en.wikipedia.org/wiki/AT&amp;T">AT&amp;T</a>,&nbsp;<a href="https://en.wikipedia.org/wiki/Vodafone">Vodafone</a>,&nbsp;<a href="https://en.wikipedia.org/wiki/T-Mobile_International_AG" class="mw-redirect">T-Mobile</a>,&nbsp;<a href="https://en.wikipedia.org/wiki/KDDI">KDDI</a>,&nbsp;<a href="https://en.wikipedia.org/wiki/Omnitel_Lietuva" class="mw-redirect">Omnitel</a>,&nbsp;<a href="https://en.wikipedia.org/wiki/Pannon_GSM" class="mw-redirect">Pannon GSM</a>,&nbsp;<a href="https://en.wikipedia.org/wiki/Telef%C3%B3nica">Telefónica Móviles de España</a>&nbsp;and&nbsp;<a href="https://en.wikipedia.org/wiki/Telecomunica%C3%A7%C3%B5es_M%C3%B3veis_Nacionais" class="mw-redirect">TMN</a>.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3 class="wp-block-heading" id="Devices">Devices</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p id="mw1Q"></p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/Ambox_current_red_Asia_Australia.svg/60px-Ambox_current_red_Asia_Australia.svg.png?utm_source=en.wikipedia.org&amp;utm_campaign=parser&amp;utm_content=thumbnail" alt=""/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>This section needs to be&nbsp;<strong>updated</strong>.&nbsp;Please help update this article to reflect recent events or newly available information.&nbsp;<em>(June 2023)</em></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p id="mwAjY">The following devices were supplied pre-installed with Opera Mini&nbsp;as of August&nbsp;2007. Some listed devices only included Opera Mini when bought from certain network operators.<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-Goldman-70">[70]</a></sup></p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul id="mwAj0" class="wp-block-list"><!-- wp:list-item -->
<li><a href="https://en.wikipedia.org/wiki/Motorola">Motorola</a> V980, E2, L7, <a href="https://en.wikipedia.org/wiki/Motorola_i1">i1</a><sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-71">[71]</a></sup></li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li><a href="https://en.wikipedia.org/wiki/Nokia">Nokia</a> <a href="https://en.wikipedia.org/wiki/Nokia_Asha_series">Nokia Asha series</a>, <a href="https://en.wikipedia.org/wiki/Nokia_2610">2610</a>, <a href="https://en.wikipedia.org/wiki/Nokia_2700_classic">2700 classic</a>, <a href="https://en.wikipedia.org/wiki/Nokia_2730_classic">2730 classic</a>, <a href="https://en.wikipedia.org/wiki/Nokia_3110_classic">3110 classic</a>, <a class="mw-redirect" href="https://en.wikipedia.org/wiki/Nokia_3120_classic">3120 classic</a>, <a href="https://en.wikipedia.org/wiki/Nokia_3500_classic">3500 classic</a>, <a class="mw-redirect" href="https://en.wikipedia.org/wiki/Nokia_3600/3650">3600</a>, <a href="https://en.wikipedia.org/wiki/Nokia_3600_slide">3600 slide</a>, 3710 fold, <a href="https://en.wikipedia.org/wiki/Nokia_3720_classic">3720 classic</a>, 5000, <a href="https://en.wikipedia.org/wiki/Nokia_5070">5070</a>, <a href="https://en.wikipedia.org/wiki/Nokia_5130">5130</a>, <a href="https://en.wikipedia.org/wiki/Nokia_5230">5230</a>, <a href="https://en.wikipedia.org/wiki/Nokia_5310">5310</a>, <a href="https://en.wikipedia.org/wiki/Nokia_5500_Sport">5500 Sport</a>, <a class="mw-redirect" href="https://en.wikipedia.org/wiki/Nokia_5610">5610</a>, 6080, <a class="mw-redirect" href="https://en.wikipedia.org/wiki/Nokia_6085">6085</a>, <a href="https://en.wikipedia.org/wiki/Nokia_6103">6103</a>, <a href="https://en.wikipedia.org/wiki/Nokia_6131">6131</a>, <a href="https://en.wikipedia.org/wiki/Nokia_6233">6233</a>, <a class="mw-redirect" href="https://en.wikipedia.org/wiki/Nokia_6288">6288</a>, <a href="https://en.wikipedia.org/wiki/Nokia_6300">6300</a>,<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-72">[72]</a></sup> <a href="https://en.wikipedia.org/wiki/Nokia_6303_classic">6303 classic</a>, <a href="https://en.wikipedia.org/wiki/Nokia_6600_slide">6600 slide</a>, 7373, <a href="https://en.wikipedia.org/wiki/Nokia_8800">8800 <em>Arte</em></a>, <a href="https://en.wikipedia.org/wiki/Nokia_C2-01">Nokia C2-01</a>, <a href="https://en.wikipedia.org/wiki/Nokia_C3-00">Nokia C3</a>, <a href="https://en.wikipedia.org/wiki/Nokia_E65">E65</a>, <a href="https://en.wikipedia.org/wiki/Nokia_N71">N71</a>, <a href="https://en.wikipedia.org/wiki/Nokia_N73">N73</a>, <a href="https://en.wikipedia.org/wiki/Nokia_N95">N95</a> and other <a href="https://en.wikipedia.org/wiki/Series_40">S40</a> and <a href="https://en.wikipedia.org/wiki/S60_(software_platform)">S60</a> phones.</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li><a href="https://en.wikipedia.org/wiki/Microsoft">Microsoft</a> and <a href="https://en.wikipedia.org/wiki/HMD_Global">HMD</a> Nokia/HMD phones with a preinstalled browser and running <a href="https://en.wikipedia.org/wiki/Series_30+">s30+</a> all run on the Opera Mini Browser,<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-73">[73]</a></sup> along with <a href="https://en.wikipedia.org/wiki/Nokia_3310_(2017)">3310 (2017)</a> that run Smart Feature OS for 3G version.</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li><a class="mw-redirect" href="https://en.wikipedia.org/wiki/Sony_Ericsson">Sony Ericsson</a> K310i, K530i, <a href="https://en.wikipedia.org/wiki/Sony_Ericsson_K550">K550</a>, <a href="https://en.wikipedia.org/wiki/Sony_Ericsson_W200">W200i</a>, <a href="https://en.wikipedia.org/wiki/Sony_Ericsson_W205">W205</a>, <a href="https://en.wikipedia.org/wiki/Sony_Ericsson_W760">W760i</a>, <a href="https://en.wikipedia.org/wiki/Sony_Ericsson_W910i">W910i</a>, Z530i, Z550i, Z780i</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li><a href="https://en.wikipedia.org/wiki/Samsung">Samsung</a> X160, E570, E420, F480, X510, X650, E900, E250, U700, ZV60, D900i</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li><a href="https://en.wikipedia.org/wiki/LG">LG</a> K880, KU250, KE970, and KU311</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li><a href="https://en.wikipedia.org/wiki/SAGEM">SAGEM</a> My411x and P9521</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li><a href="https://en.wikipedia.org/wiki/BenQ-Siemens_EL71">BenQ-Siemens EL71</a> and EF81</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li><a href="https://en.wikipedia.org/wiki/BenQ">BenQ</a> E71 fight</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li><a class="mw-redirect" href="https://en.wikipedia.org/wiki/Orange_(telecommunications)">Orange</a> Rio (<a href="https://en.wikipedia.org/wiki/ZTE">ZTE</a>-G X991)</li>
<!-- /wp:list-item --></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p id="mwAoo">While not officially supported on&nbsp;<a href="https://en.wikipedia.org/wiki/ChromeOS">ChromeOS</a>, Vlad Filippov published a guide that teaches how to run Opera Mini inside the Chromium browser.<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-74">[74]</a></sup></p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2 class="wp-block-heading" id="Release_compatibility">Release compatibility</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p><a href="https://en.wikipedia.org/wiki/Operating_system">Operating system</a>Latest versionYearAndroid<br />(including<br /><a href="https://github.com/androidarmv6/android" class="external text">Android for ARMv6</a>)6.0 and later<a href="https://ftp.opera.com/ftp/pub/opera/android/mini/99.4.2254.1608/" class="external text">99.4.2254.1608&nbsp;(ARMv7)</a>20265.0–5.1<a href="https://ftp.opera.com/ftp/pub/opera/android/mini/90.1.2254.77167/" class="external text">90.1.2254.77167 (ARMv7)</a>20254.2–4.4<a href="https://ftp.opera.com/ftp/pub/opera/android/mini/60.0.2254.59405/" class="external text">60.0.2254.59405 (ARMv7)</a>2021<a href="https://ftp.opera.com/ftp/pub/opera/android/mini/53.1.2254.55490/" class="external text">53.1.2254.55490 (ARMv5, ARMv6)</a>20214.1<a href="https://ftp.opera.com/ftp/pub/opera/android/mini/46.1.2254.55193/" class="external text">46.1.2254.55193</a>20202.3–4.0<a href="https://ftp.opera.com/ftp/pub/opera/android/mini/oldsdk/20.0.2254.110284/" class="external text">20.0.2254.110284</a>20161.5–2.2<a href="https://ftp.opera.com/ftp/pub/opera/android/mini/7.6.4/" class="external text">7.6.4</a>2015iOS16.0.142018<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-75">[75]</a></sup>Windows Phone 8.1 and later9.1.0.2322016<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-76">[76]</a></sup>Java MEMIDP 2.0 and later8.0.12014<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-77">[77]</a></sup>4.52013<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-78">[78]</a></sup>MIDP 1.x3.22010SymbianS60v2 and later7.12013<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-79">[79]</a></sup>Bada6.52012<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-80">[80]</a></sup>Windows Mobile 6, 5 and 20035.12010<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-81">[81]</a></sup>MAUI Runtime Environment4.42011<sup class="mw-ref reference"><a href="https://en.wikipedia.org/wiki/Opera_Mini#cite_note-82">[82]</a></sup></p>
<!-- /wp:paragraph -->
See also
Opera (web browser)
Opera Mobile
UC Browser, a server-based compressing browsing system
Bolt (web browser), a discontinued server-based compressing browsing system
History of the web browser
List of web browsers
References
 "Opera Mini: Fast Web Browser - Apps on Google Play". Retrieved 13 July 2026.
 Lextrait, Vincent (January 2010). "The Programming Languages Beacon, v10.0". Retrieved 14 March 2010.
 "Opera Browsers, Modes & Engines". dev.opera.com. 2 June 2015. Archived from the original on 14 June 2015.
 Bovens, Andreas (2 June 2015). "Opera Browsers, Modes & Engines". Dev.Opera. Retrieved 13 August 2017.
 Solsvik, Terje (24 February 2014). "Opera browser to be pre-installed on Nokia's X phones". Reuters. Archived from the original on 13 January 2016. Retrieved 18 April 2014.
 "Samsung delivers a faster web on non-smartphones" (Press release). Oslo, Norway: Opera Software. 23 February 2012. Retrieved 18 April 2014.
 Summers, Nick (8 May 2013). "Opera Software partners with Indian mobile OEMs to get its Opera Mini browser pre-installed on Android devices". TheNextWeb. Retrieved 18 April 2014.
 Shankland, Stephen (25 August 2011). "Opera finances improve despite fierce competition". CNET. Retrieved 16 January 2012.
 "Opera Mini is going multilingual this Republic Day". 26 January 2016.
 Lardinois, Frederic (30 April 2012). "Opera Mini Now Has 169 Million Users, 56% Of Them Only Use The Mobile Web". TechCrunch. Archived from the original on 2 February 2025. Retrieved 2 February 2025.
 "State of the Mobile Web: India on top". Opera Newsroom. 31 May 2012. Archived from the original on 6 July 2022. Retrieved 2 February 2025.
 Williams, Owen (24 December 2015). "The browser with 300 million users that's breaking your site". TNW | Dd.
 "Affiliated Organization of Firefox and Mozilla" (PDF). Mozilla Japan. 2006. Retrieved 24 October 2007.
 Goldman, Daniel (3 May 2006). "Opera Mini 2.0 Released". Opera Watch. Archived from the original on 21 July 2011. Retrieved 21 December 2007.
 "Have WAP but want WEB? Introducing Opera Mini for mobile phones" (Press release). Opera Software. 10 August 2005. Archived from the original on 18 June 2006. Retrieved 5 December 2007.
 "Mobile comfort in the cold: Opera Mini beta now available free in the Nordics" (Press release). Opera Software. 10 November 2005. Archived from the original on 9 June 2008. Retrieved 2 January 2008.
 "The full Internet for all mobile phones: Opera Mini launched in India" (Press release). Opera Software. 10 November 2005. Archived from the original on 6 October 2008. Retrieved 2 January 2008.
 Gohring, Nancy (25 January 2006). "Opera to launch Mini worldwide". PC World. IDG. Archived from the original on 14 November 2022. Retrieved 14 November 2022.
 "Mini Gets Mighty: Introducing Opera Mini 2.0 for your mobile phone" (Press release). Opera Software. 3 May 2006. Archived from the original on 6 October 2008. Retrieved 21 December 2007.
 Goldman, Daniel (1 November 2006). "Limited testing of Opera Mini 3 beta". Opera Watch. Archived from the original on 21 July 2011. Retrieved 21 December 2007.
 Spilling, Marianne (22 November 2006). "Opera Mini 3.0 Beta 2". Opera Software. Retrieved 21 December 2007.
 "Opera Mini drives social networking on mobile phones" (Press release). Opera Software. 28 November 2006. Archived from the original on 13 May 2008. Retrieved 21 December 2007.
 Schön, Johan (7 November 2007). "The power of the Web with Opera Mini 4". My.Opera.com. Retrieved 24 December 2007.
 "Opera Mini Features". Opera Software. February 2009. Archived from the original on 27 February 2009. Retrieved 13 July 2014.
 Calore, Michael "Opera 4 Beta Released Archived 30 June 2007 at the Wayback Machine", Wired News, 19 June 2007
 Heater, Brian "Opera Mini 4 Goes Live Archived 28 August 2008 at the Wayback Machine", AppScout (Ziff Davis), 7 November 2007
 "Opera Mini FAQ". Opera Software. What are the differences between the "Basic (MIDP 1)" and the "Advanced (MIDP 2)" versions?. Archived from the original on 19 December 2007.
 "Generic Advanced MIDP 2". Download Opera Mini. Opera Software. Archived from the original on 11 October 2007. Retrieved 19 December 2007.
 "Opera Software chooses Google as search partner". Reuters. 28 December 2005. Archived from the original on 6 September 2007. Retrieved 11 October 2007.
 "Opera Names Yahoo! Exclusive Global Partner for Mobile Search" (Press release). Yahoo!. Archived from the original on 13 October 2007. Retrieved 11 October 2007.
 "The story behind Opera Mini on Google Android". Archived from the original on 11 April 2008. Retrieved 4 January 2009.
 "Global mobile-browser champion enters next generation". Archived from the original on 9 March 2012. Retrieved 14 November 2009.
 "Opera Mini国际版屏蔽国内用户" (in Chinese). Solidot. 21 November 2009. Retrieved 25 November 2009.
 Millward, Steven (22 November 2009). "Opera accused of censorship, betrayal by Chinese users". CNet Asia. Archived from the original on 3 November 2013.
 "Mobile Phone Reviews » indonesia". Archived from the original on 29 March 2010. Retrieved 15 November 2010.
 "Opera Mini Submitted to App Store, Complete with Passive Aggressive "Countup" Clock". Gizmodo. 23 March 2010.
 "Opera Mini Approved for App Store". Archived from the original on 15 October 2010. Retrieved 13 April 2010.
 "Opera Mini Beta Subscriptions Now Open For Windows Phone". TechTree.com.
 "Opera Mini beta for Windows Phone now available for anyone to test". blog.gsmarena.com. 9 September 2014.
 Mathews, Lee (9 September 2015). "Opera Mini now has two compression modes: high and extreme". Geek.com. Ziff Davis. Archived from the original on 13 August 2017. Retrieved 13 August 2017.
 "Developer case study: Managing Java fragmentation, Opera Software's Java ME browser client: About Opera Mini". Sony Ericsson. 23 June 2006. Archived from the original on 4 August 2011. Retrieved 19 December 2007.
 "Opera 3Q05 Results" (PDF). 21 November 2005. p. 16. Archived from the original (PDF) on 1 December 2005. Retrieved 19 December 2007.
 Duncan, Geoff (24 January 2006). "Opera Mini Officially Brings Web to Mobiles". Digital Trends News. Retrieved 18 October 2007.
 Lawson, Bruce (26 June 2014). "Opera Mini 8 for iOS released". Dev.Opera. Opera Software.
 Ghoshal, Abhimanyu (8 September 2015). "Opera Mini browser (Android) has a new data saving mode". The Next Web. Archived from the original on 13 August 2017. Retrieved 13 August 2017.
 Mihir Patkar (11 September 2015). "Is Opera Mini's Data Compression Good Enough to Switch?". Makeuseof.com. Retrieved 18 March 2017.
 FAQ, What is the difference between ‘http connection' and ‘socket connection'?.
 Lawson, Bruce (16 March 2015). "Opera Mini server upgrade". Dev.Opera. Retrieved 12 May 2017.
 Storey, David (31 August 2007). "Evolving the Internet on your phone: Designing web sites with Opera Mini 4 in mind". Opera Software. Archived from the original on 10 August 2011. Retrieved 16 January 2008.
 "Opera Mini 4 beta out". June 2007. Archived from the original on 10 October 2011. Retrieved 22 December 2007.
 "Opera Mini Simulator". Opera.com. Opera Software. Archived from the original on 9 February 2010. Retrieved 22 December 2007.
 "Content folding". Opera Mini Features. Opera Software. Retrieved 4 January 2008.
 "Opera's Small-Screen Rendering". Opera Software. Archived from the original on 4 December 2007. Retrieved 20 December 2007.
 "Dev.Opera — Opera Mini: Web Content Authoring Guidelines". dev.opera.com. 20 November 2024.
 Mills, Chris (25 October 2007). "JavaScript support in Opera Mini 4 (deprecated article)". Opera Software. Archived from the original on 29 July 2011. Retrieved 29 December 2007.
 "HTML event types". Document Object Model (DOM) Level 2 Events Specification. 13 November 2000. Retrieved 29 December 2007.
 "Designing With Opera Mini in Mind". Opera Software. 13 November 2006. Archived from the original on 4 August 2011. Retrieved 31 December 2007.
 "Opera Mini FAQ". Opera Software. What is the purpose of the screen where you need to press keys until the indicator is full?. Archived from the original on 19 December 2007.
 "Qualys SSL Labs - Projects / SSL Client Test".
 McGee, Brandon (14 October 2007). "Recommendation for Mobile Banking Vendors & An Update on Opera Browsers". Retrieved 8 August 2017.
 FAQ, How does encryption work in Opera Mini?.
 "Opera Mini for Android | Ad blocker, File sharing, Data savings | Opera".
 "Opera Mini Simulator". Opera Mini Features. Opera Software. Archived from the original on 9 February 2010. Retrieved 4 January 2008.
 Goldman, Daniel (15 August 2007). "How to get higher quality images with Opera Mini?". Opera Watch. Archived from the original on 13 January 2008. Retrieved 4 January 2008.
 "Opera Mini 16 for Android". Opera forums. 4 May 2016.
 "Revamping Opera Mini for IOS". 5 September 2017.
 "Browser Market Share Worldwide". StatCounter. July 2017. Retrieved 1 July 2017.
 "Opera slashes power usage with new server parks". Opera b2b. Oslo, Norway: Opera Software. 24 June 2010.
 "Serving up more Opera Mini in Europe: Opera opens new data center in Poland". Opera b2b. Oslo, Norway: Opera Software. 30 June 2009.
 Goldman, Daniel (27 August 2007). "Phones with Opera Mini pre-installed, distribution partners, and more". Opera Watch. Archived from the original on 17 July 2011. Retrieved 5 February 2008.
 "Motorola and Sprint Announce World's First Push-To-Talk Android-Powered Smartphone – Motorola i1" (Press release). Motorola. 22 March 2010. Retrieved 22 March 2010.
 "Opera Mini Web browser pre-installed with Nokia 6300" (Press release). Opera Software. 14 December 2006. Retrieved 1 December 2013.
 "Nokia Corporation". www.nokia.com. Retrieved 24 September 2023.
 Filippov, Vlad (14 October 2014). "Opera Mini on your Chromebook for fun and bandwidth". dev.opera.com.
 "Opera Mini web browser on the App Store on iTunes". iTunes. 16 October 2018. Archived from the original on 19 April 2011. Retrieved 16 October 2018.
 "Opera Mini - Windows Apps on Microsoft Store". Microsoft. 16 June 2016. Retrieved 5 September 2016.
 "Got Java? Opera Mini update for Java phones". 8 July 2014. Retrieved 20 May 2023.
 "Opera keeps on bringing first-class browsing to basic phones". 5 June 2013. Retrieved 21 May 2023.
 "New Opera Mini 7.1 release for Symbian/S60". 22 January 2013. Retrieved 20 May 2023.
 "Opera Mini browser lands on Bada". 4 May 2012. Retrieved 24 June 2023.[dead link]
 "Better browsing on Windows Mobile". 9 September 2010. Retrieved 21 May 2023.
 Ionut Arghire (2 December 2011). "Opera Mini Arrives on MediaTek's Runtime Environment (MRE)". Retrieved 16 June 2023.


## About branch and tag names

Most repositories use simple branch names, such as `main` or `update-icons`. Tag names also usually follow a basic format, such as a version number like `v1.2.3`. Both branch names and tag names may also use the path separator (`/`) for structure, for example `area/item` or `level-1/level-2/level-3`. Other than some exceptions &mdash; such as not starting or ending a name with a slash, or having consecutive slashes in the name &mdash; Git has very few restrictions on what characters may be used in branch and tag names. For more information, see [git-check-ref-format](https://git-scm.com/docs/git-check-ref-format) in the Git documentation.

## Why you need to escape special characters

When using a CLI, you might have situations where a branch or tag name contains special characters that have a special meaning for your shell environment. To use these characters safely in a Git command, they must be quoted or escaped, otherwise the command may have unintended effects.

For example, the `$` character is used by many shells to refer to a variable. Most shells would interpret a valid branch name like `hello-$USER` as equivalent to the word "hello", followed by a hyphen, followed by the current value of the `USER` variable, rather than the literal string `hello-$USER`. If a branch name includes the `$` character, then the shell must be stopped from expanding it as a variable reference. Similarly, if a branch name contains a semi-colon (`;`), most shells interpret it as a command separator, so it needs to be quoted or escaped.

## How to escape special characters in branch and tag names

Most branch and tag names with special characters can be handled by including the name in single quotes, for example `'hello-$USER'`.

* In the [Bash](https://www.gnu.org/software/bash/) shell, enclosing a string of characters in single quotes preserves the literal value of the characters within the single quotes.
* [Zsh](https://www.zsh.org/) behaves similar to Bash, however this behavior is configurable using the `RC_QUOTES` option.
* [PowerShell](https://microsoft.com/powershell) also treats characters literally when inside single quotes.

For these shells, the main exception is when the branch or tag name itself contains a single quote. In this case, you should consult the official documentation for your shell:

* [Bash documentation](https://www.gnu.org/software/bash/manual/)
* [Zsh documentation](https://zsh.sourceforge.io/Doc/)
* [Fish documentation](https://fishshell.com/docs/current/)
* [PowerShell documentation](https://docs.microsoft.com/en-gb/powershell/)

## Naming branches and tags

If possible, create branch and tag names that don't contain special characters, as these would need to be escaped. A safe default set of characters to use for branch names and tag names is:

* The English alphabet (`a` to `z` and `A` to `Z`)
* Numbers (`0` to `9`)
* A limited set of punctuation characters:
<!-- markdownlint-disable GHD034 -->
  * period (`.`)
  * hyphen (`-`)
  * underscore (`_`)
  * forward slash (`/`)
<!-- markdownlint-enable GHD034 -->

To avoid confusion, you should start branch names with a letter.

## Restrictions on names in GitHub

GitHub restricts a small number of branch and tag names from being pushed up.
Those restrictions are:
* No names which look like Git object IDs (40 characters containing only 0-9 and A-F), to prevent confusion with actual Git object IDs.
* No names beginning with `refs/`, to prevent confusion with the full name of Git refs. For more information about refs, see [Git References](https://git-scm.com/book/en/v2/Git-Internals-Git-References) in the Git documentation.
