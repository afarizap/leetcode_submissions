# @param {String} jewels
# @param {String} stones
# @return {Integer}
def num_jewels_in_stones(jewels, stones)
    i = 0
    jewels.each_char { |j|
        stones.each_char { |s|
            if s == j
                i += 1
            end
        }
    }
    return i
end
