<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salesforce Chatbot Test</title>
</head>

<body>
    <h1>Salesforce Chatbot Test</h1>

    <script type="text/javascript">
        function initEmbeddedMessaging() {
            try {
                embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
                embeddedservice_bootstrap.init(
                    '00DOv000007ABPZ',
                    'Testing_App',
                    'https://clearcaptions123--nkbackup.sandbox.my.site.com/ESWTestingApp1717680368430',
                    {
                        scrt2URL: 'https://clearcaptions123--nkbackup.sandbox.my.salesforce-scrt.com'
                    }
                );
            } catch (err) {
                console.error('Error loading Embedded Messaging: ', err);
            }
        };
    </script>

    <script type="text/javascript" src="https://clearcaptions123--nkbackup.sandbox.my.site.com/ESWTestingApp1717680368430/assets/js/bootstrap.min.js" onload="initEmbeddedMessaging()"></script>

</body>

</html>
