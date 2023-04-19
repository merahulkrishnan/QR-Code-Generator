<h1 align="center">QR Code Generator</h1>

<p align="center">This is a simple Python program that allows you to generate QR codes for any link using the <code>pyqrcode</code> library and display the generated QR code in a Tkinter window.</p>

<h2>Getting Started</h2>

<p>To use this program, you will need to have Python installed on your computer. You can download Python from the official website: <a href="https://www.python.org/downloads/">https://www.python.org/downloads/</a></p>

<p>You will also need to install the <code>pyqrcode</code> and <code>Pillow</code> libraries. You can install these libraries using pip:</p>

<pre><code>pip install pyqrcode Pillow</code></pre>

<h3>Cloning the Repository</h3>

<p>To clone this repository, run the following command in your terminal:</p>

<pre><code>git clone https://github.com/merahulkrishnan/QR-Code-Generator.git</code></pre>

<h2>Usage</h2>

<ol>
  <li>Run the <code>QR_code_generator.py</code> file.</li>
  <li>Enter a name for the link and the link URL in the text fields.</li>
  <li>Click the "Generate QR Code" button.</li>
  <li>The generated QR code will be displayed in the window.</li>
</ol>

<h2>Customization</h2>

<p>You can customize the position of the generated QR code in the Tkinter window by changing the <code>x</code> and <code>y</code> coordinates in the <code>canvas.create_window()</code> function in the <code>generate()</code> function.</p>

<h2>Technologies Used</h2>

<ul>
  <li>Python 3</li>
  <li>Tkinter</li>
  <li>pyqrcode</li>
  <li>Pillow</li>
</ul>

<h2>Contributing</h2>

<p>If you would like to contribute to this project, feel free to create a pull request.</p>
