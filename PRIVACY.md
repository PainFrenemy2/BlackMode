# BlackMode - політика конфіденційності

Оновлено: 31 жовтня 2026 р.

BlackMode - внутрішня робоча програма для майстерні ПК. Нею користуються лише працівники, яким доступ надав адміністратор майстерні. Розробник програми: NullCode.

## Які дані обробляються

- **Дані користувача:** ім'я, вказане адміністратором, посада і код ПК. Код ПК обчислюється з ідентифікатора Windows.
- **Дані про вхід:** час останнього входу та IP-адреса.
- **Робочі дані:** збірки, ціни, нотатки до збірок і журнал змін (хто, коли і що змінив), а також спільні налаштування майстерні.
- **Дані складу:** залишки, ціни та курс із системи обліку майстерні Dilovod. Програма їх лише читає і нічого в Dilovod не змінює.
- **На самому ПК:** особистий ключ доступу, зашифрований засобами Windows, копія налаштувань і складу, журнали роботи програми.

Програма не збирає контакти, файли користувача чи дані про місцезнаходження, не показує рекламу і не використовує рекламні трекери.

## Навіщо

Лише для роботи майстерні: вхід у програму, розрахунок і збереження збірок, спільний доступ до них для працівників і захист доступу.

## Де зберігаються дані і скільки

- Дані зберігаються на сервері майстерні в ЄС.
- Збірка, яку не змінювали місяць, видаляється автоматично.
- Видалена збірка 14 днів лежить у кошику, а потім видаляється.
- Резервні копії бази зберігаються у приватному сховищі 7 днів.
- Запис користувача зберігається, доки адміністратор його не видалить.

## Кому передаються дані

Дані не продаються і не передаються для реклами. Для роботи програми використовуються постачальники послуг: хостинг сервера (OVH), посередник доступу до Dilovod (Cloudflare), система обліку Dilovod і приватне сховище резервних копій (GitHub).

## Ваші права

Щоб отримати, виправити або видалити свої дані, зверніться до адміністратора майстерні або створіть звернення: https://github.com/PainFrenemy2/BlackMode/issues

---

# BlackMode - Privacy Policy

Updated: October 31, 2026

BlackMode is an internal business tool for a PC repair workshop, used only by staff who were granted access by the workshop administrator. Developer: NullCode.

**Data processed:** user name set by the administrator, role and PC code (derived from a Windows identifier); last sign-in time and IP address; PC builds, prices, notes and a change log; shared workshop settings; stock levels, prices and exchange rate read from the workshop's Dilovod accounting system (read-only). Stored locally on the PC: a personal access key encrypted by Windows, a copy of settings and stock, and application logs.

The app does not collect contacts, user files or location, shows no ads and uses no advertising trackers.

**Purpose:** workshop operations only: sign-in, calculating and storing PC builds, sharing them among staff, and access protection.

**Storage and retention:** data is stored on the workshop's server in the EU. A build not changed for a month is deleted automatically. A deleted build stays in the trash for 14 days. Database backups are kept in private storage for 7 days. A user record is kept until the administrator deletes it.

**Sharing:** data is not sold or shared for advertising. Service providers used to run the app: OVH (server hosting), Cloudflare (Dilovod access relay), Dilovod (accounting system) and GitHub (private backup storage).

**Your rights:** to access, correct or delete your data, contact the workshop administrator or open a request at https://github.com/PainFrenemy2/BlackMode/issues
