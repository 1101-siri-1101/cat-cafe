<template>
  <div class="bg-stone-50 text-stone-800">
    <!-- Header -->
    <header class="sticky top-0 z-50 border-b border-stone-200 bg-white/90 backdrop-blur">
      <div class="mx-auto flex max-w-7xl items-center justify-between px-4 py-4 md:px-6 lg:px-8">
        <a href="#" class="text-xl font-semibold tracking-wide">Neko Lounge</a>

        <nav class="hidden gap-6 text-sm md:flex">
          <a href="#concept" class="hover:text-amber-700">コンセプト</a>
          <a href="#guide" class="hover:text-amber-700">はじめての方へ</a>
          <a href="#shop" class="hover:text-amber-700">店舗案内</a>
          <a href="#news" class="hover:text-amber-700">お知らせ</a>
        </nav>

        <a
          href="#"
          class="rounded-full bg-amber-700 px-5 py-2 text-sm font-medium text-white transition hover:opacity-90"
        >
          予約する
        </a>
      </div>
    </header>

    <main>
      <!-- Hero -->
      <section class="py-12 md:py-20">
        <div class="mx-auto grid max-w-7xl items-center gap-10 px-4 md:grid-cols-2 md:px-6 lg:px-8">
          <div>
            <p class="mb-3 text-sm tracking-[0.2em] text-amber-700">CAT CAFE</p>
            <h1 class="mb-5 text-4xl font-semibold leading-tight md:text-5xl lg:text-6xl">
              猫と過ごす、<br class="hidden md:block" />
              やさしい午後。
            </h1>
            <p class="mb-8 max-w-xl text-sm leading-7 text-stone-600 md:text-base">
              ふらっと立ち寄って、猫と遊んだり、本を読んだり、
              ひとり時間をのんびり楽しめる猫カフェです。
            </p>

            <div class="flex flex-col gap-3 sm:flex-row">
              <a
                href="#shop"
                class="rounded-full bg-amber-700 px-6 py-3 text-center text-sm font-medium text-white transition hover:opacity-90"
              >
                店舗を見る
              </a>
              <a
                href="#guide"
                class="rounded-full border border-stone-300 px-6 py-3 text-center text-sm font-medium transition hover:bg-stone-100"
              >
                はじめての方へ
              </a>
            </div>
          </div>

          <div class="overflow-hidden rounded-[2rem] shadow-sm">
            <img
              src="https://images.unsplash.com/photo-1511044568932-338cba0ad803?auto=format&fit=crop&w=1200&q=80"
              alt="猫カフェの猫"
              class="h-[320px] w-full object-cover md:h-[520px]"
            />
          </div>
        </div>
      </section>

      <!-- Concept -->
      <section id="concept" class="bg-amber-50 py-16 md:py-24">
        <div class="mx-auto max-w-7xl px-4 md:px-6 lg:px-8">
          <div class="mb-10 max-w-2xl">
            <p class="mb-2 text-sm tracking-[0.2em] text-amber-700">CONCEPT</p>
            <h2 class="mb-4 text-3xl font-semibold md:text-4xl">その日の気分で、猫とくつろぐ。</h2>
            <p class="leading-7 text-stone-600">
              おしゃべりしたい日も、ひとりでぼーっとしたい日も。
              それぞれの過ごし方にそっと寄り添う、やわらかな空間を目指しています。
            </p>
          </div>

          <div class="grid gap-6 md:grid-cols-2">
            <img
              src="https://images.unsplash.com/photo-1543852786-1cf6624b9987?auto=format&fit=crop&w=1000&q=80"
              alt="くつろぐ猫"
              class="aspect-[4/3] w-full rounded-3xl object-cover"
            />
            <img
              src="https://images.unsplash.com/photo-1518791841217-8f162f1e1131?auto=format&fit=crop&w=1000&q=80"
              alt="眠る猫"
              class="aspect-[4/3] w-full rounded-3xl object-cover"
            />
          </div>
        </div>
      </section>

      <!-- Ways -->
      <section class="py-16 md:py-24">
        <div class="mx-auto max-w-7xl px-4 md:px-6 lg:px-8">
          <div class="mb-10">
            <p class="mb-2 text-sm tracking-[0.2em] text-amber-700">HOW TO SPEND</p>
            <h2 class="text-3xl font-semibold md:text-4xl">いろんな過ごし方</h2>
          </div>

          <div class="grid gap-6 sm:grid-cols-2 lg:grid-cols-3">
            <article class="rounded-3xl bg-white p-6 shadow-sm transition hover:-translate-y-1 hover:shadow-lg">
              <h3 class="mb-3 text-xl font-semibold">猫と遊ぶ</h3>
              <p class="text-sm leading-7 text-stone-600">
                おもちゃを使って、自由気ままな猫たちとの時間を楽しめます。
              </p>
            </article>

            <article class="rounded-3xl bg-white p-6 shadow-sm transition hover:-translate-y-1 hover:shadow-lg">
              <h3 class="mb-3 text-xl font-semibold">おしゃべりする</h3>
              <p class="text-sm leading-7 text-stone-600">
                友達やパートナーとのカフェ時間にもぴったりです。
              </p>
            </article>

            <article class="rounded-3xl bg-white p-6 shadow-sm transition hover:-translate-y-1 hover:shadow-lg">
              <h3 class="mb-3 text-xl font-semibold">本を読む</h3>
              <p class="text-sm leading-7 text-stone-600">
                静かな席でマンガや本を読みながらのんびり過ごせます。
              </p>
            </article>

            <article class="rounded-3xl bg-white p-6 shadow-sm transition hover:-translate-y-1 hover:shadow-lg">
              <h3 class="mb-3 text-xl font-semibold">仕事・勉強</h3>
              <p class="text-sm leading-7 text-stone-600">
                Wi-Fiや電源のある席で、気分転換しながら作業できます。
              </p>
            </article>

            <article class="rounded-3xl bg-white p-6 shadow-sm transition hover:-translate-y-1 hover:shadow-lg">
              <h3 class="mb-3 text-xl font-semibold">ひと休み</h3>
              <p class="text-sm leading-7 text-stone-600">
                ドリンク片手に、なにも考えない休憩時間にもおすすめです。
              </p>
            </article>

            <article class="rounded-3xl bg-white p-6 shadow-sm transition hover:-translate-y-1 hover:shadow-lg">
              <h3 class="mb-3 text-xl font-semibold">写真を撮る</h3>
              <p class="text-sm leading-7 text-stone-600">
                かわいい瞬間に出会えたら、そっと思い出に残せます。
              </p>
            </article>
          </div>
        </div>
      </section>

      <!-- Guide -->
      <section id="guide" class="bg-white py-16 md:py-24">
        <div class="mx-auto max-w-7xl px-4 md:px-6 lg:px-8">
          <div class="mb-10">
            <p class="mb-2 text-sm tracking-[0.2em] text-amber-700">FIRST VISIT</p>
            <h2 class="text-3xl font-semibold md:text-4xl">はじめての方へ</h2>
          </div>

          <div class="grid gap-8 lg:grid-cols-2">
            <div class="rounded-3xl bg-stone-50 p-8">
              <h3 class="mb-6 text-2xl font-semibold">利用の流れ</h3>
              <ol class="space-y-4 text-sm leading-7 text-stone-600">
                <li><span class="font-semibold text-stone-800">1.</span> 受付でプランを選ぶ</li>
                <li><span class="font-semibold text-stone-800">2.</span> 注意事項を確認して入店</li>
                <li><span class="font-semibold text-stone-800">3.</span> 好きな席でゆっくり過ごす</li>
              </ol>
            </div>

            <div class="rounded-3xl bg-amber-50 p-8">
              <h3 class="mb-6 text-2xl font-semibold">料金プラン</h3>
              <div class="space-y-4">
                <div class="flex items-center justify-between rounded-2xl bg-white p-4">
                  <span>30分</span>
                  <span class="font-semibold">¥900</span>
                </div>
                <div class="flex items-center justify-between rounded-2xl bg-white p-4">
                  <span>60分</span>
                  <span class="font-semibold">¥1,500</span>
                </div>
                <div class="flex items-center justify-between rounded-2xl bg-white p-4">
                  <span>フリータイム</span>
                  <span class="font-semibold">¥2,400</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Shop -->
      <section id="shop" class="py-16 md:py-24">
        <div class="mx-auto max-w-7xl px-4 md:px-6 lg:px-8">
          <div class="mb-10">
            <p class="mb-2 text-sm tracking-[0.2em] text-amber-700">SHOP</p>
            <h2 class="text-3xl font-semibold md:text-4xl">店舗案内</h2>
          </div>

          <div class="grid gap-6 md:grid-cols-2 lg:grid-cols-3">
            <article class="overflow-hidden rounded-3xl bg-white shadow-sm">
              <img
                src="https://images.unsplash.com/photo-1517457373958-b7bdd4587205?auto=format&fit=crop&w=1200&q=80"
                alt="渋谷店のイメージ"
                class="aspect-[4/3] w-full object-cover"
              />
              <div class="p-6">
                <h3 class="mb-2 text-xl font-semibold">渋谷店</h3>
                <p class="mb-3 text-sm text-stone-600">11:00 - 20:00</p>
                <div class="flex flex-wrap gap-2 text-xs">
                  <span class="rounded-full bg-stone-100 px-3 py-1">駅近</span>
                  <span class="rounded-full bg-stone-100 px-3 py-1">Wi-Fi</span>
                  <span class="rounded-full bg-stone-100 px-3 py-1">おひとり歓迎</span>
                </div>
              </div>
            </article>

            <article class="overflow-hidden rounded-3xl bg-white shadow-sm">
              <img
                src="https://images.unsplash.com/photo-1495360010541-f48722b34f7d?auto=format&fit=crop&w=1200&q=80"
                alt="吉祥寺店のイメージ"
                class="aspect-[4/3] w-full object-cover"
              />
              <div class="p-6">
                <h3 class="mb-2 text-xl font-semibold">吉祥寺店</h3>
                <p class="mb-3 text-sm text-stone-600">10:00 - 20:00</p>
                <div class="flex flex-wrap gap-2 text-xs">
                  <span class="rounded-full bg-stone-100 px-3 py-1">静か</span>
                  <span class="rounded-full bg-stone-100 px-3 py-1">読書向き</span>
                  <span class="rounded-full bg-stone-100 px-3 py-1">電源あり</span>
                </div>
              </div>
            </article>

            <article class="overflow-hidden rounded-3xl bg-white shadow-sm">
              <img
                src="https://images.unsplash.com/photo-1519052537078-e6302a4968d4?auto=format&fit=crop&w=1200&q=80"
                alt="横浜店のイメージ"
                class="aspect-[4/3] w-full object-cover"
              />
              <div class="p-6">
                <h3 class="mb-2 text-xl font-semibold">横浜店</h3>
                <p class="mb-3 text-sm text-stone-600">11:00 - 21:00</p>
                <div class="flex flex-wrap gap-2 text-xs">
                  <span class="rounded-full bg-stone-100 px-3 py-1">広め空間</span>
                  <span class="rounded-full bg-stone-100 px-3 py-1">写真OK</span>
                  <span class="rounded-full bg-stone-100 px-3 py-1">デート向き</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </section>

      <!-- News -->
      <section id="news" class="bg-stone-100 py-16 md:py-24">
        <div class="mx-auto max-w-4xl px-4 md:px-6 lg:px-8">
          <div class="mb-10">
            <p class="mb-2 text-sm tracking-[0.2em] text-amber-700">NEWS</p>
            <h2 class="text-3xl font-semibold md:text-4xl">お知らせ</h2>
          </div>

          <div class="space-y-4">
            <a href="#" class="block rounded-3xl bg-white p-6 transition hover:shadow-md">
              <p class="mb-2 text-sm text-stone-500">2026.03.10</p>
              <p class="font-medium">春の限定スイーツがスタートしました</p>
            </a>

            <a href="#" class="block rounded-3xl bg-white p-6 transition hover:shadow-md">
              <p class="mb-2 text-sm text-stone-500">2026.03.05</p>
              <p class="font-medium">新しい猫スタッフが仲間入りしました</p>
            </a>

            <a href="#" class="block rounded-3xl bg-white p-6 transition hover:shadow-md">
              <p class="mb-2 text-sm text-stone-500">2026.03.01</p>
              <p class="font-medium">平日限定の学生プランを開始しました</p>
            </a>
          </div>
        </div>
      </section>
    </main>

    <!-- Footer -->
    <footer class="border-t border-stone-200 bg-white">
      <div
        class="mx-auto flex max-w-7xl flex-col gap-6 px-4 py-10 md:flex-row md:items-center md:justify-between md:px-6 lg:px-8"
      >
        <div>
          <p class="text-lg font-semibold">Neko Lounge</p>
          <p class="mt-2 text-sm text-stone-500">猫と過ごす、やさしい午後。</p>
        </div>

        <div class="flex flex-wrap gap-4 text-sm text-stone-600">
          <a href="#concept" class="hover:text-amber-700">コンセプト</a>
          <a href="#guide" class="hover:text-amber-700">はじめての方へ</a>
          <a href="#shop" class="hover:text-amber-700">店舗案内</a>
          <a href="#news" class="hover:text-amber-700">お知らせ</a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
// 今回は静的ページなので script は空でOK
</script>