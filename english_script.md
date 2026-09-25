# Production Reminder Feature — Speech Script (English)

## 🎤 Opening

Good morning, everyone. This is Mark from the welding line team.

Last time, I reported on the Seibi app as a whole. Today I'd like to report on a new feature we've added since then: "Production Reminder." This was built based on a request from Nukina-san on the welding line.

---

## 1. Background and Challenges

Every day, we check the Flexche production schedule CSV to see when a process tied to a quality issue or an ongoing improvement effort is coming up again.

This created three problems:

1. **Daily manual CSV checking**: To avoid missing a process being tracked for quality follow-up, staff had to open the file themselves every day to check.
2. **No notification mechanism**: Even as a process approached, there was no system to tell anyone.
3. **No way to know when it last ran**: There was no way to look back and find out when that process last ran.

---

## 2. Solution and Features

Based on Nukina-san's request, we added four features to the Seibi app.

1. **"Watch" a process for automatic notification in 3 patterns**
   Just register the process code you're tracking for quality improvement, and you'll get a push notification to your iPad at three points: "new order detected," "3 days before," and "the day of."

2. **Four browse screens, including Search and a SHOP-by-SHOP calendar**
   We built four screens: Watch List, product/process code Search, SHOP Calendar, and Customer Lookup. Search results display in the order parent product number → child product number → process code.

3. **Real-time LINE WORKS notifications**
   When a watched process is newly detected, 3 days before, or on the day itself, a notification is also sent automatically to LINE WORKS.

4. **Subscription support for the device's native calendar**
   Register a token-protected URL once, and the schedule also appears in the iPad's standard Calendar app.

---

## 3. Results
As foe checking

- We confirmed the push notification arriving on an iPad.
- We've also confirmed the LINE WORKS notification was actually delivered. 
— we confirmed the event actually appears in a calendar app.

---

## 🎤 Closing
The presentation ends here.
Thank you for listening.
