om redbeanphp te kunnen gebruiken in je TinyMvc project moet je de volgende 
stappen ondernemen:
    1.  plaats het bestand tinymvc_rb.php in de map tinymvc/myfiles/plugins
    2.  download redbeanphp en plaats het bestand rb.php in de map xampp/redbeans
    3.  voor elk project waarbij je gebruik wenst te maken van redbeanphp stel 
        je in myapp/configs/config_database.php stel je de plugin parameter in 
        op TinyMVC_RB
        $config['default']['plugin'] = 'TinyMVC_RB';