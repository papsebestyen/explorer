```{mermaid}

    flowchart LR
        
        covid_victims([Covid Victims]) --- covid_victims_covid_victim[Covid Victim]
        click covid_victims_covid_victim href "file:///tmp/tmpcl_pusvu/covid_victims/covid_victim-profile.html" "Profile"
        
        pypi_downloads([Pypi Downloads]) --- pypi_downloads_package_download[Package Download]
        click pypi_downloads_package_download href "file:///tmp/tmpcl_pusvu/pypi_downloads/package_download-profile.html" "Profile"
        
```