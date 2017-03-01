##Sublime Text Tip

###How to install packages

####1.Quickly install

+	Sublime Text 3:

<pre>
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
</pre>

+	Sublime Text 2:

<pre>
import urllib2,os; pf='Package Control.sublime-package'; ipp = sublime.installed_packages_path(); os.makedirs( ipp ) if not os.path.exists(ipp) else None; urllib2.install_opener( urllib2.build_opener( urllib2.ProxyHandler( ))); open( os.path.join( ipp, pf), 'wb' ).write( urllib2.urlopen( 'http://sublime.wbond.net/' +pf.replace( ' ','%20' )).read()); print( 'Please restart Sublime Text to finish installation')
</pre>

####2.License

+	Sublime Text 2:

<pre>
----- BEGIN LICENSE -----  
Andrew Weber  
Single User License  
EA7E-855605  
813A03DD 5E4AD9E6 6C0EEB94 BC99798F  
942194A6 02396E98 E62C9979 4BB979FE  
91424C9D A45400BF F6747D88 2FB88078  
90F5CC94 1CDC92DC 8457107A F151657B  
1D22E383 A997F016 42397640 33F41CFC  
E1D0AE85 A0BBD039 0E9C8D55 E1B89D5D  
5CDB7036 E56DE1C0 EFCC0840 650CD3A6  
B98FC99C 8FAC73EE D2B95564 DF450523  
</pre>

####3.Manually Install

+	[Download Path](https://sublime.wbond.net/Package%20Control.sublime-package)
+	Copy to Installed Packages
+	Restart Sublime Text.

####4.Recommend packages

+	Emmet
+	BracketHighlighter
+	Sublimall
+	AllAutocomplete
+	SublimeREPL
+	DocBlocker
+	AutoFileName
+	MarkdownEditing
+	SideBarEnhancement
+	AStyleFormatter
+	Alignment
