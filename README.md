# Form Eleman Kullanımı 

## Aşağıdaki sıra ile oluşturuldu.

* `index.html` eklendi.
* Ad ve soyad bilgisi için aşağıdaki elemanlar oluşturuldu.
    ```
    <label for="fname">Adınız :</label><br>
    <input type="text" id="fname"><br>
    <label for="lname">Soyadınız :</label><br>
    <input type="text" id="lname"><br>
    ```
* Mail bilgisi için aşağidaki elemanlar oluşturuldu.
```
    <label for="mail">Mail Adresiniz :</label><br>
    <input type="email" id="mail"><br>
```
* Password bilgisi için aşağıdaki elemanlar oluşturuldu.
```
<label for="password">Parola Giriniz</label><br>
<input type="password"><br>
```
* Cinsiyet bilgisi için aşağıdaki elemanlar oluşturuldu.
```
    <p>Cinsiyetinizi Giriniz :</p>
    <input type="radio" name="gender" id="male" value="male">
    <label for="male">Erkek</label>
    <input type="radio" name="gender" id="female" value="female">
    <label for="female">Kadın</label>
        <br><br>
```
 * Favori meyve bilgisi select option ile oluşturuldu.
 ```
    <label for="fruits"> Meyvenizi Seçiniz;</label>
        <select name="fruits" id="fruits">
            <option value="elma">Elma</option>
            <option value="muz">Muz</option>
            <option value="cilek">Çilek</option>
        </select>
        <br><br>
```   
* Mesaj alanı textarea ile oluşturuldu. 
```
    <label for="message">Mesaj :</label><br>
    <textarea name="message" id="message" rows="4" cols="50"></textarea>
    <br>
```
* Submit kısmı oluşturuldu ve bilgilerin gönderileceği backend olmadığı için `submit_form.html` kısmına kullanıcı yönlendirildi.
```
<input type="submit" value="Gönder">
```
*`submit_form.html` ve `index.html` style olarak değiştirildi.
```
h1 {
    text-align: center;
}
form {
    color: black;
    background-color: antiquewhite;
    border: 1px solid black;
    width: 100%;
    text-align: center;
}
```
```
html {
        background-color: antiquewhite;
    }
    h1 {
        text-align: center;
        font-size: 150px;
    }
```
