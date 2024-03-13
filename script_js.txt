function changeColor() {
    var letters = '0123456789ABCDEF';
    var color = '#';
    for (var i = 0; i < 6; i++) {
        color += letters[Math.floor(Math.random() * 16)];
    }
    document.body.style.backgroundColor = color;
    document.getElementById('color-code').innerText = color;
    
    // Set the color of the color code text
    document.getElementById('color-code').style.color = color;
}
