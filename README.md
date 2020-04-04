# Data Analysis in Python using Pandas

 পান্ডাস পাইথনের অন্যতম দরকারী ডেটা বিশ্লেষণ library (আমি জানি এই নামগুলি অদ্ভুত লাগছে, তবে পড়তে   থাকুন!)। ডেটা সায়েন্স কমিউনিটিতে পাইথনের ব্যবহার বৃদ্ধিতে তারা সহায়ক ভূমিকা পালন করছে। আমরা এখন পান্ডসকে অ্যানালিটিক্স বিদ্যা প্রতিযোগিতা থেকে প্রাপ্ত ডেটা পড়তে, অনুসন্ধান বিশ্লেষণ করতে এবং এই সমস্যাটি সমাধানের জন্য আমাদের প্রথম মৌলিক Classification অ্যালগরিদম তৈরি করতে ব্যবহার করব।
#  Introduction to Series and Dataframes

সিরিজটি 1 টি Dimension লেবেলযুক্ত / index যুক্ত অ্যারে হিসাবে বোঝা যায়। আপনি এই লেবেলের মাধ্যমে এই সিরিজের স্বতন্ত্র উপাদানগুলিতে অ্যাক্সেস করতে পারবেন । একটি ডেটা ফ্রেম এক্সেল ওয়ার্কবুকের সমান - আপনার কলামগুলির সাথে কলামের নাম উল্লেখ রয়েছে এবং আপনার সারি রয়েছে, যা সারি সংখ্যা ব্যবহার করে অ্যাক্সেস করা যায়। ডেটা ফ্রেমের ক্ষেত্রে কলামের নাম এবং সারি সংখ্যা হ'ল প্রয়োজনীয় পার্থক্যটি কলাম এবং সারি index হিসাবে পরিচিত। পাইথনের pandas এর জন্য সিরিজ এবং ডেটা ফ্রেমগুলি মূল ডেটা মডেল গঠন করে। ডেটা সেটগুলি প্রথমে এই ডেটা ফ্রেমগুলিতে পড়তে হয় এবং তারপরে বিভিন্ন ক্রেমগুলি (যেমন গ্রুপ দ্বারা, সমষ্টি ইত্যাদি) এর কলামগুলিতে খুব সহজেই প্রয়োগ করা যায়।
# Practice data set – Loan Prediction Problem
এটা লোন প্রিডিকশনের ডেটাসেট ।  আপনি ডেটাসেটগুলো ডাউনলোড করে নিতে পারেন ডেটাসেট ফোল্ডার থেকে।  এই ডেটাসেটগুলো ভেরিয়েবল ডেস্ক্রিপশন নিচে দেওয়া হলঃ
1.VARIABLE DESCRIPTIONS:
    1.Variable	          Description
    2.Loan_ID	                  Unique Loan ID
    3.Gender	                  Male/ Female
    4.Married	                  Applicant married (Y/N)
    5.Dependents	          Number of dependents
    6.Education	          Applicant Education (Graduate/ Under Graduate)
    7.Self_Employed	          Self employed (Y/N)
    8.ApplicantIncome	          Applicant income
    9.CoapplicantIncome	  Coapplicant income
    10.LoanAmount	          Loan amount in thousands
    11.Loan_Amount_Term	  Term of loan in months
    12.Credit_History	          credit history meets guidelines
    13.Property_Area	          Urban/ Semi Urban/ Rural
    14.Loan_Status	          Loan approved (Y/N)


