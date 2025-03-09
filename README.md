
         let x = "MahaK, shRivasTava";
        let y = x.split(" ");

       let z = y.map(check => {
        return check === check.toLowerCase() ? check.toUpperCase() : check.toLowerCase();
       });

        console.log(z);
