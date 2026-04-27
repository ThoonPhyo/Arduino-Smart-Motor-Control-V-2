# ======= AUTO WATER MOTAR CONTROL V-2 =======

## Function Modes

### 1. Auto Mode (No save voltage)
* **Motar Run:** When water level is lower than 100%.
* **Motar Stop:** When water level reaches 100%.

### 2. Manual Mode
* **Operation:** Motar relay is always open; you must control it using the physical On/Off switches of the Motar.
* **Sensor:** Not related to the water level sensor.
* **Usage:** This mode is preferred for external usages that do not require water level monitoring.

### 3. Auto Save Mode (Save voltage)
* **Motar Run:** When water level is low AND voltage is higher than the Save Voltage (SV).
* **Motar Stop:** When water level is 100% OR current voltage is lower than the Save Voltage.
* **Usage:** This mode is preferred for protecting the Motar using low voltage protection.

---

## Low Voltage Protection
* When current ACV is lower than **SV**, the Motar will stop.
* If this situation happens more than 2 times quickly within 1 minute, the system will identify a **Low Voltage Problem**.
* If a low voltage problem is found, the system will wait for a perfect safe voltage before attempting to restart the motar.
* The Motar will restart only when the current ACV is equal to or higher than the safe voltage.

---

## Protections and Adjustments

> [!IMPORTANT]
> **Dry Run Protection:** If no water flow is detected after 1 minute of the motar starting (in Auto Save or No Save modes), the motar will stop immediately and the LCD will display: `"No Water Flowing"`.

### Adjusting the Save Voltage (SV)
1. Ensure the system is in **Auto Save Mode**.
2. Press and hold the **Adjust Button** for 3 seconds.
3. Adjust the **SV** using the **Potentiometer**.
4. Press and hold the **Adjust Button** for 3 seconds again to save and release.


# ======= AUTO WATER MOTAR CONTROL V-2 =======

### **အသုံးပြုနိုင်သော စနစ်များ (Function Modes)**

#### **၁။ အလိုအလျောက်စနစ် - ဗို့အားမသတ်မှတ်ထား (Auto Mode - No save voltage)**
* **မော်တာလည်ပတ်ခြင်း:** ရေပမာဏ ၁၀၀% အောက် လျော့နည်းသွားပါက မော်တာ အလိုအလျောက် လည်ပတ်မည်။
* **မော်တာရပ်တန့်ခြင်း:** ရေပမာဏ ၁၀၀% ပြည့်သွားပါက မော်တာ အလိုအလျောက် ရပ်တန့်မည်။

#### **၂။ ကိုယ်တိုင်ထိန်းချုပ်စနစ် (Manual Mode)**
* **လုပ်ဆောင်ချက်:** မော်တာ Relay ကို အမြဲတမ်း ဖွင့်ထားပေးမည်ဖြစ်ပြီး မော်တာ၏ အဖွင့်/အပိတ် ခလုတ်များဖြင့်သာ ကိုယ်တိုင် ထိန်းချုပ်ရမည်။
* **အာရုံခံကိရိယာ:** ရေအနိမ့်အမြင့် အာရုံခံကိရိယာ (Sensor) နှင့် သက်ဆိုင်မှု မရှိပါ။
* **အသုံးပြုမှု:** ဤစနစ်ကို အာရုံခံကိရိယာနှင့် မပတ်သက်သော ပြင်ပကိစ္စရပ်များတွင် အသုံးပြုရန် သင့်တော်သည်။

#### **၃။ အလိုအလျောက် လုံခြုံရေးစနစ် - ဗို့အားသတ်မှတ်ထား (Auto Save Mode)**
* **မော်တာလည်ပတ်ခြင်း:** ရေပမာဏ လျော့နည်းနေပြီး လက်ရှိ ဗို့အားသည် သတ်မှတ်ထားသော လုံခြုံစိတ်ချရသည့် ဗို့အား (Save Voltage) ထက် မြင့်မှသာ လည်ပတ်မည်။
* **မော်တာရပ်တန့်ခြင်း:** ရေပမာဏ ၁၀၀% ပြည့်သွားလျှင်သော်လည်းကောင်း၊ လက်ရှိဗို့အားသည် သတ်မှတ်ထားသော ဗို့အားအောက် လျော့နည်းသွားလျှင်သော်လည်းကောင်း ရပ်တန့်ပေးမည်။
* **အသုံးပြုမှု:** ဤစနစ်သည် ဗို့အားနည်းခြင်းကြောင့် မော်တာပျက်စီးခြင်းမှ ကာကွယ်ရန်အတွက် အသင့်တော်ဆုံး ဖြစ်သည်။

---

### **ဗို့အားနည်းခြင်းမှ ကာကွယ်သည့်စနစ် (Low Voltage Protection)**
* လက်ရှိ AC ဗို့အားသည် သတ်မှတ်ထားသော ဗို့အား (SV) ထက် နည်းသွားပါက မော်တာ ရပ်တန့်သွားမည်။
* ဤအခြေအနေသည် ၁ မိနစ်အတွင်း ၂ ကြိမ်ထက်ပို၍ ဖြစ်ပေါ်နေပါက စနစ်မှ **"Low Voltage Problem"** အဖြစ် သတ်မှတ်မည်။
* ဗို့အားနည်းသော ပြဿနာ ဖြစ်ပေါ်ပါက မော်တာ ပြန်လည်မလည်ပတ်မီ လုံခြုံစိတ်ချရသော ဗို့အားအဆင့်သို့ ရောက်ရှိရန် စနစ်မှ စောင့်ဆိုင်းနေမည်။
* လက်ရှိ AC ဗို့အားသည် သတ်မှတ်ထားသော ဗို့အားနှင့် ညီမျှခြင်း သို့မဟုတ် ပိုများလာမှသာ မော်တာ ပြန်လည်လည်ပတ်မည်။

---

### **ကာကွယ်မှုများနှင့် ချိန်ညှိခြင်း (Protections and Adjustments)**

> [!CAUTION]
> **ရေမထွက်ပါက အလိုအလျောက်ရပ်တန့်ခြင်း:** Auto သို့မဟုတ် Auto Save Mode များတွင် မော်တာစတင်လည်ပတ်ပြီး ၁ မိနစ်ကြာသည်အထိ ရေထွက်မလာပါက မော်တာ ချက်ချင်းရပ်တန့်သွားမည်ဖြစ်ပြီး LCD မျက်နှာပြင်တွင် **"No Water Flowing"** ဟု ပြသမည်။

#### **Save Voltage (SV) ကို ချိန်ညှိနည်း**
1. **Adjust Button** ကို ၃ စက္ကန့်ကြာ ဖိထားပါ။
2. **Potentiometer** ကို အသုံးပြု၍ လိုချင်သော ဗို့အားပမာဏကို ချိန်ညှိပါ။
3. ပြန်လည်သိမ်းဆည်းရန် **Adjust Button** ကို ၃ စက္ကန့်ကြာ ထပ်မံဖိထားပေးပါ။
