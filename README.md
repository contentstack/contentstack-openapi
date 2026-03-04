<img
  src="https://images.contentstack.io/v3/assets/blt2d43f51baca745a8/blt2c341bd633887e37/Contentstack-LogoLockup-AmethystShadowHeavy-RGB.png" />
<br>
<p>
Contentstack provides OpenAPI files for its <a href="https://www.contentstack.com/docs/developers/apis/content-delivery-api">Content Delivery</a> and <a href="https://www.contentstack.com/docs/developers/apis/content-management-api">Content Management</a> APIs in JSON format. These files allow you to automatically generate API documentation, test requests, and streamline your development workflow.
</p>
<p>
This tutorial walks you through how to use these JSON files with Swagger Editor to interact with Contentstack’s APIs.
</p>
<h2>Content Delivery API (CDA)</h2>


<p>
To use CDA with Swagger, follow these steps:
</p>
<ol>

<li><a href="https://assets.contentstack.io/v3/assets/blt02f7b45378b008ee/bltcca6e1e737dabee0/cda-openapi-3.json?v=3.0.0&disposition=download">Download the latest CDA JSON file</a> and navigate to <a href="https://editor.swagger.io/">Swagger Editor</a>.</li>

<li>Click <strong>File</strong> on top-right and select <strong>Import File</strong> to upload the JSON.</li>

<li>Open any API request and click the <strong>Try it out</strong> button to unlock the parameter fields.</li>

<li>Enter your stack's values or use the default demo stack credentials.</li>

<li>Click <strong>Execute</strong>.</li>
</ol>
<p>
The <strong>Responses</strong> section will display the following:
</p>
<ul>

<li>The API request in cURL format.</li>

<li>The response body (JSON).</li>

<li>The HTTP status code.</li>
</ul>
<p>
<strong>Note</strong>: To ensure you are testing against the most accurate environment, always download the latest CDA file from the Contentstack documentation site.
</p>
<h2>Content Management API (CMA)</h2>


<p>
To use CDA with Swagger, follow these steps:
</p>
<ol>

<li><a href="https://assets.contentstack.io/v3/assets/blt02f7b45378b008ee/blt85399a97399b4ecf/cma-openapi-3.json?v=3.0.1&disposition=download">Download the latest CMA JSON file</a> and navigate to <a href="https://editor.swagger.io/">Swagger Editor</a>.</li>

<li>Click <strong>File</strong> on top-right and select <strong>Import File</strong> to upload the JSON.</li>

<li>Before running a request, ensure you have an authentication method ready:</li>

<li><strong>Management Token</strong>: We recommend using a management token for CMA requests. Refer to the <a href="https://www.contentstack.com/docs/developers/create-tokens/generate-a-management-token">Generate Management Token</a> guide for details.</li>

<li><strong>Authtoken</strong>: Run the <a href="https://www.contentstack.com/docs/developers/apis/content-management-api#log-in-to-your-account">Log in API request</a> under the <strong>User Session</strong> section to retrieve an <code>authtoken</code> in the response.</li>

<li>Open any API request and click the <strong>Try it out</strong> button to unlock the parameter fields.</li>

<li>Enter your stack's values or use the default demo stack credentials.</li>

<li>Click <strong>Execute</strong>.</li>
</ol>
<p>
The <strong>Responses</strong> section will display the following:
</p>
<ul>

<li>The API request in cURL format.</li>

<li>The response body (JSON).</li>

<li>The HTTP status code.</li>
</ul>
<p>
<strong>Note</strong>:
</p>
<ul>

<li>We recommend using the Management token for executing CMA requests rather than authtoken.</li>

<li>For any DELETE request that has a request body in it, you won’t be able to run it in Swagger.</li></ul
