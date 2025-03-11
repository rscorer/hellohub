<template>
  <div>
    <header>
      <SignedOut>
        <SignInButton/>
      </SignedOut>
      <SignedIn>
        <UserButton/>
      </SignedIn>
    </header>

    <main>
      <NuxtPage/>
    </main>
  </div>
</template>
