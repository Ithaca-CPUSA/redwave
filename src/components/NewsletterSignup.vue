<template>
    <section class="bg-brandRed text-brandWhite py-24">
        <div class="mx-auto max-w-6xl px-4 xl:px-0">
                <h2 class="text-4xl font-semibold tracking-tight mb-6">Sign up
                    for
                    our Newsletter</h2>
            <div class="grid grid-cols-2 gap-6">
                <div>
                    <p>Vestibulum id ligula porta felis euismod semper. Duis
                        mollis,
                        est non commodo luctus, nisi erat porttitor ligula, eget
                        lacinia odio sem nec elit. Cras justo odio, dapibus ac
                        facilisis in, egestas eget quam. Maecenas faucibus
                        mollis
                        interdum. Vestibulum id ligula porta felis euismod
                        semper.
                        Etiam porta sem malesuada magna mollis euismod.</p>
                </div>
                <form action="/newsletter-signup" class="">
                    <div class="mb-4">
                        <label class="text-sm block" for="email">Email</label>
                        <input
                            class="mt-1 block w-full rounded-md bg-gray-100 border-gray-300 shadow-sm focus:border-indigo-300 focus:ring focus:ring-indigo-200 focus:ring-opacity-50"
                            type="email" name="email"
                            placeholder="john@nightswatch.org"
                            id="newsletter-email">
                    </div>
                    <button
                        class="px-4 py-2 bg-white rounded-sm shadow-lg text-brandRed font-semibold uppercase"
                        type="submit">Sign up</button>
                </form>
            </div>
        </div>
    </section>
</template>
