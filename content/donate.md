---
title: "Donate"
date: 2024-08-26
layout: "donate"
---

Your support helps us continue to provide valuable content and services. If you would like to make a donation, please use the form below.

<form action="/donate" method="post" class="donate-form">
    <label for="amount">Donation Amount:</label>
    <input type="number" id="amount" name="amount" min="1" required>

    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <button type="submit">Donate</button>
</form>
