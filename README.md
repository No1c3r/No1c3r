<!doctype html>
<html dir="ltr" lang="en" class="loading"
    
    >
<head>
  <meta charset="utf-8">
  <meta name="color-scheme" content="light dark">
  <title>Settings</title>
  <base href="chrome://settings">
  <link rel="stylesheet" href="chrome://resources/css/md_colors.css">
  <style>
    html {
      background: var(--md-background-color);
      overflow: hidden;
      /* Remove 300ms delay for 'click' event, when using touch interface. */
      touch-action: manipulation;
    }

    html.loading::before {
      background-color: var(--md-toolbar-color);
      border-bottom: var(--md-toolbar-border);
      box-sizing: border-box;
      content: '';
      display: block;
      height: var(--md-toolbar-height);
    }

    html,
    body {
      height: 100%;
      margin: 0;
    }
  </style>
</head>
<body>
  <link rel="stylesheet" href="chrome://resources/css/text_defaults_md.css">
  <script type="module" src="settings.js"></script>
  <settings-ui></settings-ui>
</body>
</html>
