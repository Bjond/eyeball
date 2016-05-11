![alt text](https://github.com/Bjond/eyeball/blob/master/images/bjondhealthlogo-whitegrey.png "Bjönd Inc.")

#*EyeBall*

Will display, crudely, a link for every System Test HTML report inserted in a subdirectory
within the _public_ folder. An example report in the public subdirectory name 
_SystemTests_Branch_develop_Wed May 11 12:31:59 EDT 2016_ is provided for testing.

I suggest the following naming convention however you may choose what you wish:
SystemTests_Branch_<name of branch here>_Date 

The date is the default date string provided by the Unix _date_ command. This should
make things easy.

If you need to setup rails the beginning of the following tutorial is excellent: <http://guides.rubyonrails.org/getting_started.html>

Once setup you may run the following command to start rails. 
```shell
$ cd eyeball
$ rails server &
```

You may browse to <http://localhost:3000/welcome/index> to view the glorious website.

Every report that constructs a subdirectory within *public/reports* will be displayed. It is that simple.
