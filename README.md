# SDD Learning

یک وب‌سایت آموزشی و تعاملی برای یادگیری **Spec-Driven Development**.

## امکانات

- محتوای آموزشی فارسی و انگلیسی
- انتخاب زبان در اولین ورود و تغییر زبان از هدر
- شش بخش آموزشی دربارهٔ مبانی، ابزارها، مزایا، Markdown، مثال‌های عملی و آزمون
- طراحی responsive برای موبایل، تبلت و دسکتاپ
- هدر و فوتر مشترک
- پشتیبانی از RTL، LTR، keyboard navigation و reduced motion
- آزمون تعاملی با محاسبهٔ امتیاز

## اجرا

برای بارگذاری هدر و فوتر مشترک، پروژه را با یک local server اجرا کنید:

```bash
python -m http.server 8000
```

سپس به آدرس زیر بروید:

```text
http://localhost:8000
```

## ساختار پروژه

```text
index.html
components/
  header.html
  footer.html
pages/
  sdd-introduction.html
  sdd-types.html
  sdd-benefits.html
  sdd-vs-markdown.html
  practical-examples.html
  quiz.html
styles/style.css
js/main.js
```

## License

Released under the MIT License. See [LICENSE](LICENSE).
