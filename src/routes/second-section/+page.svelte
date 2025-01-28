<div class="px-portfolio-section-container">
    <div class="px-portfolio-section custom-padding">
        <article class="px-portfolio-article">
            <div>
                <p class="px-portfolio-subtitle">ادارة الخبير المالي</p>
                <h2 class="px-portfolio-header">عمرو بهاء</h2>
            </div>
            <p class="px-portfolio-paragraph">
                مدير محفظات استثمارية يتمتع بخبرة واسعة تمتد لأكثر من 10 عامًا
                في مجال الاستثمار وإدارة الأصول. خلال مسيرته المهنية، نجح في
                تحقيق عوائد مستدامة للعملاء، مع الحفاظ على توازن دقيق بين
                المخاطر والعوائد. ملتزم بأعلى معايير المهنية والشفافية،
            </p>

            <div class="px-portfolio-links-container">
                <a href="" class="px-portfolio-link px-portfolio-link-first">
                    اشترك الآن
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
                    الأسئلة الشائعة
                </a>
            </div>
        </article>
        <img
            style="justify-self: center; max-width: 100%; object-fit: contain; height: auto;"
            src="/image19.png"
            width="377"
            height="488"
            alt="Amr Bahaa"
        />
    </div>
</div>

<style>
    .custom-padding {
        padding-block: 0;
    }
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
        position: relative;
        row-gap: 2rem;
        padding: 2rem 1rem;
        padding-bottom: 0rem;
        border-radius: 1rem;
        background: linear-gradient(
            245.42deg,
            rgba(234, 247, 245, 1) 3.36%,
            #d7e6f5 85.74%
        );
        color: #1f2123;
    }

    .px-portfolio-article {
        display: grid;
        row-gap: 2rem;
        align-self: center;
    }
    .px-portfolio-header {
        font-weight: 700;
        font-size: 1.5rem;
        line-height: 1.5;
    }
    .px-portfolio-paragraph {
        font-size: 1.125rem;
        max-width: 45ch;
        line-height: 1.65;
    }

    @container (min-width: 60rem) {
        .px-portfolio-section {
            grid-template-columns: 1fr 1fr;
            padding: 0rem 3rem;
            column-gap: 2rem;
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
        background-color: #ffffff;
    }
    @container (max-width: 60rem) {
        .px-portfolio-links-container {
            position: absolute;
            inset-block-end: 2rem;
            inset-inline-end: 1rem;
        }
        .px-portfolio-link-first {
            margin-inline-start: auto;
        }
        .px-portfolio-link-second {
            margin-inline-start: auto;
        }
        .px-portfolio-links-container {
            display: grid;
        }
    }
</style>
