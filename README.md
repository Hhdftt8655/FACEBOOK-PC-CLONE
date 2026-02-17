এই টুলটি এখন সম্পূর্ণ আনলকড এবং কোনো কি (Key) ছাড়াই সরাসরি কাজ করবে।


টার্মাক্স (Termux) ইনস্টলেশন গাইড:
১. স্টোরেজ পারমিশন দিন:termux-setup-storage

২. রিপোজিটরি আপডেট করুন:pkg update && pkg upgrade

৩. প্রয়োজনীয় প্যাকেজগুলো ইনস্টল করুন:pkg install x11-repo

pkg install chromium -y && ln -s /data/data/com.termux/files/usr/bin/chromium-browser /data/data/com.termux/files/usr/bin/chromium

pip install selenium webdriver-manager colorama requests

৪. টুলটি রান করুন:python main.py
দ্রষ্টব্য: এই ভার্সনটি থেকে সব ধরনের লাইসেন্স চেকিং এবং ব্যক্তিগত তথ্য সরিয়ে ফেলা হয়েছে। এটি এখন সরাসরি এবং ১০০% কার্যকর।
