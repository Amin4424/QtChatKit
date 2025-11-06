## 🚀 How to Add to Your Project

Since `InfoCard` is a component within the `QtChatKit` repository, you cannot clone *only* this folder with a simple git command. Here are the two best ways to add it to your Qt project:

### Method 1: Manual Copy (Recommended)

This is the simplest way to get started.

1.  Download the two essential files:
    * [`InfoCard.h`](https://github.com/Amin4424/QtChatKit/blob/main/InfoCard/InfoCard.h)
    * [`InfoCard.cpp`](https://github.com/Amin4424/QtChatKit/blob/main/InfoCard/InfoCard.cpp)
2.  Add both files directly to your Qt project's source directory.
3.  **If using qmake (.pro file):** Add them to your `.pro` file:
    ```pro
    HEADERS += InfoCard.h
    SOURCES += InfoCard.cpp
    ```
4.  **If using CMake:** Add them to your `CMakeLists.txt`:
    ```cmake
    add_executable(YourApp
        main.cpp
        mainwindow.cpp
        InfoCard.cpp # Add this
        mainwindow.h
        InfoCard.h   # Add this
    )
    ```
5.  Now you can `#include "InfoCard.h"` in your code and use it.

### Method 2: Using Git Clone (Full Repository)

This method clones the entire repository, and you just copy the folder you need.

1.  Clone the full repository:
    ```bash
    git clone [https://github.com/Amin4424/QtChatKit.git](https://github.com/Amin4424/QtChatKit.git)
    ```
2.  Navigate to the `QtChatKit/InfoCard` directory.
3.  Copy the `InfoCard.h` and `InfoCard.cpp` files from this folder into your own project.
4.  Follow steps 3-5 from Method 1 to add them to your build system.

## ⚠️ Under Active Development

Please note: **QtChatKit is currently under active development.**

The repository structure is evolving, and it does not yet have a unified library format. New components, animations, and features will be added regularly.


## 🚀 نحوه افزودن به پروژه

از آنجایی که `InfoCard` یک کامپوننت در داخل ریپازیتوری `QtChatKit` است، شما نمی‌توانید *فقط* این پوشه را با یک دستور ساده git کلون کنید. در اینجا دو روش عالی برای افزودن آن به پروژه Qt شما آمده است:

### روش ۱: کپی دستی (توصیه می‌شود)

این ساده‌ترین راه برای شروع است.

1.  این دو فایل ضروری را دانلود کنید:
    * [`InfoCard.h`](https://github.com/Amin4424/QtChatKit/blob/main/InfoCard/InfoCard.h)
    * [`InfoCard.cpp`](https://github.com/Amin4424/QtChatKit/blob/main/InfoCard/InfoCard.cpp)
2.  هر دو فایل را مستقیماً به پوشه سورس پروژه Qt خود اضافه کنید.
3.  **اگر از qmake (.pro) استفاده می‌کنید:** آن‌ها را به فایل `.pro` خود اضافه کنید:
    ```pro
    HEADERS += InfoCard.h
    SOURCES += InfoCard.cpp
    ```
4.  **اگر از CMake استفاده می‌کنید:** آن‌ها را به `CMakeLists.txt` خود اضافه کنید:
    ```cmake
    add_executable(YourApp
        main.cpp
        mainwindow.cpp
        InfoCard.cpp # این را اضافه کنید
        mainwindow.h
        InfoCard.h   # این را اضافه کنید
    )
    ```
5.  اکنون می‌توانید فایل `InfoCard.h` را در کد خود `#include` کرده و از آن استفاده کنید.

### روش ۲: استفاده از Git Clone (کل ریپازیتوری)

در این روش کل ریپازیتوری کلون می‌شود و شما فایل‌های مورد نیاز را کپی می‌کنید.

1.  کل ریپازیتوری را کلون کنید:
    ```bash
    git clone [https://github.com/Amin4424/QtChatKit.git](https://github.com/Amin4424/QtChatKit.git)
    ```
2.  به پوشه `QtChatKit/InfoCard` بروید.
3.  فایل‌های `InfoCard.h` و `InfoCard.cpp` را از این پوشه در پروژه خود کپی کنید.
4.  مراحل ۳ تا ۵ از روش ۱ را دنبال کنید تا آن‌ها را به سیستم بیلد خود اضافه کنید.

## ⚠️ در حال توسعه فعال

لطفاً توجه داشته باشید: **QtChatKit در حال حاضر در مرحله توسعه فعال قرار دارد.**

ساختار ریپازیتوری در حال تکامل است و هنوز به یک فرمت کتابخانه‌ای یکپارچه نرسیده است. کامپوننت‌های جدید، انیمیشن‌ها و قابلیت‌های تازه به‌طور منظم به آن اضافه خواهند شد.
