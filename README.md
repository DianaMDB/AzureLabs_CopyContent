# AzureLabs_CopyContent

## Lab 1 
### Document 1 for cakes collection:

```
{
"name":"Chocolate Cake",
"shortDescription":"Chocolate cake is a cake flavored with melted chocolate, cocoa powder, or sometimes both.",
"description":"Chocolate cake is made with chocolate; it can be made with other ingredients, as well. These ingredients include fudge, vanilla creme, and other sweeteners. The history of chocolate cake goes back to 1764, when Dr. James Baker discovered how to make chocolate by grinding cocoa beans between two massive circular millstones.",
"image":"https://addapinch.com/wp-content/uploads/2020/04/chocolate-cake-DSC_1768.jpg",
"ingredients":[
"flour",
"sugar",
"cocoa powder"
],
"stock": 25
}
```

### Document 2 for cakes collection:
```
{
"name":"Cheese Cake",
"shortDescription":"Cheesecake is a sweet dessert consisting of one or more layers. The main, and thickest, layer consists of a mixture of a soft, fresh cheese (typically cottage cheese, cream cheese or ricotta), eggs, and sugar. ", 
"description":"Cheesecake is a sweet dessert consisting of one or more layers. The main, and thickest, layer consists of a mixture of a soft, fresh cheese (typically cottage cheese, cream cheese or ricotta), eggs, and sugar. If there is a bottom layer, it most often consists of a crust or base made from crushed cookies (or digestive biscuits), graham crackers, pastry, or sometimes sponge cake.[1] Cheesecake may be baked or unbaked (and is usually refrigerated).",
"image":"https://sallysbakingaddiction.com/wp-content/uploads/2018/05/perfect-cheesecake-recipe.jpg",
"ingredients":[
"flour",
"sugar",
"eggs"
],
"stock": 40
}
```


## Lab 2

### Power Apps : Swagger Editor
```
            properties:
                  _id:
                    type: string
                    description: _id
                    title: PassportNumber
                  firstname:
                    type: string
                    description: firstname
                    title: firstname
                  lastname:
                    type: string
                    description: lastname
                    title: lastname
                  DateOfBirth:
                    type: string
                    description: DateOfBirth
                    title: DateOfBirth
                  passportNumber:
                    type: string
                    description: passportNumber
                    title: passportNumber
                  emailId:
                    type: string
                    description: emailId
                    title: emailId
```

### Power Apps - MongoDB Insert query
```
MongoDB.InsertDocument("Sandbox","XYZBank","onboarding",{_id:Passport.Text,firstname:Upper(Fname.Text),lastname:Upper(Lname.Text),DateOfBirth:DOB.Text,passportNumber:Passport.Text,emailId:email.Text});
Reset(Fname);Reset(Lname);Reset(DOB);Reset(Passport);Reset(email);
```
