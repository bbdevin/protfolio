<template>
    <div>
        <nav>
            <ul>
                <li>
                    <NuxtLink to="/">Main</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/about">About</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/">Main</NuxtLink>
                </li>
            </ul>
        </nav>
        <slot />
    </div>
</template>