<!DOCTYPE html>
<html class="" lang="en">
<head prefix="og: http://ogp.me/ns#">
<meta charset="utf-8">
<meta content="IE=edge" http-equiv="X-UA-Compatible">

<meta content="object" property="og:type">
<meta content="GitLab" property="og:site_name">
<meta content="SECURITY.md · master · Ned Gulley / Contribution Template" property="og:title">
<meta content="This is a template for community contributions to GitHub and the File Exchange. It demonstrates the structure and some of the files of a typical community contribution." property="og:description">
<meta content="https://insidelabs-git.mathworks.com/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png" property="og:image">
<meta content="64" property="og:image:width">
<meta content="64" property="og:image:height">
<meta content="https://insidelabs-git.mathworks.com/gulley/contribution-template/-/blob/master/SECURITY.md" property="og:url">
<meta content="summary" property="twitter:card">
<meta content="SECURITY.md · master · Ned Gulley / Contribution Template" property="twitter:title">
<meta content="This is a template for community contributions to GitHub and the File Exchange. It demonstrates the structure and some of the files of a typical community contribution." property="twitter:description">
<meta content="https://insidelabs-git.mathworks.com/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png" property="twitter:image">

<title>SECURITY.md · master · Ned Gulley / Contribution Template · GitLab</title>
<meta content="This is a template for community contributions to GitHub and the File Exchange. It demonstrates the structure and some of the files of a typical community contribution." name="description">
<link rel="shortcut icon" type="image/png" href="/uploads/-/system/appearance/favicon/1/labs-icon-removebg-preview.png" id="favicon" data-original-href="/uploads/-/system/appearance/favicon/1/labs-icon-removebg-preview.png" />
<link rel="stylesheet" media="all" href="/assets/application-a9308f85e95b00007892d451fd9f6beabcd8792b4c5f8cd7524ba7e941d479c9.css" />


<link rel="stylesheet" media="all" href="/assets/highlight/themes/white-3a5ccf16b3cb943249b10b6fd8a260ac3c8a79ea432c44c3886d1d1ea9df4694.css" />
<script>
//<![CDATA[
window.gon={};gon.api_version="v4";gon.default_avatar_url="https://insidelabs-git.mathworks.com/assets/no_avatar-849f9c04a3a0d0cea2424ae97b27447dc64a7dbfae83c036c45b403392f0e8ba.png";gon.max_file_size=500;gon.asset_host=null;gon.webpack_public_path="/assets/webpack/";gon.relative_url_root="";gon.shortcuts_path="/help/shortcuts";gon.user_color_scheme="white";gon.gitlab_url="https://insidelabs-git.mathworks.com";gon.revision="0f9c583610f";gon.gitlab_logo="/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png";gon.sprite_icons="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg";gon.sprite_file_icons="/assets/file_icons-7262fc6897e02f1ceaf8de43dc33afa5e4f9a2067f4f68ef77dcc87946575e9e.svg";gon.emoji_sprites_css_path="/assets/emoji_sprites-289eccffb1183c188b630297431be837765d9ff4aed6130cf738586fb307c170.css";gon.test_env=false;gon.disable_animations=null;gon.suggested_label_colors={"#0033CC":"UA blue","#428BCA":"Moderate blue","#44AD8E":"Lime green","#A8D695":"Feijoa","#5CB85C":"Slightly desaturated green","#69D100":"Bright green","#004E00":"Very dark lime green","#34495E":"Very dark desaturated blue","#7F8C8D":"Dark grayish cyan","#A295D6":"Slightly desaturated blue","#5843AD":"Dark moderate blue","#8E44AD":"Dark moderate violet","#FFECDB":"Very pale orange","#AD4363":"Dark moderate pink","#D10069":"Strong pink","#CC0033":"Strong red","#FF0000":"Pure red","#D9534F":"Soft red","#D1D100":"Strong yellow","#F0AD4E":"Soft orange","#AD8D43":"Dark moderate orange"};gon.first_day_of_week=0;gon.ee=false;gon.current_user_id=4100;gon.current_username="lipingw";gon.current_user_fullname="Liping Wang";gon.current_user_avatar_url="/uploads/-/system/user/avatar/4100/lipingw_tn_large.jpg";gon.features={"snippetsVue":true,"monacoBlobs":false,"monacoCi":false,"snippetsEditVue":false,"webperfExperiment":false,"codeNavigation":true};
//]]>
</script>


<script src="/assets/webpack/runtime.c5d7d062.bundle.js" defer="defer"></script>
<script src="/assets/webpack/main.81873017.chunk.js" defer="defer"></script>
<script src="/assets/webpack/commons~pages.groups.milestones.edit~pages.groups.milestones.new~pages.projects.blame.show~pages.pro~410a1b97.017b3c7f.chunk.js" defer="defer"></script>
<script src="/assets/webpack/commons~pages.admin.application_settings~pages.admin.application_settings.general~pages.admin.applic~35b0fcf5.7d2d7bc0.chunk.js" defer="defer"></script>
<script src="/assets/webpack/commons~pages.projects.blame.show~pages.projects.blob.edit~pages.projects.blob.new~pages.projects.bl~046fef08.6929763b.chunk.js" defer="defer"></script>
<script src="/assets/webpack/pages.projects.blob.show.a7ec3af8.chunk.js" defer="defer"></script>
<script>
//<![CDATA[
window.uploads_path = "/gulley/contribution-template/uploads";



//]]>
</script>
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="KOdreJPXddDfpnkCEQp3sMkFyyXg3q8JA46g8GYCUtO5nFCHhly/G0GPq/cMZLyD6lXobHzgw4gDZquONhWl6A==" />
<meta name="csp-nonce" />
<meta name="action-cable-url" content="/-/cable" />
<meta content="origin-when-cross-origin" name="referrer">
<meta content="width=device-width, initial-scale=1, maximum-scale=1" name="viewport">
<meta content="#474D57" name="theme-color">
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-iphone-5a9cee0e8a51212e70b90c87c12f382c428870c0ff67d1eb034d884b78d2dae7.png" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-ipad-a6eec6aeb9da138e507593b464fdac213047e49d3093fc30e90d9a995df83ba3.png" sizes="76x76" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-iphone-retina-72e2aadf86513a56e050e7f0f2355deaa19cc17ed97bbe5147847f2748e5a3e3.png" sizes="120x120" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-ipad-retina-8ebe416f5313483d9c1bc772b5bbe03ecad52a54eba443e5215a22caed2a16a2.png" sizes="152x152" />
<link color="rgb(226, 67, 41)" href="/assets/logo-d36b5212042cebc89b96df4bf6ac24e43db316143e89926c0db839ff694d2de4.svg" rel="mask-icon">
<meta content="/assets/msapplication-tile-1196ec67452f618d39cdd85e2e3a542f76574c071051ae7effbfde01710eb17d.png" name="msapplication-TileImage">
<meta content="#30353E" name="msapplication-TileColor">




</head>

<body class="ui-indigo tab-width-8  gl-browser-chrome gl-platform-windows" data-find-file="/gulley/contribution-template/-/find_file/master" data-namespace-id="90" data-page="projects:blob:show" data-page-type-id="master/SECURITY.md" data-project="contribution-template" data-project-id="9308">

<script>
//<![CDATA[
gl = window.gl || {};
gl.client = {"isChrome":true,"isWindows":true};


//]]>
</script>


<header class="navbar navbar-gitlab navbar-expand-sm js-navbar" data-qa-selector="navbar">
<a class="sr-only gl-accessibility" href="#content-body" tabindex="1">Skip to content</a>
<div class="container-fluid">
<div class="header-content">
<div class="title-container">
<h1 class="title">
<span class="gl-sr-only">GitLab</span>
<a title="Dashboard" id="logo" href="/"><img class="brand-header-logo lazy" data-src="/uploads/-/system/appearance/header_logo/1/labs-icon-removebg-preview.png" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
</a></h1>
<ul class="list-unstyled navbar-sub-nav">
<li id="nav-projects-dropdown" class="home dropdown header-projects qa-projects-dropdown" data-track-label="projects_dropdown" data-track-event="click_dropdown" data-track-value=""><button class="btn" data-toggle="dropdown" type="button">
Projects
<svg class="caret-down"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#angle-down"></use></svg>
</button>
<div class="dropdown-menu frequent-items-dropdown-menu">
<div class="frequent-items-dropdown-container">
<div class="frequent-items-dropdown-sidebar qa-projects-dropdown-sidebar">
<ul>
<li class=""><a class="qa-your-projects-link" href="/dashboard/projects">Your projects
</a></li><li class=""><a href="/dashboard/projects/starred">Starred projects
</a></li><li class=""><a href="/explore">Explore projects
</a></li></ul>
</div>
<div class="frequent-items-dropdown-content">
<div data-project-id="9308" data-project-name="Contribution Template" data-project-namespace="Ned Gulley / Contribution Template" data-project-web-url="/gulley/contribution-template" data-user-name="lipingw" id="js-projects-dropdown"></div>
</div>
</div>

</div>
</li><li id="nav-groups-dropdown" class="d-none d-md-block home dropdown header-groups qa-groups-dropdown" data-track-label="groups_dropdown" data-track-event="click_dropdown" data-track-value=""><button class="btn" data-toggle="dropdown" type="button">
Groups
<svg class="caret-down"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#angle-down"></use></svg>
</button>
<div class="dropdown-menu frequent-items-dropdown-menu">
<div class="frequent-items-dropdown-container">
<div class="frequent-items-dropdown-sidebar qa-groups-dropdown-sidebar">
<ul>
<li class=""><a class="qa-your-groups-link" href="/dashboard/groups">Your groups
</a></li><li class=""><a href="/explore/groups">Explore groups
</a></li></ul>
</div>
<div class="frequent-items-dropdown-content">
<div data-user-name="lipingw" id="js-groups-dropdown"></div>
</div>
</div>

</div>
</li><li class="header-more dropdown">
<a data-qa-selector="more_dropdown" data-toggle="dropdown" href="#">
More
<svg class="caret-down"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#angle-down"></use></svg>
</a>
<div class="dropdown-menu">
<ul>
<li class="d-md-none">
<a class="dashboard-shortcuts-groups" data-qa-selector="groups_link" href="/dashboard/groups">Groups
</a></li>
<li class=""><a class="dashboard-shortcuts-activity" data-qa-selector="activity_link" href="/dashboard/activity">Activity
</a></li><li class=""><a class="dashboard-shortcuts-milestones" data-qa-selector="milestones_link" href="/dashboard/milestones">Milestones
</a></li><li class=""><a class="dashboard-shortcuts-snippets" data-qa-selector="snippets_link" href="/dashboard/snippets">Snippets
</a></li><li class=""><a class="d-xl-none" href="/-/instance_statistics">Analytics
</a></li>
<li class="dropdown">

</li>
</ul>
</div>
</li>
<li class="d-none d-xl-block"><a class="chart-icon" title="Analytics" aria-label="Analytics" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/-/instance_statistics"><svg class="s18"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#chart"></use></svg>
</a></li>
<li class="hidden">
<a class="dashboard-shortcuts-projects" href="/dashboard/projects">Projects
</a></li>

</ul>

</div>
<div class="navbar-collapse collapse">
<ul class="nav navbar-nav">
<li class="header-new dropdown" data-track-event="click_dropdown" data-track-label="new_dropdown" data-track-value="">
<a class="header-new-dropdown-toggle has-tooltip qa-new-menu-toggle" id="js-onboarding-new-project-link" title="New..." ref="tooltip" aria-label="New..." data-toggle="dropdown" data-placement="bottom" data-container="body" data-display="static" href="/projects/new"><svg class="s16"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#plus-square"></use></svg>
<svg class="caret-down"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#angle-down"></use></svg>
</a><div class="dropdown-menu dropdown-menu-right">
<ul>
<li class="dropdown-bold-header">
This project
</li>
<li><a href="/gulley/contribution-template/-/issues/new">New issue</a></li>
<li class="divider"></li>
<li class="dropdown-bold-header">GitLab</li>
<li><a class="qa-global-new-project-link" href="/projects/new">New project</a></li>
<li><a href="/groups/new">New group</a></li>
<li><a class="qa-global-new-snippet-link" href="/snippets/new">New snippet</a></li>
</ul>
</div>
</li>

<li class="nav-item d-none d-lg-block m-auto">
<div class="search search-form" data-track-event="activate_form_input" data-track-label="navbar_search" data-track-value="">
<form class="form-inline" action="/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><div class="search-input-container">
<div class="search-input-wrap">
<div class="dropdown" data-url="/search/autocomplete">
<input type="search" name="search" id="search" placeholder="Search or jump to…" class="search-input dropdown-menu-toggle no-outline js-search-dashboard-options" spellcheck="false" tabindex="1" autocomplete="off" data-issues-path="/dashboard/issues" data-mr-path="/dashboard/merge_requests" data-qa-selector="search_term_field" aria-label="Search or jump to…" />
<button class="hidden js-dropdown-search-toggle" data-toggle="dropdown" type="button"></button>
<div class="dropdown-menu dropdown-select js-dashboard-search-options">
<div class="dropdown-content"><ul>
<li class="dropdown-menu-empty-item">
<a>
Loading...
</a>
</li>
</ul>
</div><div class="dropdown-loading"><i aria-hidden="true" data-hidden="true" class="fa fa-spinner fa-spin"></i></div>
</div>
<svg class="s16 search-icon"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#search"></use></svg>
<svg class="s16 clear-icon js-clear-input"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#close"></use></svg>
</div>
</div>
</div>
<input type="hidden" name="group_id" id="group_id" value="" class="js-search-group-options" />
<input type="hidden" name="project_id" id="search_project_id" value="9308" class="js-search-project-options" data-project-path="contribution-template" data-name="Contribution Template" data-issues-path="/gulley/contribution-template/-/issues" data-mr-path="/gulley/contribution-template/-/merge_requests" data-issues-disabled="false" />
<input type="hidden" name="scope" id="scope" />
<input type="hidden" name="search_code" id="search_code" value="true" />
<input type="hidden" name="snippets" id="snippets" value="false" />
<input type="hidden" name="repository_ref" id="repository_ref" value="master" />
<input type="hidden" name="nav_source" id="nav_source" value="navbar" />
<div class="search-autocomplete-opts hide" data-autocomplete-path="/search/autocomplete" data-autocomplete-project-id="9308" data-autocomplete-project-ref="master"></div>
</form></div>

</li>
<li class="nav-item d-inline-block d-lg-none">
<a title="Search" aria-label="Search" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/search?project_id=9308"><svg class="s16"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#search"></use></svg>
</a></li>
<li class="user-counter"><a title="Issues" class="dashboard-shortcuts-issues" aria-label="Issues" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/dashboard/issues?assignee_username=lipingw"><svg class="s16"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#issues"></use></svg>
<span class="badge badge-pill green-badge hidden issues-count">
0
</span>
</a></li><li class="user-counter"><a title="Merge requests" class="dashboard-shortcuts-merge_requests" aria-label="Merge requests" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/dashboard/merge_requests?assignee_username=lipingw"><svg class="s16"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#git-merge"></use></svg>
<span class="badge badge-pill hidden merge-requests-count">
0
</span>
</a></li><li class="user-counter"><a title="To-Do List" aria-label="To-Do List" class="shortcuts-todos" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/dashboard/todos"><svg class="s16"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#todo-done"></use></svg>
<span class="badge badge-pill hidden todos-count">
0
</span>
</a></li><li class="nav-item header-help dropdown d-none d-md-block">
<a class="header-help-dropdown-toggle" data-toggle="dropdown" href="/help"><span class="gl-sr-only">
Help
</span>
<svg class="s16"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#question"></use></svg>
<svg class="caret-down"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#angle-down"></use></svg>
</a><div class="dropdown-menu dropdown-menu-right">
<ul>

<li>
<a href="/help">Help</a>
</li>
<li>
<a href="https://insidelabs.insidelabspages.mathworks.com/gitlab-tutorials">Support</a>
</li>
<li>
<button class="js-shortcuts-modal-trigger" type="button">
Keyboard shortcuts
<span aria-hidden class="text-secondary float-right">?</span>
</button>
</li>
<li class="divider"></li>
<li>
<a href="https://about.gitlab.com/submit-feedback">Submit feedback</a>
</li>
<li>
<a target="_blank" class="text-nowrap" href="https://about.gitlab.com/contributing">Contribute to GitLab
</a>
</li>

</ul>

</div>
</li>
<li class="dropdown header-user js-nav-user-dropdown nav-item" data-qa-selector="user_menu" data-track-event="click_dropdown" data-track-label="profile_dropdown" data-track-value="">
<a class="header-user-dropdown-toggle" data-toggle="dropdown" href="/lipingw"><img width="23" height="23" class="header-user-avatar qa-user-avatar lazy" alt="Liping Wang" data-src="/uploads/-/system/user/avatar/4100/lipingw_tn_large.jpg?width=23" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />

<svg class="caret-down"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#angle-down"></use></svg>
</a><div class="dropdown-menu dropdown-menu-right">
<ul>
<li class="current-user">
<div class="user-name bold">
Liping Wang
</div>
@lipingw
</li>
<li class="divider"></li>
<li>
<div class="js-set-status-modal-trigger" data-has-status="false"></div>
</li>
<li>
<a class="profile-link" data-user="lipingw" href="/lipingw">Profile</a>
</li>
<li>
<a data-qa-selector="settings_link" href="/profile">Settings</a>
</li>


<li class="divider d-md-none"></li>
<li class="d-md-none">
<a href="/help">Help</a>
</li>
<li class="d-md-none">
<a href="https://insidelabs.insidelabspages.mathworks.com/gitlab-tutorials">Support</a>
</li>
<li class="d-md-none">
<a href="https://about.gitlab.com/submit-feedback">Submit feedback</a>
</li>
<li class="d-md-none">
<a target="_blank" class="text-nowrap" href="https://about.gitlab.com/contributing">Contribute to GitLab
</a>
</li>

<li class="divider"></li>
<li>
<a class="sign-out-link" data-qa-selector="sign_out_link" rel="nofollow" data-method="post" href="/users/sign_out">Sign out</a>
</li>
</ul>

</div>
</li>
</ul>
</div>
<button class="navbar-toggler d-block d-sm-none" type="button">
<span class="sr-only">Toggle navigation</span>
<svg class="s12 more-icon js-navbar-toggle-right"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#ellipsis_h"></use></svg>
<svg class="s12 close-icon js-navbar-toggle-left"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#close"></use></svg>
</button>
</div>
</div>
</header>
<div class="js-set-status-modal-wrapper" data-current-emoji="" data-current-message=""></div>

<div class="layout-page page-with-contextual-sidebar">
<div class="nav-sidebar">
<div class="nav-sidebar-inner-scroll">
<div class="context-header">
<a title="Contribution Template" href="/gulley/contribution-template"><div class="avatar-container rect-avatar s40 project-avatar">
<div class="avatar s40 avatar-tile identicon bg6">C</div>
</div>
<div class="sidebar-context-title">
Contribution Template
</div>
</a></div>
<ul class="sidebar-top-level-items qa-project-sidebar">
<li class="home"><a class="shortcuts-project rspec-project-link" data-qa-selector="project_link" href="/gulley/contribution-template"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#home"></use></svg>
</div>
<span class="nav-item-name">
Project overview
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a href="/gulley/contribution-template"><strong class="fly-out-top-item-name">
Project overview
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a title="Project details" class="shortcuts-project" href="/gulley/contribution-template"><span>Details</span>
</a></li><li class=""><a title="Activity" class="shortcuts-project-activity" data-qa-selector="activity_link" href="/gulley/contribution-template/activity"><span>Activity</span>
</a></li><li class=""><a title="Releases" class="shortcuts-project-releases" href="/gulley/contribution-template/-/releases"><span>Releases</span>
</a></li></ul>
</li><li class="active"><a class="shortcuts-tree" data-qa-selector="repository_link" href="/gulley/contribution-template/-/tree/master"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#doc-text"></use></svg>
</div>
<span class="nav-item-name" id="js-onboarding-repo-link">
Repository
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item active"><a href="/gulley/contribution-template/-/tree/master"><strong class="fly-out-top-item-name">
Repository
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class="active"><a href="/gulley/contribution-template/-/tree/master">Files
</a></li><li class=""><a id="js-onboarding-commits-link" href="/gulley/contribution-template/-/commits/master">Commits
</a></li><li class=""><a data-qa-selector="branches_link" id="js-onboarding-branches-link" href="/gulley/contribution-template/-/branches">Branches
</a></li><li class=""><a data-qa-selector="tags_link" href="/gulley/contribution-template/-/tags">Tags
</a></li><li class=""><a href="/gulley/contribution-template/-/graphs/master">Contributors
</a></li><li class=""><a href="/gulley/contribution-template/-/network/master">Graph
</a></li><li class=""><a href="/gulley/contribution-template/-/compare?from=master&amp;to=master">Compare
</a></li>
</ul>
</li><li class=""><a class="shortcuts-issues qa-issues-item" href="/gulley/contribution-template/-/issues"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#issues"></use></svg>
</div>
<span class="nav-item-name" id="js-onboarding-issues-link">
Issues
</span>
<span class="badge badge-pill count issue_counter">
0
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a href="/gulley/contribution-template/-/issues"><strong class="fly-out-top-item-name">
Issues
</strong>
<span class="badge badge-pill count issue_counter fly-out-badge">
0
</span>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a title="Issues" href="/gulley/contribution-template/-/issues"><span>
List
</span>
</a></li><li class=""><a title="Boards" data-qa-selector="issue_boards_link" href="/gulley/contribution-template/-/boards"><span>
Boards
</span>
</a></li><li class=""><a title="Labels" class="qa-labels-link" href="/gulley/contribution-template/-/labels"><span>
Labels
</span>
</a></li><li class=""><a title="Service Desk" href="/gulley/contribution-template/-/issues/service_desk">Service Desk
</a></li>
<li class=""><a title="Milestones" class="qa-milestones-link" href="/gulley/contribution-template/-/milestones"><span>
Milestones
</span>
</a></li></ul>
</li><li class=""><a class="shortcuts-merge_requests" data-qa-selector="merge_requests_link" href="/gulley/contribution-template/-/merge_requests"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#git-merge"></use></svg>
</div>
<span class="nav-item-name" id="js-onboarding-mr-link">
Merge Requests
</span>
<span class="badge badge-pill count merge_counter js-merge-counter">
0
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a href="/gulley/contribution-template/-/merge_requests"><strong class="fly-out-top-item-name">
Merge Requests
</strong>
<span class="badge badge-pill count merge_counter js-merge-counter fly-out-badge">
0
</span>
</a></li></ul>
</li>
<li class=""><a class="shortcuts-pipelines qa-link-pipelines rspec-link-pipelines" data-qa-selector="ci_cd_link" href="/gulley/contribution-template/-/pipelines"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#rocket"></use></svg>
</div>
<span class="nav-item-name" id="js-onboarding-pipelines-link">
CI / CD
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a href="/gulley/contribution-template/-/pipelines"><strong class="fly-out-top-item-name">
CI / CD
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a title="Pipelines" class="shortcuts-pipelines" href="/gulley/contribution-template/-/pipelines"><span>
Pipelines
</span>
</a></li><li class=""><a title="Jobs" class="shortcuts-builds" href="/gulley/contribution-template/-/jobs"><span>
Jobs
</span>
</a></li><li class=""><a title="Schedules" class="shortcuts-builds" href="/gulley/contribution-template/-/pipeline_schedules"><span>
Schedules
</span>
</a></li></ul>
</li>

<li class=""><a data-qa-selector="analytics_anchor" href="/gulley/contribution-template/-/value_stream_analytics"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#chart"></use></svg>
</div>
<span class="nav-item-name" data-qa-selector="analytics_link">
Analytics
</span>
</a><ul class="sidebar-sub-level-items" data-qa-selector="analytics_sidebar_submenu">
<li class="fly-out-top-item"><a href="/gulley/contribution-template/-/value_stream_analytics"><strong class="fly-out-top-item-name">
Analytics
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a title="CI / CD" href="/gulley/contribution-template/-/pipelines/charts"><span>CI / CD</span>
</a></li><li class=""><a class="shortcuts-repository-charts" title="Repository" href="/gulley/contribution-template/-/graphs/master/charts"><span>Repository</span>
</a></li><li class=""><a class="shortcuts-project-cycle-analytics" title="Value Stream" href="/gulley/contribution-template/-/value_stream_analytics"><span>Value Stream</span>
</a></li></ul>
</li>
<li class=""><a class="shortcuts-wiki" data-qa-selector="wiki_link" href="/gulley/contribution-template/-/wikis/home"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#book"></use></svg>
</div>
<span class="nav-item-name">
Wiki
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a href="/gulley/contribution-template/-/wikis/home"><strong class="fly-out-top-item-name">
Wiki
</strong>
</a></li></ul>
</li>
<li class=""><a class="shortcuts-snippets" data-qa-selector="snippets_link" href="/gulley/contribution-template/snippets"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#snippet"></use></svg>
</div>
<span class="nav-item-name">
Snippets
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a href="/gulley/contribution-template/snippets"><strong class="fly-out-top-item-name">
Snippets
</strong>
</a></li></ul>
</li><li class=""><a title="Members" class="qa-members-link" id="js-onboarding-members-link" href="/gulley/contribution-template/-/project_members"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#users"></use></svg>
</div>
<span class="nav-item-name">
Members
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a href="/gulley/contribution-template/-/project_members"><strong class="fly-out-top-item-name">
Members
</strong>
</a></li></ul>
</li><a class="toggle-sidebar-button js-toggle-sidebar qa-toggle-sidebar rspec-toggle-sidebar" role="button" title="Toggle sidebar" type="button">
<svg class="icon-chevron-double-lg-left"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#chevron-double-lg-left"></use></svg>
<svg class="icon-chevron-double-lg-right"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#chevron-double-lg-right"></use></svg>
<span class="collapse-text">Collapse sidebar</span>
</a>
<button name="button" type="button" class="close-nav-button"><svg class="s16"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#close"></use></svg>
<span class="collapse-text">Close sidebar</span>
</button>
<li class="hidden">
<a title="Activity" class="shortcuts-project-activity" href="/gulley/contribution-template/activity"><span>
Activity
</span>
</a></li>
<li class="hidden">
<a title="Network" class="shortcuts-network" href="/gulley/contribution-template/-/network/master">Graph
</a></li>
<li class="hidden">
<a class="shortcuts-new-issue" href="/gulley/contribution-template/-/issues/new">Create a new issue
</a></li>
<li class="hidden">
<a title="Jobs" class="shortcuts-builds" href="/gulley/contribution-template/-/jobs">Jobs
</a></li>
<li class="hidden">
<a title="Commits" class="shortcuts-commits" href="/gulley/contribution-template/-/commits/master">Commits
</a></li>
<li class="hidden">
<a title="Issue Boards" class="shortcuts-issue-boards" href="/gulley/contribution-template/-/boards">Issue Boards</a>
</li>
</ul>
</div>
</div>

<div class="content-wrapper">
<div class="mobile-overlay"></div>
<div class="alert-wrapper">












<nav class="breadcrumbs container-fluid container-limited" role="navigation">
<div class="breadcrumbs-container">
<button name="button" type="button" class="toggle-mobile-nav"><span class="sr-only">Open sidebar</span>
<i aria-hidden="true" data-hidden="true" class="fa fa-bars"></i>
</button><div class="breadcrumbs-links js-title-container" data-qa-selector="breadcrumb_links_content">
<ul class="list-unstyled breadcrumbs-list js-breadcrumbs-list">
<li><a href="/gulley">Ned Gulley</a><svg class="s8 breadcrumbs-list-angle"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#angle-right"></use></svg></li> <li><a href="/gulley/contribution-template"><span class="breadcrumb-item-text js-breadcrumb-item-text">Contribution Template</span></a><svg class="s8 breadcrumbs-list-angle"><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#angle-right"></use></svg></li>

<li>
<h2 class="breadcrumbs-sub-title"><a href="/gulley/contribution-template/-/blob/master/SECURITY.md">Repository</a></h2>
</li>
</ul>
</div>

</div>
</nav>

<div class="d-flex"></div>
</div>
<div class="container-fluid container-limited ">
<div class="content" id="content-body">
<div class="flash-container flash-container-page sticky">
</div>

<div class="js-signature-container" data-signatures-path="/gulley/contribution-template/-/commits/3050cf920a9322a77b21286dd02b66da420771e5/signatures?limit=1"></div>

<div class="tree-holder" id="tree-holder">
<div class="nav-block">
<div class="tree-ref-container">
<div class="tree-ref-holder">
<form class="project-refs-form" action="/gulley/contribution-template/-/refs/switch" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="destination" id="destination" value="blob" />
<input type="hidden" name="path" id="path" value="SECURITY.md" />
<div class="dropdown">
<button class="dropdown-menu-toggle js-project-refs-dropdown qa-branches-select" type="button" data-toggle="dropdown" data-selected="master" data-ref="master" data-refs-url="/gulley/contribution-template/refs?sort=updated_desc" data-field-name="ref" data-submit-form-on-click="true" data-visit="true"><span class="dropdown-toggle-text ">master</span><i aria-hidden="true" data-hidden="true" class="fa fa-chevron-down"></i></button>
<div class="dropdown-menu dropdown-menu-paging dropdown-menu-selectable git-revision-dropdown qa-branches-dropdown">
<div class="dropdown-page-one">
<div class="dropdown-title"><span>Switch branch/tag</span><button class="dropdown-title-button dropdown-menu-close" aria-label="Close" type="button"><i aria-hidden="true" data-hidden="true" class="fa fa-times dropdown-menu-close-icon"></i></button></div>
<div class="dropdown-input"><input type="search" id="" class="dropdown-input-field qa-dropdown-input-field" placeholder="Search branches and tags" autocomplete="off" /><i aria-hidden="true" data-hidden="true" class="fa fa-search dropdown-input-search"></i><i aria-hidden="true" data-hidden="true" role="button" class="fa fa-times dropdown-input-clear js-dropdown-input-clear"></i></div>
<div class="dropdown-content"></div>
<div class="dropdown-loading"><i aria-hidden="true" data-hidden="true" class="fa fa-spinner fa-spin"></i></div>
</div>
</div>
</div>
</form>
</div>
<ul class="breadcrumb repo-breadcrumb">
<li class="breadcrumb-item">
<a href="/gulley/contribution-template/-/tree/master">contribution-template
</a></li>
<li class="breadcrumb-item">
<a href="/gulley/contribution-template/-/blob/master/SECURITY.md"><strong>SECURITY.md</strong>
</a></li>
</ul>
</div>
<div class="tree-controls gl-children-ml-sm-3"><a class="btn shortcuts-find-file" rel="nofollow" href="/gulley/contribution-template/-/find_file/master">Find file
</a><a class="btn js-blob-blame-link" href="/gulley/contribution-template/-/blame/master/SECURITY.md">Blame</a><a class="btn" href="/gulley/contribution-template/-/commits/master/SECURITY.md">History</a><a class="btn js-data-file-blob-permalink-url" href="/gulley/contribution-template/-/blob/9af890249e4ebf727ec1f107b87421c6c284c180/SECURITY.md">Permalink</a></div>
</div>

<div class="info-well d-none d-sm-block">
<div class="well-segment">
<ul class="blob-commit-info">
<li class="commit flex-row js-toggle-container" id="commit-3050cf92">
<div class="avatar-cell d-none d-sm-block">
<a href="/mshakeri"><img alt="Mojdeh Shakeri&#39;s avatar" src="/uploads/-/system/user/avatar/3046/mshakeri_tn_large.jpg?width=40" class="avatar s40 d-none d-sm-inline-block" title="Mojdeh Shakeri" /></a>
</div>
<div class="commit-detail flex-list">
<div class="commit-content qa-commit-content">
<a class="commit-row-message item-title js-onboarding-commit-item " href="/gulley/contribution-template/-/commit/3050cf920a9322a77b21286dd02b66da420771e5">Update SECURITY.md. Removed reporting to Github, and added markup.</a>
<span class="commit-row-message d-inline d-sm-none">
&middot;
3050cf92
</span>
<div class="committer">
<a class="commit-author-link js-user-link" data-user-id="3046" href="/mshakeri">Mojdeh Shakeri</a> authored <time class="js-timeago" title="Feb 19, 2020 4:16pm" datetime="2020-02-19T16:16:04Z" data-toggle="tooltip" data-placement="bottom" data-container="body">Feb 19, 2020</time>
</div>

</div>
<div class="commit-actions flex-row">

<div class="js-commit-pipeline-status" data-endpoint="/gulley/contribution-template/-/commit/3050cf920a9322a77b21286dd02b66da420771e5/pipelines?ref=master"></div>
<div class="commit-sha-group d-none d-sm-flex">
<div class="label label-monospace monospace">
3050cf92
</div>
<button class="btn btn btn-default" data-toggle="tooltip" data-placement="bottom" data-container="body" data-title="Copy commit SHA" data-class="btn btn-default" data-clipboard-text="3050cf920a9322a77b21286dd02b66da420771e5" type="button" title="Copy commit SHA" aria-label="Copy commit SHA"><svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#copy-to-clipboard"></use></svg></button>

</div>
</div>
</div>
</li>

</ul>
</div>


</div>
<div class="blob-content-holder" id="blob-content-holder">
<article class="file-holder">
<div class="js-file-title file-title-flex-parent">
<div class="file-header-content">
<i aria-hidden="true" data-hidden="true" class="fa fa-file-text-o fa-fw"></i>
<strong class="file-title-name">
SECURITY.md
</strong>
<button class="btn btn-clipboard btn-transparent" data-toggle="tooltip" data-placement="bottom" data-container="body" data-class="btn-clipboard btn-transparent" data-title="Copy file path" data-clipboard-text="{&quot;text&quot;:&quot;SECURITY.md&quot;,&quot;gfm&quot;:&quot;`SECURITY.md`&quot;}" type="button" title="Copy file path" aria-label="Copy file path"><svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#copy-to-clipboard"></use></svg></button>
<small class="mr-1">
389 Bytes
</small>
</div>

<div class="file-actions"><div class="btn-group js-blob-viewer-switcher ml-2" role="group">
<button aria-label="Display source" class="btn btn-default btn-sm js-blob-viewer-switch-btn has-tooltip" data-container="body" data-viewer="simple" title="Display source">
<svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#code"></use></svg>
</button><button aria-label="Display rendered file" class="btn btn-default btn-sm js-blob-viewer-switch-btn has-tooltip" data-container="body" data-viewer="rich" title="Display rendered file">
<svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#doc-text"></use></svg>
</button></div><button name="button" type="submit" class="btn btn-primary js-edit-blob ml-2  js-edit-blob-link-fork-toggler" data-action="edit" data-fork-path="/gulley/contribution-template/-/forks?continue%5Bnotice%5D=You%27re+not+allowed+to+make+changes+to+this+project+directly.+A+fork+of+this+project+has+been+created+that+you+can+make+changes+in%2C+so+you+can+submit+a+merge+request.&amp;continue%5Bnotice_now%5D=You%27re+not+allowed+to+make+changes+to+this+project+directly.+A+fork+of+this+project+is+being+created+that+you+can+make+changes+in%2C+so+you+can+submit+a+merge+request.&amp;continue%5Bto%5D=%2Fgulley%2Fcontribution-template%2F-%2Fedit%2Fmaster%2FSECURITY.md&amp;namespace_key=4750">Edit</button><button name="button" type="submit" class="btn btn-inverted btn-primary ide-edit-button ml-2 js-edit-blob-link-fork-toggler" data-action="edit" data-fork-path="/gulley/contribution-template/-/forks?continue%5Bnotice%5D=You%27re+not+allowed+to+make+changes+to+this+project+directly.+A+fork+of+this+project+has+been+created+that+you+can+make+changes+in%2C+so+you+can+submit+a+merge+request.&amp;continue%5Bnotice_now%5D=You%27re+not+allowed+to+make+changes+to+this+project+directly.+A+fork+of+this+project+is+being+created+that+you+can+make+changes+in%2C+so+you+can+submit+a+merge+request.&amp;continue%5Bto%5D=%2F-%2Fide%2Fproject%2Flipingw%2Fcontribution-template%2Fedit%2Fmaster%2F-%2FSECURITY.md&amp;namespace_key=4750">Web IDE</button><div class="btn-group ml-2" role="group">

<button name="button" type="submit" class="btn btn-default js-edit-blob-link-fork-toggler" data-action="replace" data-fork-path="/gulley/contribution-template/-/forks?continue%5Bnotice%5D=You%27re+not+allowed+to+make+changes+to+this+project+directly.+A+fork+of+this+project+has+been+created+that+you+can+make+changes+in%2C+so+you+can+submit+a+merge+request.+Try+to+replace+this+file+again.&amp;continue%5Bnotice_now%5D=You%27re+not+allowed+to+make+changes+to+this+project+directly.+A+fork+of+this+project+is+being+created+that+you+can+make+changes+in%2C+so+you+can+submit+a+merge+request.&amp;continue%5Bto%5D=%2Fgulley%2Fcontribution-template%2F-%2Fblob%2Fmaster%2FSECURITY.md&amp;namespace_key=4750">Replace</button>
<button name="button" type="submit" class="btn btn-default js-edit-blob-link-fork-toggler" data-action="delete" data-fork-path="/gulley/contribution-template/-/forks?continue%5Bnotice%5D=You%27re+not+allowed+to+make+changes+to+this+project+directly.+A+fork+of+this+project+has+been+created+that+you+can+make+changes+in%2C+so+you+can+submit+a+merge+request.+Try+to+delete+this+file+again.&amp;continue%5Bnotice_now%5D=You%27re+not+allowed+to+make+changes+to+this+project+directly.+A+fork+of+this+project+is+being+created+that+you+can+make+changes+in%2C+so+you+can+submit+a+merge+request.&amp;continue%5Bto%5D=%2Fgulley%2Fcontribution-template%2F-%2Fblob%2Fmaster%2FSECURITY.md&amp;namespace_key=4750">Delete</button>
</div><div class="btn-group ml-2" role="group">
<button class="btn btn btn-sm js-copy-blob-source-btn" data-toggle="tooltip" data-placement="bottom" data-container="body" data-class="btn btn-sm js-copy-blob-source-btn" data-title="Copy file contents" data-clipboard-target=".blob-content[data-blob-id=&#39;221952e44bcd5a86b1b981693bff30829ab597ae&#39;]" type="button" title="Copy file contents" aria-label="Copy file contents"><svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#copy-to-clipboard"></use></svg></button>
<a class="btn btn-sm has-tooltip" target="_blank" rel="noopener noreferrer" aria-label="Open raw" title="Open raw" data-container="body" href="/gulley/contribution-template/-/raw/master/SECURITY.md"><svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#doc-code"></use></svg></a>
<a download="SECURITY.md" class="btn btn-sm has-tooltip" target="_blank" rel="noopener noreferrer" aria-label="Download" title="Download" data-container="body" href="/gulley/contribution-template/-/raw/master/SECURITY.md?inline=false"><svg><use xlink:href="/assets/icons-ec7938f444d9d661d3229540fb7eb27a11097485f6b2b8424e0b588d2f3369ae.svg#download"></use></svg></a>

</div></div>
</div>
<div class="js-file-fork-suggestion-section file-fork-suggestion hidden">
<span class="file-fork-suggestion-note">
You're not allowed to
<span class="js-file-fork-suggestion-section-action">
edit
</span>
files in this project directly. Please fork this project,
make your changes there, and submit a merge request.
</span>
<a class="js-fork-suggestion-button btn btn-grouped btn-inverted btn-success" rel="nofollow" data-method="post" href="/gulley/contribution-template/-/blob/master/SECURITY.md">Fork</a>
<button class="js-cancel-fork-suggestion-button btn btn-grouped" type="button">
Cancel
</button>
</div>



<div class="blob-viewer hidden" data-path="SECURITY.md" data-type="simple" data-url="/gulley/contribution-template/-/blob/master/SECURITY.md?format=json&amp;viewer=simple">
<div class="text-center gl-mt-3 gl-mb-3">
<i aria-hidden="true" aria-label="Loading content…" class="fa fa-spinner fa-spin fa-2x qa-spinner"></i>
</div>

</div>

<div class="blob-viewer" data-path="SECURITY.md" data-rich-type="markup" data-type="rich" data-url="/gulley/contribution-template/-/blob/master/SECURITY.md?format=json&amp;viewer=rich">
<div class="text-center gl-mt-3 gl-mb-3">
<i aria-hidden="true" aria-label="Loading content…" class="fa fa-spinner fa-spin fa-2x qa-spinner"></i>
</div>

</div>


</article>
</div>

<div class="modal" id="modal-upload-blob">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<h3 class="page-title">Replace SECURITY.md</h3>
<button aria-label="Close" class="close" data-dismiss="modal" type="button">
<span aria-hidden>&times;</span>
</button>
</div>
<div class="modal-body">
<form class="js-quick-submit js-upload-blob-form" data-method="put" action="/gulley/contribution-template/-/update/master/SECURITY.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="02fiGtVZPxqRJUknzvJorAiLlHoJXJj6M2yIf5nRZg5CHNnlwNL10Q8Mm9LTnKOfK9u3M5Vi9HszhIMBycaRNQ==" /><div class="dropzone">
<div class="dropzone-previews blob-upload-dropzone-previews">
<p class="dz-message light">
Attach a file by drag &amp; drop or <a class="markdown-selector" href="#">click to upload</a>
</p>
</div>
</div>
<br>
<div class="dropzone-alerts alert alert-danger data" style="display:none"></div>
<div class="form-group row commit_message-group">
<label class="col-form-label col-sm-2" for="commit_message-7586ba1f5496c73cc763d155e8073cf0">Commit message
</label><div class="col-sm-10">
<div class="commit-message-container">
<div class="max-width-marker"></div>
<textarea name="commit_message" id="commit_message-7586ba1f5496c73cc763d155e8073cf0" class="form-control js-commit-message" placeholder="Replace SECURITY.md" required="required" rows="3">
Replace SECURITY.md</textarea>
</div>
</div>
</div>

<input type="hidden" name="branch_name" id="branch_name" />
<input type="hidden" name="create_merge_request" id="create_merge_request" value="1" />
<input type="hidden" name="original_branch" id="original_branch" value="master" class="js-original-branch" />

<div class="form-actions">
<button name="button" type="button" class="btn btn-success btn-upload-file" id="submit-all"><i aria-hidden="true" data-hidden="true" class="fa fa-spin fa-spinner js-loading-icon hidden"></i>
Replace file
</button><a class="btn btn-cancel" data-dismiss="modal" href="#">Cancel</a>
<div class="inline gl-ml-3">
A new branch will be created in your fork and a new merge request will be started.
</div>

</div>
</form></div>
</div>
</div>
</div>

</div>


</div>
</div>
</div>
</div>


<script>
//<![CDATA[
if ('loading' in HTMLImageElement.prototype) {
  document.querySelectorAll('img.lazy').forEach(img => {
    img.loading = 'lazy';
    let imgUrl = img.dataset.src;
    // Only adding width + height for avatars for now
    if (imgUrl.indexOf('/avatar/') > -1 && imgUrl.indexOf('?') === -1) {
      const targetWidth = img.getAttribute('width') || img.width;
      imgUrl += `?width=${targetWidth}`;
    }
    img.src = imgUrl;
    img.removeAttribute('data-src');
    img.classList.remove('lazy');
    img.classList.add('js-lazy-loaded', 'qa-js-lazy-loaded');
  });
}

//]]>
</script>

</body>
</html>

