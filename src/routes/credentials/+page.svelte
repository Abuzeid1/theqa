<div class="px-credentials-list-container">
    <ul class="px-credentials-list">
        <li class="px-credentials-list-item">
            <span class="px-credentials-list-number">
                10<span class="px-credentials-list-item-symbol">+</span>
            </span><span class="px-credentials-list-title">سنوات خبرة</span>
        </li>
        <li class="px-credentials-list-item">
            <span class="px-credentials-list-number">
                <span class="px-credentials-list-item-symbol">%</span>4.55
            </span><span class="px-credentials-list-title">
                متوسط نسبة الأرباح الشهرية
            </span>
        </li>
        <li class="px-credentials-list-item">
            <span class="px-credentials-list-number">
                <span class="px-credentials-list-item-symbol">%</span>73
            </span><span class="px-credentials-list-title">
                متوسط نسبة الفوز
            </span>
        </li>
        <li class="px-credentials-list-item">
            <span class="px-credentials-list-number">
                <span class="px-credentials-list-item-symbol">%</span>4.55
            </span><span class="px-credentials-list-title">
                متوسط سنوات الخبرة
            </span>
        </li>
    </ul>
</div>

<style>
    .px-credentials-list-container {
        container-type: inline-size;
    }
    .px-credentials-list {
        display: grid;
        flex-wrap: wrap;
        gap: 0.5rem;
        background: white;
        list-style-type: none;
        grid-auto-rows: 1fr;
        grid-template-columns: repeat(
            auto-fit,
            minmax(max(33%, 25rem), 1fr)
        );
    }

    @container (min-width: 25rem) {
        .px-credentials-list {
            grid-template-columns: repeat(2, 1fr);
        }
    }
    @container (min-width: 70rem) {
        .px-credentials-list {
            gap: 2rem; */
            /* grid-template-columns: repeat(4, 1fr);
        }
    }
    .px-credentials-list-item-symbol {
        font-size: 1.5rem;
    }
    .px-credentials-list-item {
        padding: 1rem;
        border-radius: 0.5rem;
        border: solid 1px #e1e8ef;
        display: grid;
        gap: 0.5rem;
    }
    .px-credentials-list-number {
        font-size: 3rem;
        line-height: 1;
        font-weight: 700;
    }
    .px-credentials-list-title {
        font-size: 0.875rem;
        line-height: 1.25;
    }
</style>
