document type html>
 <head>
     <title>important question</title>
     <h1>📚 DEGREE IMPORTANT QUESTION</h1>
      
 </head>
 <body>
       <div class="container">
       <select id="subject">
    <option value="">--semster-1--</option>
    <option value="english">english-1</option>
    <option value="telugu">telugu-1</option>
    <option value="maths">Differential and calcus</option>
    <option value="mechincs">Mechincs and osclliation</option>
    <option value="PROGRAMMING">PROGRAMMING IN C</option>
    <option value="AECC"> Enivormental science</option>
  </select>
      <select id="subject">
        <option value="">--semster-2</option>
        <option value="general">english-2</option>
        <option value="second ">Telugu-2</option>
        <option value="Differential">Differential Equations</option>
        <option value="thermal">Thermal physics</option>
        <option value="programming">PROGRAMMING IN C++</option>
      </select>
  <div id="output"></div>

       
 </body>
 <style>
    .container{
        max-width: 600px;
        margin:30px auto;
        background-color: white;
        padding:20px;
        border-radius:10px;
        box-shadow: 0 0 10px #ccc;


    }
      h1{
        text-align: center;
        color:#333;

      }
      label,select{
        display:block;
        margin: 15px 0 5px;
        font-weight:bold;
      }
      select{
        width: 100%;
        padding:10px;
        font-size: 16px;
      }
      body{
        font-family: Arial, Helvetica, sans-serif;
        background-color: #ccc;
        margin: 0;
        padding: 0;
      }
      </style>

  <script>
    const questions = {
      english:[
      
        "UNIT-1",
        "Rauskin Bond narrated a touching story justifly",
        "write a brief note on Ruskin Bond judtifly",
        "oh! how lucky you are i wish! i were going to Mussorie i love the hills espically in october",
        "she was an interstin girl , i said can you tell me ... did she keep her hair long or short?",
        "UNIT-2",
        "Explian A.P.J Abdul kalam a duty as an engineer",
        "Kalam is a commited aerospace engineer and people's president Explian",
        "UNIT-3",
        "write a brief on Bangle seller's",
        "Explian how Sarojini Naidu showed colorful lite of indian Woman?",
        "UNIT-4",
        "write an essay on The Merchant of venice",
        "Antonio's plight,Discuss",
        "And by our holy Sabbath have i sworn to have the due and foriet of my bond;",
        "if every ducal in six thousand ducats were in six parts, and every part a ducat i would not draw them; I would have my bond !",
        "Therefore prepare thee to cut off the flesh shed thou no blood,nor cut off the thou less nor more But just a pound of flesh", 
        

      ],
    
      telugu: [
        "UNIT-1",
        "1. శకుంతల రాజసభలో దుష్యంతునికి కాపాలించిన ధర్మ ప్రకటనను వివరించండి",

        "శకుంతల రాజసభలో చేసిన ధర్మోపదేశాన్ని వివరించండి.",
        "శకుంతల ధర్మోపదేశాన్ని వివరంగా తెలపండి",
        "కొత్త పంథా పోషకుడు నిన్ను పోషకునిగా ఎలా చెబుతాడు?",
        ". కడపలయో హీన గతి కలిగిన దేశమా?",
        ". కలతకరం! ఇండియా ముజప్పరం",
        ". ఓ.సి. నేడు పారాయణ ద్రావ?",
        ". పదములో దాదా జలజల వదమా?నోదివ మాదరలో జడజల వదమా?",
        ". కాపుసాలలకీ కష్టపాలవేమీ?",
       " 1. సంస్కరుడు రచనను రచించిన విధానాన్ని అర్ధంచేసుకొని గంగాధర రచనా శైలి ఏవిధంగా ఉంది? (లఘు)సంస్కరుడు రచనను రచించిన విధానాన్ని తెలియజేయండి.",
      "2. సంస్కరుడు, చంద్రశేఖర రాజా, జడా, సూర్యరావు వంటి పాత్రల ముఖ్య పాత్రలను వివరించండి.ముఖ్యంగా భక్తిరసం, పొలాండాస సూర్యరావు పాత్ర ప్రాముఖ్యతను వివరించాలి.",
        "UNIT-2",
       "‘కాములు’ కవితా విధాకం గురించి వివరించండి. ఈ విధాకం మీద దృష్టిని వివరించండి. (O.U & P.U 2016)",
       "‘రాజా - కవి’ అనుబంధాన్ని ఆధారంగా రాజశేఖర కవి విశిష్టత వివరించండి.",
       "అండాల రాజశేఖరుని కవితా వైశిష్ట్యం వివరించండి",

       "గంగాధరమేఘవాహనుడు గంగాధరుడిగా ఎలా ప్రసిద్ధి చెందాడు?",
      " 1. జాతిపిత మహాత్మా గాంధీజీ (శ్రీ మోకా అశోక్)?",
      "శ్రీ భగవంతుని జయజయకారము ",
       "1. దుర్వాసముని గురించి వివరించండి. (O.U 2016)", 







      ],
       mechincs: [
        "UNIT-1",
        "VECTOR ANALYSICS",
        "Long question",
        "state and prove Gauess Divgence theroem?",
        "state and probe Green identical theroem?",
        "state and prove stokes theroem",
        "short question",
        "explian Divegernce of vector field",
        "explian Gradient of scalar field",
        "explian line ,volume,sufarce intergal?,",
        "UNIT-2",
        "LONG QUESTION",
        "MECHIANCS PARTICULE",
        "explian variable mass system",
        "explian motion of rocket ",
        "explian about elastic collision two dimensional",
        "SHORT QUESTION",
        "conservation of linear momentum",
        "conservation of angular momentum",
        "conservation of energy law's",
        "explian about mutil-stage rocket",
        "explian about Gyroscope?",
        "explian about impact parameter",
        "MECHANICS OF RIGID BODY",
        "LONG QUESTION",
        "explain about euler's equations",
        "equations of motion of  rigid body roating body  ",
        "explian about angluar momentum",
        "short question",
        "Relation between torque and angluar momentum",
        "angluar momentum aand intnerta tensor",
        "UNIT-3",
        "CENTRAL FORCE",
        "LONG QUESTION",
        "Equation of motion under central force",
        "kepler's first law ",
        "SHORT QUESTION",
        "kepler's second law",
        "kepler's thrid law",
        "UNIT-3",
        "SPECIAL THEORY OF RELATIVITY",
        "LONG  QUESTION",
        "Galien  Transformation",
        "lortenz transformation of space and time",
        "energy and momentum realtion",
        "SHORT QUESTION",
        "length contraction",
        "time dilation",
        "UNIT-4",
        "FUNDAMENTALS OF VIBRATION",
        "LONG QUESTION",
        "DAMPED HAROMIC OSCLLIATIONS",
        "FORCE HAROMIC OSCLLIATIONS",
        "SIMPLE HAROMUC OSCLLIATIONS",

        

        
        
      ],
        
      PROGRAMMING:[
        
          "UNIT-1",
          "LONG QUESTION",
          "Generation of computer",
          "classfication of computer",
          "Data types ",
          "operator",
          "SHORT QUESTION",
          "C tokens",
          "idenfiles",
          "UNIT-2",
          "LONG QUESTION",
          "Forammted and unformatted ",
          "two-dimesional arrays",
          "conditon stament",
          "control stament",
          "arrays",
          "strings",
          "string manuplication",
          "SHORT QUESTION",
          "formatted and unformatted",
          "one - dimesional arrays",
          "switch stament",
          "break",
          "conutine",
          "UNIT-3",
          "LONG QUESTION",
          "arrays to function",
          "recursion",
          "function",
          "pointer to pointer",
          "array to pointer",
          
          "SHORT QUESTION",
          "storage class",
          "call by value and call by refernece",
          "lnline function",
          "dymanic allocation",
          "UNIT-4",
          "LONG QUESTION",
          "structure",
          "union",
          "worling with text files",
          "binray files",
          "files of rcords",
          "SHORT QUESTION",
          "enumarted data type"

          


      
      ],
     
      AECC:[
       




    ]
    };
        

    document.getElementById("subject").onchange = function() {
      const t = this.value;
      const q = questions[t] || [];
      document.getElementById("output").innerHTML = "<ul>" + q.map(q => "<li>" + q + "</li>").join("") + "</ul>";
    };
    
  </script>


</body>
</html>

</body>
</html>

</body>
</html>