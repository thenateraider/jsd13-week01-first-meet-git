# Product Requirement Document

## HTML Tag Library & Usage for PRD

### 1. Headings (`<h1>` – `<h6>`)
Used for document structure and hierarchy.

```html
<h1>Document Title</h1>
<h2>Section Title</h2>
<h3>Sub-section Title</h3>
```

### 2. Paragraph (`<p>`)
Used for body text, descriptions, and requirements.

```html
<p>The system shall allow users to log in using email and password.</p>
```

### 3. Lists (`<ul>`, `<ol>`, `<li>`)
Used for feature lists, acceptance criteria, and steps.

```html
<ul>
  <li>User authentication</li>
  <li>Profile management</li>
  <li>Payment processing</li>
</ul>

<ol>
  <li>Open the application</li>
  <li>Enter credentials</li>
  <li>Click Login</li>
</ol>
```

### 4. Tables (`<table>`, `<tr>`, `<th>`, `<td>`)
Used for comparing features, specifications, or data mapping.

```html
<table>
  <tr>
    <th>Feature</th>
    <th>Priority</th>
    <th>Status</th>
  </tr>
  <tr>
    <td>Login</td>
    <td>High</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>Search</td>
    <td>Medium</td>
    <td>In Progress</td>
  </tr>
</table>
```

### 5. Links (`<a>`)
Used for referencing external docs, designs, or APIs.

```html
<a href="https://example.com/api-docs">API Documentation</a>
```

### 6. Images (`<img>`)
Used for wireframes, mockups, and diagrams.

```html
<img src="wireframe-login.png" alt="Login Screen Wireframe" width="600">
```

### 7. Text Formatting (`<strong>`, `<em>`, `<code>`)
Used for emphasis and inline code references.

```html
<p>This is a <strong>critical</strong> requirement.</p>
<p><em>Note:</em> This applies only to admin users.</p>
<p>Use the <code>authenticate()</code> method to verify credentials.</p>
```

### 8. Blockquotes (`<blockquote>`)
Used for quoting stakeholders or important notes.

```html
<blockquote>
  "The dashboard must load within 2 seconds." — Product Owner
</blockquote>
```

### 9. Code Blocks (`<pre><code>`)
Used for API examples, configs, or technical specs.

```html
<pre><code>
POST /api/login
{
  "email": "user@example.com",
  "password": "********"
}
</code></pre>
```

### 10. Divisions (`<div>`) & Spans (`<span>`)
Used for layout and inline grouping.

```html
<div class="requirement">
  <span class="priority high">High</span>
  <span>Implement OAuth 2.0</span>
</div>
```

---

## Example PRD Snippet Using HTML Tags

```html
<h1>PRD: E-Commerce Platform v2.0</h1>

<h2>1. Overview</h2>
<p>The platform will support <strong>multi-vendor</strong> selling with real-time inventory tracking.</p>

<h2>2. Features</h2>
<ul>
  <li>Vendor dashboard</li>
  <li>Order management</li>
  <li>Payment gateway integration</li>
</ul>

<h2>3. Acceptance Criteria</h2>
<ol>
  <li>Vendor can list up to 100 products</li>
  <li>Orders sync within 30 seconds</li>
  <li>Support PayPal and Stripe</li>
</ol>

<h2>4. Wireframe</h2>
<img src="mockup-dashboard.png" alt="Vendor Dashboard Mockup">

<h2>5. API Reference</h2>
<pre><code>GET /api/v1/products
Authorization: Bearer {token}</code></pre>
```
