# Original Source guides.rubyonrails.org

## 2 What is Rails?
Rails ဆိုတာက web application development frame ပါ။ အဲ့ဒီမှာ web application or web app ဆိုတာက client-server program ပါ။ client နဲ့ server ကြား ဆက်သွယ်မှုလုပ်နိုင်တဲ့ program ကို browser ကနေ တဆင့်သုံးလို့ရအောင် ရေးထားတာပါ။ အဲ့လို web app တွေ ရေးဖို့ အဆင်သင့်နည်းပါ လုပ်ပေးထားတဲ့ frame work ပါ။ rails (ruby on rails) က back-end, front-end, api only(api only ဆို များသောအားဖြင့် Sinatra နဲ့ ရေးတယ်) ရေးလို့ရတယ်။ တခြား နာမည်ကြီး programming language တွေက အဲ့လို သုံးမျိုးလုံး ရေးနိုင်တာမျိုးသိပ်ရှိဘူး။ ဥပမာ - node.js ဆို server site (back-end)နဲ့ api ပဲရေးလို့ရတယ်. front-end အတွက်ဆို တခြား front-end javascript frameworks (angular.js, react.js, vue.js, express.js, ...) တွေလိုတယ်.

Ruby က developer အတွက် ရည်ရွယ်ပြီးရေးထားတဲ့ programming language ဖြစ်လို့ လူနားလည်လွယ်တယ်။ အဲ့ဒီ ruby ကို အခြေခံပြီး rails ကို ရေးထားတာဖြစ်တယ်။ rails က MVC လို့ ခေါ်တဲ့ model, view, controller pattern ကိုသုံးထားပါတယ်။ MVC ဆိုတာက  data store model (aka database) သတ်သတ်၊ user ကို ပြတဲ့ UI view သတ်သတ်, အလုပ်လုပ်တဲ့ definitions( aka functions, methods) သတ်သတ် ခွဲ ရေးထားတာကို ပြောတာပါ။

## 3. Rails project တည်ဆောက်ခြင်း
အောက်ပါအချက်များကို တစ်ဆင့်ခြင်းစီ သေချာစွာဖတ်ပါ။ အဆိုပါအဆင့်များသည် အခြေခံကျသော rails app တစ်ခုတည်ဆောက်ရန် လိုအပ်သည့် အဆင့်များဖြစ်သည်။

Rails app မဆောက်ခင် လိုအပ်သော ruby, rails gem တို့ကို အသုံးပြုမည့် computer တွင် သွင်းရန်။

### 3.1 Installing Rails
Ruby on rails ကို စတင်လေ့လာတော့မယ်ဆိုရင် Rails ထက်အရင် Ruby နှင့် SQLite3 တို့ကို သွင်းထားဖို့လိုပါတယ်။ 
Ruby ကို 'sudo apt-get install ruby' နဲ့ သွင်းမယ့်အစား Ruby Version Manager(RVM) နှင့် သွင်းထားတာက နောက်ပိုင်း အတွက် ပိုအဆင်ပြေပါတယ်။ RVM မှာ ruby version အမျိုးမျိုးကို တပြိုင်နက်သွင်းထားနိုင်ပြီး ကိုယ့်အတွက် လိုအပ်တဲ့ ruby version ကို အလွယ်တကူ ပြောင်းသုံးလို့ရပါတယ်။ 
https://rvm.io/rvm/install မှာ ruby ကို RVM နဲ့ သွင်းနည်းကို လေ့လာနိုင်ပါတယ်။
Ruby သွင်းပြီးသွားရင်တော့ terminal (command prompt in Window) မှာ 'ruby --version' သို့မဟုတ် 'ruby -v' လို့ ရိုက်ပြီး မိမိ၏ ruby version ကို ကြည့်နိုင်ပါတယ်။ Rails gem ကိုသွင်းဖို့အတွက်တော့ Ruby version 2.2 နှင့်အထက်လိုပါတယ်။ ယခု ruby version က 2.5.1 အထိ ရှိနေပြီဖြစ်ပါတယ်။

Rails ကို သွင်းဖို့ဆိုရင်တော့ 'gem install' ကို သုံးနိုင်ပါတယ်။ 'gem install rails'. သွင်းပြီးရင်တော့ ကိုယ်သွင်းလိုက်တဲ့ Rails version ကို 'rails --version' နဲ့ ပြန်ကြည့်လို့ရပါတယ်။ Rails gem က '2.5.2' အထိရောက်နေပါပြီ။

