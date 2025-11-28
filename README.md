function sendMessage(event) {
    event.preventDefault();

    const name = document.getElementById("name").value;

    document.getElementById("response-message").innerText =
        `धन्यवाद ${name}! आपका संदेश भेज दिया गया है।`;

    document.querySelector(".contact-form").reset();
} Munendr-Kumar-
Munendr yadav digital marketing institute 
