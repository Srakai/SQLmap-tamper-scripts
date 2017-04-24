# SQLmap-tamper-scripts
used to bypass some firewalls

    Encapsulates statements in speciall comment

        * Useful to bypass weak and bespoke web application firewalls
        * Propably works only with MySQL	
        * Baypasses firewalls that forbid certain words
        * Tested against some custom firewalls, did great job

    >>> tamper('SELECT id FROM users')
    '/**//*!50000SELECT*//**/ id /**//*!50000FROM*//**/ users'
    
# Author
@Srakai (swientymateusz at gmail d0t com)
