This powershell script will add the categories defined in the config file and then create Flow security policies for the categories.  

The design is to create an entry in the AppType category and then nest the application name under the proper group.  This was done this way to allow for more categories since the current limit on categories is 25 keys and 50 values per key.  This method allows for more than 50 values.
