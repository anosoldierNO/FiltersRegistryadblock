<h1>Welcome to the AG Filters Registry</h1>

<p>Discover the realm of AdGuard Filters Registry, your go-to source for curated filter subscriptions tailored for AdGuard users. At <code>filters.adtidy.org</code>, we host these invaluable filters, occasionally fine-tuned to enhance compatibility with AdGuard. Read on to dive into our filtering universe.</p>

<h2>Unlocking the Gate: Filter Additions</h2>

<p>Embracing third-party filters into the AdGuard Filters Registry follows a meticulous process that reflects our dedication to quality and user satisfaction. These are the guiding principles for admitting a third-party filter:</p>

<ol>
  <li><strong>Alignment with Browser Content Blockers:</strong> Filters should be designed for browser content blocking purposes.</li>
  <li><strong>Upholding Legality:</strong> Filters must abide by legal norms. Filters that engage in paywall circumvention are excluded.</li>
  <li><strong>Open Discussions:</strong> Filters should have channels for user feedback and discourse, such as GitHub repositories or public websites.</li>
  <li><strong>Popularity Matters:</strong> The popularity bar is set high:
    <ul>
      <li>If hosted on GitHub, a minimum of 50 stars is expected.</li>
      <li>For non-GitHub filters, an estimated 10 monthly interactions (issues and discussions) is a benchmark.</li>
      <li>Filters need to be actively maintained for at least 6 months.</li>
    </ul>
  </li>
  <li><strong>Regular Updates:</strong> Filters must receive at least 10 monthly updates to ensure current relevance.</li>
  <li><strong>Compatibility with AdGuard Products:</strong> Filters must align with AdGuard syntax, as outlined <a href="https://adguard.com/kb/general/ad-filtering/create-own-filters/">here</a>.</li>
  <li><strong>Selective Platform Inclusion:</strong> Filters working exclusively on certain platforms will be considered only for those supported platforms.</li>
  <li><strong>Timely Maintenance:</strong> Filters not updated or supported for a year will be considered for removal, with possible exceptions.</li>
  <li><strong>Problematic Rule Scrutiny:</strong> Filters must avoid problematic rules that lead to false positives or undesirable behavior. Rules blocking access solely based on personal opinion won't be entertained.</li>
  <li><strong>Local Popularity:</strong> Filters catering to specific regions without alternatives may be included as-is.</li>
  <li><strong>Trust Levels:</strong> Filters are assigned trust levels (Low, High, Full) based on rule quality. Filters below "Full" trust may have specific rules disabled, with the potential for review and upgrade.</li>
  <li><strong>Duplicates and Conflicts:</strong> Similar filters can coexist if they offer value and don't replicate or conflict excessively.</li>
</ol>

<h2>Unveiling Filter Metadata</h2>

<ul>
  <li><code>template.txt</code>: A blueprint for the final filter version, essential for filter compilation.</li>
  <li><code>exclude.txt</code>: Houses a set of regular expressions. Rules matching these are excluded from the final filter.</li>
  <li><code>metadata.json</code>: Filter metadata encompasses details like name, description, and more.</li>
  <li><code>revision.json</code>: Records filter version metadata, updated with each build.</li>
  <li><code>filter.txt</code>: The optimized compiled filter, stripped of unused rules.</li>
  <li><code>diff.txt</code>: A build log containing excluded and converted rules.</li>
</ul>

<h2>Lend Your Voice: Filter Localization</h2>

<p>Enrich our filtering landscape by contributing to filter translations on Crowdin. Join us on <a href="https://crowdin.com/project/adguard-applications/en#/miscellaneous/filters-registry">Crowdin</a> to help bring AdGuard's filters to diverse languages.</p>

<h2>Crafting Custom Filters</h2>

<p>Harness the power of <code>@include</code> directives to seamlessly integrate external content into filters. Customize filter builds using <code>/notOptimized</code> to retain rules during optimization.</p>

<h2>The Building Symphony</h2>

<p>To embark on our journey:</p>

<ol>
  <li>Install the required dependencies with <code>yarn install</code>.</li>
  <li>Execute <code>node index.js</code>.</li>
</ol>

<p>For advanced users, customize builds with white/black lists using the <code>-i</code> and <code>-s</code> parameters.</p>

<h2>Embrace the Filtering Odyssey</h2>

<p>The AG Filters Registry is your gateway to a refined filtering experience. Embrace our meticulously curated filters, tailored to perfection. Let's enhance your browsing journey together.</p>
