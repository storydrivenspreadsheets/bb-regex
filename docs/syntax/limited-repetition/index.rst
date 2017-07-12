******************
Limited Repetition
******************


Match exactly :t:`n` repetitions
================================

.. admonition:: Example

    Match the character ``0`` when it's repeated 3 times

    Pattern:
        :regexp:`0{3}`

    Match:
        .. rst-class:: regex-matched-text-block

        Repeat 10,\ :emphasis:`000` times:
        100 x 100 = 1\ :emphasis:`000`\ 0
        1\ :emphasis:`000` + 100 = 1100


Match between :t:`m` and :t:`n` repetitions
===========================================


.. admonition:: Example

    Match the character ``m`` when it's repeated 3 to 5 times

    Pattern:
        :regexp:`m{3,5}`

    Match:
        .. rst-class:: regex-matched-text-block

            She hummed to him
            Mmm M\ :emphasis:`mmm` M\ :emphasis:`mmmmm`\ m
            H\ :emphasis:`mmmm` Hmm.


Match :t:`n` or more repetitions
================================

Use curly brackets, but leave out the upper-limit, i.e. the second number.


.. admonition:: Example

    Match 10-or-more word characters

    Pattern:
        :regexp:`\w{10,}`

    Match:
        .. rst-class:: regex-matched-text-block

        The best actors in the world, either for tragedy,
        comedy, history, pastoral, pastoral-comical,
        :emphasis:`historical`-pastoral, tragical-\ :emphasis:`historical`,
        tragical-comical-\ :emphasis:`historical`-pastoral,
        scene :emphasis:`individable`, or poem unlimited


