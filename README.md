# Diff_code

$ids = explode(',', $this->selector);
        $needle = 'video';
        $a = array_filter($ids, function ($haystack) use ($needle) {
            return(strpos($haystack, $needle));
        });
