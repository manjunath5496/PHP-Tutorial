
<p><strong>PHP</strong>&nbsp;is a popular general-purpose scripting language that is especially suited to web development. It was originally created by&nbsp;<a title="Rasmus Lerdorf" href="https://en.wikipedia.org/wiki/Rasmus_Lerdorf">Rasmus Lerdorf</a>&nbsp;in 1994;&nbsp;the PHP&nbsp;<a title="Reference implementation" href="https://en.wikipedia.org/wiki/Reference_implementation">reference implementation</a>&nbsp;is now produced by The PHP Group.&nbsp;PHP originally stood for&nbsp;<em>Personal Home Page</em>,&nbsp;but it now stands for the&nbsp;<a class="mw-redirect" title="Recursive initialism" href="https://en.wikipedia.org/wiki/Recursive_initialism">recursive initialism</a>&nbsp;<em>PHP: Hypertext Preprocessor</em>.</p>
<p>PHP code is usually processed on a web server by a PHP&nbsp;<a title="Interpreter (computing)" href="https://en.wikipedia.org/wiki/Interpreter_(computing)">interpreter</a>&nbsp;implemented as a&nbsp;<a class="mw-redirect" title="Plugin (computing)" href="https://en.wikipedia.org/wiki/Plugin_(computing)">module</a>, a&nbsp;<a title="Daemon (computing)" href="https://en.wikipedia.org/wiki/Daemon_(computing)">daemon</a>&nbsp;or as a&nbsp;<a title="Common Gateway Interface" href="https://en.wikipedia.org/wiki/Common_Gateway_Interface">Common Gateway Interface</a>&nbsp;(CGI) executable. On a web server, the result of the interpreted and executed PHP code &mdash; which may be any type of data, such as generated HTML or binary image data &mdash; would form the whole or part of a HTTP response. Various&nbsp;<a title="Web template system" href="https://en.wikipedia.org/wiki/Web_template_system">web template systems</a>, web&nbsp;<a title="Content management system" href="https://en.wikipedia.org/wiki/Content_management_system">content management systems</a>, and&nbsp;<a title="Web framework" href="https://en.wikipedia.org/wiki/Web_framework">web frameworks</a>&nbsp;exist which can be employed to orchestrate or facilitate the generation of that response. Additionally, PHP can be used for many programming tasks outside of the web context, such as&nbsp;<a class="mw-redirect" title="Computer software" href="https://en.wikipedia.org/wiki/Computer_software">standalone</a>&nbsp;<a title="Graphical user interface" href="https://en.wikipedia.org/wiki/Graphical_user_interface">graphical applications</a>&nbsp;and robotic&nbsp;<a title="Unmanned aerial vehicle" href="https://en.wikipedia.org/wiki/Unmanned_aerial_vehicle">drone</a>&nbsp;control. Arbitrary PHP code can also be interpreted and executed via&nbsp;<a title="Command-line interface" href="https://en.wikipedia.org/wiki/Command-line_interface">command line interface</a>&nbsp;(CLI).</p>
<p>The standard PHP interpreter, powered by the&nbsp;<a title="Zend Engine" href="https://en.wikipedia.org/wiki/Zend_Engine">Zend Engine</a>, is&nbsp;<a title="Free software" href="https://en.wikipedia.org/wiki/Free_software">free software</a>&nbsp;released under the&nbsp;<a title="PHP License" href="https://en.wikipedia.org/wiki/PHP_License">PHP License</a>. PHP has been widely ported and can be deployed on most web servers on almost every&nbsp;<a title="Operating system" href="https://en.wikipedia.org/wiki/Operating_system">operating system</a>&nbsp;and&nbsp;<a title="Computing platform" href="https://en.wikipedia.org/wiki/Computing_platform">platform</a>, free of charge.</p>
<p>The PHP language evolved without a written&nbsp;<a title="Formal specification" href="https://en.wikipedia.org/wiki/Formal_specification">formal specification</a>&nbsp;or standard until 2014, with the original implementation acting as the&nbsp;<em><a title="De facto" href="https://en.wikipedia.org/wiki/De_facto">de facto</a></em>&nbsp;standard which other implementations aimed to follow. Since 2014, work has gone on to create a formal PHP specification.</p>
<p>As of February&nbsp;2020, over half of sites on the web using PHP are still on&nbsp;<a title="End-of-life (product)" href="https://en.wikipedia.org/wiki/End-of-life_(product)#Computing">discontinued/"EOLed"</a>&nbsp;version 5.6 or older;&nbsp;and over 55% of all websites in the world run versions prior to 7.2, that are neither officially supported by The PHP Development Team,&nbsp;while security support is provided by third parties, such as&nbsp;<a title="Debian" href="https://en.wikipedia.org/wiki/Debian">Debian</a>&nbsp;(up to June 2020 for PHP 5).</p>


<div class="toctitle" dir="ltr" lang="en">
<h2 id="mw-toc-heading">Contents</h2>
<label class="toctogglelabel" for="toctogglecheckbox"></label></div>
<ul>
<li class="toclevel-1 tocsection-1"><a href="#History"><span class="toctext">History</span></a>
<ul>
<li class="toclevel-2 tocsection-2"><a href="#Early_history"><span class="toctext">Early history</span></a></li>
<li class="toclevel-2 tocsection-3"><a href="#PHP_3_and_4"><span class="toctext">PHP 3 and 4</span></a></li>
<li class="toclevel-2 tocsection-4"><a href="#PHP_5"><span class="toctext">PHP 5</span></a></li>
<li class="toclevel-2 tocsection-5"><a href="#PHP_6_and_Unicode"><span class="toctext">PHP 6 and Unicode</span></a></li>
<li class="toclevel-2 tocsection-6"><a href="#PHP_7"><span class="toctext">PHP 7</span></a></li>
<li class="toclevel-2 tocsection-7"><a href="#Release_history"><span class="toctext">Release history</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-8"><a href="#Mascot"><span class="toctext">Mascot</span></a></li>
<li class="toclevel-1 tocsection-9"><a href="#Syntax"><span class="toctext">Syntax</span></a>
<ul>
<li class="toclevel-2 tocsection-10"><a href="#Data_types"><span class="toctext">Data types</span></a></li>
<li class="toclevel-2 tocsection-11"><a href="#Functions"><span class="toctext">Functions</span></a></li>
<li class="toclevel-2 tocsection-12"><a href="#PHP_Objects"><span class="toctext">PHP Objects</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-13"><a href="#Implementations"><span class="toctext">Implementations</span></a></li>
<li class="toclevel-1 tocsection-14"><a href="#Licensing"><span class="toctext">Licensing</span></a></li>
<li class="toclevel-1 tocsection-15"><a href="#Development_and_community"><span class="toctext">Development and community</span></a></li>
<li class="toclevel-1 tocsection-16"><a href="#Installation_and_configuration"><span class="toctext">Installation and configuration</span></a></li>
<li class="toclevel-1 tocsection-17"><a href="#Use"><span class="toctext">Use</span></a></li>
<li class="toclevel-1 tocsection-18"><a href="#Security"><span class="toctext">Security</span></a></li>
</ul>
  
  
  
  
</div>
<h2>&nbsp;</h2>
<h2><span id="History" class="mw-headline">History</span></h2>
<h3><span id="Early_history" class="mw-headline">Early history</span></h3>
<div class="thumb tmulti tleft">
<div class="thumbinner">
<div class="trow">
<div class="tsingle">
<div class="thumbimage"><a class="image" href="Rasmus_Lerdorf.jpg"><img src="Rasmus_Lerdorf.jpg" srcset="Rasmus_Lerdorf.jpg" alt="" width="105" height="142" data-file-width="495" data-file-height="669" /></a></div>
</div>
<div class="tsingle">
<div class="thumbimage"><a class="image" href="Andi_Gutmans.jpg"><img src="Andi_Gutmans.jpg" srcset="Andi_Gutmans.jpg" alt="" width="105" height="142" data-file-width="597" data-file-height="808" /></a></div>
</div>
<div class="tsingle">
<div class="thumbimage"><a class="image" href="Zeev_Suraski.jpg"><img src="Zeev_Suraski.jpg" srcset="Zeev_Suraski.jpg" alt="" width="105" height="142" data-file-width="220" data-file-height="298" /></a></div>
</div>
</div>
<div class="trow">
<div class="thumbcaption"><a title="Rasmus Lerdorf" href="https://en.wikipedia.org/wiki/Rasmus_Lerdorf">Rasmus Lerdorf</a>, who wrote the original&nbsp;<a title="Common Gateway Interface" href="https://en.wikipedia.org/wiki/Common_Gateway_Interface">Common Gateway Interface</a>&nbsp;(CGI) component, together with&nbsp;<a title="Andi Gutmans" href="https://en.wikipedia.org/wiki/Andi_Gutmans">Andi Gutmans</a>&nbsp;and&nbsp;<a title="Zeev Suraski" href="https://en.wikipedia.org/wiki/Zeev_Suraski">Zeev Suraski</a>, who rewrote the&nbsp;<a class="mw-redirect" title="Parser" href="https://en.wikipedia.org/wiki/Parser">parser</a>&nbsp;that formed PHP&nbsp;3.</div>
<div class="thumbcaption">&nbsp;</div>
</div>
</div>
</div>
<p>PHP development began in 1994 when&nbsp;<a title="Rasmus Lerdorf" href="https://en.wikipedia.org/wiki/Rasmus_Lerdorf">Rasmus Lerdorf</a>&nbsp;wrote several&nbsp;<a title="Common Gateway Interface" href="https://en.wikipedia.org/wiki/Common_Gateway_Interface">Common Gateway Interface</a>&nbsp;(CGI) programs in C,&nbsp;which he used to maintain his&nbsp;<a class="mw-redirect" title="Personal homepage" href="https://en.wikipedia.org/wiki/Personal_homepage">personal homepage</a>. He extended them to work with&nbsp;<a class="mw-redirect" title="Web form" href="https://en.wikipedia.org/wiki/Web_form">web forms</a>&nbsp;and to communicate with&nbsp;<a title="Database" href="https://en.wikipedia.org/wiki/Database">databases</a>, and called this implementation "Personal Home Page/Forms Interpreter" or PHP/FI.</p>
<p>PHP/FI could be used to build simple,&nbsp;<a class="mw-redirect" title="Dynamic web application" href="https://en.wikipedia.org/wiki/Dynamic_web_application">dynamic web applications</a>. To accelerate&nbsp;<a title="Software bug" href="https://en.wikipedia.org/wiki/Software_bug">bug</a>&nbsp;reporting and improve the code, Lerdorf initially announced the release of PHP/FI as "Personal Home Page Tools (PHP Tools) version 1.0" on the&nbsp;<a title="Usenet" href="https://en.wikipedia.org/wiki/Usenet">Usenet</a>&nbsp;discussion group&nbsp;<em>comp.infosystems.www.authoring.cgi</em>&nbsp;on June 8, 1995.&nbsp;This release already had the basic functionality that PHP has today. This included&nbsp;<a title="Local variable" href="https://en.wikipedia.org/wiki/Local_variable#Local_variables_in_Perl">Perl-like variables</a>, form handling, and the ability to embed HTML. The&nbsp;<a title="Syntax" href="https://en.wikipedia.org/wiki/Syntax">syntax</a>&nbsp;resembled that of Perl, but was simpler, more limited and less consistent.</p>
<div>&nbsp;</div>
<p>An example of the early PHP syntax:</p>
<div class="mw-highlight mw-highlight-lang-php mw-content-ltr" dir="ltr">
<pre><span class="o">&lt;!--</span><span class="k">include</span> <span class="o">/</span><span class="nx">text</span><span class="o">/</span><span class="nb">header</span><span class="o">.</span><span class="nx">html</span><span class="o">--&gt;</span>

<span class="o">&lt;!--</span><span class="nb">getenv</span> <span class="nx">HTTP_USER_AGENT</span><span class="o">--&gt;</span>
<span class="o">&lt;!--</span><span class="nx">ifsubstr</span> <span class="nv">$exec_result</span> <span class="nx">Mozilla</span><span class="o">--&gt;</span>
  <span class="nx">Hey</span><span class="p">,</span> <span class="nx">you</span> <span class="nx">are</span> <span class="nx">using</span> <span class="nx">Netscape</span><span class="o">!&lt;</span><span class="nx">p</span><span class="o">&gt;</span>
<span class="o">&lt;!--</span><span class="k">endif</span><span class="o">--&gt;</span>

<span class="o">&lt;!--</span><span class="nx">sql</span> <span class="nx">database</span> <span class="nx">select</span> <span class="o">*</span> <span class="nx">from</span> <span class="nx">table</span> <span class="nx">where</span> <span class="nx">user</span><span class="o">=</span><span class="s1">'$username'</span><span class="o">--&gt;</span>
<span class="o">&lt;!--</span><span class="nx">ifless</span> <span class="nv">$numentries</span> <span class="mi">1</span><span class="o">--&gt;</span>
  <span class="nx">Sorry</span><span class="p">,</span> <span class="nx">that</span> <span class="nx">record</span> <span class="nx">does</span> <span class="k">not</span> <span class="nx">exist</span><span class="o">&lt;</span><span class="nx">p</span><span class="o">&gt;</span>
<span class="o">&lt;!--</span><span class="k">endif</span> <span class="k">exit</span><span class="o">--&gt;</span>
  <span class="nx">Welcome</span> <span class="o">&lt;!--</span><span class="nv">$user</span><span class="o">--&gt;!&lt;</span><span class="nx">p</span><span class="o">&gt;</span>
  <span class="nx">You</span> <span class="nx">have</span> <span class="o">&lt;!--</span><span class="nv">$index</span><span class="o">:</span><span class="mi">0</span><span class="o">--&gt;</span> <span class="nx">credits</span> <span class="nx">left</span> <span class="nx">in</span> <span class="nx">your</span> <span class="nx">account</span><span class="o">.&lt;</span><span class="nx">p</span><span class="o">&gt;</span>

<span class="o">&lt;!--</span><span class="k">include</span> <span class="o">/</span><span class="nx">text</span><span class="o">/</span><span class="nx">footer</span><span class="o">.</span><span class="nx">html</span><span class="o">--&gt;</span>
</pre>
</div>
<p>Early PHP was not intended to be a new&nbsp;<a title="Programming language theory" href="https://en.wikipedia.org/wiki/Programming_language_theory">programming language</a>, and grew organically, with Lerdorf noting in retrospect: "I don't know how to stop it, there was never any intent to write a programming language [...] I have absolutely no idea how to write a programming language, I just kept adding the next logical step on the way."&nbsp;A development team began to form and, after months of work and&nbsp;<a class="mw-redirect" title="Beta development stage" href="https://en.wikipedia.org/wiki/Beta_development_stage">beta</a>&nbsp;testing, officially released PHP/FI 2 in November 1997.</p>
<p>The fact that PHP was not originally designed, but instead was developed organically has led to inconsistent naming of functions and inconsistent ordering of their parameters.&nbsp;In some cases, the function names were chosen to match the lower-level libraries which PHP was "wrapping",&nbsp;while in some very early versions of PHP the length of the function names was used internally as a&nbsp;<a title="Hash function" href="https://en.wikipedia.org/wiki/Hash_function">hash function</a>, so names were chosen to improve the distribution of hash values.</p>
<p>&nbsp;</p>

<h3><span id="PHP_3_and_4" class="mw-headline">PHP 3 and 4</span></h3>
<div class="thumb tright">
<div class="thumbinner"><a class="image" href="Custom-software-developement.JPG"><img class="thumbimage" src="Custom-software-developement.JPG" srcset="Custom-software-developement.JPG" alt="" width="220" height="170" data-file-width="1239" data-file-height="956" /></a>
<div class="thumbcaption">
<div class="magnify">&nbsp;</div>
This is an example of custom PHP code for the&nbsp;<a title="WordPress" href="https://en.wikipedia.org/wiki/WordPress">WordPress</a>&nbsp;<a title="Content management system" href="https://en.wikipedia.org/wiki/Content_management_system">content management system</a>.</div>
<div class="thumbcaption">&nbsp;</div>
</div>
</div>
<p><a title="Zeev Suraski" href="https://en.wikipedia.org/wiki/Zeev_Suraski">Zeev Suraski</a>&nbsp;and&nbsp;<a title="Andi Gutmans" href="https://en.wikipedia.org/wiki/Andi_Gutmans">Andi Gutmans</a>&nbsp;rewrote the&nbsp;<a class="mw-redirect" title="Parser" href="https://en.wikipedia.org/wiki/Parser">parser</a>&nbsp;in 1997 and formed the base of PHP&nbsp;3, changing the language's name to the&nbsp;<a title="Recursive acronym" href="https://en.wikipedia.org/wiki/Recursive_acronym">recursive acronym</a>&nbsp;<em>PHP: Hypertext Preprocessor</em>.&nbsp;Afterwards, public testing of PHP&nbsp;3 began, and the official launch came in June 1998. Suraski and Gutmans then started a new&nbsp;<a title="Rewrite (programming)" href="https://en.wikipedia.org/wiki/Rewrite_(programming)">rewrite</a>&nbsp;of PHP's core, producing the&nbsp;<a title="Zend Engine" href="https://en.wikipedia.org/wiki/Zend_Engine">Zend Engine</a>&nbsp;in 1999.&nbsp;They also founded&nbsp;<a title="Zend Technologies" href="https://en.wikipedia.org/wiki/Zend_Technologies">Zend Technologies</a>&nbsp;in&nbsp;<a title="Ramat Gan" href="https://en.wikipedia.org/wiki/Ramat_Gan">Ramat Gan</a>, Israel.</p>
<p>On May 22, 2000, PHP 4, powered by the Zend Engine 1.0, was released.&nbsp;As of August 2008 this branch reached version 4.4.9. PHP&nbsp;4 is no longer under development nor will any security updates be released.</p>
<h3><span id="PHP_5" class="mw-headline">PHP 5</span></h3>
<p>On July 14, 2004, PHP 5 was released, powered by the new Zend Engine II.&nbsp;PHP&nbsp;5 included new features such as improved support for&nbsp;<a title="Object-oriented programming" href="https://en.wikipedia.org/wiki/Object-oriented_programming">object-oriented programming</a>, the PHP Data Objects (PDO) extension (which defines a lightweight and consistent interface for accessing databases), and numerous performance enhancements.&nbsp;In 2008, PHP&nbsp;5 became the only stable version under development.&nbsp;<a class="mw-redirect" title="Late static binding" href="https://en.wikipedia.org/wiki/Late_static_binding">Late static binding</a>&nbsp;had been missing from PHP and was added in version 5.3.</p>
<p>Many high-profile open-source projects ceased to support PHP&nbsp;4 in new code as of February 5, 2008, because of the GoPHP5 initiative,&nbsp;provided by a consortium of PHP developers promoting the transition from PHP&nbsp;4 to PHP&nbsp;5.</p>
<p>Over time, PHP interpreters became available on most existing&nbsp;<a class="mw-redirect" title="32-bit" href="https://en.wikipedia.org/wiki/32-bit">32-bit</a>&nbsp;and&nbsp;<a class="mw-redirect" title="64-bit" href="https://en.wikipedia.org/wiki/64-bit">64-bit</a>&nbsp;operating systems, either by building them from the PHP source code, or by using pre-built binaries.<sup id="cite_ref-36" class="reference"><a href="https://en.wikipedia.org/wiki/PHP#cite_note-36">[36]</a></sup>&nbsp;For PHP versions 5.3 and 5.4, the only available&nbsp;<a title="Microsoft Windows" href="https://en.wikipedia.org/wiki/Microsoft_Windows">Microsoft Windows</a>&nbsp;binary distributions were 32-bit&nbsp;<a title="IA-32" href="https://en.wikipedia.org/wiki/IA-32">IA-32</a>&nbsp;builds,&nbsp;requiring Windows 32-bit compatibility mode while using&nbsp;<a title="Internet Information Services" href="https://en.wikipedia.org/wiki/Internet_Information_Services">Internet Information Services</a>&nbsp;(IIS) on a 64-bit Windows platform. PHP version 5.5 made the 64-bit&nbsp;<a title="X86-64" href="https://en.wikipedia.org/wiki/X86-64">x86-64</a>&nbsp;builds available for Microsoft Windows.</p>
<p>Official security support for PHP 5.6 ended on 31 December 2018,&nbsp;but&nbsp;<a title="Debian" href="https://en.wikipedia.org/wiki/Debian">Debian 8.0 Jessie</a>&nbsp;will extend support until June 2020.</p>
<h3><span id="PHP_6_and_Unicode" class="mw-headline"><span id="PHP6-UNICODE">PHP 6 and Unicode</span></span></h3>
<p>PHP received mixed reviews due to lacking native&nbsp;<a title="Unicode" href="https://en.wikipedia.org/wiki/Unicode">Unicode</a>&nbsp;support at the core language level.&nbsp;In 2005, a project headed by Andrei Zmievski was initiated to bring native Unicode support throughout PHP, by embedding the&nbsp;<a title="International Components for Unicode" href="https://en.wikipedia.org/wiki/International_Components_for_Unicode">International Components for Unicode</a>&nbsp;(ICU) library, and representing text strings as&nbsp;<a title="UTF-16" href="https://en.wikipedia.org/wiki/UTF-16">UTF-16</a>&nbsp;internally.&nbsp;Since this would cause major changes both to the internals of the language and to user code, it was planned to release this as version 6.0 of the language, along with other major features then in development.</p>
<p>However, a shortage of developers who understood the necessary changes, and performance problems arising from conversion to and from UTF-16, which is rarely used in a web context, led to delays in the project.&nbsp;As a result, a PHP&nbsp;5.3 release was created in 2009, with many non-Unicode features back-ported from PHP&nbsp;6, notably namespaces. In March 2010, the project in its current form was officially abandoned, and a PHP&nbsp;5.4 release was prepared containing most remaining non-Unicode features from PHP&nbsp;6, such as traits and closure re-binding.&nbsp;Initial hopes were that a new plan would be formed for Unicode integration, but as of 2014&nbsp;none had been adopted.</p>
