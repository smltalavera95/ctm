**Instructions:**
1. Fork this repository to create your own copy.
2. Complete the code test within 30 minutes.
3. The code test consists of 10 multiple-choice questions and one code challenge.
4. For multiple-choice questions, select the correct option (a, b, c, or d).
5. For the code challenge, write the code based on the given requirements.
6. Modify the `README.md` file to provide your answers and code solution.
7. Commit your changes to your forked repository.
8. Once you've completed the code test, share the link to your forked repository for evaluation.
9. Good luck!

**Multiple-Choice Questions:**

1. What is WordPress?
   - [x] a) A content management system (CMS)
   - [ ] b) A programming language
   - [ ] c) An operating system
   - [ ] d) A database management system

2. Which file is responsible for displaying the content of a single blog post in WordPress?
   - [x] a) single.php
   - [ ] b) page.php
   - [ ] c) archive.php
   - [ ] d) index.php

3. Which of the following hooks is executed after a new user is registered in WordPress?
   - [ ] a) init
   - [ ] b) wp_login
   - [x] c) wp_insert_user
   - [ ] d) wp_enqueue_scripts

4. What is the correct way to enqueue a JavaScript file in WordPress?
   - [ ] a) add_script()
   - [ ] b) enqueue_script()
   - [x] c) wp_enqueue_script()
   - [ ] d) include_script()

5. What is the purpose of the functions.php file in a WordPress theme?
   - [ ] a) To define custom post types
   - [ ] b) To add custom CSS styles
   - [x] c) To add custom PHP functions
   - [ ] d) To create template files

6. Which function can be used to retrieve the URL of the site's homepage in WordPress?
   - [ ] a) get_permalink()
   - [ ] b) get_home_url()
   - [ ] c) get_site_url()
   - [x] d) home_url()

7. Which database table stores WordPress plugin settings?
   - [ ] a) wp_posts
   - [x] b) wp_options
   - [ ] c) wp_users
   - [ ] d) wp_meta

8. What is the purpose of the `wp_head()` function in a WordPress theme?
   - [ ] a) It displays the site's header content.
   - [ ] b) It registers custom post types.
   - [x] c) It loads JavaScript files.
   - [ ] d) It generates the site's footer.

9. Which function can be used to retrieve the title of the current WordPress post or page?
   - [ ] a) get_the_content()
   - [ ] b) the_title()
   - [x] c) get_the_title()
   - [ ] d) the_content()

10. How can you add a custom menu location in a WordPress theme?
    - [ ] a) By adding a menu widget to a sidebar
    - [x] b) By using the `register_nav_menu()` function in the theme's functions.php file
    - [ ] c) By modifying the style.css file
    - [ ] d) By installing a menu plugin

**Code Challenge:**

Write a function in PHP that takes an

 array of post IDs as input and returns an array of their corresponding post titles. Use the WordPress function `get_the_title()` to retrieve the title of each post.

```php
/**
 * Retrieves an array of post titles based on the given post IDs.
 *
 * @param array $post_ids Array of post IDs.
 * @return array Array of post titles.
 */
function get_post_titles($post_ids) {
    $post_titles = array();

    foreach ($post_ids as $post_id) {
        $post_title = get_the_title($post_id);
        $post_titles[] = $post_title;
    }

    
    // Return an array of post titles
   return $post_titles;
}
```

**Submission:**
- Modify the `README.md` file in your forked repository to include your answers to the multiple-choice questions and your code solution to the code challenge.
- Commit and push your changes to your forked repository.
- Share the link to your forked repository for evaluation.


