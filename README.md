import React from "react";

export default function About() {
  return (
    <div className="min-h-screen bg-white text-gray-900 p-6 md:p-12">
      <h1 className="text-3xl font-bold mb-4">من أنا | About Me</h1>
      <p>
        اسمي Issa Nahoul، أمتلك خبرة واسعة في إدارة الأعمال والتجارة الإلكترونية.
        أساعد الشركات على تحقيق النمو من خلال حلول مخصصة واستراتيجيات فعالة في التسويق الرقمي وتطوير العمليات.
      </p>
    </div>
  );
}import React from "react";

export default function Services() {
  return (
    <div className="min-h-screen bg-white text-gray-900 p-6 md:p-12">
      <h1 className="text-3xl font-bold mb-4">خدماتي | My Services</h1>
      <div className="space-y-6">
        <div>
          <h2 className="text-xl font-semibold">إدارة الأعمال | Business Management</h2>
          <p>
            تقديم استشارات في تحسين الأداء الإداري، تطوير الهيكل التنظيمي، وإعداد خطط عمل استراتيجية.
          </p>
        </div>
        <div>
          <h2 className="text-xl font-semibold">التجارة الإلكترونية | E-Commerce</h2>
          <p>
            إنشاء وتطوير متاجر إلكترونية، التسويق الرقمي، وتحسين تجربة المستخدم لزيادة العائدات.
          </p>
        </div>
      </div>
    </div>
  );
}import React from "react";

export default function Contact() {
  return (
    <div className="min-h-screen bg-white text-gray-900 p-6 md:p-12">
      <h1 className="text-3xl font-bold mb-4">تواصل معي | Contact Me</h1>
      <form className="grid gap-4 max-w-xl">
        <input type="text" placeholder="الاسم | Name" className="border rounded p-2" />
        <input type="email" placeholder="البريد الإلكتروني | Email" className="border rounded p-2" />
        <textarea rows={4} placeholder="رسالتك | Message" className="border rounded p-2"></textarea>
        <button type="submit" className="bg-blue-600 text-white py-2 px-4 rounded">إرسال | Send</button>
      </form>
    </div>
  );
}# Portfolio
