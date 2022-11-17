function hello() {
    let userName = prompt("Hello Rider, who are you?")
    if (userName == "") {
        alert("You got one more chance");
    }
    userName = prompt("for real, who are you??");
    document.write("Rider " + userName);
    console.log("Rider's name is: " + userName);
    return userName;
}



let response = prompt("Do you promise to ride safe?");
if (response == "Yes") {
    alert("Good Job");
    document.write("  promised to be SAFE");
} else if (response == "No") {
    alert("That's TERRIBLE CHOISE");
    document.write("  is DANGEROUS :)");
} else {
    alert("Try again!!!");
    document.write(" not sure about his life");
}


(https://yhluk.github.io/hello-world/)
