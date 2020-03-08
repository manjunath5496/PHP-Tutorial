
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

<h3><span id="PHP_7" class="mw-headline"><span id="NG"><span id="ZE3"><span id="PHP7">PHP 7</span></span></span></span></h3>
<p>During 2014 and 2015, a new major PHP version was developed, which was numbered PHP&nbsp;7. The numbering of this version involved some debate.&nbsp;While the PHP&nbsp;6 Unicode experiment had never been released, several articles and book titles referenced the PHP&nbsp;6 name, which might have caused confusion if a new release were to reuse the name.&nbsp;After a vote, the name PHP&nbsp;7 was chosen.</p>
<p>The foundation of PHP 7 is a PHP&nbsp;<a title="Branching (version control)" href="https://en.wikipedia.org/wiki/Branching_(version_control)">branch</a>&nbsp;that was originally dubbed&nbsp;<em>PHP next generation</em>&nbsp;(<em>phpng</em>). It was authored by Dmitry Stogov, Xinchen Hui and Nikita Popov,&nbsp;and aimed to optimize PHP performance by refactoring the Zend Engine while retaining near-complete language compatibility.<sup id="cite_ref-51" class="reference"><a href="https://en.wikipedia.org/wiki/PHP#cite_note-51">[51]</a></sup>&nbsp;As of 14&nbsp;July&nbsp;2014,&nbsp;<a title="WordPress" href="https://en.wikipedia.org/wiki/WordPress">WordPress</a>-based benchmarks, which served as the main benchmark suite for the phpng project, showed an almost 100% increase in performance. Changes from phpng are also expected to make it easier to improve performance in the future, as more compact data structures and other changes are seen as better suited for a successful migration to a&nbsp;<a title="Just-in-time compilation" href="https://en.wikipedia.org/wiki/Just-in-time_compilation">just-in-time</a>&nbsp;(JIT) compiler.&nbsp;Because of the significant changes, the reworked Zend Engine is called&nbsp;<em>Zend Engine 3</em>, succeeding Zend Engine 2 used in PHP&nbsp;5.</p>
<p>Because of major internal changes in phpng it must receive a new&nbsp;<a title="Software versioning" href="https://en.wikipedia.org/wiki/Software_versioning">major version</a>&nbsp;number of PHP, rather than a minor PHP&nbsp;5 release, according to PHP's release process.&nbsp;Major versions of PHP are allowed to break backward-compatibility of code and therefore PHP&nbsp;7 presented an opportunity for other improvements beyond phpng that require backward-compatibility breaks. In particular, it involved the following changes:</p>
<ul>
<li>Many fatal- or recoverable-level legacy PHP error mechanisms were replaced with modern object-oriented&nbsp;<a class="mw-redirect" title="Exception (computer science)" href="https://en.wikipedia.org/wiki/Exception_(computer_science)">exceptions</a></li>
<li>The syntax for variable dereferencing was reworked to be internally more consistent and complete, allowing the use of the operators&nbsp;<code>-&gt;</code>,&nbsp;<code>[]</code>,&nbsp;<code>()</code>,<code>{}</code>, and&nbsp;<code>::</code>, with arbitrary meaningful left-side expressions</li>
<li>Support for legacy PHP&nbsp;4-style constructor methods was deprecated</li>
<li>The behavior of the&nbsp;<a title="Foreach loop" href="https://en.wikipedia.org/wiki/Foreach_loop"><code>foreach</code>&nbsp;statement</a>&nbsp;was changed to be more predictable</li>
<li>Constructors for the few classes built-in to PHP which returned null upon failure were changed to throw an exception instead, for consistency</li>
<li>Several unmaintained or deprecated&nbsp;<a class="mw-redirect" title="Server application programming interface" href="https://en.wikipedia.org/wiki/Server_application_programming_interface">server application programming interfaces</a>&nbsp;(SAPIs) and extensions were removed from the PHP core, most notably the legacy&nbsp;<code>mysql</code>&nbsp;extension<sup id="cite_ref-60" class="reference"><a href="https://en.wikipedia.org/wiki/PHP#cite_note-60">[60]</a></sup></li>
<li>The behavior of the&nbsp;<code>list()</code>&nbsp;operator was changed to remove support for strings</li>
<li>Support was removed for legacy ASP-style delimiters&nbsp;<code>&lt;%</code>&nbsp;and&nbsp;<code>%&gt;</code>&nbsp;and&nbsp;<code>&lt;script language="php"&gt; ... &lt;/script&gt;</code></li>
<li>An oversight allowing a&nbsp;<a title="Switch statement" href="https://en.wikipedia.org/wiki/Switch_statement">switch statement</a>&nbsp;to have multiple&nbsp;<code>default</code>&nbsp;clauses was fixed</li>
<li>Support for hexadecimal number support in some implicit conversions from strings to number types was removed</li>
<li>The&nbsp;<a class="mw-redirect" title="Left-shift operator" href="https://en.wikipedia.org/wiki/Left-shift_operator">left-shift</a>&nbsp;and&nbsp;<a class="mw-redirect" title="Right-shift operator" href="https://en.wikipedia.org/wiki/Right-shift_operator">right-shift</a>&nbsp;operators were changed to behave more consistently across platforms</li>
<li>Conversions between integers and floating point numbers were tightened and implemented more consistently across platforms</li>
</ul>
<p>PHP 7 also included new language features. Most notably, it introduces return type declarations for functions&nbsp;which complement the existing parameter type declarations, and support for the&nbsp;<a title="Variable (computer science)" href="https://en.wikipedia.org/wiki/Variable_(computer_science)">scalar</a>&nbsp;types (integer, float, string, and boolean) in parameter and return type declarations.</p>


<h3><span id="Release_history" class="mw-headline">Release history</span></h3>
<table class="wikitable">
<tbody>
<tr>
<th>Version</th>
<th>Release date</th>
<th>Supported until</th>
<th>Notes</th>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="1.0">1.0</td>
<td>8 June 1995</td>
<td>&nbsp;</td>
<td>Officially called "Personal Home Page Tools (PHP Tools)". This is the first use of the name "PHP".</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="2.0">2.0</td>
<td>1 November 1997</td>
<td>&nbsp;</td>
<td>Officially called "PHP/FI 2.0". This is the first release that could actually be characterised as PHP, being a standalone language with many features that have endured to the present day.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="3.0">3.0</td>
<td>6 June 1998</td>
<td>20 October 2000</td>
<td>Development moves from one person to multiple developers. Zeev Suraski and Andi Gutmans rewrite the base for this version.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="4.0">4.0</td>
<td>22 May 2000</td>
<td>23 June 2001</td>
<td>Added more advanced two-stage parse/execute tag-parsing system called the Zend engine.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="4.1">4.1</td>
<td>10 December 2001</td>
<td>12 March 2002</td>
<td>Introduced "superglobals" (<code id="" class="mw-highlight mw-highlight-lang-php" dir="ltr"><span class="nv">$_GET</span></code>,&nbsp;<code id="" class="mw-highlight mw-highlight-lang-php" dir="ltr"><span class="nv">$_POST</span></code>,&nbsp;<code id="" class="mw-highlight mw-highlight-lang-php" dir="ltr"><span class="nv">$_SESSION</span></code>, etc.)</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="4.2">4.2</td>
<td>22 April 2002</td>
<td>6 September 2002</td>
<td>Disabled&nbsp;<code>register_globals</code>&nbsp;by default. Data received over the network is not inserted directly into the&nbsp;<a title="Global variable" href="https://en.wikipedia.org/wiki/Global_variable">global</a>&nbsp;namespace anymore, closing possible security holes in applications.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="4.3">4.3</td>
<td>27 December 2002</td>
<td>31 March 2005</td>
<td>Introduced the&nbsp;<a title="Command-line interface" href="https://en.wikipedia.org/wiki/Command-line_interface">command-line interface</a>&nbsp;(CLI), to supplement the CGI.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="4.4">4.4</td>
<td>11 July 2005</td>
<td>7 August 2008</td>
<td>Fixed a memory corruption bug, which required breaking binary compatibility with extensions compiled against PHP version 4.3.x.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="5.0">5.0</td>
<td>13 July 2004</td>
<td>5 September 2005</td>
<td>Zend Engine II with a new object model.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="5.1">5.1</td>
<td>24 November 2005</td>
<td>24 August 2006</td>
<td>Performance improvements with introduction of compiler variables in re-engineered PHP Engine.&nbsp;Added PHP Data Objects (PDO) as a consistent interface for accessing databases.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="5.2">5.2</td>
<td>2 November 2006</td>
<td>6 January 2011</td>
<td>Enabled the filter extension by default. Native&nbsp;<a title="JSON" href="https://en.wikipedia.org/wiki/JSON">JSON</a>&nbsp;support.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="5.3">5.3</td>
<td>30 June 2009</td>
<td>14 August 2014</td>
<td><a title="Namespace" href="https://en.wikipedia.org/wiki/Namespace">Namespace</a>&nbsp;support;&nbsp;<a title="Name binding" href="https://en.wikipedia.org/wiki/Name_binding">late static bindings</a>, jump label (limited&nbsp;<a title="Goto" href="https://en.wikipedia.org/wiki/Goto">goto</a>),&nbsp;<a class="mw-redirect" title="Closure (computer science)" href="https://en.wikipedia.org/wiki/Closure_(computer_science)">closures</a>, PHP archives (phar),&nbsp;<a title="Garbage collection (computer science)" href="https://en.wikipedia.org/wiki/Garbage_collection_(computer_science)">garbage collection</a>&nbsp;for circular references, improved&nbsp;<a title="Microsoft Windows" href="https://en.wikipedia.org/wiki/Microsoft_Windows">Windows</a>&nbsp;support, sqlite3, mysqlnd as a replacement for libmysql as underlying library for the extensions that work with&nbsp;<a title="MySQL" href="https://en.wikipedia.org/wiki/MySQL">MySQL</a>, fileinfo as a replacement for mime_magic for better&nbsp;<a title="MIME" href="https://en.wikipedia.org/wiki/MIME">MIME</a>&nbsp;support, the Internationalization extension, and deprecation of ereg extension.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="5.4">5.4</td>
<td>1 March 2012</td>
<td>3 September 2015</td>
<td><a title="Trait (computer programming)" href="https://en.wikipedia.org/wiki/Trait_(computer_programming)">Trait</a>&nbsp;support, short array syntax support. Removed items:&nbsp;<code>register_globals</code>,&nbsp;<code>safe_mode</code>,&nbsp;<code>allow_call_time_pass_reference</code>,&nbsp;<code id="" class="mw-highlight mw-highlight-lang-php" dir="ltr"><span class="nb">session_register</span><span class="p">()</span></code>,&nbsp;<code id="" class="mw-highlight mw-highlight-lang-php" dir="ltr"><span class="nb">session_unregister</span><span class="p">()</span></code>&nbsp;and&nbsp;<code id="" class="mw-highlight mw-highlight-lang-php" dir="ltr"><span class="nb">session_is_registered</span><span class="p">()</span></code>. Built-in web server.&nbsp;Several improvements to existing features, performance and reduced memory requirements.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="5.5">5.5</td>
<td>20 June 2013</td>
<td>10 July 2016</td>
<td>Support for&nbsp;<a title="Generator (computer programming)" href="https://en.wikipedia.org/wiki/Generator_(computer_programming)">generators</a>,&nbsp;<code>finally</code>&nbsp;blocks for exceptions handling, OpCache (based on Zend Optimizer+) bundled in official distribution.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="5.6">5.6</td>
<td>28 August 2014</td>
<td>31 December 2018</td>
<td>Constant scalar expressions,&nbsp;<a title="Variadic function" href="https://en.wikipedia.org/wiki/Variadic_function">variadic functions</a>, argument unpacking, new exponentiation operator, extensions of the&nbsp;<code>use</code>&nbsp;statement for functions and constants, new&nbsp;<code>phpdbg</code>&nbsp;debugger as a SAPI module, and other smaller improvements.</td>
</tr>
<tr>
<td>6.x</td>
<td class="table-na" data-sort-value="">Not released</td>
<td class="table-na" data-sort-value="">N/A</td>
<td>Abandoned version of PHP that planned to include native Unicode support.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="7.0">7.0</td>
<td>3 December 2015</td>
<td>3 December 2018</td>
<td>Zend Engine 3 (performance improvements&nbsp;and 64-bit integer support on Windows), uniform variable syntax,&nbsp;<a class="mw-redirect" title="Abstract Syntax Tree" href="https://en.wikipedia.org/wiki/Abstract_Syntax_Tree">AST</a>-based compilation process,&nbsp;added&nbsp;<code id="" class="mw-highlight mw-highlight-lang-php" dir="ltr"><span class="nx">Closure</span><span class="o">::</span><span class="na">call</span><span class="p">()</span></code>,&nbsp;bitwise shift consistency across platforms,<span style="font-size: xx-small;">&nbsp;</span><code id="" class="mw-highlight mw-highlight-lang-php" dir="ltr"><span class="o">??</span></code>&nbsp;(<a title="Null coalescing operator" href="https://en.wikipedia.org/wiki/Null_coalescing_operator">null coalesce</a>) operator,&nbsp;<a title="Unicode" href="https://en.wikipedia.org/wiki/Unicode">Unicode</a>&nbsp;code point&nbsp;<a title="String literal" href="https://en.wikipedia.org/wiki/String_literal#Escape_sequences">escape syntax</a>,&nbsp;return type declarations, scalar type (integer, float, string and boolean) declarations,&nbsp;<code>&lt;=&gt;</code>&nbsp;"spaceship"&nbsp;<a title="Three-way comparison" href="https://en.wikipedia.org/wiki/Three-way_comparison">three-way comparison</a>&nbsp;operator,&nbsp;<a title="Generator (computer programming)" href="https://en.wikipedia.org/wiki/Generator_(computer_programming)">generator</a>&nbsp;delegation,&nbsp;<a class="mw-redirect" title="Anonymous class" href="https://en.wikipedia.org/wiki/Anonymous_class">anonymous classes</a>,&nbsp;simpler and more consistently available&nbsp;<a class="mw-redirect" title="CSPRNG" href="https://en.wikipedia.org/wiki/CSPRNG">CSPRNG</a>&nbsp;API,&nbsp;replacement of many remaining internal PHP "errors" with the more modern&nbsp;<a class="mw-redirect" title="Exception (computer science)" href="https://en.wikipedia.org/wiki/Exception_(computer_science)">exceptions</a>,&nbsp;and shorthand syntax for importing multiple items from a namespace.</td>
</tr>
<tr>
<td title="Old version, no longer maintained" data-sort-value="7.1">7.1</td>
<td>1 December 2016</td>
<td>1 December 2019</td>
<td><a title="Void type" href="https://en.wikipedia.org/wiki/Void_type">void return type</a>,&nbsp;class constant&nbsp;<a title="Information hiding" href="https://en.wikipedia.org/wiki/Information_hiding">visibility modifiers</a></td>
</tr>
<tr>
<td class="templateVersion co" title="Older version, yet still maintained" data-sort-value="7.2">7.2</td>
<td>30 November 2017</td>
<td>30 November 2020</td>
<td>Object parameter and return type hint,&nbsp;Libsodium extension,&nbsp;Abstract method overriding,&nbsp;Parameter type widening</td>
</tr>
<tr>
<td class="templateVersion co" title="Older version, yet still maintained" data-sort-value="7.3">7.3</td>
<td>6 December 2018</td>
<td>6 December 2021</td>
<td>Flexible&nbsp;<a title="Here document" href="https://en.wikipedia.org/wiki/Here_document#PHP">Heredoc</a>&nbsp;and Nowdoc syntax,&nbsp;support for reference assignment and array deconstruction with list(),&nbsp;PCRE2 support,&nbsp;hrtime() function</td>
</tr>
<tr>
<td class="templateVersion c" title="Current stable version" data-sort-value="7.4"><strong>7.4</strong></td>
<td>28 November 2019</td>
<td>28 November 2022</td>
<td>Typed Properties 2.0,&nbsp;Preloading,&nbsp;Null Coalescing Assignment Operator,&nbsp;Improve openssl_random_pseudo_bytes,&nbsp;Weak References,&nbsp;FFI&nbsp;&ndash; Foreign Function Interface
<p>Always available hash extension,&nbsp;Password Hash Registry,&nbsp;Split multibyte string,&nbsp;Reflection for references,&nbsp;Unbundle ext/wddx,&nbsp;New custom object serialization mechanism</p>
</td>
</tr>
<tr>
<td class="templateVersion p" title="Future release" data-sort-value="8.0">8.0</td>
<td>Q4 2020 or Q1 2021</td>
<td>Q4 2023 or Q1 2024</td>
<td><a title="Just-in-time compilation" href="https://en.wikipedia.org/wiki/Just-in-time_compilation">Just In Time compilation (JIT)</a>,&nbsp;arrays starting with a negative index,&nbsp;consistent type errors for internal functions,&nbsp;fatal error for incompatible method signatures</td>
</tr>
<tr class="sortbottom">
<td colspan="4">
<div class="templateVersion l">
<div><strong>Legend:</strong></div>
<div><span title="Old version, no longer maintained">Old version</span></div>
<div><span title="An older version, yet still maintained">Older version, still maintained</span></div>
<div><span title="Latest stable version"><strong>Latest version</strong></span></div>
<div><span title="Latest preview of a future release">Latest preview version</span></div>
<div><span title="A future release">Future release</span></div>
<div>&nbsp;</div>
</div>
</td>
</tr>
</tbody>
</table>
<p>Beginning on June 28, 2011, the PHP Development Team implemented a timeline for the release of new versions of PHP.&nbsp;Under this system, at least one release should occur every month. Once per year, a minor release should occur which may include new features. Every minor release should at least be supported for two years with security and bug fixes, followed by at least one year of only security fixes, for a total of a three-year release process for every minor release. No new features, unless small and self-contained, are to be introduced into a minor release during the three-year release process. Latest versions of PHP are PHP 7.2.27, PHP 7.3.14 and PHP 7.4.3 released on 20 Feb 2020.</p>




