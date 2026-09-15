# সহজে কেনাকাটা — বাস্তব শপ স্টার্টার

বাংলাদেশ-কেন্দ্রিক অনলাইন শপের জন্য Node.js + Express + SQLite starter।

## চালু করা
1. Node.js 18+ ইনস্টল করুন।
2. এই ফোল্ডারে terminal খুলে `npm install` চালান।
3. `npm start` চালান।
4. ব্রাউজারে `http://localhost:3000` খুলুন।
5. Admin: `http://localhost:3000/admin.html`

## নিরাপত্তা
লাইভ করার আগে environment variables দিন:
- `JWT_SECRET` = শক্তিশালী random secret
- `ADMIN_PASSWORD` = শক্তিশালী admin password

## আপনার দেওয়া ব্যবসার তথ্য
- Email: sohojekenakata.official@gmail.com
- Contact: 7738357
- Customer market: বাংলাদেশ
- Payment: বিকাশ / Cash on Delivery
- Dashboard name: কেনাকাটা ড্যাশবোর্ড

## গুরুত্বপূর্ণ
বিকাশের আসল API payment integration-এর জন্য merchant/API credentials এবং approved gateway configuration লাগবে। বর্তমানে "বিকাশ (ম্যানুয়াল)" অপশনটি checkout-এ রাখা হয়েছে; টাকা পাঠানোর নম্বর পরে বসাতে হবে।
