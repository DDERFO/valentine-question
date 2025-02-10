document.getElementById("yes-btn").addEventListener("click", function() {
    document.body.innerHTML = "<h1>Knew you would say yes! ❤️</h1>";
});

document.getElementById("no-btn").addEventListener("mouseover", function() {
    let yesBtn = document.getElementById("yes-btn");
    let currentSize = parseFloat(window.getComputedStyle(yesBtn).fontSize);
    yesBtn.style.fontSize = (currentSize + 5) + "px";
    yesBtn.innerHTML = "Are you sure? 😢";
});
