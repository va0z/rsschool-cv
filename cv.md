# Resume

## Name
 Dmitrii M
## Contact Info
va0z@ya.ru
## Symmary
Hone existing skills HTML & CSS, lern JS. Become a high-level web developer  =) and it is possible to find a job. I have a little experience in website development, for a long time I am a system administrator of a large organization.
## Skills
WEB skills: html and some css, I also have experience in php and mysql.
## Code examples (fragment)
Parsing news site for internal web site:

 ```php
 ...
    #process a link to a specific news item
    for($i=0; $i<count($out[0]); $i++)
    {
      $link=$link_b[$i][1][0];
      $titl=$titl_b[$i][1][0];
      if(!ereg("http://",$link) and !ereg("https://",$link)){$link=$news_url_root.$link;}
      if(ereg("3dnews",$link)){$link=$link."print/";} //edit link

      #search link in base
      $bzcount=file($baza);
      $link_new=$link."\n";
      if(in_array($link_new, $bzcount))  
      {
        echo "!!!".$link." - already exists in base \n";
        continue;
      }    #link there is
      fwrite($bz, $link."\n *** ".$titl."\n"); #save link in base

      ### loging ###
      echo "----------------------------------\n";
      echo "link:=> ".$link." saved in base \n";
      fwrite($log, "link:=> ".$link." saved in base \n"); 
      ####################
    ...
```
## Experience 
WEB: internal website of the company division.
## Education 
Higher education and various courses in system administration: 
- plan&adm win2k8+AD, 
- msexchange, 
- cisco CCNA ICND
- and much more.
## English proficiency
 So so. I wish it were better +)
