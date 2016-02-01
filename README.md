# Enkla, svåra och svårare uppgifter i Javascript

# Enkla Uppgifter:
1. Skriv en funktion 'max' som returnerar den största av alla tal i en lista.
2. Skriv en funktion 'min' som returnerar den minsta av alla tal i en lista.
3. Skriv en funktion 'sum' som returnerar summan av alla tal i en lista.
4. Skriv en funktion 'multiply' som returnerar produkten av alla tal i en lista.


# Lite svårare uppgifter:
1. Skapa en lista av 1 miljon slumpvalda tal mellan 0 och 10.
2. Koppiera listan i tre olika tester. Test 1 använder en 'loop', test2 'slice' och test3 'concat'. Benchmark alla tester och visa resultat. Vilken metod är snabbast?


# Svårare uppgifter:
1. Förklara resultatet av följande kod:

   var fullname = 'Java Script';
   var obj = {
      fullname: 'Ruby Mine',
      prop: {
         fullname: 'Web Storm',
         getFullname: function() {
            return this.fullname;
         }
      }
   };

   console.log(obj.prop.getFullname());

   var test = obj.prop.getFullname;

   console.log(test());
