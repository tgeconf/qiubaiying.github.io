#How to use Webpack to combine multiple JS files

<h2>What is Webpack</h2> 
<p>Webpack is a <b>module hundler</b>

<h2>Start to Use Webpack</h2>
<p><b>Installation</b>
<p>using npm to install
<p>npm install -g webpack

<p><b>Warmup</b>
<ol>
  <li>
    generate package.json:<br/>
    npm init
  </li>
  <li>
    install webpack as the dependent package<br/>
    npm install --save-dev webpack
  </li>
  <li>
    create two folders "src" and "public", "src" is for the JS modules we are going to write and "public" is for the packed JS file.
  </li>
  <li>
    create webpack.config.js as the conf file to export JS file.
  </li>
  <li>
    npx webpack --config webpack.config.js  
  </li>
</ol>
