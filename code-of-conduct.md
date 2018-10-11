CONTRIBUTOR CODE

Open Source has always been a foundation of the Internet, and with the advent of social open source networks this is more true than ever. But free, libre, and open source projects suffer from a startling lack of diversity, with dramatically low representation by women, people of color, and other marginalized populations.

Part of this problem lies with the very structure of some projects: the use of insensitive language, thoughtless use of pronouns, assumptions of gender, and even sexualized or culturally insensitive names.

Marginalized people also suffer some of the unintended consequences of dogmatic insistence on meritocratic principles of governance. Studies have shown that organizational cultures that value meritocracy often result in greater inequality. People with “merit” are often excused for their bad behavior in public spaces based on the value of their technical contributions. Meritocracy also naively assumes a level playing field, in which everyone has access to the same resources, free time, and common life experiences to draw upon. These factors and more make contributing to open source a daunting prospect for many people, especially women and other underrepresented people.

(For more critical analysis of meritocracy, refer to this entry on the Geek Feminism wiki.)

## Using the Contributor Covenant
We recommend that you add the Markdown or text version of the Contributor Covenant to your source code repository at the root level.

Thanks to Simon Vansintjan there is an automated way to add Contributor Covenant to your project. Assuming that you have Node.js installed, simply run the following two commands from your project folder:

npm install -g covgen
covgen giansalex@gmail.com
If you have npm 5.x installed you can run npx covgen giansalex@gmail.com instead of installing globally.

For subsequent projects, simply repeat the second command.

You may want to add language similar to this to introduce your code of conduct:

Please note that this project is released with a Contributor Code of Conduct. By participating in this project you agree to abide by its terms.

You may also use the permalinks given above to reference from your project home page.

Important! You must add a contact method to the placeholder in the document so that people know how to report violations.

The Contributor Covenant is released under the Creative Commons Attribution 4.0 International Public License, which requires that attribution be included.
