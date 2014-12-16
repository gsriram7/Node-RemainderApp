Node-RemainderApp
=================
Install 

MongoDB
NodeJS
npm

Mongo cmd to update med

> db.users.update({'email':'gsriram7@gmail.com'},{$set:{'meds':{'name':'Paracetemol','start_date':"2012-10-05",'end_date':"2014-12-12",'course':100000,'desc':'F
ever tablet','dosage':'2 mg'}}})
WriteResult({ "nMatched" : 1, "nUpserted" : 0, "nModified" : 1 })
