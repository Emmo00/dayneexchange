<script setup>
import NavBarComponent from '@/components/layout/NavBarComponent.vue';
</script>
<template>
  <NavBarComponent />
  <div class="flex flex-col min-h-[100dvh]">
    <main class="flex-1">
      <section class="w-full py-12 md:py-24 lg:py-12 xl:py-18 bg-gradient-to-r from-[#1abc9c] to-[#2ecc71]">
        <div class="container px-12 ">
          <div class="grid gap-6 lg:grid-cols-[1fr_400px] lg:gap-12 xl:grid-cols-[1fr_600px]">
            <div class="flex flex-col justify-center space-y-4 text-white">
              <div class="space-y-2">
                <h1 class="text-3xl font-bold tracking-tighter sm:text-5xl xl:text-6xl/none">
                  Join the revolution of digital trading
                </h1>
                <p class="max-w-[600px] text-white/80 md:text-xl">
                  Experience the power of blockchain technology and seize new opportunities to exchange crypto and
                  gift cards today!
                </p>
              </div>
              <div class="flex flex-col gap-2 min-[400px]:flex-row">
                <a class="inline-flex h-10 items-center justify-center rounded-md bg-foreground px-8 text-sm font-bold text- shadow transition-colors hover:bg-white/90 focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50"
                  href="#">
                  Get Started
                </a>
                <a class="inline-flex h-10 items-center justify-center rounded-md border border-white bg-transparent px-8 text-sm font-medium text-white shadow-sm transition-colors hover:bg-white hover:text-[#1abc9c] focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50"
                  href="#">
                  Learn More
                </a>
              </div>
            </div>
            <img src="/image.webp" width="550" height="550" alt="Hero"
              class="mx-auto aspect-video overflow-hidden rounded-xl object-cover sm:w-full lg:order-last lg:aspect-square" />
          </div>
        </div>
      </section>
      <section id="features" class="w-full py-12 md:py-24 lg:py-32 bg-background text-foreground">
        <div class="container px-4 md:px-6">
          <div class="flex flex-col items-center justify-center space-y-4 text-center">
            <div class="space-y-2">
              <div class="inline-block rounded-lg bg-muted px-3 py-1 text-sm text-foreground">Key Features</div>
              <h2 class="text-3xl font-bold tracking-tighter sm:text-5xl">Experience the power of digital trading</h2>
              <p class="max-w-[900px] text-muted-foreground md:text-xl/relaxed lg:text-base/relaxed xl:text-xl/relaxed">
                Our platform offers fast and easy trades, best rates, and secure transactions to help you seize new
                opportunities in the world of crypto and gift cards.
              </p>
            </div>
          </div>
          <div class="mx-auto grid max-w-5xl items-center gap-6 py-12 lg:grid-cols-2 lg:gap-12">
            <div class="flex flex-col justify-center space-y-4">
              <ul class="grid gap-6">
                <li>
                  <div class="grid gap-1">
                    <h3 class="text-xl font-bold">Fast and Easy Trades</h3>
                    <p class="text-muted-foreground">
                      Our user-friendly platform makes it simple to exchange crypto and gift cards in just a few
                      clicks.
                    </p>
                  </div>
                </li>
                <li>
                  <div class="grid gap-1">
                    <h3 class="text-xl font-bold">Best Rates</h3>
                    <p class="text-muted-foreground">
                      We offer the most competitive rates in the market to ensure you get the best value for your
                      trades.
                    </p>
                  </div>
                </li>
                <li>
                  <div class="grid gap-1">
                    <h3 class="text-xl font-bold">Secure Transactions</h3>
                    <p class="text-muted-foreground">
                      Your transactions are protected by advanced security measures, giving you peace of mind.
                    </p>
                  </div>
                </li>
              </ul>
            </div>
            <img src="/image2.webp" width="550" height="310" alt="Image"
              class="mx-auto aspect-video overflow-hidden rounded-xl object-cover object-center sm:w-full lg:order-last" />
          </div>
        </div>
      </section>
      <section id="faq" class="w-full py-12 md:py-24 lg:py-32 bg-muted text-foreground">
        <div class="container px-4 md:px-6">
          <div class="flex flex-col items-center justify-center space-y-4 text-center">
            <div class="space-y-2">
              <div class="inline-block rounded-lg bg-muted px-3 py-1 text-sm">FAQ</div>
              <h2 class="text-3xl font-bold tracking-tighter sm:text-5xl">Frequently Asked Questions</h2>
              <p class="max-w-[900px] text-muted-foreground md:text-xl/relaxed lg:text-base/relaxed xl:text-xl/relaxed">
                Check out our FAQ section to find answers to common questions about our crypto and gift card trading
                platform.
              </p>
            </div>
          </div>
          <div class="mx-auto grid max-w-5xl items-center gap-6 py-12 lg:grid-cols-2 lg:gap-12">
            <div class="flex flex-col justify-center space-y-4">
              <div class="w-full" data-orientation="vertical">
                <div data-state="closed" data-orientation="vertical" class="border-b">
                  <h3 data-orientation="vertical" data-state="closed" class="flex">
                    <button type="button" aria-controls="radix-:Rjdenpnltf9f:" aria-expanded="false" data-state="closed"
                      data-orientation="vertical" id="radix-:R3denpnltf9f:"
                      class="flex flex-1 items-center justify-between py-4 font-medium transition-all hover:underline [&amp;[data-state=open]>svg]:rotate-180 text-left"
                      data-radix-collection-item="">
                      How do I get started with your platform?
                      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                        stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                        class="lucide lucide-chevron-down h-4 w-4 shrink-0 transition-transform duration-200">
                        <path d="m6 9 6 6 6-6"></path>
                      </svg>
                    </button>
                  </h3>
                  <div data-state="closed" id="radix-:Rjdenpnltf9f:" hidden="" role="region"
                    aria-labelledby="radix-:R3denpnltf9f:" data-orientation="vertical"
                    class="overflow-hidden text-sm transition-all data-[state=closed]:animate-accordion-up data-[state=open]:animate-accordion-down"
                    style="--radix-accordion-content-height: var(--radix-collapsible-content-height); --radix-accordion-content-width: var(--radix-collapsible-content-width);">
                  </div>
                </div>
                <div data-state="closed" data-orientation="vertical" class="border-b">
                  <h3 data-orientation="vertical" data-state="closed" class="flex">
                    <button type="button" aria-controls="radix-:Rldenpnltf9f:" aria-expanded="false" data-state="closed"
                      data-orientation="vertical" id="radix-:R5denpnltf9f:"
                      class="flex flex-1 items-center justify-between py-4 font-medium transition-all hover:underline [&amp;[data-state=open]>svg]:rotate-180 text-left"
                      data-radix-collection-item="">
                      What payment methods do you accept?
                      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                        stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                        class="lucide lucide-chevron-down h-4 w-4 shrink-0 transition-transform duration-200">
                        <path d="m6 9 6 6 6-6"></path>
                      </svg>
                    </button>
                  </h3>
                  <div data-state="closed" id="radix-:Rldenpnltf9f:" hidden="" role="region"
                    aria-labelledby="radix-:R5denpnltf9f:" data-orientation="vertical"
                    class="overflow-hidden text-sm transition-all data-[state=closed]:animate-accordion-up data-[state=open]:animate-accordion-down"
                    style="--radix-accordion-content-height: var(--radix-collapsible-content-height); --radix-accordion-content-width: var(--radix-collapsible-content-width);">
                  </div>
                </div>
                <div data-state="closed" data-orientation="vertical" class="border-b">
                  <h3 data-orientation="vertical" data-state="closed" class="flex">
                    <button type="button" aria-controls="radix-:Rndenpnltf9f:" aria-expanded="false" data-state="closed"
                      data-orientation="vertical" id="radix-:R7denpnltf9f:"
                      class="flex flex-1 items-center justify-between py-4 font-medium transition-all hover:underline [&amp;[data-state=open]>svg]:rotate-180 text-left"
                      data-radix-collection-item="">
                      How secure are your transactions?
                      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                        stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                        class="lucide lucide-chevron-down h-4 w-4 shrink-0 transition-transform duration-200">
                        <path d="m6 9 6 6 6-6"></path>
                      </svg>
                    </button>
                  </h3>
                  <div data-state="closed" id="radix-:Rndenpnltf9f:" hidden="" role="region"
                    aria-labelledby="radix-:R7denpnltf9f:" data-orientation="vertical"
                    class="overflow-hidden text-sm transition-all data-[state=closed]:animate-accordion-up data-[state=open]:animate-accordion-down"
                    style="--radix-accordion-content-height: var(--radix-collapsible-content-height); --radix-accordion-content-width: var(--radix-collapsible-content-width);">
                  </div>
                </div>
                <div data-state="closed" data-orientation="vertical" class="border-b">
                  <h3 data-orientation="vertical" data-state="closed" class="flex">
                    <button type="button" aria-controls="radix-:Rpdenpnltf9f:" aria-expanded="false" data-state="closed"
                      data-orientation="vertical" id="radix-:R9denpnltf9f:"
                      class="flex flex-1 items-center justify-between py-4 font-medium transition-all hover:underline [&amp;[data-state=open]>svg]:rotate-180 text-left"
                      data-radix-collection-item="">
                      What is your customer support like?
                      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                        stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                        class="lucide lucide-chevron-down h-4 w-4 shrink-0 transition-transform duration-200">
                        <path d="m6 9 6 6 6-6"></path>
                      </svg>
                    </button>
                  </h3>
                  <div data-state="closed" id="radix-:Rpdenpnltf9f:" hidden="" role="region"
                    aria-labelledby="radix-:R9denpnltf9f:" data-orientation="vertical"
                    class="overflow-hidden text-sm transition-all data-[state=closed]:animate-accordion-up data-[state=open]:animate-accordion-down"
                    style="--radix-accordion-content-height: var(--radix-collapsible-content-height); --radix-accordion-content-width: var(--radix-collapsible-content-width);">
                  </div>
                </div>
              </div>
            </div>
            <img src="/image.webp" width="550" height="310" alt="Image"
              class="mx-auto aspect-video overflow-hidden rounded-xl object-cover object-center sm:w-full lg:order-last" />
          </div>
        </div>
      </section>
      <section id="contact" class="w-full py-12 md:py-24 lg:py-32 bg-background text-foreground">
        <div class="container px-4 md:px-6">
          <div class="flex flex-col items-center justify-center space-y-4 text-center">
            <div class="space-y-2">
              <div class="inline-block rounded-lg bg-muted px-3 py-1 text-sm">Contact Us</div>
              <h2 class="text-3xl font-bold tracking-tighter sm:text-5xl">Get in touch with us</h2>
              <p class="max-w-[900px] text-muted-foreground md:text-xl/relaxed lg:text-base/relaxed xl:text-xl/relaxed">
                Have any questions or need assistance? Fill out the form below and our team will get back to you as
                soon as possible.
              </p>
            </div>
          </div>
          <div class="mx-auto w-full max-w-sm space-y-2">
            <form class="flex flex-col gap-4">
              <input
                class="flex h-10 rounded-md border border-input bg-background px-3 py-2 text-sm ring-offset-background file:border-0 file:bg-transparent file:text-sm file:font-medium placeholder:text-muted-foreground focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50 w-full"
                type="text" placeholder="Name" />
              <input
                class="flex h-10 rounded-md border border-input bg-background px-3 py-2 text-sm ring-offset-background file:border-0 file:bg-transparent file:text-sm file:font-medium placeholder:text-muted-foreground focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50 w-full"
                type="email" placeholder="Email" />
              <textarea
                class="flex min-h-[80px] rounded-md border border-input bg-background px-3 py-2 text-sm ring-offset-background placeholder:text-muted-foreground focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50 w-full"
                placeholder="Message"></textarea>
              <button
                class="bg-muted inline-flex items-center justify-center whitespace-nowrap rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 bg-primary text-primary-foreground hover:bg-primary/90 h-10 px-4 py-2"
                type="submit">
                Submit
              </button>
            </form>
          </div>
        </div>
      </section>
    </main>
    <footer class="bg-muted p-6 md:py-12 w-full">
      <div class="container max-w-7xl grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-8 text-sm">
        <div class="grid gap-1">
          <h3 class="font-semibold">Company</h3>
          <a href="#">About Us</a>
          <a href="#">Our Team</a>
          <a href="#">Careers</a>
          <a href="#">News</a>
        </div>
        <div class="grid gap-1">
          <h3 class="font-semibold">Products</h3>
          <a href="#">Crypto Trading</a>
          <a href="#">Gift Card Trading</a>
          <a href="#">Referral Program</a>
        </div>
        <div class="grid gap-1">
          <h3 class="font-semibold">Resources</h3>
          <a href="#">Blog</a>
          <a href="#">FAQ</a>
          <a href="#">Support</a>
        </div>
        <div class="grid gap-1">
          <h3 class="font-semibold">Legal</h3>
          <a href="#">Privacy Policy</a>
          <a href="#">Terms of Service</a>
          <a href="#">Cookie Policy</a>
        </div>
        <div class="grid gap-1">
          <h3 class="font-semibold">Contact</h3>
          <a href="#">Email</a>
          <a href="#">Phone</a>
          <a href="#">Live Chat</a>
        </div>
      </div>
    </footer>
  </div>
</template>