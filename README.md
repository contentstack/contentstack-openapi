<img
  src="https://images.contentstack.io/v3/assets/bltc5a09bf374882538/blt8f67099538d234d7/600a87ac6215cf0f9a18c467/contentstack_icon.svg" />
<br>
<p>Contentstack provides OpenAPI files for its Content Delivery and Content Management REST APIs. These files are in
  JSON format. Using these JSON files, you can automatically generate API documentation, test API, and do a lot more.
</p>
<p>This tutorial will walk you through the process of using Contentstack APIs (Content Delivery and Content Management
  APIs) with Swagger.</p><br>
<h2>Content Delivery API (CDA)</h2>
<p>Version: 3.0.0 <a
    href="https://assets.contentstack.io/v3/assets/blt02f7b45378b008ee/bltcca6e1e737dabee0/cda-openapi-3.json?v=3.0.0&disposition=download">[Download]</a></p>
<p>Last Updated: Feb 06, 2023</p>
<p><strong>Note</strong>: To use the latest version, <a
    href="https://assets.contentstack.io/v3/assets/blt02f7b45378b008ee/bltcca6e1e737dabee0/cda-openapi-3.json?v=3.0.0&disposition=download">download
    the CDA file</a> on your system. </p>
<p>To use Contentstack Content Delivery API (CDA) with Swagger, perform the following steps: </p>
<ol>
  <li><a
      href="https://assets.contentstack.io/v3/assets/blt02f7b45378b008ee/bltcca6e1e737dabee0/cda-openapi-3.json?v=3.0.0&disposition=download">Download
      the CDA file</a> and go to the <a href="https://editor.swagger.io/">Swagger Editor</a>.</li>
  <li>On the “Swagger Editor” page, click on <strong>File</strong>, and select the <strong>Import file</strong> option.
  </li>
</ol>
<p>Alternatively, if you want to use the Import URL option, you can <a
    href="https://www.contentstack.com/docs/content-managers/working-with-assets/create-upload-assets/">upload the CDA
    file as an asset</a> in Contentstack, and then paste the asset’s URL in the prompt.</p>
<ol>
  <li>Open any API request and click on the <strong>Try it out </strong>button. Clicking this button will unlock the
    fields, so you can either run the API request on our demo stack or can use your own values.</li>
  <li>Click on <strong>Execute</strong>.</li>
</ol><br>
<p>In the <strong>Responses </strong>section, you can see the following details:</p>
<ul>
  <li>API request in CURL format</li>
  <li>Response body</li>
  <li>Status code </li>
</ul><br>
<h2>Content Management API</h2>
<p>Version: 3.0.0 <a
    href="https://assets.contentstack.io/v3/assets/blt02f7b45378b008ee/blt85399a97399b4ecf/cma-openapi-3.json?v=3.0.1&disposition=download">[Download]</a></p>
<p>Last Updated: Feb 06, 2023</p>
<p><strong>Note</strong>: To use the latest version, <a
    href="https://assets.contentstack.io/v3/assets/blt02f7b45378b008ee/blt85399a97399b4ecf/cma-openapi-3.json?v=3.0.1&disposition=download">download
    the CMA file</a> on your system. </p>
<p>To use Contentstack Content Management API (CMA) with Swagger, perform the following steps: </p>
<ol>
  <li><a
      href="https://assets.contentstack.io/v3/assets/blt02f7b45378b008ee/blt85399a97399b4ecf/cma-openapi-3.json?v=3.0.1&disposition=download">Download
      the CMA file</a> and go to the <a href="https://editor.swagger.io/">Swagger Editor</a>. </li>
  <li>On the “Swagger Editor” page, click on<strong> File</strong>, and select the <strong>Import file </strong>option.
  </li>
  <li>Alternatively, you can <a
      href="https://www.contentstack.com/docs/content-managers/working-with-assets/create-upload-assets/">upload the CMA
      file as an asset</a> in Contentstack. Then, you can use the <strong>Import URL</strong> option and paste the
    asset’s URL in the prompt. </li>
  <li>To run any API request for CMA, make sure you have either the Management token or Auth token in hand. <ol>
      <li>To use a management token, refer to the Generate Management token guide. </li>
      <li>To use Auth token, run the <strong>Login </strong>API request, located under the <strong>User Session
        </strong>section. </li>
    </ol>
  </li>
  <li>Open any API request and click on the <strong>Try it out</strong> button. Clicking this button will unlock the
    fields for you to use your enter the values. </li>
  <li>Click <strong>Execute</strong>.</li>
</ol><br>
<p>In the <strong>Responses </strong>section, you can see the following details:</p>
<ul>
  <li>API request in CURL format</li>
  <li>Response body</li>
  <li>Status code</li>
</ul>
<h2>Points to note:</h2>
<ul>
  <li>We recommend using the Management token for executing CMA requests rather than Auth token. </li>
  <li>For any DELETE request that has a request body in it, you won’t be able to run it in Swagger. In such scenarios,
    refer to the documentation link provided in the call for more details.</li>
</ul><br>