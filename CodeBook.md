


<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>R/CodeBook.md at master · joellove/R</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="joellove/R" name="twitter:title" /><meta content="Contribute to R development by creating an account on GitHub." name="twitter:description" /><meta content="https://avatars2.githubusercontent.com/u/3461427?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars2.githubusercontent.com/u/3461427?v=3&amp;s=400" property="og:image" /><meta content="joellove/R" property="og:title" /><meta content="https://github.com/joellove/R" property="og:url" /><meta content="Contribute to R development by creating an account on GitHub." property="og:description" />
      <meta name="browser-stats-url" content="/_stats">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="xhr-socket" href="/_sockets">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="B6E1AAED:4528:2AB683:550ED6A3" name="octolytics-dimension-request_id" /><meta content="10575513" name="octolytics-actor-id" /><meta content="seonsu" name="octolytics-actor-login" /><meta content="8370db6795ef6da5a31d63fa3adab35ee33cb0d31a203cdac33f24cb676ca66e" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />

    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="hnqkPjJfVFY5h/oQMGgkUZxeNo5Zo+ieWh6HHGhzKQcLEdBK0Evjr4oCFxWjiAs8musk+mq5kkfSc6j4o+h6Ag==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github-099e0ecc2851c8aca89ef6dafa191df3b0f2a2c8ad34e134c5473ca1ba0a59b2.css" media="all" rel="stylesheet" />
    <link href="https://assets-cdn.github.com/assets/github2-1171344316fc088255ee2a06c271d14240f1a4e06985fe9e897762947872e858.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="c0f32272c66bfb10ed7d46b7c88c6299">

      
  <meta name="description" content="Contribute to R development by creating an account on GitHub.">
  <meta name="go-import" content="github.com/joellove/R git https://github.com/joellove/R.git">

  <meta content="3461427" name="octolytics-dimension-user_id" /><meta content="joellove" name="octolytics-dimension-user_login" /><meta content="18982095" name="octolytics-dimension-repository_id" /><meta content="joellove/R" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="18982095" name="octolytics-dimension-repository_network_root_id" /><meta content="joellove/R" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/joellove/R/commits/master.atom" rel="alternate" title="Recent Commits to R:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      


        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/joellove/R/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/joellove/R/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <input type="text"
    class="js-site-search-field is-clearable"
    data-hotkey="s"
    name="q"
    placeholder="Search"
    data-global-scope-placeholder="Search GitHub"
    data-repo-scope-placeholder="Search"
    tabindex="1"
    autocapitalize="off">
  <div class="scope-badge">This repository</div>
</form>
      </div>
      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item explore">
          <a class="header-nav-link" href="/explore" data-ga-click="Header, go to explore, text:explore">Explore</a>
        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/blog" data-ga-click="Header, go to blog, text:blog">Blog</a>
          </li>
        <li class="header-nav-item">
          <a class="header-nav-link" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
        </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name" href="/seonsu" data-ga-click="Header, go to profile, text:username">
      <img alt="@seonsu" class="avatar" data-user="10575513" height="20" src="https://avatars2.githubusercontent.com/u/10575513?v=3&amp;s=40" width="20" />
      <span class="css-truncate">
        <span class="css-truncate-target">seonsu</span>
      </span>
    </a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link js-menu-target tooltipped tooltipped-s" href="#" aria-label="Create new..." data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      
<ul class="dropdown-menu">
  <li>
    <a href="/new" data-ga-click="Header, create new repository, icon:repo"><span class="octicon octicon-repo"></span> New repository</a>
  </li>
  <li>
    <a href="/organizations/new" data-ga-click="Header, create new organization, icon:organization"><span class="octicon octicon-organization"></span> New organization</a>
  </li>


    <li class="dropdown-divider"></li>
    <li class="dropdown-header">
      <span title="joellove/R">This repository</span>
    </li>
      <li>
        <a href="/joellove/R/issues/new" data-ga-click="Header, create new issue, icon:issue"><span class="octicon octicon-issue-opened"></span> New issue</a>
      </li>
</ul>

    </div>
  </li>

  <li class="header-nav-item">
        <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
        <span class="mail-status all-read"></span>
        <span class="octicon octicon-inbox"></span>
</a>
  </li>

  <li class="header-nav-item">
    <a class="header-nav-link tooltipped tooltipped-s" href="/settings/profile" id="account_settings" aria-label="Settings" data-ga-click="Header, go to settings, icon:settings">
      <span class="octicon octicon-gear"></span>
    </a>
  </li>

  <li class="header-nav-item">
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="aUGS9N3I5sIq4zZYKKyyo6646k/ItWkZ2Qc6Lm6g4RoAaUsOYNTxDoTXHQK2pruJPB5fnUhc11Dgn4v8sXH64A==" /></div>
      <button class="header-nav-link sign-out-button tooltipped tooltipped-s" aria-label="Sign out" data-ga-click="Header, sign out, icon:logout">
        <span class="octicon octicon-sign-out"></span>
      </button>
</form>  </li>

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
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Ol8Bivah9zYqOKp6LkibobgWjOhJfxO7pdT32LplWsMgc6lztxbP/pRVFun+rrbGvY8NtI6x2VBl52F4EqRibA==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="18982095" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/joellove/R/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Watch
          </span>
        </a>
        <a class="social-count js-social-count" href="/joellove/R/watchers">
          1
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore" />
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
                    Stop ignoring
                  </span>
                </div>
              </div>

            </div>

          </div>
        </div>
      </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/joellove/R/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="SVnizt2iA991q4N/Hy1l18eqXSpkgxDBmHelSP5SHuaPC0Q0KMSfFdsYfYT24lEqTdVsLPQi1WVZIOJAe+OXiA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar joellove/R"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/joellove/R/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/joellove/R/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="R1FhPO28OWHlTa4sGs+Z6CSkjg+DG1i8ShhSZVdY20b31TuZotdEJe3K6fyx3tB6OBoji+XiM6JaNvigiC+3qQ==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star joellove/R"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/joellove/R/stargazers">
          0
        </a>
</form>  </div>

  </li>

        <li>
          <form accept-charset="UTF-8" action="/joellove/R/fork" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="haOKZxHG3KncjiPK9N5+zuQk5dZmmWYL1vrXYQF1z1wWf7gpL6o7X6iJJSBtZsHhzZWbHTOhhAuVkZRt+v7TMQ==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of joellove/R to your account"
                aria-label="Fork your own copy of joellove/R to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
            <a href="/joellove/R/network" class="social-count">1</a>
</form>        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/joellove" class="url fn" itemprop="url" rel="author"><span itemprop="title">joellove</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/joellove/R" class="js-current-repository" data-pjax="#js-repo-pjax-container">R</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
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
     data-issue-count-url="/joellove/R/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/joellove/R" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /joellove/R">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/joellove/R/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /joellove/R/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/joellove/R/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /joellove/R/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>


      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/joellove/R/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /joellove/R/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/joellove/R/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /joellove/R/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/joellove/R/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /joellove/R/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/joellove/R.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:joellove/R.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/joellove/R" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<p class="clone-options">You can clone with
  <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>, <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>, or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>


  <a href="github-windows://openRepo/https://github.com/joellove/R" class="btn btn-sm sidebar-button" title="Save joellove/R to your computer and use it in GitHub Desktop." aria-label="Save joellove/R to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>

                <a href="/joellove/R/archive/master.zip"
                   class="btn btn-sm sidebar-button"
                   aria-label="Download the contents of joellove/R as a zip file"
                   title="Download the contents of joellove/R as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          

<a href="/joellove/R/blob/5ca266ba96689cbcb04550c988bdd4afc5ef415c/coursera/getting%26cleaningdata/project/CodeBook.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:6c800d01c84b2b2fccf1d6117c7f06bd -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-master-branch="master"
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
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/joellove/R/blob/master/coursera/getting&amp;cleaningdata/project/CodeBook.md"
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
    <a href="/joellove/R/find/master"
          class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/joellove/R" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">R</span></a></span></span><span class="separator">/</span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/joellove/R/tree/master/coursera" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">coursera</span></a></span><span class="separator">/</span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/joellove/R/tree/master/coursera/getting%26cleaningdata" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">getting&amp;cleaningdata</span></a></span><span class="separator">/</span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/joellove/R/tree/master/coursera/getting%26cleaningdata/project" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">project</span></a></span><span class="separator">/</span><strong class="final-path">CodeBook.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="@joellove" class="avatar" data-user="3461427" height="24" src="https://avatars0.githubusercontent.com/u/3461427?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/joellove" rel="author">joellove</a></span>
        <time datetime="2014-10-14T13:28:32Z" is="relative-time">Oct 14, 2014</time>
        <div class="commit-title">
            <a href="/joellove/R/commit/5ca266ba96689cbcb04550c988bdd4afc5ef415c" class="message" data-pjax="true" title="Create CodeBook.md">Create CodeBook.md</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>1</strong>
           contributor
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="@joellove" data-user="3461427" height="24" src="https://avatars0.githubusercontent.com/u/3461427?v=3&amp;s=48" width="24" />
            <a href="/joellove">joellove</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
    <div class="file-actions">

      <div class="btn-group">
        <a href="/joellove/R/raw/master/coursera/getting%26cleaningdata/project/CodeBook.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/joellove/R/blame/master/coursera/getting%26cleaningdata/project/CodeBook.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/joellove/R/commits/master/coursera/getting%26cleaningdata/project/CodeBook.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="github-windows://openRepo/https://github.com/joellove/R?branch=master&amp;filepath=coursera%2Fgetting%26cleaningdata%2Fproject%2FCodeBook.md"
           aria-label="Open this file in GitHub for Windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

            <form accept-charset="UTF-8" action="/joellove/R/edit/master/coursera/getting&amp;cleaningdata/project/CodeBook.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="iG2ypBstAw4KmlFUjnkOfVMbplLtxHNYZAfT/WGIhrKwnatM9cfdUJeqvezZ/zQm+dqI0USNlkSWKhOxP07ChQ==" /></div>
              <button class="octicon-btn tooltipped tooltipped-n" type="submit" aria-label="Clicking this button will fork this project so you can edit the file" data-hotkey="e" data-disable-with>
                <span class="octicon octicon-pencil"></span>
              </button>
</form>
          <form accept-charset="UTF-8" action="/joellove/R/delete/master/coursera/getting&amp;cleaningdata/project/CodeBook.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="DjjgeQEhjbjQOxTIAFBOpda5doJOobNlKFI0ndE0iwU/+r8Ea1RnYk7XKLL+/AfMxyjVlOWi/Ldt5NOg9xit+Q==" /></div>
            <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-n" type="submit" aria-label="Fork this project and delete file" data-disable-with>
              <span class="octicon octicon-trashcan"></span>
            </button>
</form>    </div>

    <div class="file-info">
        109 lines (94 sloc)
        <span class="file-info-divider"></span>
      5.086 kb
    </div>
  </div>
    <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1>
<a id="user-content-code-book" class="anchor" href="#code-book" aria-hidden="true"><span class="octicon octicon-link"></span></a>Code Book</h1>

<h2>
<a id="user-content-id-fields" class="anchor" href="#id-fields" aria-hidden="true"><span class="octicon octicon-link"></span></a>ID Fields</h2>

<ul class="task-list">
<li>
<code>subject</code> - The participant ("subject") ID</li>
<li>
<code>activity</code> - The label of the activity performed when the corresponding measurements were taken</li>
</ul>

<h2>
<a id="user-content-extracted-feature-fields" class="anchor" href="#extracted-feature-fields" aria-hidden="true"><span class="octicon octicon-link"></span></a>Extracted Feature Fields</h2>

<ul class="task-list">
<li>
<code>tBodyAcc-mean()-X</code> (column <code>1</code>)</li>
<li>
<code>tBodyAcc-mean()-Y</code> (column <code>2</code>)</li>
<li>
<code>tBodyAcc-mean()-Z</code> (column <code>3</code>)</li>
<li>
<code>tBodyAcc-std()-X</code> (column <code>4</code>)</li>
<li>
<code>tBodyAcc-std()-Y</code> (column <code>5</code>)</li>
<li>
<code>tBodyAcc-std()-Z</code> (column <code>6</code>)</li>
<li>
<code>tGravityAcc-mean()-X</code> (column <code>41</code>)</li>
<li>
<code>tGravityAcc-mean()-Y</code> (column <code>42</code>)</li>
<li>
<code>tGravityAcc-mean()-Z</code> (column <code>43</code>)</li>
<li>
<code>tGravityAcc-std()-X</code> (column <code>44</code>)</li>
<li>
<code>tGravityAcc-std()-Y</code> (column <code>45</code>)</li>
<li>
<code>tGravityAcc-std()-Z</code> (column <code>46</code>)</li>
<li>
<code>tBodyAccJerk-mean()-X</code> (column <code>81</code>)</li>
<li>
<code>tBodyAccJerk-mean()-Y</code> (column <code>82</code>)</li>
<li>
<code>tBodyAccJerk-mean()-Z</code> (column <code>83</code>)</li>
<li>
<code>tBodyAccJerk-std()-X</code> (column <code>84</code>)</li>
<li>
<code>tBodyAccJerk-std()-Y</code> (column <code>85</code>)</li>
<li>
<code>tBodyAccJerk-std()-Z</code> (column <code>86</code>)</li>
<li>
<code>tBodyGyro-mean()-X</code> (column <code>121</code>)</li>
<li>
<code>tBodyGyro-mean()-Y</code> (column <code>122</code>)</li>
<li>
<code>tBodyGyro-mean()-Z</code> (column <code>123</code>)</li>
<li>
<code>tBodyGyro-std()-X</code> (column <code>124</code>)</li>
<li>
<code>tBodyGyro-std()-Y</code> (column <code>125</code>)</li>
<li>
<code>tBodyGyro-std()-Z</code> (column <code>126</code>)</li>
<li>
<code>tBodyGyroJerk-mean()-X</code> (column <code>161</code>)</li>
<li>
<code>tBodyGyroJerk-mean()-Y</code> (column <code>162</code>)</li>
<li>
<code>tBodyGyroJerk-mean()-Z</code> (column <code>163</code>)</li>
<li>
<code>tBodyGyroJerk-std()-X</code> (column <code>164</code>)</li>
<li>
<code>tBodyGyroJerk-std()-Y</code> (column <code>165</code>)</li>
<li>
<code>tBodyGyroJerk-std()-Z</code> (column <code>166</code>)</li>
<li>
<code>tBodyAccMag-mean()</code> (column <code>201</code>)</li>
<li>
<code>tBodyAccMag-std()</code> (column <code>202</code>)</li>
<li>
<code>tGravityAccMag-mean()</code> (column <code>214</code>)</li>
<li>
<code>tGravityAccMag-std()</code> (column <code>215</code>)</li>
<li>
<code>tBodyAccJerkMag-mean()</code> (column <code>227</code>)</li>
<li>
<code>tBodyAccJerkMag-std()</code> (column <code>228</code>)</li>
<li>
<code>tBodyGyroMag-mean()</code> (column <code>240</code>)</li>
<li>
<code>tBodyGyroMag-std()</code> (column <code>241</code>)</li>
<li>
<code>tBodyGyroJerkMag-mean()</code> (column <code>253</code>)</li>
<li>
<code>tBodyGyroJerkMag-std()</code> (column <code>254</code>)</li>
<li>
<code>fBodyAcc-mean()-X</code> (column <code>266</code>)</li>
<li>
<code>fBodyAcc-mean()-Y</code> (column <code>267</code>)</li>
<li>
<code>fBodyAcc-mean()-Z</code> (column <code>268</code>)</li>
<li>
<code>fBodyAcc-std()-X</code> (column <code>269</code>)</li>
<li>
<code>fBodyAcc-std()-Y</code> (column <code>270</code>)</li>
<li>
<code>fBodyAcc-std()-Z</code> (column <code>271</code>)</li>
<li>
<code>fBodyAccJerk-mean()-X</code> (column <code>345</code>)</li>
<li>
<code>fBodyAccJerk-mean()-Y</code> (column <code>346</code>)</li>
<li>
<code>fBodyAccJerk-mean()-Z</code> (column <code>347</code>)</li>
<li>
<code>fBodyAccJerk-std()-X</code> (column <code>348</code>)</li>
<li>
<code>fBodyAccJerk-std()-Y</code> (column <code>349</code>)</li>
<li>
<code>fBodyAccJerk-std()-Z</code> (column <code>350</code>)</li>
<li>
<code>fBodyGyro-mean()-X</code> (column <code>424</code>)</li>
<li>
<code>fBodyGyro-mean()-Y</code> (column <code>425</code>)</li>
<li>
<code>fBodyGyro-mean()-Z</code> (column <code>426</code>)</li>
<li>
<code>fBodyGyro-std()-X</code> (column <code>427</code>)</li>
<li>
<code>fBodyGyro-std()-Y</code> (column <code>428</code>)</li>
<li>
<code>fBodyGyro-std()-Z</code> (column <code>429</code>)</li>
<li>
<code>fBodyAccMag-mean()</code> (column <code>503</code>)</li>
<li>
<code>fBodyAccMag-std()</code> (column <code>504</code>)</li>
<li>
<code>fBodyBodyAccJerkMag-mean()</code> (column <code>516</code>)</li>
<li>
<code>fBodyBodyAccJerkMag-std()</code> (column <code>517</code>)</li>
<li>
<code>fBodyBodyGyroMag-mean()</code> (column <code>529</code>)</li>
<li>
<code>fBodyBodyGyroMag-std()</code> (column <code>530</code>)</li>
<li>
<code>fBodyBodyGyroJerkMag-mean()</code> (column <code>542</code>)</li>
<li>
<code>fBodyBodyGyroJerkMag-std()</code> (column <code>543</code>)</li>
</ul>

<h2>
<a id="user-content-activity-labels" class="anchor" href="#activity-labels" aria-hidden="true"><span class="octicon octicon-link"></span></a>Activity Labels</h2>

<ul class="task-list">
<li>
<code>WALKING</code> (value <code>1</code>)</li>
<li>
<code>WALKING_UPSTAIRS</code> (value <code>2</code>)</li>
<li>
<code>WALKING_DOWNSTAIRS</code> (value <code>3</code>)</li>
<li>
<code>SITTING</code> (value <code>4</code>)</li>
<li>
<code>STANDING</code> (value <code>5</code>)</li>
<li>
<code>LAYING</code> (value <code>6</code>)</li>
</ul>

<h2>
<a id="user-content-extracted-features-vector" class="anchor" href="#extracted-features-vector" aria-hidden="true"><span class="octicon octicon-link"></span></a>Extracted Features Vector</h2>

<div class="highlight highlight-R"><pre>c(<span class="pl-c1">1</span>, <span class="pl-c1">2</span>, <span class="pl-c1">3</span>, <span class="pl-c1">4</span>, <span class="pl-c1">5</span>, <span class="pl-c1">6</span>, <span class="pl-c1">41</span>, <span class="pl-c1">42</span>, <span class="pl-c1">43</span>, <span class="pl-c1">44</span>, <span class="pl-c1">45</span>, <span class="pl-c1">46</span>, <span class="pl-c1">81</span>, <span class="pl-c1">82</span>, <span class="pl-c1">83</span>, <span class="pl-c1">84</span>, <span class="pl-c1">85</span>, <span class="pl-c1">86</span>, <span class="pl-c1">121</span>, <span class="pl-c1">122</span>, <span class="pl-c1">123</span>, <span class="pl-c1">124</span>, <span class="pl-c1">125</span>, <span class="pl-c1">126</span>, <span class="pl-c1">161</span>, <span class="pl-c1">162</span>, <span class="pl-c1">163</span>, <span class="pl-c1">164</span>, <span class="pl-c1">165</span>, <span class="pl-c1">166</span>, <span class="pl-c1">201</span>, <span class="pl-c1">202</span>, <span class="pl-c1">214</span>, <span class="pl-c1">215</span>, <span class="pl-c1">227</span>, <span class="pl-c1">228</span>, <span class="pl-c1">240</span>, <span class="pl-c1">241</span>, <span class="pl-c1">253</span>, <span class="pl-c1">254</span>, <span class="pl-c1">266</span>, <span class="pl-c1">267</span>, <span class="pl-c1">268</span>, <span class="pl-c1">269</span>, <span class="pl-c1">270</span>, <span class="pl-c1">271</span>, <span class="pl-c1">345</span>, <span class="pl-c1">346</span>, <span class="pl-c1">347</span>, <span class="pl-c1">348</span>, <span class="pl-c1">349</span>, <span class="pl-c1">350</span>, <span class="pl-c1">424</span>, <span class="pl-c1">425</span>, <span class="pl-c1">426</span>, <span class="pl-c1">427</span>, <span class="pl-c1">428</span>, <span class="pl-c1">429</span>, <span class="pl-c1">503</span>, <span class="pl-c1">504</span>, <span class="pl-c1">516</span>, <span class="pl-c1">517</span>, <span class="pl-c1">529</span>, <span class="pl-c1">530</span>, <span class="pl-c1">542</span>, <span class="pl-c1">543</span>)</pre></div>

<h2>
<a id="user-content-extracted-feature-names-vector" class="anchor" href="#extracted-feature-names-vector" aria-hidden="true"><span class="octicon octicon-link"></span></a>Extracted Feature Names Vector</h2>

<div class="highlight highlight-R"><pre>c("tBodyAcc-mean()-X", "tBodyAcc-mean()-Y", "tBodyAcc-mean()-Z", "tBodyAcc-std()-X", "tBodyAcc-std()-Y", "tBodyAcc-std()-Z", "tGravityAcc-mean()-X", "tGravityAcc-mean()-Y", "tGravityAcc-mean()-Z", "tGravityAcc-std()-X", "tGravityAcc-std()-Y", "tGravityAcc-std()-Z", "tBodyAccJerk-mean()-X", "tBodyAccJerk-mean()-Y", "tBodyAccJerk-mean()-Z", "tBodyAccJerk-std()-X", "tBodyAccJerk-std()-Y", "tBodyAccJerk-std()-Z", "tBodyGyro-mean()-X", "tBodyGyro-mean()-Y", "tBodyGyro-mean()-Z", "tBodyGyro-std()-X", "tBodyGyro-std()-Y", "tBodyGyro-std()-Z", "tBodyGyroJerk-mean()-X", "tBodyGyroJerk-mean()-Y", "tBodyGyroJerk-mean()-Z", "tBodyGyroJerk-std()-X", "tBodyGyroJerk-std()-Y", "tBodyGyroJerk-std()-Z", "tBodyAccMag-mean()", "tBodyAccMag-std()", "tGravityAccMag-mean()", "tGravityAccMag-std()", "tBodyAccJerkMag-mean()", "tBodyAccJerkMag-std()", "tBodyGyroMag-mean()", "tBodyGyroMag-std()", "tBodyGyroJerkMag-mean()", "tBodyGyroJerkMag-std()", "fBodyAcc-mean()-X", "fBodyAcc-mean()-Y", "fBodyAcc-mean()-Z", "fBodyAcc-std()-X", "fBodyAcc-std()-Y", "fBodyAcc-std()-Z", "fBodyAccJerk-mean()-X", "fBodyAccJerk-mean()-Y", "fBodyAccJerk-mean()-Z", "fBodyAccJerk-std()-X", "fBodyAccJerk-std()-Y", "fBodyAccJerk-std()-Z", "fBodyGyro-mean()-X", "fBodyGyro-mean()-Y", "fBodyGyro-mean()-Z", "fBodyGyro-std()-X", "fBodyGyro-std()-Y", "fBodyGyro-std()-Z", "fBodyAccMag-mean()", "fBodyAccMag-std()", "fBodyBodyAccJerkMag-mean()", "fBodyBodyAccJerkMag-std()", "fBodyBodyGyroMag-mean()", "fBodyBodyGyroMag-std()", "fBodyBodyGyroJerkMag-mean()", "fBodyBodyGyroJerkMag-std()")</pre></div>

<h2>
<a id="user-content-activities-vector" class="anchor" href="#activities-vector" aria-hidden="true"><span class="octicon octicon-link"></span></a>Activities Vector</h2>

<div class="highlight highlight-R"><pre>c(<span class="pl-c1">1</span>, <span class="pl-c1">2</span>, <span class="pl-c1">3</span>, <span class="pl-c1">4</span>, <span class="pl-c1">5</span>, <span class="pl-c1">6</span>)</pre></div>

<h2>
<a id="user-content-activity-names-vector" class="anchor" href="#activity-names-vector" aria-hidden="true"><span class="octicon octicon-link"></span></a>Activity Names Vector</h2>

<div class="highlight highlight-R"><pre>c(<span class="pl-s"><span class="pl-pds">"</span>WALKING<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>WALKING_UPSTAIRS<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>WALKING_DOWNSTAIRS<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>SITTING<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>STANDING<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>LAYING<span class="pl-pds">"</span></span>)</pre></div>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" class="js-jump-to-line-form">
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="btn">Go</button>
  </form>
</div>

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

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.05263s from github-fe134-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
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


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-d22b59d0085e83b7549ba4341ec9e68f80c2f29c8e49213ee182003dc8d568c6.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-0bc0f45c838b5d9d25bc071d2a4b0abe759a093392087dce55cd2caa00ea4f36.js"></script>
      
      

  </body>
</html>

