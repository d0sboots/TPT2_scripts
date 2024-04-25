# Turbo exec V2.2

This set of scripts is a wrapper for the "turbo exec" AI bug/exploit that allows you to run scripts very quickly.

This is V2.2 of turbo exec, which lives in a package. It is **backwards compatible**
with the previous turbo exec V2, so you can delete the old one and replace it
with this and your old scripts will still work.

**IMPORTANT UPGRADE NOTE**: This import includes the scripts `turbo start` and
`turbo stop` **outside** of any package. For compatibility reasons, they must
stay outside of any package. If you are upgrading, I strongly suggest you
delete the old copy **first**, so you don't get mixed up and delete these by
accident.

## Bundle Import:
```
7VfNj6M2FP9fct09EBhXm0p7ABJIUEIGZgdjVz3E9jQJa7uoCUlI1f+9MuQDQzozu4rUPWwOKCB4fu/38fz8d29D/1rn203v1996bj/2ZuuHci5DA6WBYV9/w+oi2IaYwYq4ICcyKqiZGK4f7oh6HwLDsYHB0mBNSlBiyHJqxZwuwYoKbiz8Pmc+z6aCF8wGkviDNYL7YgGBMRWMM3uVERMcme8VzI7mbJyUSHwqqEjkIg0NnE4myBwU1IpXREYj+2nTvHftSGV4kBgCToVah+2Y/2nK/KQkwitfnqqcH6kVlwsI5FSovOPVAoLjCF7qOrJxkBNBC9ypbXuuTeVo4EjLd0xlUhDBC7xvPg8ylVUzjr2cqEczbCYFToMclcBCkGtr2fsr8L2PPZdfaSFWgxR7pi5zbB52SHibCloXHHEaaVANZdynIthNZcCxyY8KkqHwykUa/0lgYizgrKKhTW8Xglv0ajA4Uw2WiVPJxmeciKRU62BzYJD91sBpUKA0ALUcBhfYVd7M93IiZ/GlLhkaVEFbAtmuzbXOtSnJxlzPl5UMAlWbvEGBJh+0b8lHstVCX2vYAP5z72NveKHlCmutQmwhuOUsPVmnCt1SvAy/VfFuHa2ZYiUHneo6p8Nk3KC6AT+14h3V1/WS0XM5zUa34O5I6XW44xz7B/5ml3Ccs4yyFxhucDorCPQeNIo2S1Vs3HYJg8BYwP0cmYMt9ZWEwx1ZV+u0bdCRyi0b6PmPPugyqQB/bOTAX/wkY526wXP8ZVLMsjwjVlIwnxf44F34vnScLufTC+dWvGL+s5avYwV9IoCyxZsWH41PtYkQIPPAaQm2KF1q+ilVNY7XknjcJzLOiQ0yYvb3KA1yag6K2paale12J3PsyYfHiFUcE8iL72sft3aHb4j5Hi3x4bBl95H9ZLytlzamd+DUHSvPOnv1bdOXzPRyPc7s2mycO2hJeBnzuYnjO8Ty+VfiPzd3MEmseOcqPgVYUfn1tJ2EO5I6it8jMR/utsU8Ll/Xpb2knfbuVF7+rNr2dcip6b3Vsmvrd1rtvDFMnHesx1YrWhNzsBlalxaqUjUQ5AXVBoPoC7zYmzFoXWWRRli9l6E08lUJyPRaEHnkDgOLk+r37h/j/ftruWWF7hD3Hhnptlwj8X/JxrG35zZex9L5mtXb5OQXBENjkWI+NBtTTbriyEraGHe+UVODd5Lf2ZFRY6yo/g8aM2zygGHY73SRloSbw4gId/UmCWQjsPu+8f3QbqY3BpA3B5nZmXVk8Yz4yfH7Zs1Xc/mP8b82+GlGmYx/nmJ+pFOMvNLy8xTzg5xifv/nXw==
```

If **all** your scripts are designed for TEv2.2, you can choose to disable or delete `turbo start`
and `turbo stop`. They exist only for compatibility with old TEv2 scripts.

For more informations about this bug, check out the [FAQ](/common/turbo_exec/FAQ.md).

If you are a coder and want to integrate use turbo exec with your script, check out the [Manual](/common/turbo_exec/MANUAL.md).

This package is **not** compatible with the (very) old execution stack, which works using turbo exec V1.

If you simply want to accelerate your current scripts and don't want to bother with modifying scripts, you can
grab the `turbo exec toggle` script from [here](/common/utilities/README.md). Be aware that not all scripts will
work as intended with this.
It is strongly advised that published scripts don't rely on this script and instead use the intended API explained in the manual.

