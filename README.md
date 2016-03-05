# SQLiteBD
Basic SQLite wrapper for Swift 2.0 and up(https://github.com/FahimF/SQLiteDB) add a new feature

I add a new feature to FahimF's source code. 

        //sAQuery only return one element
        let Count = db.sAQuery("select count(*) from t_user") as! Int!
        numberOfUser.text = String(Count) + " User"
