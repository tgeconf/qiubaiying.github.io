<style>
  p{
    margin: .5em;
  }
</style>
<h2>What is Webpack</h2> 
<p>Webpack is a <b>module hundler</b>. It can be used to bundle your scripts, images, or styles.

<h2>Start to Use Webpack</h2>
<h4>Installation</h4>
<p>using npm to install
<pre style="background: #eee">npm install -g webpack</pre>

<h4>Warmup</h4>
<ol>
  <li>
    Generate package.json:<br/>
    <pre style="background: #eee">npm init</pre>
    then we add <i>scripts</i> in the end of package.json:
    <pre style="background: #eee">
      "scripts":{
        "dev":"cross-env NODE_ENV=development webpack",
        "opt":"cross-env NODE_ENV=production webpack"
      }
    </pre>
  </li>
  <li>
    install webpack as the dependent package<br/>
    <pre style="background: #eee">npm install --save-dev webpack</pre>
  </li>
  <li>
    create two folders "src" and "public", "src" is for the JS modules we are going to write and "public" is for the packed JS file.
  </li>
  <li>
    create webpack.config.js as the conf file to export JS file.
  </li>
  <li>
    bundle JS files:
    <pre style="background: #eee">npx webpack --config webpack.config.js</pre>
  </li>
</ol>
