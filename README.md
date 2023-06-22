Personnel API
* Deparment ve Personnel tablolarımız olacak bunları birbirlerine bağlayacağız. Her deparmentın altında kendisine ait personel olacak.
* Staff olan personel yeni personel listeye ekleyebilecek, update edebilecek.(staff dan kasıt yetkili olan bunu farklı cheff de diyebilirsiniz. Staff ismi django user modelinde bulunan is_staff dan geliyor )
* Dinamik url ile url de gelen isteğe göre response değişecek. Yani departmenlara ait personeli listelemek istediğimizde bunu tek bir url üzerinden yapacağız. Swagger da örneği var.
* Staff olmayanlar sadece listeleyebiliecek.
* Personeli silme yetkisi sadece superuserlarda olacak.
* Token authentication kullanacağız. Kullanıcı logout olduğunda tokeni sileceğiz.

<br/>

Personnel API
* We will have Deparment and Personnel tables, and we will connect them to each other. Each department will have its own personnel under it.
* Staff members will be able to add new personnel to the list and update them.
* The response will change according to the dynamic url and the url request. In other words, when we want to list the personnel of the departments, we will do this through a single url. Swagger also has an example.
* Non-staff members will only be able to list.
* The authority to delete personnel will be only for superusers.
* We will use token authentication. We will delete the token when the user logout.
