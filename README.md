<h1>⬡ Universal File Viewer</h1>

<p>
A powerful, browser-based file inspection tool that runs entirely client-side.
Open, inspect, and analyze <strong>500+ file formats</strong> with zero uploads and zero servers.
</p>

<p>
🔗 <strong>Live Demo:</strong><br>
<a href="https://boothy91.github.io/FileViewer/" target="_blank">
https://py0sc.github.io/FileViewer/
</a>
</p>

<hr>

<h2>Overview</h2>

<p>
Universal File Viewer is a single-page web application designed for developers,
designers, analysts, and power users. All processing happens locally using browser APIs.
Files never leave your device.
</p>

<h3>Supported Categories</h3>

<p>
Images · Video · Audio · Code · PDF · CSV/XLSX · GPX/KML · GLB/STL · ZIP · Fonts · MIDI · Certificates · Binary
</p>

<hr>

<h2>Core Features</h2>

<h3>📂 Drag & Drop Interface</h3>
<ul>
<li>Tap or drag files directly into the viewer</li>
<li>Fullscreen mode</li>
<li>Dark / Light theme toggle</li>
<li>Recent file history (stored locally)</li>
<li>Mobile-optimized UI</li>
</ul>

<h3>🧠 Smart File Detection</h3>
<ul>
<li>Extension-based routing</li>
<li>Magic byte signature detection</li>
<li>Automatic viewer selection</li>
</ul>

<h3>👁 Built-in Viewers</h3>

<ul>
<li><strong>Images:</strong> PNG, JPG, WebP, AVIF, SVG, ICO, RAW + EXIF & color palette extraction</li>
<li><strong>Video:</strong> MP4, MKV, MOV, AVI with thumbnail strip</li>
<li><strong>Audio:</strong> MP3, WAV, FLAC + waveform + MIDI piano roll</li>
<li><strong>Documents:</strong> TXT, Markdown, PDF, DOCX</li>
<li><strong>Data:</strong> CSV, XLSX (multi-sheet), JSON (formatted)</li>
<li><strong>Code:</strong> Syntax highlighting + line numbers</li>
<li><strong>Archives:</strong> ZIP browser with file extraction</li>
<li><strong>3D Models:</strong> GLB, GLTF, STL, OBJ (interactive viewer)</li>
<li><strong>Geospatial:</strong> GPX, KML map rendering</li>
<li><strong>Fonts:</strong> TTF, OTF, WOFF live preview</li>
<li><strong>Binary:</strong> Hex viewer with ASCII column</li>
</ul>

<hr>

<h2>Built-in Tools</h2>

<ul>
<li><strong>Converter</strong> – Base64, text transformations, 30+ conversions</li>
<li><strong>Diff Viewer</strong> – Side-by-side comparison</li>
<li><strong>Hash Checker</strong> – MD5, SHA1, SHA256</li>
<li><strong>QR Generator</strong> – Encode text to QR</li>
<li><strong>Text Tools</strong> – Sort, dedupe, word count</li>
<li><strong>Image Editor</strong> – Resize, crop, filters</li>
</ul>

<hr>

<h2>Architecture</h2>

<p>
This project is a single <code>index.html</code> file.
No build system. No backend. No dependencies to install.
</p>

<h3>Core Technologies</h3>

<ul>
<li>Vanilla JavaScript</li>
<li>FileReader API</li>
<li>Canvas API</li>
<li>WebAudio API</li>
<li>LocalStorage</li>
</ul>

<h3>External Libraries (CDN)</h3>

<ul>
<li>Three.js – 3D rendering</li>
<li>Leaflet – Map rendering</li>
<li>SheetJS – XLSX parsing</li>
<li>Mammoth.js – DOCX rendering</li>
<li>JSZip – ZIP browsing</li>
<li>QRCode.js – QR generation</li>
</ul>

<hr>

<h2>Privacy & Security</h2>

<ul>
<li>100% client-side</li>
<li>No uploads</li>
<li>No analytics</li>
<li>No tracking</li>
<li>No server processing</li>
</ul>

<hr>

<h2>Local Development</h2>

<pre>
git clone https://github.com/py0sc/FileViewer.git
cd FileViewer
open index.html
</pre>

<hr>

<h2>License</h2>

<p>MIT License</p>

<p>If this project is useful, consider starring the repository ⭐</p>
