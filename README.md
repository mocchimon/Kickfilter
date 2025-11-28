# Kickfilter
uBlock Origin Filter for Kick.com
Hides offline followed channels


! Sep 11, 2024 https://kick.com hide offline followed channels
kick.com##button:not(:has(.text-white))

! Sep 11, 2024 https://kick.com grey's out offline followed channels but still displays icon
kick.com##.text-neutral-700.leading-\[1\.2\].font-bold.text-sm.truncate.shrink
kick.com##.grayscale.mix-blend-luminosity.rounded-full.overflow-hidden.w-full.h-full

!hide recommended
kick.com##section.p-3.flex-col.w-full.flex:nth-of-type(2)
kick.com##div.justify-between.items-center.flex.mx-3:nth-of-type(2)
