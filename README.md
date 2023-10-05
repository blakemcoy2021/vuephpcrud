# vuephpcrud
simple vue php crud development

---

after cloning this:
1) make sure this is hosted properly (e.g. inside htdocs of xampp)
2) go here to download database: https://drive.google.com/file/d/1OdSLTCdyfNF-9XllHzlJkI0nG_xBFtEk/view?usp=sharing
3) import database in mysql server (e.g. using xampp) or run SQL script (e.g. via phpmyadmin SQL inside a table named __`test`__)

    ```
    CREATE TABLE `vueuser` (
    `id` int(11) NOT NULL,
    `name` varchar(30) NOT NULL,
    `email` varchar(30) NOT NULL
    ) ENGINE=InnoDB DEFAULT CHARSET=latin1;

    INSERT INTO `vueuser` (`id`, `name`, `email`) VALUES
    (1, 'cairocoders', 'cairocoders@gmail.com'),
    (2, 'tutorial101.blogspot.com', 'tutorial101@gmail.com'),
    (3, 'Ashton Cox', 'AshtonCox@gmail.com'),
    (4, 'Bradley Greer', 'BradleyGreer@gmail.com'),
    (5, 'Clydey Ednalan', 'clydeyednalan@gmail.com');

    ALTER TABLE `vueuser`
    ADD PRIMARY KEY (`id`);

    ALTER TABLE `vueuser`
    MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=6;
    ```


4) go to model.php and setup database credentials properly according to previous steps

---

__NOTE__: this is based of tutorial https://www.youtube.com/watch?v=hTV9UstoWUc&ab_channel=Cairocoders and you can watch it for reference too.