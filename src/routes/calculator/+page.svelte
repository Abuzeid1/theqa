<script>
    $effect(() => {
        const radios = document.querySelectorAll("input[name=px-calculator]");
        if (!radios) return;
        radios.forEach((radio) => {
            radio.addEventListener("change", (event) => {
                const returnedValue = document.getElementById(
                    "px-calculator-result",
                );
                const value = event.currentTarget?.value;
                if (!value) return;
                if (!returnedValue) return;
                if (document.startViewTransition) {
                    document.startViewTransition(() => {
                        returnedValue.innerHTML = `${value * 0.1}`;
                    });
                } else {
                    returnedValue.innerHTML = `${value * 0.1}`;
                }
            });
        });
    });
</script>

<div class="px-portfolio-section-container">
    <div class="px-portfolio-section px-portfolio-custom-background">
        <div class="px-calculator-container">
            <h3 class="px-calculator-header">
                حجم المحفظة

                <svg
                    width="12"
                    height="12"
                    viewBox="0 0 12 12"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                >
                    <path
                        d="M6 0C2.68594 0 0 2.68594 0 6C0 9.31406 2.68594 12 6 12C9.31406 12 12 9.31406 12 6C12 2.68594 9.31406 0 6 0ZM6 10.875C3.31172 10.875 1.125 8.68805 1.125 6C1.125 3.31195 3.31172 1.125 6 1.125C8.68828 1.125 10.875 3.31195 10.875 6C10.875 8.68805 8.68828 10.875 6 10.875ZM6.9375 7.875H6.5625V5.8125C6.5625 5.50313 6.31172 5.25 6 5.25H5.25C4.94063 5.25 4.6875 5.50313 4.6875 5.8125C4.6875 6.12187 4.94063 6.375 5.25 6.375H5.4375V7.875H5.0625C4.75313 7.875 4.5 8.12813 4.5 8.4375C4.5 8.74687 4.75313 9 5.0625 9H6.9375C7.24805 9 7.5 8.74805 7.5 8.4375C7.5 8.12695 7.24922 7.875 6.9375 7.875ZM6 4.5C6.41414 4.5 6.75 4.16414 6.75 3.75C6.75 3.33586 6.41414 3 6 3C5.58586 3 5.25 3.33516 5.25 3.75C5.25 4.16484 5.58516 4.5 6 4.5Z"
                        fill="#7B8995"
                    />
                </svg>
            </h3>
            <ul class="px-calculator-list">
                <li class="px-calculator-list-element">
                    <label class="px-calculator-label"
                        >$10,000<input
                            type="radio"
                            name="px-calculator"
                            value="10000"
                            class="px-calculator-input"
                        /></label
                    >
                </li>
                <li class="px-list-element">
                    <label class="px-calculator-label"
                        >$50,000<input
                            checked
                            type="radio"
                            name="px-calculator"
                            value="50000"
                            class="px-calculator-input"
                        /></label
                    >
                </li>
                <li class="px-list-element">
                    <label class="px-calculator-label"
                        >$100,000<input
                            type="radio"
                            name="px-calculator"
                            value="100000"
                            class="px-calculator-input"
                        /></label
                    >
                </li>
            </ul>
            <h4 class="px-calculator-subheader">
                $<span id="px-calculator-result">9,000</span>+
                <span
                    style="font-size: .875rem; line-height: 1.15; display: block; color: #7b8895; font-weight: bold; margin-top: .25rem;"
                    >العائد المتوقع بنسبة ١٠٪</span
                >
            </h4>
        </div>
        <article class="px-portfolio-article">
            <div>
                <p class="px-portfolio-subtitle">
                    خدمة إدارة محفظتك الاستثمارية مع فريق ثقة المتخصص
                </p>
                <h2 class="px-portfolio-header">دع أموالك تعمل من أجلك</h2>
            </div>
            <p class="px-portfolio-paragraph">
                لمن يبحث عن شروط تداول خاصة وتجربة آمنة، هذه الخدمة لك.
                <br />
                احصل على خدمات مميزة لدخول عالم التداول والاستثمار واثق الخطوة، ابدأ
                التداول حسب شروط خاصة مع شركات آمنة ومرخصة في أسواق المال
            </p>
            <ul class="px-portfolio-paragraph px-portfolio-list">
                <li class="px-portfolio-list-item">
                    سحب وايداع بيد المستثمر وثقة هي مجرد مدير للمحفظة
                </li>
                <li class="px-portfolio-list-item">
                    نسبة التشغيل 30% من العائد المتوقع
                </li>
                <li class="px-portfolio-list-item">
                    نسبة النمو والمخاطرة تصل الى 20%
                </li>
            </ul>
            <div class="px-portfolio-links-container">
                <a href="" class="px-portfolio-link px-portfolio-link-first">
                    سجل الآن
                    <svg
                        width="20"
                        height="20"
                        viewBox="0 0 20 20"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            d="M9.11719 18.3828C9.60547 18.8711 10.3984 18.8711 10.8867 18.3828L17.1367 12.1328C17.625 11.6445 17.625 10.8516 17.1367 10.3633C16.6484 9.875 15.8555 9.875 15.3672 10.3633L11.25 14.4844V2.5C11.25 1.80859 10.6914 1.25 10 1.25C9.30859 1.25 8.75 1.80859 8.75 2.5V14.4805L4.63281 10.3672C4.14453 9.87891 3.35156 9.87891 2.86328 10.3672C2.375 10.8555 2.375 11.6484 2.86328 12.1367L9.11328 18.3867L9.11719 18.3828Z"
                            fill="#1F2123"
                        />
                    </svg>
                </a>
                <a href="" class="px-portfolio-link px-portfolio-link-second">
                    طلب المساعدة
                </a>
            </div>
        </article>
    </div>
</div>

<style>
    .px-portfolio-section-container {
        container-type: inline-size;
    }
    .px-portfolio-subtitle {
        display: block;
        font-size: 1rem;
        line-height: 1.5;
        color: #007bff;
        margin-bottom: 0.5rem;
    }
    .px-portfolio-section {
        display: grid;
        row-gap: 2rem;
        padding: 2rem 1rem;
        border-radius: 1rem;
        background: linear-gradient(
            245.42deg,
            rgba(234, 247, 245, 1) 3.36%,
            #d7e6f5 85.74%
        );
        color: #1f2123;
    }
    .px-portfolio-custom-background {
        background:
            radial-gradient(
                    circle,
                    rgba(255, 255, 255, 0.7) 2px,
                    transparent 2px
                )
                16px 16px / 16px 16px,
            url("/Isolation_Mode.svg") left bottom no-repeat,
            url("/Frame.png") center center / cover no-repeat,
            linear-gradient(
                245.42deg,
                rgba(234, 247, 245, 1) 3.36%,
                #d7e6f5 85.74%
            );
    }

    .px-portfolio-article {
        display: grid;
        row-gap: 2rem;
    }
    .px-portfolio-header {
        font-weight: 700;
        font-size: 1.5rem;
        line-height: 1.5;
    }
    .px-portfolio-paragraph {
        font-size: 1.125rem;
        line-height: 1.65;
    }
    .px-portfolio-list {
        list-style-type: none;
        display: grid;
        gap: 0.5rem;
    }
    .px-portfolio-list-item {
        padding-inline-start: 2rem;
        background-image: url("data:image/svg+xml,%3Csvg width='24' height='24' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cg clip-path='url(%23clip0_6324_421576)'%3E%3Cpath d='M11.4281 15.9281C10.9172 16.4391 10.0828 16.4391 9.57187 15.9281L6.57187 12.9281C6.06094 12.4172 6.06094 11.5828 6.57187 11.0719C7.08281 10.5609 7.91719 10.5609 8.42813 11.0719L10.5 13.1437L15.5719 8.07187C16.0828 7.56094 16.9172 7.56094 17.4281 8.07187C17.9391 8.58281 17.9391 9.41719 17.4281 9.92813L11.4281 15.9281ZM24 12C24 18.6281 18.6281 24 12 24C5.37188 24 0 18.6281 0 12C0 5.37188 5.37188 0 12 0C18.6281 0 24 5.37188 24 12ZM12 2.25C6.61406 2.25 2.25 6.61406 2.25 12C2.25 17.3859 6.61406 21.75 12 21.75C17.3859 21.75 21.75 17.3859 21.75 12C21.75 6.61406 17.3859 2.25 12 2.25Z' fill='%23007BFF'/%3E%3C/g%3E%3Cdefs%3E%3CclipPath id='clip0_6324_421576'%3E%3Crect width='24' height='24' fill='white'/%3E%3C/clipPath%3E%3C/defs%3E%3C/svg%3E");
        background-repeat: no-repeat;
        background-position: right top 4px;
    }
    @container (min-width: 60rem) {
        .px-portfolio-section {
            grid-template-columns: 1fr 1fr;
            padding: 4rem 3rem;
            column-gap: 2rem;
        }
        .px-calculator-container {
            max-width: 30rem;
            width: 100%;
            place-self: center;
            grid-area: 1/2;
        }
        .px-portfolio-header {
            font-size: 3rem;
            line-height: 1.25;
        }
        .px-portfolio-paragraph {
            font-weight: 700;
        }
        .px-portfolio-subtitle {
            font-size: 1.125rem;
            line-height: 1.67;
        }
    }

    .px-calculator-container {
        padding: 1rem;
        border-radius: 0.75rem;
        gap: 1rem;
        background-color: #fff;
        display: grid;
        container-type: inline-size;
    }

    .px-calculator-header {
        font-weight: bold;
        font-size: 1.125rem;
        line-height: 1.67;
        display: flex;
        align-items: center;
        gap: 0.125rem;
    }
    .px-calculator-header svg {
        cursor: pointer;
        height: 0.5lh;
        width: auto;
    }

    .px-calculator-list {
        display: grid;
        gap: 0.5rem;
        list-style: none;
        text-align: center;
        padding: 0;
    }

    @container (min-width: 20rem) {
        .px-calculator-list {
            grid-template-columns: repeat(3, 1fr);
        }
    }
    .px-calculator-subheader {
        font-size: 3rem;
        line-height: 1;
        color: #007bff;
        text-align: center;
        font-weight: bold;
        margin: 0;
        padding-block: 0.5rem;
    }
    .px-calculator-label {
        display: block;
        border-radius: 0.5rem;
        border: 1px solid #e1e8ef;

        padding: 0.5rem;
        cursor: pointer;
    }
    .px-calculator-label:has(input:checked) {
        border-color: #007bff;
    }

    .px-calculator-input {
        appearance: none;
        -webkit-appearance: none;
    }
    .px-portfolio-link {
        border-radius: 9999px;
        font-size: 1.25rem;
        line-height: 1.67;
        font-weight: 700;
        padding: 0.5rem 1.5rem;
        text-decoration: none;
        color: #1f2123;
    }
    .px-portfolio-links-container {
        display: flex;
        flex-wrap: wrap;

        gap: 0.5rem;
    }

    .px-portfolio-link-first {
        display: flex;
        gap: 0.5rem;
        align-items: center;
        background-color: #fbbf0d;
    }
    .px-portfolio-link-second {
        place-self: start;
        background-color: #ffffff;
    }
</style>
