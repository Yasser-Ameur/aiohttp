Fixed ``Range: bytes=-0`` being answered with ``206`` and the whole file instead of ``416``, as a zero suffix length is unsatisfiable per :rfc:`9110` section 14.1.2 -- by :user:`Yasser-Ameur`.
