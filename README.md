# Kotlin Q&A (বাংলা) 🇧🇩

এই রেপোজিটরিটি **Kotlin সম্পর্কিত গুরুত্বপূর্ণ প্রশ্নোত্তর (Q&A)** বাংলায় সাজানো হয়েছে।  
নতুনরা Kotlin শেখার সময় এই রেফারেন্সটি ব্যবহার করতে পারবে।  

---

## 📚 Kotlin Q&A

### Q1: Kotlin কোন প্ল্যাটফর্মে চলে?  
**A1:** Kotlin মূলত **JVM (Java Virtual Machine)** এ চলে।  

### Q2: Kotlin কে তৈরি করেছে?  
**A2:** Kotlin তৈরি করেছে **JetBrains**।  

### Q3: Kotlin নামটি কোথা থেকে এসেছে?  
**A3:** Kotlin নাম এসেছে **রাশিয়ার Kotlin Island** থেকে।  

### Q4: Kotlin কি ধরনের টাইপিং ব্যবহার করে?  
**A4:** Kotlin হলো **statically typed language**, অর্থাৎ variable এর type **compile time** এ নির্ধারিত হয়।  

### Q5: Kotlin এর প্রথম রিলিজ কখন হয়েছিল?  
**A5:** Kotlin প্রথম রিলিজ হয় **2016 সালে**।  

### Q6: Google প্রথমবার Kotlin কে স্বীকৃতি দেয় কখন?  
**A6:** Google Kotlin কে প্রথমবার সমর্থন দেয় **2017 সালে**।  

### Q7: Google Kotlin কে প্রস্তুত করে কোন উদ্দেশ্যে?  
**A7:** Google Kotlin কে **Android development** এর জন্য prepared language হিসেবে **2019 সালে officially ঘোষণা** করে।  

### Q8: Kotlin কি একটি প্রকল্পে অন্য language এর সাথে ব্যবহার করা যায়?  
**A8:** হ্যাঁ, উদাহরণস্বরূপ একটি **Java project** এ Kotlin ব্যবহার করা যায়।  

### Q9: Kotlin এর অনলাইন প্র্যাকটিস করার জন্য কোন প্ল্যাটফর্ম আছে?  
**A9:** হ্যাঁ, **Kotlin Playground** এর মাধ্যমে অনলাইনে কোড লেখা ও পরীক্ষা করা যায়।  

### Q10: LTS (Long-Term Support) বলতে কী বোঝায়? 
**A10:**  LTS মানে: এমন Java সংস্করণ, যেটিতে কয়েক বছর ধরে নিরাপত্তা আপডেট, বাগ ফিক্স ও প্যাচ সাপোর্ট দেওয়া হয়।

### Q11:  Kotlin কোড রান করতে JDK কেন প্রয়োজন?
**A11:** কারণ Kotlin হলো JVM-ভিত্তিক ভাষা। তুমি যখন Kotlin কোড লিখো, সেটি Java bytecode-এ কম্পাইল হয়,
        আর সেই bytecode JVM (Java Virtual Machine) দিয়ে চালানো হয়। JVM আসে JDK-এর সঙ্গে, তাই JDK ইনস্টল ছাড়া Kotlin কোড রান হয় না।

### Q12: Kotlin-এ program execution শুরু করার entry point কোন function?
**A12: Kotlin-এ entry point হলো main function।অথবা arguments সহ

### Q13: Kotlin project-এ src ফোল্ডারের প্রধান কাজ কী?
**A13: src হলো source folder, যেখানে project-এর সব source code রাখা হয়।


### Q14: package কি এবং Kotlin-এ package ব্যবহারের মূল সুবিধা কী কী?
**A14: Package হলো code organize করার একটি system।

### Q15: নিচের comment tag গুলোর কাজ কী? @author @param @return
**A15:
@author → কোড লিখেছেন কারা তা দেখানোর জন্য।
@param → Function parameter গুলোর উদ্দেশ্য বা ব্যাখ্যা বোঝাতে।
@return → Function return value কী তা ব্যাখ্যা করতে।

### Q16: KDoc comment সাধারণ multi-line comment থেকে কীভাবে আলাদা?
**A16: 
KDoc comment /** ... */ দিয়ে লেখা হয় এবং special tags ব্যবহার করা যায়।
সাধারণ multi-line comment /* ... */ শুধুমাত্র কোডের মধ্যে note বা explanation এর জন্য।

### Q17: Parentheses ()কবে ব্যবহার করা হয়? Function declare করা আর function call করার সময় এর ভূমিকা কী?
**A17: () ব্যবহার হয় function এর parameter define করতে এবং function call করার সময় argument pass করতে।

### Q18: Kotlin এ {} কোথায় ব্যবহার হয়? Code block বলতে কী বোঝায়?
**A18: {} ব্যবহার হয় code block তৈরি করতে। যেমন class body, function body, loop body, if-else block ইত্যাদি।


### Q19: Kotlin এ < > এর কাজ কী? Generic type বলতে কী বোঝায়?
**A19: <> ব্যবহার হয় Generic type define করতে — মানে variable, class বা function কে এমনভাবে বানানো যাতে সেটা বিভিন্ন data type নিয়ে কাজ করতে পারে।

### Q20: Kotlin এ .kt ফাইল কী? এটা কী কাজ করে?
**A20: এই .kt ফাইলে আমরা Kotlin কোড লিখি — class, function, variable ইত্যাদি।
Kotlin compiler (kotlinc) এই .kt ফাইলকে Bytecode (.class file) এ রূপান্তর করে, যা JVM এ রান করতে পারে।

### Q21: Bytecode কী? Kotlin কোড কীভাবে Bytecode এ রূপান্তরিত হয়?
**A21: 👉 Bytecode হচ্ছে এমন একটা মধ্যবর্তী কোড যা সরাসরি operating system বুঝতে পারে না, কিন্তু JVM বুঝতে পারে।


### Q22: JVM কী এবং কেন Kotlin এর জন্য দরকার?
**A22: 👉 JVM (Java Virtual Machine) হল একটা সফটওয়্যার layer যেটা Bytecode কে Machine Code এ রূপান্তর করে, যাতে সেটা তোমার Operating System বুঝতে পারে।

---Kotlin → Bytecode → JVM → OS → CPU
---Kotlin Source Code (.kt)→ Kotlin Compiler (kotlinc)→ Bytecode (.class file)→ JVM (Java Virtual Machine)→ Operating System (Windows/Mac/Linux)→ Hardware (CPU)

## ⚡ Features

- বাংলা ভাষায় সহজভাবে Q&A  
- নতুনরা Kotlin শেখার জন্য উপযুক্ত  
- অনলাইন প্র্যাকটিস ও বাস্তব প্রজেক্টে ব্যবহারযোগ্য  

---

## 📌 License

MIT License © 2025  
ছাড়পত্র অনুযায়ী কোড ব্যবহারের অনুমতি রয়েছে।  

---

## 🙌 Contributing

প্রস্তুতকারকরা চাইলে নতুন Q&A বা resource যোগ করতে পারেন।  
Pull request করুন বা Issues খুলুন।  
