


<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>Reproducible-Research/PA1_template.md at master · shainadel/Reproducible-Research · GitHub</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="shainadel/Reproducible-Research" name="twitter:title" /><meta content="Reproducible-Research - Reproducible Research Peer Assessment 1" name="twitter:description" /><meta content="https://avatars3.githubusercontent.com/u/10096299?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars3.githubusercontent.com/u/10096299?v=3&amp;s=400" property="og:image" /><meta content="shainadel/Reproducible-Research" property="og:title" /><meta content="https://github.com/shainadel/Reproducible-Research" property="og:url" /><meta content="Reproducible-Research - Reproducible Research Peer Assessment 1" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    
    <meta name="pjax-timeout" content="1000">
    

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

        <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="4FB4A882:0553:1384F007:55AC072E" name="octolytics-dimension-request_id" />
    
    <meta content="Rails, view, blob#show" data-pjax-transient="true" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged Out">
    <meta name="is-dotcom" content="true">
      <meta name="hostname" content="github.com">
    <meta name="user-login" content="">

      <link rel="icon" sizes="any" mask href="https://assets-cdn.github.com/pinned-octocat.svg">
      <meta name="theme-color" content="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="zRbj6tjOwc0b5w8659aBulyrdrhMnI2ruLDmOsKoj+N3UQFlne1s3XXiW0yrOb4k1JxdRyoggFZQ/NrhS3vxSA==" name="csrf-token" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github/index-8824a5ef57ac4ae0b5ca429778b9660b1c66d09deea2ff11681de18d86a4bbb1.css" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2/index-f0d033a37796c27f6b5b24aa8dc21af9c206a51ed2fe782d660dc20267c17d2b.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="8ba97455ee93c7e28f6153eb82266087">

      
  <meta name="description" content="Reproducible-Research - Reproducible Research Peer Assessment 1">
  <meta name="go-import" content="github.com/shainadel/Reproducible-Research git https://github.com/shainadel/Reproducible-Research.git">

  <meta content="10096299" name="octolytics-dimension-user_id" /><meta content="shainadel" name="octolytics-dimension-user_login" /><meta content="39332669" name="octolytics-dimension-repository_id" /><meta content="shainadel/Reproducible-Research" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="39332669" name="octolytics-dimension-repository_network_root_id" /><meta content="shainadel/Reproducible-Research" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/shainadel/Reproducible-Research/commits/master.atom" rel="alternate" title="Recent Commits to Reproducible-Research:master" type="application/atom+xml">

  </head>


  <body class="logged_out  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      



        
        <div class="header header-logged-out" role="banner">
  <div class="container clearfix">

    <a class="header-logo-wordmark" href="https://github.com/" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
      <span class="mega-octicon octicon-logo-github"></span>
    </a>

    <div class="header-actions" role="navigation">
        <a class="btn btn-primary" href="/join" data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">Sign up</a>
      <a class="btn" href="/login?return_to=%2Fshainadel%2FReproducible-Research%2Fblob%2Fmaster%2FPA1_template.md" data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">Sign in</a>
    </div>

    <div class="site-search repo-scope js-site-search" role="search">
      <form accept-charset="UTF-8" action="/shainadel/Reproducible-Research/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/shainadel/Reproducible-Research/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
    </div>

      <ul class="header-nav left" role="navigation">
          <li class="header-nav-item">
            <a class="header-nav-link" href="/explore" data-ga-click="(Logged out) Header, go to explore, text:explore">Explore</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/features" data-ga-click="(Logged out) Header, go to features, text:features">Features</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://enterprise.github.com/" data-ga-click="(Logged out) Header, go to enterprise, text:enterprise">Enterprise</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/blog" data-ga-click="(Logged out) Header, go to blog, text:blog">Blog</a>
          </li>
      </ul>

  </div>
</div>



      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">

        
<ul class="pagehead-actions">

  <li>
      <a href="/login?return_to=%2Fshainadel%2FReproducible-Research"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to watch a repository" rel="nofollow">
    <span class="octicon octicon-eye"></span>
    Watch
  </a>
  <a class="social-count" href="/shainadel/Reproducible-Research/watchers">
    1
  </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fshainadel%2FReproducible-Research"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to star a repository" rel="nofollow">
    <span class="octicon octicon-star"></span>
    Star
  </a>

    <a class="social-count js-social-count" href="/shainadel/Reproducible-Research/stargazers">
      0
    </a>

  </li>

    <li>
      <a href="/login?return_to=%2Fshainadel%2FReproducible-Research"
        class="btn btn-sm btn-with-count tooltipped tooltipped-n"
        aria-label="You must be signed in to fork a repository" rel="nofollow">
        <span class="octicon octicon-repo-forked"></span>
        Fork
      </a>
      <a href="/shainadel/Reproducible-Research/network" class="social-count">
        0
      </a>
    </li>
</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/shainadel" class="url fn" itemprop="url" rel="author"><span itemprop="title">shainadel</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/shainadel/Reproducible-Research" data-pjax="#js-repo-pjax-container">Reproducible-Research</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/shainadel/Reproducible-Research/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/shainadel/Reproducible-Research" aria-label="Code" aria-selected="true" class="js-selected-navigation-item selected sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /shainadel/Reproducible-Research">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/shainadel/Reproducible-Research/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /shainadel/Reproducible-Research/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/shainadel/Reproducible-Research/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /shainadel/Reproducible-Research/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/shainadel/Reproducible-Research/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /shainadel/Reproducible-Research/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/shainadel/Reproducible-Research/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /shainadel/Reproducible-Research/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                  
<div class="js-clone-url clone-url open"
  data-protocol-type="http">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/shainadel/Reproducible-Research.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="subversion">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/shainadel/Reproducible-Research" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<div class="clone-options">You can clone with
  <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone" class="inline-form js-clone-selector-form " data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="BiSt96omEwBYf5xANTKlCaS97iwCOKBdABXi2jTRf46+83ZQfsn6kNY7AV/QWhp5AAKhCw6SXF4ZnmKWYITSeQ==" /></div><button class="btn-link js-clone-selector" data-protocol="http" type="submit">HTTPS</button></form> or <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone" class="inline-form js-clone-selector-form " data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="XTTIgQrPlRot/ZKJyM+9r8a6LDdMCFDCLipDbJeQcDxG9sjsdK6F962WJoCUfyqpijP0HQSRBkc/bcQLWFQeZQ==" /></div><button class="btn-link js-clone-selector" data-protocol="subversion" type="submit">Subversion</button></form>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</div>


  <a href="https://windows.github.com" class="btn btn-sm sidebar-button" title="Save shainadel/Reproducible-Research to your computer and use it in GitHub Desktop." aria-label="Save shainadel/Reproducible-Research to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>


                <a href="/shainadel/Reproducible-Research/archive/master.zip"
                   class="btn btn-sm sidebar-button"
                   aria-label="Download the contents of shainadel/Reproducible-Research as a zip file"
                   title="Download the contents of shainadel/Reproducible-Research as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

          

<a href="/shainadel/Reproducible-Research/blob/02b9ed8d52dd30fbdefa600fd5df711e0d257a0f/PA1_template.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:edb88aa4bbcb91aec4b7872cb73840cb -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/shainadel/Reproducible-Research/blob/master/PA1_template.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="btn-group right">
    <a href="/shainadel/Reproducible-Research/find/master"
          class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/shainadel/Reproducible-Research" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">Reproducible-Research</span></a></span></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
  </div>
</div>

<include-fragment class="commit commit-loader file-history-tease" src="/shainadel/Reproducible-Research/contributors/master/PA1_template.md">
  <div class="file-history-tease-header">
    Fetching contributors&hellip;
  </div>

  <div class="participation">
    <p class="loader-loading"><img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32-EAF2F5.gif" width="16" /></p>
    <p class="loader-error">Cannot retrieve contributors at this time</p>
  </div>
</include-fragment>
<div class="file">
  <div class="file-header">
    <div class="file-actions">

      <div class="btn-group">
        <a href="/shainadel/Reproducible-Research/raw/master/PA1_template.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/shainadel/Reproducible-Research/blame/master/PA1_template.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/shainadel/Reproducible-Research/commits/master/PA1_template.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="https://windows.github.com"
           aria-label="Open this file in GitHub for Windows"
           data-ga-click="Repository, open with desktop, type:windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

          <button type="button" class="octicon-btn disabled tooltipped tooltipped-n" aria-label="You must be signed in to make or propose changes">
            <span class="octicon octicon-pencil"></span>
          </button>

        <button type="button" class="octicon-btn octicon-btn-danger disabled tooltipped tooltipped-n" aria-label="You must be signed in to make or propose changes">
          <span class="octicon octicon-trashcan"></span>
        </button>
    </div>

    <div class="file-info">
        198 lines (147 sloc)
        <span class="file-info-divider"></span>
      5.38 kB
    </div>
  </div>
  
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><table data-table-type="yaml-metadata">
  <thead>
  <tr>
  <th>title</th>

  <th>output</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div>Activity Monitoring Data Analysis</div></td>

  <td><div>html_document</div></td>
  </tr>
  </tbody>
</table>

<p>This is an analisys of activity monitor collected data .
The data for this analysis can be downloaded from <a href="https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip">https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip</a>.</p>

<p>After download and extraction, loading the file:</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">amd</span> <span class="pl-k">&lt;-</span> read.csv(<span class="pl-s"><span class="pl-pds">"</span>activity.csv<span class="pl-pds">"</span></span>)</pre></div>

<pre><code>## Warning in file(file, "rt"): cannot open file 'activity.csv': No such file
## or directory
</code></pre>

<pre><code>## Error in file(file, "rt"): cannot open the connection
</code></pre>

<h2><a id="user-content-daily-steps" class="anchor" href="#daily-steps" aria-hidden="true"><span class="octicon octicon-link"></span></a>Daily Steps</h2>

<p>The number of daily steps is calculated by:</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">days</span> <span class="pl-k">&lt;-</span> levels(<span class="pl-smi">amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>date<span class="pl-pds">"</span></span>)
<span class="pl-smi">daily_steps</span> <span class="pl-k">&lt;-</span> vector(<span class="pl-v">length</span> <span class="pl-k">=</span> length(<span class="pl-smi">days</span>), <span class="pl-v">mode</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>numeric<span class="pl-pds">"</span></span>)
<span class="pl-smi">index</span> <span class="pl-k">&lt;-</span> <span class="pl-c1">1</span>
<span class="pl-k">for</span>(<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-smi">days</span>)
{
    <span class="pl-smi">daily_steps</span>[<span class="pl-smi">index</span>] <span class="pl-k">&lt;-</span> sum(<span class="pl-smi">amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>steps<span class="pl-pds">"</span></span>[<span class="pl-smi">amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>date<span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-smi">i</span>], <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
    <span class="pl-smi">index</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">index</span> <span class="pl-k">+</span> <span class="pl-c1">1</span>
}</pre></div>

<p>A histogram for the number of daily steps is plotted by:</p>

<div class="highlight highlight-r"><pre>hist(<span class="pl-smi">daily_steps</span>, <span class="pl-v">col</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>RED<span class="pl-pds">"</span></span>, <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Number of steps per day<span class="pl-pds">"</span></span>, <span class="pl-v">main</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Daily Steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/shainadel/Reproducible-Research/blob/master/figure/unnamed-chunk-3-1.png" target="_blank"><img src="/shainadel/Reproducible-Research/raw/master/figure/unnamed-chunk-3-1.png" alt="plot of chunk unnamed-chunk-3" style="max-width:100%;"></a> </p>

<p>And the mean and media are calculated by:</p>

<div class="highlight highlight-r"><pre>print(paste(<span class="pl-s"><span class="pl-pds">"</span>The mean number of daily steps is<span class="pl-pds">"</span></span>,
            toString(mean(<span class="pl-smi">daily_steps</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)),
            <span class="pl-s"><span class="pl-pds">"</span>and the median is<span class="pl-pds">"</span></span>,
            toString(median(<span class="pl-smi">daily_steps</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>))))</pre></div>

<pre><code>## [1] "The mean number of daily steps is 9354.22950819672 and the median is 10395"
</code></pre>

<h2><a id="user-content-interval-average" class="anchor" href="#interval-average" aria-hidden="true"><span class="octicon octicon-link"></span></a>Interval Average</h2>

<p>The average number of steps in a given 5 minute interval in the day is calculated by:</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">intervals</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>interval<span class="pl-pds">"</span></span>[<span class="pl-smi">amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>date<span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-smi">amd</span>[<span class="pl-c1">1</span>,<span class="pl-c1">2</span>]]
<span class="pl-smi">avg_interval_steps</span> <span class="pl-k">&lt;-</span> vector(<span class="pl-v">length</span> <span class="pl-k">=</span> length(<span class="pl-smi">intervals</span>), <span class="pl-v">mode</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>numeric<span class="pl-pds">"</span></span>)
<span class="pl-smi">index</span> <span class="pl-k">&lt;-</span> <span class="pl-c1">1</span>
<span class="pl-k">for</span>(<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-smi">intervals</span>)
{
    <span class="pl-smi">avg_interval_steps</span>[<span class="pl-smi">index</span>] <span class="pl-k">&lt;-</span> mean(<span class="pl-smi">amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>steps<span class="pl-pds">"</span></span>[<span class="pl-smi">amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>interval<span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-smi">i</span>], <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
    <span class="pl-smi">index</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">index</span> <span class="pl-k">+</span> <span class="pl-c1">1</span>
}</pre></div>

<p>The average number of steps changes along the daily intervals like so:</p>

<div class="highlight highlight-r"><pre>plot( <span class="pl-smi">intervals</span>, <span class="pl-smi">avg_interval_steps</span>, <span class="pl-v">type</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>, <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Daily interval<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Average number of steps<span class="pl-pds">"</span></span> )</pre></div>

<p><a href="/shainadel/Reproducible-Research/blob/master/figure/unnamed-chunk-6-1.png" target="_blank"><img src="/shainadel/Reproducible-Research/raw/master/figure/unnamed-chunk-6-1.png" alt="plot of chunk unnamed-chunk-6" style="max-width:100%;"></a> </p>

<p>The daily 5 minute interval with the maximum average steps is:</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">intervals</span>[<span class="pl-smi">avg_interval_steps</span> <span class="pl-k">==</span> max(<span class="pl-smi">avg_interval_steps</span>)]</pre></div>

<pre><code>## [1] 835
</code></pre>

<h2><a id="user-content-missing-values" class="anchor" href="#missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>Missing Values</h2>

<p>Counting the missing values in the dataset:</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">missing_steps</span> <span class="pl-k">&lt;-</span> sum(is.na(<span class="pl-smi">amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>steps<span class="pl-pds">"</span></span>))
<span class="pl-smi">missing_dates</span> <span class="pl-k">&lt;-</span> sum(is.na(<span class="pl-smi">amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>date<span class="pl-pds">"</span></span>))
<span class="pl-smi">missing_intervals</span> <span class="pl-k">&lt;-</span> sum(is.na(<span class="pl-smi">amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>interval<span class="pl-pds">"</span></span>))</pre></div>

<p>There are 2304 missing values in the "steps" column, 0 missing values in the "dates" column and 0 missing values in the "intervals" column.</p>

<p>The interval's average number of steps will be used to fill in for a missing value in the "steps" column.</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">filled_amd</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">amd</span>
<span class="pl-k">for</span> ( <span class="pl-smi">i</span> <span class="pl-k">in</span> c(<span class="pl-c1">1</span><span class="pl-k">:</span>length(<span class="pl-smi">filled_amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>steps<span class="pl-pds">"</span></span>)) )
{
    <span class="pl-k">if</span>(is.na(<span class="pl-smi">filled_amd</span>[<span class="pl-smi">i</span>,<span class="pl-c1">1</span>]))
    {
        <span class="pl-smi">filled_amd</span>[<span class="pl-smi">i</span>,<span class="pl-c1">1</span>] <span class="pl-k">&lt;-</span> <span class="pl-smi">avg_interval_steps</span>[<span class="pl-smi">intervals</span> <span class="pl-k">==</span> <span class="pl-smi">filled_amd</span>[<span class="pl-smi">i</span>,<span class="pl-c1">3</span>]]
    }
}</pre></div>

<h2><a id="user-content-daily-steps-with-filled-in-missing-values" class="anchor" href="#daily-steps-with-filled-in-missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>Daily Steps With Filled-In Missing Values</h2>

<p>The number of daily steps is calculated by:</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">days</span> <span class="pl-k">&lt;-</span> levels(<span class="pl-smi">filled_amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>date<span class="pl-pds">"</span></span>)
<span class="pl-smi">daily_steps</span> <span class="pl-k">&lt;-</span> vector(<span class="pl-v">length</span> <span class="pl-k">=</span> length(<span class="pl-smi">days</span>), <span class="pl-v">mode</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>numeric<span class="pl-pds">"</span></span>)
<span class="pl-smi">index</span> <span class="pl-k">&lt;-</span> <span class="pl-c1">1</span>
<span class="pl-k">for</span>(<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-smi">days</span>)
{
    <span class="pl-smi">daily_steps</span>[<span class="pl-smi">index</span>] <span class="pl-k">&lt;-</span> sum(<span class="pl-smi">filled_amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>steps<span class="pl-pds">"</span></span>[<span class="pl-smi">filled_amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>date<span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-smi">i</span>], <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
    <span class="pl-smi">index</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">index</span> <span class="pl-k">+</span> <span class="pl-c1">1</span>
}</pre></div>

<p>A histogram for the number of daily steps is plotted by:</p>

<div class="highlight highlight-r"><pre>hist(<span class="pl-smi">daily_steps</span>, <span class="pl-v">col</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>RED<span class="pl-pds">"</span></span>, <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Number of steps per day<span class="pl-pds">"</span></span>, <span class="pl-v">main</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Daily Steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/shainadel/Reproducible-Research/blob/master/figure/unnamed-chunk-11-1.png" target="_blank"><img src="/shainadel/Reproducible-Research/raw/master/figure/unnamed-chunk-11-1.png" alt="plot of chunk unnamed-chunk-11" style="max-width:100%;"></a> </p>

<p>And the mean and media are calculated by:</p>

<div class="highlight highlight-r"><pre>print(paste(<span class="pl-s"><span class="pl-pds">"</span>The mean number of daily steps is<span class="pl-pds">"</span></span>,
            toString(mean(<span class="pl-smi">daily_steps</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)),
            <span class="pl-s"><span class="pl-pds">"</span>and the median is<span class="pl-pds">"</span></span>,
            toString(median(<span class="pl-smi">daily_steps</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>))))</pre></div>

<pre><code>## [1] "The mean number of daily steps is 10766.1886792453 and the median is 10766.1886792453"
</code></pre>

<p>Both the average daily steps, as well as the median are much higher when missing values are filled in using their interval daily average.</p>

<h2><a id="user-content-the-difference-in-activity-patterns-between-weekdays-and-weekends" class="anchor" href="#the-difference-in-activity-patterns-between-weekdays-and-weekends" aria-hidden="true"><span class="octicon octicon-link"></span></a>The Difference in Activity Patterns Between Weekdays and Weekends</h2>

<p>To answer this question the dataset will be expanded with a logical column for weekday/weekend.</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">weekend_day</span> <span class="pl-k">&lt;-</span> weekdays(as.Date(<span class="pl-smi">filled_amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>date<span class="pl-pds">"</span></span>)) <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">"</span>Saturday<span class="pl-pds">"</span></span> <span class="pl-k">|</span> weekdays(as.Date(<span class="pl-smi">filled_amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>date<span class="pl-pds">"</span></span>)) <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">"</span>Sunday<span class="pl-pds">"</span></span>
<span class="pl-smi">xp_amd</span> <span class="pl-k">&lt;-</span> cbind(<span class="pl-smi">filled_amd</span>, <span class="pl-smi">weekend_day</span>)</pre></div>

<p>The average steps per interval are caluculate by weekday/weekend:</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">wd_avg_interval_steps</span> <span class="pl-k">&lt;-</span> vector(<span class="pl-v">length</span> <span class="pl-k">=</span> length(<span class="pl-smi">intervals</span>), <span class="pl-v">mode</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>numeric<span class="pl-pds">"</span></span>)
<span class="pl-smi">we_avg_interval_steps</span> <span class="pl-k">&lt;-</span> vector(<span class="pl-v">length</span> <span class="pl-k">=</span> length(<span class="pl-smi">intervals</span>), <span class="pl-v">mode</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>numeric<span class="pl-pds">"</span></span>)
<span class="pl-smi">wd_logical</span> <span class="pl-k">&lt;-</span> vector(<span class="pl-v">length</span> <span class="pl-k">=</span> length(<span class="pl-smi">intervals</span>), <span class="pl-v">mode</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>logical<span class="pl-pds">"</span></span>)
<span class="pl-smi">we_logical</span> <span class="pl-k">&lt;-</span> vector(<span class="pl-v">length</span> <span class="pl-k">=</span> length(<span class="pl-smi">intervals</span>), <span class="pl-v">mode</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>logical<span class="pl-pds">"</span></span>)
<span class="pl-smi">index</span> <span class="pl-k">&lt;-</span> <span class="pl-c1">1</span>
<span class="pl-k">for</span>(<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-smi">intervals</span>)
{
    <span class="pl-smi">wd_avg_interval_steps</span>[<span class="pl-smi">index</span>] <span class="pl-k">&lt;-</span> mean(<span class="pl-smi">xp_amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>steps<span class="pl-pds">"</span></span>[<span class="pl-smi">xp_amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>interval<span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-smi">i</span> <span class="pl-k">&amp;</span> <span class="pl-smi">xp_amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>weekend_day<span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-c1">FALSE</span>], <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
    <span class="pl-smi">we_avg_interval_steps</span>[<span class="pl-smi">index</span>] <span class="pl-k">&lt;-</span> mean(<span class="pl-smi">xp_amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>steps<span class="pl-pds">"</span></span>[<span class="pl-smi">xp_amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>interval<span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-smi">i</span> <span class="pl-k">&amp;</span> <span class="pl-smi">xp_amd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>weekend_day<span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-c1">TRUE</span>], <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
    <span class="pl-smi">wd_logical</span>[<span class="pl-smi">index</span>] <span class="pl-k">&lt;-</span> <span class="pl-c1">TRUE</span>
    <span class="pl-smi">we_logical</span>[<span class="pl-smi">index</span>] <span class="pl-k">&lt;-</span> <span class="pl-c1">FALSE</span>
    <span class="pl-smi">index</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">index</span> <span class="pl-k">+</span> <span class="pl-c1">1</span>
}

<span class="pl-smi">avg_interval_steps_wd</span> <span class="pl-k">&lt;-</span> <span class="pl-k">data.frame</span>(c(<span class="pl-smi">wd_avg_interval_steps</span>,<span class="pl-smi">we_avg_interval_steps</span>),c(<span class="pl-smi">wd_logical</span>,<span class="pl-smi">we_logical</span>))
colnames(<span class="pl-smi">avg_interval_steps_wd</span>) <span class="pl-k">&lt;-</span> c(<span class="pl-s"><span class="pl-pds">"</span>avg<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>is.weekday<span class="pl-pds">"</span></span>)</pre></div>

<p>And a density plot is made:</p>

<div class="highlight highlight-r"><pre>library(<span class="pl-smi">lattice</span>)
densityplot(<span class="pl-k">~</span><span class="pl-smi">avg_interval_steps_wd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>avg<span class="pl-pds">"</span></span><span class="pl-k">|</span><span class="pl-smi">avg_interval_steps_wd</span><span class="pl-k">$</span><span class="pl-s"><span class="pl-pds">"</span>is.weekday<span class="pl-pds">"</span></span>, 
            <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Density Plot by weekday<span class="pl-pds">"</span></span>,
            <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Average interval steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/shainadel/Reproducible-Research/blob/master/figure/unnamed-chunk-15-1.png" target="_blank"><img src="/shainadel/Reproducible-Research/raw/master/figure/unnamed-chunk-15-1.png" alt="plot of chunk unnamed-chunk-15" style="max-width:100%;"></a> </p>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.05770s from github-fe125-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-3241a40a58a82e21daef3dd3cdca01bde189158793c1b6f9193fff2b5293cd1d.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github/index-93799dc3b48721586da77cc7c73632bc4fb8e157356876ec160370ab6be81349.js"></script>
      
      
  </body>
</html>

