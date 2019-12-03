<template>
  <div>
  <div>
    <h1 class="contactMe">KONTAKT</h1>
    <b-form class="formular">
      <p class="divText">För förfrågan eller beställning av bilder använd gärna formuläret nedan:</p>
      <label class="sr-only" for="inline-form-input-name">Name</label>
      <b-input
        id="inline-form-input-name"
        class="formularInput"
        placeholder="Namn..">
      </b-input>
      <label class="sr-only" for="inline-form-input-email">Email</label>
      <b-input
        id="inline-form-input-email"
        class="formularInput"
        placeholder="Email..">
      </b-input>
      <label class="sr-only" for="inline-form-input-email">Message</label>
      <b-form-textarea id="inline-form-input-text" class="formularInput" placeholder="Skriv ditt meddelande här.."></b-form-textarea>
      <b-button variant="bg-transparent" class="sendButton">Skicka</b-button>
    </b-form>
  </div>
      <p class="divTextTwo">För övriga frågor når du mig på:</p>
   <div class="divText">
      <a href="tel:+46855050000" class="iconSpace"> <font-awesome-icon :icon="{ prefix: 'fa', iconName: 'phone-square' }" class="zoom" /></a>
        0736723176
    </div>
    <div class="divText">
      <a href="mailto:name@email.com" class="iconSpace"><font-awesome-icon :icon="{ prefix: 'fa', iconName: 'envelope-square' }" class="zoom" /></a>
        diana.skshipek@hotmail.com
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contact'
}
</script>

<style>
.formular {
  width: 25%;
  margin-left: 5px;
  margin-top: 100px;
  margin-bottom: 20px;
}

.formularInput {
  width: 100%;
  background-color: transparent;
  border: 1px solid black;
  margin: 5px;
  color: #e3ddcd;
  box-shadow: inset 0 0 10px grey;
  font-size: 15px;
  font-family: 'Montserrat'; 
  font-style: normal;
}

.formularInput::placeholder {
  color: #e3ddcd;
}

.sendButton {
  border: 1px solid black;
  width: 20%;
  border-radius: 10px;
  box-shadow: inset 0 0 10px grey;
  color: #e3ddcd;
  font-family: 'Montserrat'; 
  font-style: normal;
  margin: 5px;
}

.divText {
  margin-left: 10px;
  font-size: 17px;
  font-family: 'Montserrat'; 
  color: #e3ddcd;
}

.divTextTwo{
  margin-left: 5px;
  font-size: 17px;
  margin-top: 50px;
  font-family: 'Montserrat'; 
  color: #e3ddcd;
}

.contactMe {
  margin-top: 40px;
  margin-left: 20px;
  margin-bottom: 30px;
  color: #e3ddcd;
}

.iconSpace {
  margin-right: 5px;
}
</style>