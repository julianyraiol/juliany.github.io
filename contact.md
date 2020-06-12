---
layout: page
title: Entre em contato conosco!
form: true
background: "/img/banner_home4.jpg"
---

<form name="sentMessage" id="contactForm" novalidate>
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>Name</label>
      <input
        type="text"
        class="form-control"
        placeholder="Nome"
        id="name"
        required
        data-validation-required-message="Por favor, insira seu nome."
      />
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>Email Address</label>
      <input
        type="email"
        class="form-control"
        placeholder="E-mail"
        id="email"
        required
        data-validation-required-message="Por favor, insira seu e-mail."
      />
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <div class="control-group">
    <div class="form-group col-xs-12 floating-label-form-group controls">
      <label>Phone Number</label>
      <input
        type="tel"
        class="form-control"
        placeholder="Telefone"
        id="phone"
        required
        data-validation-required-message="Por favor, insira seu número para contato."
      />
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>Message</label>
      <textarea
        rows="5"
        class="form-control"
        placeholder="Mensagem"
        id="message"
        required
        data-validation-required-message="Por favor, insira a mensagem."
      ></textarea>
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <br />
  <div id="success"></div>
  <div class="form-group">
    <button type="submit" class="btn btn-primary" id="sendMessageButton">
      Enviar
    </button>
  </div>
</form>
